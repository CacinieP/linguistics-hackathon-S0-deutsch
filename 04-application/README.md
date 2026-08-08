# 04 · 应用检查 (Anwendung)

> CP4 阶段。把前三个语言学阶段（语音 / 形态 / 句法）学到的，做成一个**能跑的东西**证明真学会了。

---

## 🎯 产出：deutsch-voice 点读工具

黑客松中途（11:33）冒出的副产品，最终长成了一个完整的德语点读页：**哪里不会点哪里，点击即发音**。

### 这个 demo 是什么

[`deutsch-voice-demo.html`](./deutsch-voice-demo.html) —— **脱敏演示版**，双击即开。

- 用浏览器内置 `speechSynthesis` 实时发音（无需 API、无需生成音频）。
- 例词**全部原创**（der Tisch / die Lampe / das Buch …），不来自任何版权词表。
- 每个名词**连定冠词一起念**（`der Apfel` 而非裸 `Apfel`）。

### 关于完整版

歌德学院 A0–A2 官方词表与模考句属于版权材料的派生作品，完整版（235 句 + 1952 词的 VoxCPM2 预生成音频）未公开。本仓只放这个脱敏 demo + 实现说明。

---

## 为什么名词要连冠词一起念

这是 `02-morphology/README.md §1.1` 的核心方法论：

> 德语的「性」（der/die/das）是名词不可分割的一部分。背 `Apfel` 没用——说 `ich esse den Apfel` 时宾格要 `der → den`，说 `das ist ein Apfel` 时要用不定冠词 `ein`。所以必须**把冠词和词当整体记**。

demo 里点击 `der Apfel` 听到的是 "der Apfel" 而非 "Apfel"，就是这个原则的落地。

---

## 技术实现（完整版）

| 层 | 技术 |
|----|------|
| 资料 | 歌德官方 PDF（5 个）→ 文本提取 → 句子表 + 词表 |
| TTS | VoxCPM2（[OpenBMB/VoxCPM](https://github.com/OpenBMB/VoxCPM)），经 ModelBest 免费 API，OpenAI `/v1/audio/speech` 兼容格式 |
| 管线 | WAV → ffmpeg 转 MP3 → base64 内嵌进单文件 HTML |
| 点读页 | `deutsch-voice.html`（29MB，双击即用，Safari/Chrome 兼容） |

### 关键 bug 修复

初版单词朗读走浏览器 `speechSynthesis`，播放函数里有一条正则**把 der/die/das 删掉了**——点到 `der Apfel` 只听到 "Apfel"，恰好违背了形态学「连冠词一起背」的原则。修复：改用预生成带冠词 MP3 内嵌。详见 [`CHANGELOG.md`](../CHANGELOG.md) 「voxcpm2 点读工具实现」段。

### 复现脚本

```bash
python3 clean_and_reindex.py   # 清洗 PDF 解析残片 + 重建映射
python3 tts_words.py           # 生成单词音频（~16 分钟 / 1952 词）
python3 rebuild_html.py        # 注入音频 + 改写播放函数
```

---

## 48h 收获自评

- ✅ 语音字母（CP1）：字母表、长短元音、变元音规则
- ✅ 形态学（CP2）：三性、四格、变格表、动词变位
- ✅ **应用副产品**：一个真能用的点读工具，且过程中发现了「冠词被代码删掉」这种只有真做才会暴露的问题
