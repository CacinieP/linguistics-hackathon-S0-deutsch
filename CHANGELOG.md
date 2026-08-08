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

### 新计划：voxcpm2 个性化音频点读 (11:33 提出)

- 使用 **voxcpm2**（支持 30+ 语种的 TTS）生成个性化 HTML 音频点读页。
- 基于歌德学院 0-A2 大纲，把学过的语音/形态内容做成可点击发音的点读卡片。
- modelbest 免费 API 体验平台：https://platform.modelbest.cn/console/login?ref=A93DCA73
- 状态：**计划中**，待 CP2 收尾后启动实现。

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
| 14:00 | CP2 截止（形态学，进行中）|
| 18:00 | CP3 截止（句法遍历）|
| 22:00 | CP4 截止（应用 & 自测）|

---

## 待办 / Upcoming

- [ ] CP2 · 形态学补全收尾（14:00 前 push）
- [ ] CP3 · 0–A2 句法规则遍历（V2 语序、从句动词尾置、框形结构、四格支配、介词+格）
- [ ] CP4 · 综合自测 + 收官小结
- [ ] voxcpm2 HTML 音频点读实现（TTS + 歌德 0-A2 大纲）
