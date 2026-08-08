# Changelog

记录 48h 德语 0→A2 学习直播黑客松全过程。格式遵循 [Keep a Changelog](https://keepachangelog.com/)，日期 `YYYY-MM-DD`。

---

## 2026-08-08 · Day 1

### 启动与计划 (08:04 – 09:15)

- **08:04 启动** —— 下载歌德学院 0-A2 大纲 PDF，制定 48h 学习计划与 timeline。
- 确立 **8 个 checkpoints**（Day 1 + Day 2 各 4 个），节点 `10:00 / 14:00 / 18:00 / 22:00`，每节点前 10 分钟必须 push 一次。
- **08:15 GitHub 仓库建立** —— [`CacinieP/linguistics-hackathon-S0-deutsch`](https://github.com/CacinieP/linguistics-hackathon-S0-deutsch)。commit 流即直播画面。
- 浏览一遍语音 + 句法大纲，建立整体学习路径认知。

### CP1 · 语音 & 字母 (08:16 – 10:00) ✅

- 搭建仓库骨架：四个语言学阶段目录（`01-phonology-alphabet` → `04-application`）+ checkpoint log。
- 完成语音字母阶段笔记（`01-phonology-alphabet/README.md`）：字母表、长短元音、变元音 `ä ö ü ß`、字母→音素规则、重音与节奏。
- 完成 CP1 A2 测试题（`01-phonology-alphabet/test-a2.md`）。
- **10:00 CP1 达标** ✅

### CP2 · 形态学 (10:00 – 14:00 进行中)

- 完成形态学阶段笔记（`02-morphology/README.md`）：名词性/数/格、冠词变格表、动词现在时变位、可分前缀、复合词拆解。
- 完成 CP2 A2 测试题（`02-morphology/test-a2.md`），CP1+CP2 合计 655 道（190+465）。
- **语素层级分类体系**（`sp-morpheme/`，7 个文件）：自由词根 → 自由功能词 → 派生前缀 → 派生后缀 → 复合词 → 屈折词缀 → 例题，按 A1-C2 分级。

### 新计划：voxcpm2 个性化音频点读 (11:33 提出 → ✅ 已落地)

- 使用 **voxcpm2**（支持 30+ 语种的 TTS）生成个性化 HTML 音频点读页。
- 基于歌德学院 0-A2 大纲，把学过的语音/形态内容做成可点击发音的点读卡片。
- modelbest 免费 API 体验平台：https://platform.modelbest.cn/console/login?ref=A93DCA73
- 状态：**✅ 已完成**（详见下方「voxcpm2 点读工具实现」段，代码在私有仓 [`deutsch-voice`](https://github.com/CacinieP/deutsch-voice)，本仓 `04-application/` 放脱敏 demo）。

### 时间线速览

| 时间 | 事件 |
|------|------|
| 08:04 | 启动，下载 PDF，制定计划与 timeline |
| 08:15 | GitHub 仓库建立 |
| 08:16 – 09:15 | 浏览语音+句法大纲，搭建骨架 |
| 09:13 – 09:17 | 语素层级分类体系（sp-morpheme）完成 |
| 10:00 | **CP1 达标** ✅ 语音字母 |
| 10:40 | 出门买咖啡，回家继续 |
| 11:33 | 提出 voxcpm2 音频点读计划 |
| 11:14 – 12:52 | **voxcpm2 点读工具实现** ✅ 235 句 + 1952 词音频 |
| 14:00 | CP2 截止（形态学，进行中）|
| 18:00 | CP3 截止（句法遍历）|
| 22:00 | CP4 截止（应用 & 自测）|

---

## 2026-08-08 · voxcpm2 点读工具实现 (11:14 – 13:00) ✅

把 11:33 的计划做成可用的点读 HTML。代码与完整产物在**私有仓** [`CacinieP/deutsch-voice`](https://github.com/CacinieP/deutsch-voice)（含歌德版权 PDF/词表派生音频，故不公开）；本仓 `04-application/` 放脱敏 demo。

### 做了什么

- **资料层**：歌德 A0–A2 官方 PDF（5 个）→ raw 文本 → `saetze.md`(235 句) + `wortliste-a1/a2.md`。
- **TTS 层**：VoxCPM2（ModelBest 免费 API，OpenAI `/v1/audio/speech` 兼容格式）→ WAV → ffmpeg 转 MP3。
- **句子音频**：235 句（A0=15, A1=100, A2=120），base64 内嵌进单文件 HTML。
- **单词音频**：1952 词（A1=624, A2=1328），**带定冠词**（`der Apfel` 而非 `Apfel`），呼应形态学「连冠词一起背」方法。
- **点读页**：`deutsch-voice.html`（29MB，双击即用，Safari/Chrome 均可，哪里不会点哪里）。

### 关键 bug 修复：单词不读冠词

初版单词朗读走浏览器 `speechSynthesis`，播放函数里有一条正则**把 der/die/das 删掉了**——点到 `der Apfel` 只听到 "Apfel"。形态学笔记明确要求「**记复数连 die 一起背**」「**性是名词的一部分**」，删冠词等于把学的骨架抽掉了。修复方案：改用预生成带冠词 MP3 内嵌，与句子音频管线一致。

### 顺带清掉的脏数据

- `A2WORDS` 里混入 42 条 PDF 解析残片（`n.` / `ch.` / `n Durst.` / `t mir nicht.` 等），清掉后 1370 → 1328 词。
- 旧 `output/words/`（1507 个孤儿 mp3，HTML 从未引用）标注废弃。

### 复现脚本（私有仓）

```bash
python3 clean_and_reindex.py   # 清洗 A2WORDS 解析残片 + 重建映射
python3 tts_words.py           # 生成 1952 词音频（~16 分钟）
python3 rebuild_html.py        # 注入 WORD_AUDIO_DB + 改写 speakWord
```

---

## 待办 / Upcoming

- [ ] CP2 · 形态学补全收尾（14:00 前 push）
- [ ] CP3 · 0–A2 句法规则遍历（V2 语序、从句动词尾置、框形结构、四格支配、介词+格）
- [ ] CP4 · 综合自测 + 收官小结
- [x] ~~voxcpm2 HTML 音频点读实现（TTS + 歌德 0-A2 大纲）~~ ✅ 2026-08-08 13:00 完成（私有仓 deutsch-voice + 本仓 04-application 脱敏 demo）
