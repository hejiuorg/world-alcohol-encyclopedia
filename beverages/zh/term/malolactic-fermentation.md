---
schema_version: 1
id: term:malolactic-fermentation
type: term
lang: zh
slug: malolactic-fermentation
title: 苹果酸-乳酸发酵（malolactic fermentation）
summary: 乳酸菌把苹果酸转化为乳酸与二氧化碳的二次发酵，会降低酸度、柔化口感；它不同于酒精发酵，也并非所有酒款都需要。
status: reviewed
revision: 2
legacy_refs: []
aliases:
  - 苹果酸-乳酸发酵
  - 苹乳发酵
  - MLF
  - malolactic fermentation
tags:
  - term
  - wine
  - winemaking
related:
  - relation: about
    target_id: term:acidity
  - relation: about
    target_id: process:fermentation
  - relation: about
    target_id: drink-style:red-wine
  - relation: about
    target_id: drink-style:white-wine
references:
  - key: acidity
    target_id: term:acidity
  - key: fermentation
    target_id: process:fermentation
  - key: red-wine
    target_id: drink-style:red-wine
  - key: white-wine
    target_id: drink-style:white-wine
sources:
  - key: oiv-definitions
    title: OIV International Code of Oenological Practices — Part I Definitions
    url: https://www.oiv.int/standards/international-oenological-codex/part-i-definitions
    publisher: International Organisation of Vine and Wine (OIV)
    note: 用于核对苹果酸-乳酸发酵在葡萄酒工艺定义中的位置，未复制原文。
    accessed: 2026-11-07
  - key: oxford-wine
    title: The Oxford Companion to Wine
    publisher: Oxford University Press
    note: 参考其关于苹果酸-乳酸发酵、乳酸菌与降酸的条目。
    accessed: 2026-11-07
    url: https://global.oup.com/academic/product/the-oxford-companion-to-wine-9780198871316
  - key: awri-mlf
    title: Australian Wine Research Institute — Achieving successful malolactic fermentation
    url: https://www.awri.com.au/wp-content/uploads/2011/06/Malolactic-fermentation.pdf
    publisher: Australian Wine Research Institute
    note: 用于核对温度、酒精与二氧化硫对乳酸菌活性的影响；未复制原文。
    accessed: 2026-11-07
  - key: r16-jancis-mlc
    title: malolactic conversion — The Oxford Companion to Wine (JancisRobinson.com)
    url: https://www.jancisrobinson.com/ocw/detail/malolactic-conversion
    publisher: JancisRobinson.com / Oxford University Press
    note: 用于核对苹果酸-乳酸发酵（malolactic conversion）的机理与常用缩写；未复制原文。
    accessed: 2026-11-07
  - key: ref
    title: "The Oxford Companion to Wine（Oxford University Press）。"
    publisher: "未注明"
    note: 由原条目末尾参考资料迁移，未逐条复核访问日期。
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写，依据 OIV 定义与葡萄酒工具书核验；未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方文本、商标与图片不在本许可内；来源仅作核验引用。
verification_scope: source-verified
---
# 苹果酸-乳酸发酵（malolactic fermentation）

苹果酸-乳酸发酵（malolactic fermentation，常缩写为 MLF，中文也称苹乳发酵）是葡萄酒酿造中的二次发酵，但主角不是酵母，而是乳酸菌。乳酸菌把酒液中的苹果酸转化为乳酸，并释放少量二氧化碳。结果不产生酒精，而是改变酸的结构。

![苹果酸-乳酸发酵（malolactic fermentation） 图像](/media/photos/term-malolactic-fermentation-2d4ece59.jpg)

图：苹果酸-乳酸发酵（malolactic fermentation）。图片：Agne27，CC BY-SA 3.0，via Wikimedia Commons（[原图页面](https://commons.wikimedia.org/wiki/File:Malolactic_spotting.JPG)）。

## 定义与边界

MLF 的定义可以拆成三点：底物是苹果酸，产物是乳酸与二氧化碳，执行者是乳酸菌。它通常发生在酒精发酵结束后，也可以在酒精发酵过程中或结束后由人工接种启动。它不把糖转成酒精，所以不是“第二次酒精发酵”；它也不等于所有降酸操作，添加酒石酸、碳酸钙或离子交换属于另一类工艺。

边界还包括“是否完成”。MLF 可能只转化一部分苹果酸，也可能在中途停滞；未完成的 MLF 会让酒在装瓶后继续变化，带来浑浊或产气。因此，生产上常用纸层析、酶法或色谱检测苹果酸残留，以判断发酵是否结束。

## 词源与命名

malolactic 由 malic（苹果酸）与 lactic（乳酸）组合而成，字面就是“苹果酸转为乳酸”。中文“苹果酸-乳酸发酵”是直译，“苹乳发酵”是简称。英语中常把它叫作 secondary fermentation，但这个词也用于起泡酒的瓶内二次发酵，二者含义不同：起泡酒的二次发酵仍是酵母把糖转成酒精与二氧化碳，MLF 则是细菌改造酸。

命名的混淆来自“二次”二字。只要在酒精发酵之后发生，就可能被叫作二次发酵；但真正决定酒精度的是酵母，决定酸结构的是乳酸菌。读技术资料时，看到 secondary fermentation，应先问“是谁在发酵、底物是什么”。

## 生化机制

苹果酸是二元羧酸，带两个可解离的质子；乳酸是一元羧酸，只有一个。苹果酸-乳酸发酵把苹果酸脱羧，生成乳酸与二氧化碳，因此酸的总量下降，pH 略微上升。反应由苹果酸-乳酸酶催化，能量用于乳酸菌维持细胞活动。这个过程不产生 ATP 意义上的大量能量，但对乳酸菌在酒中的生存有利。

葡萄汁中的苹果酸含量随品种、成熟度与产区而变，常见范围约 1–4 g/L。转化后，总酸下降的幅度取决于初始苹果酸量，pH 上升常见 0.1–0.3。这个变化对高酸红葡萄酒是柔化，对追求清爽的白葡萄酒则可能是损失。理解机制，才能判断“降酸”是目标还是副作用。

## 工艺参数与控制

乳酸菌的活性受温度、pH、酒精与二氧化硫影响。常用接种温度约 18–22 °C；温度低于 15 °C 会明显减慢，高于 25 °C 又会增加挥发酸与异味风险。pH 3.2–3.6 是比较适宜的范围，pH 低于 3.0 时发酵容易迟缓或无法启动。酒精达到约 10% v/v 后，乳酸菌的耐受性下降；游离二氧化硫会直接抑制细菌，因此接种前后要控制硫的用量。

工艺路线主要有两种：酒精发酵结束后顺序接种，或在酒精发酵中途共接种。顺序接种便于分别观察酒精发酵与 MLF，但酒液已含酒精，启动更慢；共接种可缩短总发酵时间，却要求更精细的温度与营养管理。无论哪种路线，营养缺陷、温度波动与 SO₂ 过量都是停滞的常见原因。

## 在酒业中的实际用法

红葡萄酒普遍进行或允许 MLF，因为红葡萄酒的酸度较高、结构较硬，降酸能让口感更易接受，也有利于后续陈年。部分红葡萄酒会刻意保留部分苹果酸，以维持新鲜感，这取决于品种、产区与年份。

[白葡萄酒](ref:white-wine)则因风格而异。追求圆润、奶油质感的白葡萄酒可能进行 MLF，例如部分勃艮第霞多丽；追求清爽、高酸的白葡萄酒通常避免，例如大多数雷司令与长相思。起泡酒的基酒也常阻止 MLF，以保留酸度与气泡的清爽感。对[红葡萄酒](ref:red-wine)与白葡萄酒采用不同策略，说明 MLF 是风格工具，不是固定步骤。

## 感官变化：不只是“奶油味”

MLF 最直接的变化是酸度下降与口感变柔。除此之外，它还会改变香气与质地：乳酸菌代谢可能带来奶油、黄油、酸奶类的气味，增加酒体的圆润感，也会改变部分果香的表达。这些变化与菌株、温度、时间与酒液营养有关，不同酒款不能一概而论。

“黄油味”常被归因于 MLF，但更准确的来源是二乙酰（diacetyl）。二乙酰来自乳酸菌对柠檬酸的代谢，适量时呈现黄油或奶油感，过量时则像黄油糖或人造奶油。并非所有 MLF 都会产生明显二乙酰，菌株与发酵条件决定其高低。把黄油味等同于 MLF，是把一个副产物当成了整个过程。

## 易混术语对照

第一组：MLF 与酒精发酵。前者由乳酸菌执行，底物是苹果酸，产物是乳酸；后者由酵母执行，底物是糖，产物是乙醇与二氧化碳。第二组：MLF 与“二次发酵”。在起泡酒语境中，二次发酵指瓶内酵母发酵；在葡萄酒工艺中，MLF 有时也被叫作二次发酵，但两者不是同一反应。

第三组：MLF 与人工降酸。添加酒石酸是加酸，添加碳酸钙或离子交换是降酸，它们不依赖细菌，也不改变酸的种类。第四组：MLF 与乳酸菌污染。MLF 是受控的细菌活动，污染是失控的细菌活动；同一种菌在不同条件下可能带来风格，也可能带来缺陷。

## 常见误用与争议

第一，把 MLF 叫作“第二次酒精发酵”。第二，认为所有葡萄酒都必须进行 MLF。第三，认为乳酸菌等于益生菌；酒中的乳酸菌是工艺微生物，控制不当仍会产生生物胺与异味。第四，认为酸度越低越好；对高酸风格，保留苹果酸是刻意选择。

争议集中在接种策略与生物胺。支持人工接种的观点强调可控性与稳定性，支持自然发酵的观点强调复杂度与地方微生物；两者都有失败案例。生物胺（如组胺）在部分酒中受到关注，其生成与菌株、卫生条件与发酵管理有关；对敏感人群，这是标签与生产端需要说明的风险。另一个争议是“MLF 一定让酒更柔和”的说法：对某些白葡萄酒，MLF 会削弱清爽感，甚至让果香显得沉闷。

## 典型数值与例子

常用参数：接种温度约 18–22 °C；pH 3.2–3.6 较适宜，低于 3.0 容易失败；酒精约 10% v/v 以上会抑制乳酸菌；苹果酸常见 1–4 g/L；完全转化后 pH 上升约 0.1–0.3。检测上，苹果酸残留低于约 0.1 g/L 常被视为完成，但方法不同，判定阈值也会变化。

具体例子：一款 pH 3.2、总酸 7 g/L 的赤霞珠，MLF 后总酸可能降到 5.5–6.5 g/L，口感明显变柔；一款 pH 3.0 的雷司令若进行 MLF，可能失去标志性的酸爽。理解这些数字与风格目标，比记住“苹乳”两个字更重要。

相关条目：[酸度（acidity）](ref:acidity)、[发酵](ref:fermentation)。

## 另见

- [酸度](ref:acidity)
- [发酵](ref:fermentation)
- [红葡萄酒](ref:red-wine)
- [白葡萄酒](ref:white-wine)
