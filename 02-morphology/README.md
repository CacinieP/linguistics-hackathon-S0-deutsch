# 02 · 形态学补全 (Morphologie)

> CP2 · 形态学阶段。目标:拿到任意一个德语名词/动词/形容词,能说清它的**性、数、格 / 时态、人称 / 比较等级**,并能把缺失的词形**补全**。

德语的"难"九成在形态:性、格、变位、变格。但只要把**骨架表**背牢,剩下的全是填空。

---

## 1. 名词 (Substantiv)

### 1.1 三性 (Genus): der / die / das

每个名词有固定语法性,与自然性别无关。

| 性 | 定冠词 | A1–A2 高频例 |
|---|---|---|
| **阳性 m.** | der | der Mann, Tisch, Montag, Vater, Löffel |
| **阴性 f.** | die | die Frau, Sonne, Hand, Mutter, Gabel |
| **中性 n.** | das | das Kind, Mädchen, Buch, Auto, Messer |
| **复数 Pl.** | die | die Leute, Kinder, Bücher, Autos |

> ⚠️ **所有复数定冠词都是 die**,不管单数什么性。这是最大安慰也是最大陷阱。

#### 性别判定规则(强,按后缀记最快)

| 后缀 → 性 | 后缀 |
|---|---|
| **阳性** | `-ig -ling -ismus -ant -ent -or -er`(指人) `-ich` |
| **阴性** | `-ung -heit -keit -schaft -tion -tät -ur -ik -ei -in` |
| **中性** | `-chen -lein -ment -tum -ma -(i)um`;**动词不定式做名词**(`das Essen, das Sprechen`) |

> **例外预警**:
> - `das Mädchen`(虽然指女孩,但 `-chen` 永远中性)——性 ≠ 自然性别。
> - 阳性无后缀的自然物:**der Baum, der Tisch, der Tag** 多靠死记。
> - 日/月/季节多阳:**der Montag, der Mai, der Winter**;但 **die Woche, das Jahr**。
> - 方位、颜色(做名词)、车 brand 多中/阴:das Auto, das Blau。

### 1.2 单复数 (Numerus)

德语复数**有 5 种标记**,要连冠词一起记:`der Apfel → die Äpfel`。

| 类型 | 加 | 例 | 频率 |
|---|---|---|---|
| ① 加 **-e** | (-e) | das Wort → die Wörter; der Tisch → die Tische | 最常见 |
| ② 加 **-er**(常带变元音) | -er | das Buch → die Bücher; das Kind → die Kinder | 中性多 |
| ③ 加 **-n / -en**(阴性主导) | -n/-en | die Frau → die Frauen; die Zeitung → die Zeitungen | 阴性几乎全用 |
| ④ 加 **-s**(外来/缩略) | -s | das Auto → die Autos; der Park → die Parks | 外来词 |
| ⑤ 零标记(只变元音) | ∅ + 变元音 | der Vater → die Väter; die Mutter → die Mütter | 少数 |

> **记复数的诀窍:连 die + 复数形一起背**,而不是只背"Apfel 的复数是 Äpfel"。视觉记忆 `der Apfel / die Äpfel`。

> 🔊 **配套点读工具**:`04-application/` 的点读页给每个名词都生成了**带定冠词**的语音（`der Apfel` 而非裸 `Apfel`），点击即念完整词条——强迫耳朵把「性 + 词」当一个整体记。这正是本节「连冠词一起背」方法论的落地。（实现细节见 CHANGELOG「voxcpm2 点读工具实现」段；因歌德词表版权，本仓 demo 用原创例词。）

### 1.3 四格 (Kasus) —— 德语形态的心脏

| 格 | 问 | 功能 | m. | n. | f. | Pl. |
|---|---|---|---|---|---|---|
| **Nominativ** 主 | Wer? Was? | 主语/表语 | der | das | die | die |
| **Akkusativ** 宾 | Wen? Was? | 直接宾语 | **den** | das | die | die |
| **Dativ** 与 | Wem? | 间接宾语 | **dem** | dem | **der** | **den (+n)** |
| **Genitiv** 属 | Wessen? | 所有 | **des (+s)** | des (+s) | der | der |

**最小记忆量**:
- Akkusativ **只有阳性变了**(der→den)。
- Dativ **阳中→dem,阴→der,复数→den 且名词尾加 -n**。
- Genitiv **阳中→des,名词加 -(e)s**;A2 用得少,口语多用 `von`。

### 1.4 冠词变格全表(定冠词 + 不定冠词)

#### 定冠词 (bestimmter Artikel)

| | m. | n. | f. | Pl. |
|---|---|---|---|---|
| Nom | der | das | die | die |
| Akk | **den** | das | die | die |
| Dat | dem | dem | **der** | **den** |
| Gen | des | des | der | der |

#### 不定冠词 (unbestimmter Artikel) —— 无复数

| | m. | n. | f. |
|---|---|---|---|
| Nom | ein | ein | eine |
| Akk | **einen** | ein | eine |
| Dat | einem | einem | einer |
| Gen | eines | eines | einer |

#### 否定冠词 (kein) —— 跟不定冠词同形,但有复数

| | m. | n. | f. | Pl. |
|---|---|---|---|---|
| Nom | kein | kein | keine | keine |
| Akk | keinen | kein | keine | keine |
| Dat | keinem | keinem | keiner | keinen |
| Gen | keines | keines | keiner | keiner |

> **记忆口诀**:定冠词背熟 → 不定冠词"少了复数那列" → kein = 不定冠词 + 补回复数列。三表一锅端。

#### 物主冠词 (mein/dein/sein…) —— 变格同 `kein`

只换词干,词尾完全跟 kein:`mein Vater, meinen Vater, meinem Vater…`。

### 1.5 名词变格 (Substantivdeklination)

绝大多数名词**只在 Gen/Dat 改变**。但有 3 类**词尾也变**的"弱变化":

#### ① 弱变化名词 (n-Deklination) —— 阳性为主

某些阳性名词(及少数中性)在**非 Nom 单数全部加 -(e)n**:

| Nom | Akk | Dat | Gen | 规律 |
|---|---|---|---|---|
| der Herr**n** | den Herr**n** | dem Herr**n**(e) | des Herr**n** | 词干也加 n |
| der Student | den Student**en** | dem Student**en** | des Student**en** | 后缀类 |
| der Junge**n** | den Junge**n** | dem Junge**n** | des Junge**n** | -e 结尾 |

> 常见 n-变化阳性:**der Herr, Student, Junge, Kollege, Name(`des Namens` 带 s), Löwe, Affe, Neffe,zeuge→**
> 记法:**"所有格非主单,一律 -(e)n"**。唯一例外:`des Herrn`(Gen 也加 n)。

#### ② Genitiv 加 -s(普通阳中)

| Nom | Gen |
|---|---|
| der Tag | des Tag**es** |
| das Buch | des Buch**es** |
| das Auto | des Auto**s** |

> 多音节、以元音结尾、外来词加 `-s`;短词、辅音簇加 `-es`。

#### ③ 形容词式变格(仅 `Herz` 等极个别)

`das Herz → des Herzens, dem Herzen`。A2 记一个 `Herz` 即可。

---

## 2. 代词 (Pronomen)

### 2.1 人称代词

| Nom | Akk | Dat | 含义 |
|---|---|---|---|
| ich | mich | mir | 我 |
| du | dich | dir | 你(单非正式) |
| er | ihn | ihm | 他 |
| sie | sie | ihr | 她 |
| es | es | ihm | 它 |
| wir | uns | uns | 我们 |
| ihr | euch | euch | 你们(复非正式) |
| Sie / sie | Sie / sie | Ihnen / ihnen | 您 / 他们 |

> Akk/Dat 形式一定要和冠词一起记:`den → ihn, dem → ihm; die → sie, der → ihr`。

### 2.2 反身代词 (sich)

| 人称 | Akk | Dat |
|---|---|---|
| ich | mich | mir |
| du | dich | dir |
| er/sie/es | **sich** | **sich** |
| wir | uns | uns |
| ihr | euch | euch |
| sie/Sie | **sich** | **sich** |

> 三单和三复是 `sich`。反身动词:`sich freuen auf`(Akk) / `sich interessieren für`(Akk) / `sich etwas ansehen`(Dat 反身)。

---

## 3. 动词 (Verb)

### 3.1 现在时变位 (Präsens) —— 规则

词干 + 词尾。**1/3 复数同形**(wir/Sie/sie)。

| 人称 | 词尾 | sagen | lernen |
|---|---|---|---|
| ich | -e | sag-e | lern-e |
| du | -st | sag-st | lern-st |
| er/sie/es | -t | sag-t | lern-t |
| wir | -en | sag-en | lern-en |
| ihr | -t | sag-t | lern-t |
| sie/Sie | -en | sag-en | lern-en |

### 3.2 强变化动词(元音交替)

第二、三人称单数**词干元音变**:`a→ä, e→i/ie, au→äu`。

| 不定式 | ich | du | er |
|---|---|---|---|
| **fahren** | fahre | f**ä**hrst | f**ä**hrt |
| **geben** | gebe | g**i**bst | g**i**bt |
| **sehen** | sehe | s**ie**hst | s**ie**ht |
| **lesen** | lese | l**ie**st | l**ie**st |
| **sprechen** | spreche | spr**i**chst | spr**i**cht |
| **nehmen** | nehme | n**imm**st | n**imm**t(双重变化!) |
| **laufen** | laufe | l**ä**ufst | l**ä**uft |

> 记法:**只有 du/er 单数变,ich/wir/ihr/Sie 不变**。A2 常考的 10 个左右,集中突击。

### 3.3 不规则但不变元音的几个

| | ich | du | er |
|---|---|---|---|
| **sein** | bin | bist | ist |
| **haben** | habe | hast | hat |
| **werden** | werde | wirst | wird |
| **wissen** | weiß | weißt | weiß |

### 3.4 情态动词 (Modalverben)

**变位特殊**:1/3 单数无词尾 -t,词干变。

| | können | müssen | dürfen | sollen | wollen | mögen→möchte* |
|---|---|---|---|---|---|---|
| ich | kann | muss | darf | soll | will | möchte |
| du | kannst | musst | darfst | sollst | willst | möchtest |
| er | kann | muss | darf | soll | will | möchte |
| wir | können | müssen | dürfen | sollen | wollen | möchten |

> *`möchte` 是 `mögen` 的虚拟式,但 A1/A2 当独立词用(表示"想要"),它**没有过去式**,过去式借 `wollte`。
> **情态动词的句法**:变位在第二位,**动词原形放句尾**:`Ich muss heute arbeiten.`(框形结构,见 03 句法)。

### 3.5 时态(A2 范围)

| 时态 | 何时用 | 构成 |
|---|---|---|
| **Präsens** 现在 | 现状、未来确定计划 | 词干+词尾 |
| **Perfekt** 完成时(口语过去) | 口语讲过去的事 | haben/sein + 过去分词 |
| **Präteritum** 过去时 | 书面、叙述 | 词干 + -te(弱)/ 强变化表 |
| **Futur I** 将来 | 明确将来/意图 | werden + 不定式 |

#### 过去分词 (Partizip II)

- **弱动词**:`ge- + 词干 + -(e)t` → `machen → ge-mach-t, lernen → ge-lern-t`
- **强动词**:`ge- + 变化词干 + -en` → `trinken → ge-trunk-en, sehen → ge-seh-en`
- **以 -ieren 结尾外来词**:**无 ge-** → `studieren → studiert, passieren → passiert`
- **不可分前缀**(be-/ver-/er-/ent-/emp-/miss-/zer-/ge-):**无 ge-** → `ver-stehen → ver-stan-den`
- **可分前缀**:ge- 插中间 → `auf-stehen → auf-ge-stand-en`

#### haben 还是 sein 作助动词?

- **haben**:绝大多数及物动词、反身动词、情态动词。
- **sein**:**位移**(gehen, fahren, kommen, fliegen)、**状态改变**(werden, sterben, aufwachen)、**短暂停留**(sein, bleiben)。

> `Ich bin nach Berlin gefahren.`(位移=sein)
> `Ich habe das Auto gefahren.`(有宾语=haben)—— **同一个动词 fahren 看用法!**

### 3.6 可分动词 (Trennbare Verben) —— A2 重点

重音在前缀上的动词,变位时**前缀跑到句尾**:

| 不定式 | 句中 | 释义 |
|---|---|---|
| **anrufen** | Ich rufe dich **an**. | 打电话 |
| **einkaufen** | Ich kaufe ein. | 购物 |
| **aufstehen** | Ich stehe um 7 Uhr **auf**. | 起床 |
| **mitkommen** | Kommst du **mit**? | 一起来 |
| **fernsehen** | Ich sehe **fern**. | 看电视 |

**可分前缀**(重读):`ab- an- auf- aus- ein- mit- nach- vor- zu- zurück- zusammen-`
**不可分前缀**(不重读,无 ge-):`be- ge- er- ver- zer- ent- emp- miss-`

> 判定靠**重音**:重音在前缀 → 可分;重音在词干 → 不可分。少数动词两重(`wiederholen` 取舍不同义)。

---

## 4. 形容词与比较 (Adjektiv & Komparation)

### 4.1 作定语时的词尾变格 —— A2 最难点之一

形容词在名词前要加**变格词尾**。分两种范式:

#### 定冠词后 (schwache Deklination)

> 冠词已显格,形容词只加 `-e` 或 `-en`。

| | m. | n. | f. | Pl. |
|---|---|---|---|---|
| Nom | -e | -e | -e | -en |
| Akk | -en | -e | -e | -en |
| Dat | -en | -en | -en | -en |
| Gen | -en | -en | -en | -en |

> 口诀:**只有 Nom.m./n./f. 和 Akk.n./f. 是 -e,其余全 -en**(5 个 -e,其余 -en)。

#### 不定冠词 / 物主后 (gemischte Deklination)

| | m. | n. | f. |
|---|---|---|---|
| Nom | -er | -es | -e |
| Akk | -en | -es | -e |
| Dat | -en | -en | -en |
| Gen | -en | -en | -en |

> 口诀:**Nom/Akk 看定冠词缺什么就补什么**(ein **guter** Mann = 缺 der 的 -er),其余 -en。

#### 无冠词 (starke Deklination)

> 形容词承担全部格信息,词尾≈定冠词词尾。

| | m. | n. | f. | Pl. |
|---|---|---|---|---|
| Nom | -er | -es | -e | -e |
| Akk | -en | -es | -e | -e |
| Dat | -em | -em | -er | -en |
| Gen | -en | -en | -er | -er |

> 三套总规律:**"谁没标,谁补标"**——冠词没显示的格信息,由形容词词尾补上。

### 4.2 比较等级 (Komparation)

| 级 | 构成 | 例 |
|---|---|---|
| 原级 | — | klein, schön |
| 比较级 | + `-er` | klein-er, schön-er |
| 最高级 | + `-st` | klein-st, schön-st |

- 单音节、强变化动词词干常**变元音**: alt→ält-er→ält-est, groß→größ-er→größ-t, jung→jüng-er, viel→mehr→meist。
- 形容词最高级作定语:**有定冠词式**(`der/die/das + -st + 变格词尾`):`das schönste Haus`。

#### 不规则比较级(必背)

| 原级 | 比较级 | 最高级 |
|---|---|---|
| gut | besser | am besten / der beste |
| viel | mehr | am meisten |
| hoch | höher | am höchsten |
| groß | größer | am größten |
| nah | näher | am nächsten |

### 4.3 作表语/副词 —— 不变格

`Der Mann ist groß.`(表语) / `Er läuft schnell.`(副词)—— 形容词**不带词尾**。

---

## 5. 形态学补全练习 (Aufgaben)

> 把"补全"做到能条件反射,本阶段就过了。

### 练习 A:给格位填冠词

1. Ich gebe ___ Lehrer ___ Buch. (m./n., Dat/Akk)
2. Wir warten auf ___ Bus. (m., Akk)
3. ___ Mutter kauft ___ Kinder ___ Eis. (f./Pl./n.)

<details><summary>答案</summary>

1. dem / ein
2. den
3. Die / den / ein
</details>

### 练习 B:填动词变位

1. Wir ___ (fahren) nach München.
2. Er ___ (lesen) ein Buch.
3. ___ du ___ (mitkommen)?
4. Ich ___ (müssen) morgen früh ___ (aufstehen).

<details><summary>答案</summary>

1. fahren
2. liest
3. Willst / kommst … mit
4. muss … aufstehen
</details>

### 练习 C:过去分词

写出 Partizip II:`machen, trinken, studieren, verstehen, aufstehen, kaufen`

<details><summary>答案</summary>

gemacht, getrunken, studiert, verstanden, aufgestanden, gekauft
</details>

### 练习 D:形容词词尾

1. ein klein_ Hund (m. Nom)
2. das schön_ Haus (n. Nom)
3. mit ein_ alt_ Freund (m. Dat)
4. frisch_ Brot (n. Nom, 无冠词)

<details><summary>答案</summary>

1. kleiner
2. schöne
3. einem alten
4. frisches
</details>

---

## 6. 此刻学会了什么 / 还卡在哪 (CP2 现场记录)

- [x] 四格全表 + 定/不定/kein/物主四套冠词
- [x] 现在时规则 + 强变化 du/er 元音交替
- [x] 可分/不可分前缀 + 重音判定
- [ ] 形容词三套变格还得查表,没到条件反射
- [ ] Perfekt 用 haben 还是 sein 还要现场判断

---

## 📚 参考 / References

- Duden · *Die Grammatik*
- Helbig/Buscha · *Deutsche Grammatik*
- Goethe-Institut A1/A2 词汇表
- Hueber / Hueber Arbeitsbuch Morphologie
