# 03 · 0–A2 句法规则遍历 (Syntax)

> CP3 · 句法阶段。目标:拿到任何一个德语句子,能说清它的**语序、框形结构、格支配**,并能把缺掉的词补回正确的位置。

形态学解决「一个词长什么样」,句法解决「词与词怎么排队」。德语句法九成的难点收敛在两条铁律:**动词第二位 (V2)** 与 **框形结构 (Satzklammer)**。把这两条背成肌肉记忆,剩下的全是填空。

---

## 1. 语序总原则:动词第二位 (V2)

### 1.1 主句 V2 —— 德语句法的地基

**陈述主句里,变位动词永远在第二个位置 (Position 2)。** 不是「第二个词」,是「第二个成分」——主语、宾语、时间状语、地点状语,任何一个都能占第一位。

| 位 1 (话题) | **位 2 (动词)** | 位 3+ | 译 |
|---|---|---|---|
| Ich | **lerne** | heute Deutsch. | 我今天学德语。 |
| Heute | **lerne** | ich Deutsch. | 今天我学德语。 |
| Deutsch | **lerne** | ich heute. | 德语我今天学。 |
| Um 7 Uhr | **stehe** | ich auf. | 我七点起床。 |

> ⚠️ **最大陷阱**:位 1 可以是任何成分,但**位 2 必须是动词**。把时间状语提前后,中文母语者常把主语也提前,写成 `Heute ich lerne Deutsch` ❌ —— 主语被挤到了位 3,动词就掉到第三位了。正确:`Heute lerne ich Deutsch.`

> 📐 **判断法**:数「成分」不数「词」。`Um 7 Uhr`(一个时间状语)= 1 个成分。`Ich`(主语)= 1 个成分。动词紧跟在第一个成分之后。

### 1.2 疑问句:动词回到位 1 (V1)

**是非问句 (Ja/Nein-Frage)**:动词直接提到句首。

- **Kommst** du mit? —— 你一起来吗?
- **Hast** du Zeit? —— 你有空吗?
- **Ist** das dein Auto? —— 这是你的车吗?

**特殊疑问句 (W-Frage)**:疑问词在位 1,动词仍在位 2。

| 位 1 (W) | **位 2** | 位 3+ |
|---|---|---|
| Wer | **ist** | das? |
| Was | **machst** | du? |
| Wo | **wohnst** | du? |
| Wann | **kommt** | der Zug? |
| Warum | **lernst** | du Deutsch? |
| Wie | **heißt** | du? |

> 疑问词表:`wer was wo wann wohin woher warum wieso wie welche(r/s) wie viel wie oft wie lange`。

### 1.3 命令式 (Imperativ) —— 动词在位 1

| 对象 | 形式 | 例 |
|---|---|---|
| du | 词干(去 -st,常去 -e) | **Komm**! **Trink**! **Lies**!(lesen→lies) |
| ihr | ihr 变位 | **Kommt**! **Trinkt**! |
| Sie | Sie 变位 + Sie | **Kommen** Sie! **Sprechen** Sie bitte langsamer! |

> du 命令式:强变化动词常变元音(`geben→Gib!`, `lesen→Lies!`, `fahren→Fahr!`),但 `sein` 特殊:`Sei! Seid! Seien Sie!`。

---

## 2. 框形结构 (Satzklammer) —— 德语句法的心脏

### 2.1 什么是「框」

德语里很多结构**由两半组成**,把句子其余内容夹在中间,像一个括号:

```
[ 左框 ............ 右框 ]
```

- **左框** = 变位动词(在位 2)
- **右框** = 动词的「另一半」,放句尾

中间夹的东西(宾语、状语)叫 **Mittelfeld**(中场)。

### 2.2 四种框

| 结构 | 左框 | 右框 | 例 |
|---|---|---|---|
| **情态动词** | muss | arbeiten | Ich **muss** heute **arbeiten**. |
| **完成时** | habe | gearbeitet | Ich **habe** gestern **gearbeitet**. |
| **可分动词** | rufe ... | an | Ich **rufe** dich morgen **an**. |
| **从句**(见 §3) | ..., dass | komme | Er sagt, **dass** ich morgen **komme**. |

> 🔑 **记法**:看到情态动词、haben/sein、可分前缀、从句连词,就条件反射地**把动词的另一半送进「右框」(句尾)**。这是德语「听感」的来源——句子两头是动词。

### 2.3 中场 (Mittelfeld) 的内部顺序

框中间的东西有个**经验顺序**(TEmpo-Mo-Lo,可背可不背,A2 知道即可):

**TeMPo** = **Te**mpus(时间)· **Mo**dus(方式)· **P**lace(地点)... 但德语是 **Time before Place**(和英语相反!)。

- ✅ Ich fahre **morgen** **nach Berlin**.(时间 → 地点)
- ❌ Ich fahre **nach Berlin** **morgen**.

> 例外:方向性强的 `nach Hause / zur Schule` 常紧跟动词。这条规则 A2 知道「时间先于地点」即可,别钻牛角尖。

### 2.4 nicht 的位置 —— 也被框结构支配

`nicht` 否定,位置是 A2 重点:

| 否定对象 | nicht 位置 | 例 |
|---|---|---|
| 整句 | 句末(右框前) | Ich komme heute **nicht**. |
| 带右框的句 | 右框**之前** | Ich habe das **nicht** **gesehen**. / Ich rufe dich **nicht** **an**. |
| 特定成分 | 紧贴被否成分 | Ich komme **nicht heute**, sondern morgen. |

> 口诀:**有右框,nicht 站右框前面;没右框,nicht 站句末**。

---

## 3. 从句 (Nebensatz) —— 动词尾巴

### 3.1 从句 = 动词跑到句尾

主句动词在位 2,但**从句里变位动词跑到句子的最末尾**。这是德语和英语最大的语序差异,也是 A2 必考。

| 连词 | 主句 | 从句(动词尾巴) |
|---|---|---|
| dass( that) | Ich glaube, | **dass** er morgen **kommt**. |
| weil( because) | Ich bleibe zu Hause, | **weil** ich krank **bin**. |
| dass( that) | Er sagt, | **dass** ich recht **habe**. |
| wenn( if/when) | **Wenn** ich Zeit **habe**, | komme ich. |

> ⚠️ **weil 从句最容易错**:英语 `because I am sick` 动词在中间,德语 `weil ich krank bin` 动词在尾巴。母语者口语有时用 `weil + 主句语序`(口语化),**考试一律按动词尾置**。

### 3.2 从句在前:动词第二位复活

从句整个当「位 1」,主句动词回到位 2:

- **Weil ich krank bin,** `bleibe` ich zu Hause.(从句=位1,bleibe=位2)
- **Wenn es regnet,** `lese` ich ein Buch.

> 又是 V2!「位 1 = 任意一个成分(包括一整个从句),位 2 = 动词」。

### 3.3 连词表

| 连词 | 义 | 用法 |
|---|---|---|
| **dass** | that | 引导宾语从句 |
| **weil** | 因为(原因) | 回答 warum |
| **denn** | 因为 | **主句语序!** 不推动词:`Ich bleibe, denn ich bin krank.` |
| **wenn** | 如果 / 当...时 | 条件/时间 |
| **als** | 当...(过去一次性) | `Als ich Kind war, ...` |
| **ob** | 是否 | `Ich weiß nicht, ob er kommt.` |
| **obwohl** | 虽然 | 让步 |
| **damit** | 为了(从句) | 目的 |
| **während** | 在...期间 / 而 | 同时/对比 |

> **denn vs weil**:意思一样,**denn 接主句语序**(动词位2),**weil 接从句语序**(动词尾置)。这是高频考点。
> - `Ich bleibe, denn ich bin krank.`(denn)
> - `Ich bleibe, weil ich krank bin.`(weil)

---

## 4. 四格支配 (Kasusrektion)

### 4.1 动词支配格

| 支配 | 动词 | 例 |
|---|---|---|
| **Akk** | haben, kaufen, suchen, sehen, essen, trinken, lesen, nehmen | Ich **kaufe** einen Apfel. |
| **Dat** | helfen, danken, folgen, gefallen, gehören, antworten | Ich **helfe** dem Mann. |
| **Akk + Dat** | geben, schenken, zeigen, erzählen, bringen, senden | Ich **gebe** dir(Akk-人?见下) **ein Buch**. |

> ⚠️ 双宾语动词:**人(Dat)在前,物(Akk)在后**。`Ich gebe **dem Kind**(Dat) **das Buch**(Akk).` —— 不是「先宾后双宾」的英语顺序。

**Dat 宾语动词(必背)**:helfen(帮助,dem)、danken(感谢,dem)、gefallen(使...喜欢,der)、folgen(跟随,dem)、gehören(属于,dem)、antworten(回答,dem)、passen(合适)、schmecken(尝起来)。这些**永远加三格**,A2 高频考点。

### 4.2 形容词/分词支配

| 形容词 | 支配 | 例 |
|---|---|---|
| zufrieden mit | Dat | Ich bin zufrieden mit **der Arbeit**. |
| stolz auf | Akk | Er ist stolz auf **seinen Sohn**. |
| fertig mit | Dat | Bist du fertig mit **der Hausaufgabe**? |
| krank / böse auf | Akk | Sie ist böse auf **mich**. |

### 4.3 es 的形式变格

| Nom | Akk | Dat |
|---|---|---|
| es | es | ihm |

> `Ich helfe ihm.`(帮他,=es 的 Dat)—— 别写成 `Ich helfe es.` ❌

---

## 5. 介词 + 格 (Präpositionen)

德语介词**强制支配某个格**,这是 A1/A2 的背记重灾区。按格分组:

### 5.1 永远加第四格 (Akk)

**记忆口诀:DOGBUD**(durch ohne gegen für um ohne → 但缺 wider/bis)。A2 常用:

`durch für gegen ohne um wider bis`

- für **mich**, gegen **den Baum**, ohne **dich**, um **acht Uhr**
- Ich kaufe das **für meinen Sohn**.(für + Akk,物主词尾跟格)

### 5.2 永远加第三格 (Dat)

`aus bei mit nach seit von zu gegenüber`

口诀:**「从贝特南,自从对面」**(aus bei mit nach seit von zu + gegenüber)。

- aus **Deutschland**, bei **der Arbeit**, mit **dem Bus**, nach **Hause**, seit **einem Jahr**, von **Berlin**, zu **Hause**, gegenüber **der Bank**

> `zu Hause`(在家)/ `nach Hause`(回家)是固定搭配,无冠词。

### 5.3 混合介词 (Wechselpräpositionen) —— 看「去哪 vs 在哪」

`an auf in hinter neben über unter vor zwischen` —— **9 个**。

| 问 | 格 | 义 |
|---|---|---|
| **Wohin?**(去哪) | **Akk** | 方向(动态) |
| **Wo?**(在哪) | **Dat** | 位置(静态) |

- Ich hänge das Bild **an die Wand**.(Akk,挂上去=动作)
- Das Bild hängt **an der Wand**.(Dat,挂在墙上=状态)
- Ich lege das Buch **auf den Tisch**.(Akk)
- Das Buch liegt **auf dem Tisch**.(Dat)

> 🔑 **动作答 Wohin→Akk,状态答 Wo→Dat**。同一对介词,格随「动/静」变。这是 A2 必考的判断题。

#### 9 个混合介词的常用固定搭配

- **an**:am Bahnhof, am Fenster, an der Tür
- **auf**:auf dem Tisch, auf der Straße
- **in**:in Berlin, in der Schule, im Kino
- **hinter / neben / vor / zwischen**:方位(后/旁/前/之间)
- **über / unter**:上/下(über dem Bett)

> `in + dem = im`,`an + dem = am`,`zu + dem = zum`,`bei + dem = beim` —— 缩合形式 A2 必会。

### 5.4 介词与格的关系一览表

| 格 | 介词 |
|---|---|
| **Akk 固定** | durch, für, gegen, ohne, um, wider, bis |
| **Dat 固定** | aus, bei, mit, nach, seit, von, zu, gegenüber |
| **Akk/Dat 混合** | an, auf, in, hinter, neben, über, unter, vor, zwischen |

---

## 6. 句法综合练习 (Aufgaben)

> 把「动词往哪放、用哪个格」练到条件反射,本阶段就过了。

### 练习 A:V2 语序(把时间状语提到位 1)

1. (Ich / lerne / heute / Deutsch) → Heute ___.
2. (Ich / stehe / um 7 Uhr / auf) → Um 7 Uhr ___.
3. (Wir / fahren / morgen / nach Berlin) → Morgen ___.

<details><summary>答案</summary>

1. Heute lerne ich Deutsch.
2. Um 7 Uhr stehe ich auf.
3. Morgen fahren wir nach Berlin.

</details>

### 练习 B:框形结构(把右框送到句尾)

1. Ich (müssen / heute / arbeiten) → ___.
2. Ich (haben / gestern / ein Buch / lesen) → ___. (Perfekt)
3. Ich (anrufen / dich / morgen) → ___.

<details><summary>答案</summary>

1. Ich muss heute arbeiten.
2. Ich habe gestern ein Buch gelesen.
3. Ich rufe dich morgen an.

</details>

### 练习 C:从句动词尾置

1. Ich bleibe zu Hause, (weil / ich / krank / sein) → ___.
2. Er sagt, (dass / ich / recht / haben) → ___.
3. (Wenn / es / regnen) → ___, lese ich.

<details><summary>答案</summary>

1. Ich bleibe zu Hause, weil ich krank bin.
2. Er sagt, dass ich recht habe.
3. Wenn es regnet, lese ich.

</details>

### 练习 D:介词 + 格(填冠词)

1. Ich fahre mit ___ Bus. (der, Dat)
2. Das Buch liegt auf ___ Tisch. (der, Dat - 静态)
3. Ich lege das Buch auf ___ Tisch. (der, Akk - 动态)
4. Wir warten seit ___ Stunde. (ein, Dat)
5. Das Geschenk ist für ___ Mann. (der, Akk)

<details><summary>答案</summary>

1. dem (mit dem Bus)
2. dem (auf dem Tisch - Wo?)
3. den (auf den Tisch - Wohin?)
4. einer (seit einer Stunde)
5. den (für den Mann)

</details>

### 练习 E:连词辨析(denn vs weil)

1. Ich bleibe zu Hause, ___ ich krank bin. (用 weil)
2. Ich bleibe zu Hause, ___ ich bin krank. (用 denn)
3. (Weil / Denn) es regnet, bleibe ich drinnen. (从句在前用哪个?)

<details><summary>答案</summary>

1. Ich bleibe zu Hause, **weil** ich krank **bin**.(动词尾置)
2. Ich bleibe zu Hause, **denn** ich **bin** krank.(动词位 2)
3. **Weil** es **regnet**, bleibe ich drinnen.(从句在前必须用从句连词 weil,denn 不能引从句)

</details>

---

## 7. 此刻学会了什么 / 还卡在哪 (CP3 现场记录)

- [x] V2 主句语序 + 成分计数(位1=任意成分,位2=动词)
- [x] V1 疑问句(是非问 V1,W-问 V2)+ 命令式
- [x] 框形结构四种:情态 / 完成时 / 可分 / 从句
- [x] 从句动词尾置 + denn(主句)vs weil(从句)
- [x] 四格支配:双宾语「人 Dat 在前 物 Akk 在后」、纯 Dat 动词表
- [x] 介词三组:Akk 固定 / Dat 固定 / 混合(Wohin=Akk / Wo=Dat)
- [ ] 混合介词在「动作 vs 状态」切换时,格的判断还要停顿一下
- [ ] 长从句嵌套(主句套从句套从句)语序容易乱

---

## 📚 参考 / References

- Duden · *Die Grammatik*(框形结构、语序章节)
- Helbig/Buscha · *Deutsche Grammatik*
- Goethe-Zertifikat A1/A2 · 句型与介词要求
- Hueber · *Übungsgrammatik für die Grundstufe*(A2 语序/介词练习来源)
- 🔊 配套点读见 `04-application/`(名词连冠词发音,呼应 §4 格支配)
