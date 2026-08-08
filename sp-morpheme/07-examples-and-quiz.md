# 07 · 语素分析示例与自测 (Morphemanalyse & Selbsttest)

> 把前 6 篇串起来:**拿到任意一个词,从左到右切成语素,标注每个零件的类型与功能**。
> 能稳定拆词 = 真正理解了德语词汇的构造原理。

---

## 1. 语素类型标注系统

分析时用以下标记:

| 标记 | 类型 | 例 |
|---|---|---|
| **W** | 词根 Wurzel(free root) | `fahr`, `Haus` |
| **Pfx-d** | 派生前缀 | `ver-`, `be-`, `er-` |
| **Sfx-d** | 派生后缀 | `-ung`, `-heit`, `-bar` |
| **Pfx-t** | 可分前缀 | `ab-`, `an-`, `auf-` |
| **Flex** | 屈折词缀 | `-e`(人称), `ge-`(分词), `-s`(Gen) |
| **Fuge** | 连接元素(非语素) | `-s-`, `-en-` |
| **Konp** | 复合成分标记 | Bestimmung / Grund |

---

## 2. 完整分析示例(由浅入深)

### 示例 1 · `Wohnungen` [A1]

```
W oh n u ng en
│       │    │
│       │    └─ Flex: 复数 -en(屈折)
│       └────── Sfx-d: -ung(派生后缀,动→阴名)
└──────────── W: wohn-(词根,自由,动词)
```
- 语素:`wohn`(W)+ `ung`(Sfx-d)+ `en`(Flex 复数)
- 解读:居住 + 名词化 → 住所 → 复数

### 示例 2 · `Freundschaft` [A2]

```
Freund schaft
  │     │
  │     └─ Sfx-d: -schaft(派生后缀,名→阴名集合)
  └────── W: Freund(词根,自由,名词)
```
- 语素:`Freund`(W)+ `schaft`(Sfx-d)
- 解读:朋友 + 集合状态 → 友谊

### 示例 3 · `Unabhängigkeit` [B2/C1]

```
Un ab häng ig keit
 │  │   │   │   │
 │  │   │   │   └─ Sfx-d: -keit(派生后缀,形→阴名抽象)
 │  │   │   └───── Sfx-d: -ig(派生后缀,根→形)
 │  │   └───────── W: häng-(词根,来自 hängen)
 │  └─────────── Pfx-t: ab-(可分前缀,脱离)
 └────────────── Pfx-d: un-(派生前缀,否定,否定形容词)
```
- 语素:`un`(Pfx-d)+ `ab`(Pfx-t)+ `häng`(W)+ `ig`(Sfx-d)+ `keit`(Sfx-d)
- 解读:不 + 脱 + 依附 + 的 + 性 = 独立性

### 示例 4 · `Verantwortlichkeit` [B2]

```
Ver ant wort lich keit
 │   │    │    │   │
 │   │    │    │   └─ Sfx-d: -keit(形→名)
 │   │    │    └───── Sfx-d: -lich(根/名→形)
 │   │    └────────── W: wort(词根,Antwort 的一部分)
 │   └─────────────── (Antwort 本身 = ant + wort 复合)
 └─────────────────── Pfx-d: ver-(不可分前缀,转变)
```
- 语素:`ver`(Pfx-d)+ `antwort`(W,复合词根)+ `lich`(Sfx-d)+ `keit`(Sfx-d)
- 解读:转变 + 答 + 的 + 性 = 责任(感)

### 示例 5 · `Kühlschrank` [A2](复合)

```
Kühl s Schrank
 │   │   │
 │   │   └─ W: Schrank(基础词,定词性:阳)
 │   └───── Fuge: -s-(连接元素,非语素)
 └───────── W: kühl(限定词,自由,形容词)
```
- 语素:`kühl`(W·Bestimmung)+ `[s Fuge]`+ `Schrank`(W·Grundwort)
- 解读:凉 + 柜 = 冰箱(复合,非派生)

### 示例 6 · `unverständlich` [B1]

```
Un ver steh lich
 │   │   │    │
 │   │   │    └─ Sfx-d: -lich(根/动→形)
 │   │   └────── W: steh-(词根,stehen)
 │   └────────── Pfx-d: ver-(不可分前缀)
 └────────────── Pfx-d: un-(否定)
```
- 语素:`un`(Pfx-d)+ `ver`(Pfx-d)+ `steh`(W)+ `lich`(Sfx-d)
- 解读:不 + 理解 + 的 = 不可理解的

### 示例 7 · `Nahrungsmittelunverträglichkeit` [C1](超长复合)

```
Nahrung + s + Mittel + Un + ver + träglich + keit
  │       │    │       │    │      │         │
  │       │    │       │    │      │         └─ Sfx-d -keit
  │       │    │       │    │      └────────── W: trag-(根)+ -ig(Sfx-d)+ -lich(合)
  │       │    │       │    └───────────────── Pfx-d: ver-
  │       │    │       └────────────────────── Pfx-d: un-
  │       │    └────────────────────────────── W: Mittel(根)
  │       └─────────────────────────────────── Fuge -s-
  └─────────────────────────────────────────── W: Nahrung(根)
```
- 拆解:`Nahrung`(W)+ `[s Fuge]`+ `Mittel`(W)+ `un`(Pfx-d)+ `ver`(Pfx-d)+ `träglich`(W+Sfx-d)+ `keit`(Sfx-d)
- 解读:食物 + 制品 + 不 + 能忍 + 的 + 性质 = 食物不耐受

---

## 3. 拆词自测(A1–C2,30 题)

> 拆分下列词,标注每个语素类型(W / Pfx-d / Sfx-d / Pfx-t / Flex / Fuge)。

### A1–A2

1. `Mädchen`
2. `Zeitung`
3. `Schreibtisch`
4. `Lehrerin`
5. `Arbeiter`
6. `Freiheit`
7. `Sicherheit`
8. `Möglichkeit`
9. `ankommen`
10. `einkaufen`
11. `Häuschen`
12. `täglich`
13. `freundlich`
14. `Wohnung`
15. `Bedeutung`

### B1

16. `Entwicklung`
17. `Entscheidung`
18. `Erfahrung`
19. `erklären`
20. `erfinden`
21. `verändern`
22. `lesbar`
23. `arbeitslos`
24. `wissenschaftlich`
25. `Verständnis`

### B2

26. `Unabhängigkeit`
27. `Verantwortlichkeit`
28. `unverständlich`
29. `Zusammenarbeit`
30. `Nahrungsmittel`

---

## 4. 答案(Lösungen)

1. `Mädchen` = `Magd`(W,古)+ `chen`(Sfx-d·指小,中)。注:现代已不分析为 Magd+chen,整体视作词根。
2. `Zeitung` = `Zeit`(W)+ `ung`(Sfx-d)
3. `Schreibtisch` = `schreib`(W·动词干)+ `Tisch`(W·基础词)= 复合
4. `Lehrerin` = `lehr`(W)+ `er`(Sfx-d·指人)+ `in`(Sfx-d·女性)
5. `Arbeiter` = `arbeit`(W)+ `er`(Sfx-d·指人)
6. `Freiheit` = `frei`(W)+ `heit`(Sfx-d)
7. `Sicherheit` = `sicher`(W)+ `heit`(Sfx-d)
8. `Möglichkeit` = `möglich`(W,内含 -lich)+ `keit`(Sfx-d)
9. `ankommen` = `an`(Pfx-t·可分)+ `komm`(W)
10. `einkaufen` = `ein`(Pfx-t)+ `kauf`(W)
11. `Häuschen` = `Haus`(W,变元音)+ `chen`(Sfx-d)
12. `täglich` = `Tag`(W,变元音)+ `lich`(Sfx-d)
13. `freundlich` = `Freund`(W)+ `lich`(Sfx-d)
14. `Wohnung` = `wohn`(W)+ `ung`(Sfx-d)
15. `Bedeutung` = `be`(Pfx-d)+ `deut`(W)+ `ung`(Sfx-d)
16. `Entwicklung` = `ent`(Pfx-d)+ `wickel`(W)+ `ung`(Sfx-d)
17. `Entscheidung` = `ent`(Pfx-d)+ `scheid`(W)+ `ung`(Sfx-d)
18. `Erfahrung` = `er`(Pfx-d)+ `fahr`(W)+ `ung`(Sfx-d)
19. `erklären` = `er`(Pfx-d)+ `klär`(W)
20. `erfinden` = `er`(Pfx-d)+ `find`(W)
21. `verändern` = `ver`(Pfx-d)+ `änder`(W)
22. `lesbar` = `les`(W)+ `bar`(Sfx-d·可…)
23. `arbeitslos` = `arbeit`(W)+ `s`(Fuge)+ `los`(Sfx-d·无)
24. `wissenschaftlich` = `Wissen`(W)+ `schaft`(Sfx-d)+ `lich`(Sfx-d)
25. `Verständnis` = `ver`(Pfx-d)+ `ständ`(W,stehen 变体)+ `nis`(Sfx-d·结果)
26. `Unabhängigkeit` = `un`(Pfx-d)+ `ab`(Pfx-t)+ `häng`(W)+ `ig`(Sfx-d)+ `keit`(Sfx-d)
27. `Verantwortlichkeit` = `ver`(Pfx-d)+ `antwort`(W)+ `lich`(Sfx-d)+ `keit`(Sfx-d)
28. `unverständlich` = `un`(Pfx-d)+ `ver`(Pfx-d)+ `steh`(W)+ `lich`(Sfx-d)
29. `Zusammenarbeit` = `Zusammen`(副)+ `arbeit`(W)= 复合
30. `Nahrungsmittel` = `Nahrung`(W)+ `s`(Fuge)+ `Mittel`(W)= 复合

---

## 5. 拆词心法(Methode)

拿到一个长词,按以下步骤:

1. **找基础词**(最右边能独立成词的部分)→ 它定词性和核心义。
2. **往前切**:每切一段,问「这是词根还是词缀?」
   - 有义、能独立 → **词根 W**(或复合的限定词)。
   - 无义、表功能 → **词缀**(派生 / 屈折)。
3. **判词缀类型**:
   - 改词性/词义 → **派生**(Pfx-d / Sfx-d)。
   - 只变格/人称 → **屈折**(Flex)。
   - 可分/重音 → **可分前缀**(Pfx-t)。
4. **处理变元音/Allomorph**:`Sprach-/sprech-/gesproch-` 是同一根的变体。
5. **复合判定**:如果前后都是能独立的词根 → **复合**(Fuge 可能存在)。

---

## 6. 小结

- 任何德语词 = **有限词根 + 有限词缀 + 复合规则** 的组合。
- ~300 词根 + ~80 词缀 + 复合 = 理解上万个词的能力。
- 拆词能力 = **从「背单词」升级到「算单词」**:见词即拆,拆即理解。

这是 sp-morpheme 模块的终极目标:把德语词汇从「无限」还原为「有限可算」。

---

_本模块完。配合 `01-phonology-alphabet/`(读音)与 `02-morphology/`(变格变位)使用,形成 A1–C2 词汇的完整语言学工具链。_
