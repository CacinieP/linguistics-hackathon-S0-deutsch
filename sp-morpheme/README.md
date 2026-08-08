# sp-morpheme · 德语语素层级分类 (Morphemische Hierarchie A1–C2)

> 把 0→C2 词汇拆到**语素(Morphem)**层级,按树形结构分类。
> 应用是副产品,这里是为了**真正看懂德语词是怎么组装的**——拆到底,所有"难词"都是熟悉的零件拼出来的。

---

## 0. 为什么是「语素」而不是「单词」

德语词汇的 90% 不是死的整体,而是**可拆解的零件组合**:

- `Un-ver-frei-lich-keit`(不可原谅性)= `un-` + `ver-` + `frei` + `-lich` + `-keit`
- `Ver-ant-wort-lich-keit`(责任)= `ver-` + `antwort`(答) + `-lich` + `-keit`
- `Kühlschrank`(冰箱)= `kühl`(凉)+ `Schrank`(柜)

一旦把 0→C2 的词汇拆到**语素层级**,你会发现:掌握 ~300 个词根 + ~80 个词缀,就能理解、生成、记忆上万个词。这就是本模块的目的。

---

## 1. 语素的两大分类(Top-Level)

```
语素 Morphem
├── 自由语素 freies Morphem (free) —— 能独立成词
│   ├── 词根 Wurzel/Root (Lexikalischer Kern)
│   └── 功能词 Funktionswort (介词/冠词/连词等)
└── 黏着语素 gebundenes Morphem (bound) —— 不能独立出现
    ├── 派生词缀 Derivationsmorphem (改变词性/词义)
    │   ├── 前缀 Präfix
    │   └── 后缀 Suffix
    └── 屈折词缀 Flexionsmorphem (只变格位/人称/时态,不变词性)
        ├── 名词变格 Nominalflexion
        ├── 动词变位 Verbalflexion
        └── 形容词变格 Adjektivflexion
```

外加一类跨层级的构词方式:**复合 Komposition**(词根+词根 → 新词),如 `Kühlschrank`。

---

## 2. 文件导航 / 目录结构

本模块拆成多个文件,按语素类型组织:

| 文件 | 内容 | 语素类型 |
|---|---|---|
| `01-free-roots.md` | 自由语素·词根(名词/动词/形容词核心词根,A1→C2 分层) | 自由·词根 |
| `02-free-function.md` | 自由语素·功能词(冠词/介词/代词/连词/情态) | 自由·功能 |
| `03-derivational-prefixes.md` | 派生前缀(不可分 be-/ver-…、可分 ab-/an-…、外来前缀) | 黏着·派生 |
| `04-derivational-suffixes.md` | 派生后缀(-ung/-heit/-keit/-lich/-bar…,按产出词性分) | 黏着·派生 |
| `05-compounds.md` | 复合词(名词+名词、动词+名词、限定关系类型) | 跨层级·复合 |
| `06-inflectional.md` | 屈折词缀(变格/变位/比较级/分词) | 黏着·屈折 |
| `07-examples-and-quiz.md` | 完整语素树分析示例 + 自测拆词 | 综合 |

---

## 3. CEFR 分层标记法

每个词根/词例标注 CEFR 等级,方便按阶段攻克:

| 标记 | 等级 | 词汇量参考 |
|---|---|---|
| `[A1]` | 入门 | ~500 词 |
| `[A2]` | 基础 | ~1000 词(累计 ~1500) |
| `[B1]` | 中级 | ~2000 词(累计 ~3500) |
| `[B2]` | 中高级 | ~2500 词(累计 ~6000) |
| `[C1]` | 高级 | ~2500 词(累计 ~8500) |
| `[C2]` | 精通 | ~3000+ 词(累计 ~11500) |

---

## 4. 一张图看懂「一个 C2 词是怎么拼起来的」

```
Unabhängigkeit (独立性) [B2/C1]
│
├─ un-        (派生前缀·否定)         ← 03-derivational-prefixes
├─ ab-häng    (词根:hängen 的可分变体)← 01-free-roots
│   ├─ ab-    (可分前缀·分离/脱离)
│   └─ -häng  (词根:悬挂/依附)
├─ -ig        (派生后缀·形容词化)     ← 04-derivational-suffixes
└─ -keit      (派生后缀·名词化)        ← 04-derivational-suffixes

= un + ab + häng + ig + keit = 不 + 脱 + 离 + 的 + 性 = 独立性
```

> 同一根 `häng-`[A1](挂)还能长出:`abhängen`(依赖)、`aufhängen`(挂起)、`aushängen`、`umhängen`、`verschieden…`——**一个词根 = 一串词**。这是语素视角的力量。

---

## 5. 阅读建议

1. 先读 `01-free-roots.md` —— 词根是宇宙的中心,~300 高频根覆盖大半词汇。
2. 再读 `04-derivational-suffixes.md` —— 后缀决定词性,最规律、回报最高。
3. 然后 `03-derivational-prefixes.md` —— 前缀改变/微调词义。
4. 最后 `05-compounds.md` —— 复合是德语的招牌,规则简单但威力巨大。
5. 用 `07-examples-and-quiz.md` 自测拆词能力。

---

_本模块为学习直播黑客松的副产品之一,词汇覆盖 A1–C2 的高频核心,旨在建立"可无限生长"的记忆网络,而非穷举全部词典词。_
