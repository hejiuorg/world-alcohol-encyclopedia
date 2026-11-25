---
schema_version: 1
id: term:acidity
type: term
lang: zh
slug: acidity
title: 酸度（acidity）
summary: 酸度描述酒中酸类物质的总量与强度，常用总酸（g/L）与 pH 两个不同指标；它支撑清爽感、平衡与陈年潜力，也影响二氧化硫的有效性。
status: reviewed
revision: 2
legacy_refs: []
aliases:
  - 酸度
  - 总酸
  - acidity
tags:
  - term
  - chemistry
  - wine
related:
  - relation: about
    target_id: drink-style:wine
  - relation: about
    target_id: drink-style:white-wine
  - relation: about
    target_id: variety:riesling
  - relation: about
    target_id: drink-style:beer
  - relation: about
    target_id: drink-style:sake
  - relation: about
    target_id: process:fermentation
references:
  - key: wine
    target_id: drink-style:wine
  - key: white-wine
    target_id: drink-style:white-wine
  - key: riesling
    target_id: variety:riesling
  - key: beer
    target_id: drink-style:beer
  - key: sake
    target_id: drink-style:sake
  - key: fermentation
    target_id: process:fermentation
sources:
  - key: oiv-definitions
    title: OIV International Code of Oenological Practices — Part I Definitions
    url: https://www.oiv.int/standards/international-oenological-codex/part-i-definitions
    publisher: International Organisation of Vine and Wine (OIV)
    note: 用于核对葡萄酒总酸、pH 与挥发性酸的相关定义，未复制原文。
    accessed: 2026-11-07
  - key: oiv-total-acidity
    title: OIV-MA-AS313-01 Total acidity (Type-I method)
    url: https://www.oiv.int/standards/annex-a-methods-of-analysis-of-wines-and-musts/section-3-chemical-analysis/section-3-1-organic-compounds/section-3-1-3-acids/total-acidity-(type-i)
    publisher: International Organisation of Vine and Wine (OIV)
    note: 用于核对总酸的滴定终点、折算系数与结果表达，未复制原文。
    accessed: 2026-11-07
  - key: oxford-wine
    title: The Oxford Companion to Wine
    publisher: Oxford University Press
    note: 参考其关于酸度、pH 与酒石酸的条目。
    accessed: 2026-11-07
    url: https://global.oup.com/academic/product/the-oxford-companion-to-wine-9780198871316
  - key: asbc
    title: American Society of Brewing Chemists — Methods of Analysis
    publisher: ASBC
    note: 用于核对啤酒酸度与 pH 的常见测量口径，未复制方法原文。
    accessed: 2026-11-07
    url: https://www.asbcnet.org/methods
  - key: wsu-acidity
    title: Managing High Acidity in Grape Must and Wine
    url: https://wine.wsu.edu/managing-high-acidity-in-grape-must-and-wine/
    publisher: Washington State University — Viticulture & Enology
    note: 用于核对红葡萄醪的总酸目标与成品酒 pH 范围，未复制原文。
    accessed: 2026-11-07
  - key: oiv
    title: "OIV-MA-AS313-01 Total acidity (Type-I method)"
    url: https://www.oiv.int/standards/annex-a-methods-of-analysis-of-wines-and-musts/section-3-chemical-analysis/section-3-1-organic-compounds/section-3-1-3-acids/total-acidity-
    publisher: "type-i"
    note: 由原条目末尾参考资料迁移，未逐条复核访问日期。
  - key: ref
    title: "The Oxford Companion to Wine（Oxford University Press）。"
    publisher: "未注明"
    note: 由原条目末尾参考资料迁移，未逐条复核访问日期。
  - key: ref-2
    title: "American Society of Brewing Chemists — Methods of Analysis（ASBC）。"
    publisher: "未注明"
    note: 由原条目末尾参考资料迁移，未逐条复核访问日期。
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写；依据 OIV 分析方法、大学推广资料、啤酒分析方法与葡萄酒工具书核验，未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方文本、商标与图片不在本许可内；来源仅作核验引用。
verification_scope: source-verified
---
# 酸度（acidity）

![酸度（acidity） 图像](/media/photos/term-acidity-5f4c1ad7.jpg)

图：酸度（acidity）。图片：Chemicalinterest，Public domain，via Wikimedia Commons（[原图页面](https://commons.wikimedia.org/wiki/File:Zn_reaction_with_HCl.JPG)）。

## 定义与边界

酸度描述酒中酸类物质的含量与强度。它让酒显得清爽、有骨架，也影响微生物稳定性与陈年表现。酸度不是一个单一数字：总酸、pH 与挥发性酸回答不同问题，混用它们会得到错误结论。总酸回答“可滴定的酸有多少”，pH 回答“氢离子活度有多高”，挥发性酸回答“有多少可挥发的酸，主要是醋酸”。

这里至少要分清三层边界。酸度不是“酸味强度”的同义词：高酸酒不一定喝起来最酸，低酸酒也可能因为糖分低而显得尖锐。酸度也不是“加酸”的同义词：酸化的法定允许量、苹果酸乳酸发酵造成的酸度变化，与葡萄本身的酸度是不同层面。讨论酸度时，先说明是总酸、pH 还是挥发性酸，可以避免大部分误解。

## 词源与来源

acidity 来自拉丁语 acidus，意为“酸的、尖锐的”，与 acere（变酸）和 acetum（醋）同源。这个词从描述味觉的“酸”扩展到化学上的“酸类物质”，再进入酿酒与品鉴语言。中文“酸度”同样把味觉与化学量合并在一个词里，因此日常说“这酒酸度高”时，听者往往不知道指的是总酸、pH，还是主观酸感。

酒石酸、苹果酸与柠檬酸是葡萄酒中最常被提到的酸。酒石酸来自葡萄本身，苹果酸在未成熟葡萄中较多，柠檬酸含量较低。不同酸的解离程度不同，所以同样的总酸可以对应不同的 pH；这也是“总酸高但 pH 不低”的情况并不罕见的原因。

## 机制或参数

OIV 将总酸定义为酒液用标准碱液滴定至 pH 7 时可滴定酸的总和，二氧化碳不计入总酸。结果可以用硫酸或酒石酸折算：每升毫当量数乘以 0.075 得到以酒石酸计的克每升数，乘以 0.049 得到以硫酸计的克每升数。这个滴定终点与折算系数是总酸可比性的基础，不同实验室必须使用同一口径。

pH 是氢离子活度的负对数，反映酸的“强度”而不是“数量”。pH 越低，酸越强，二氧化硫的有效性越高，微生物环境也越严苛。pH 每变化 0.1，二氧化硫的活性、微生物风险与感官平衡都会改变，因此酿酒师常把 pH 与总酸分开记录。

葡萄酒的总酸常见于 6–9 g/L（以酒石酸计），pH 多在 3.0–3.8。白葡萄酒通常比红葡萄酒酸度更高、pH 更低；红葡萄酒的 pH 可能接近 3.8 甚至更高，这与浸渍和苹果酸乳酸发酵有关。华盛顿州立大学的推广资料以红葡萄醪总酸接近 6 g/L 为目标，并指出成品红葡萄酒的 pH 可在 3.3–3.8，具体取决于单宁含量，低单宁酒通常 pH 更低。

苹果酸乳酸发酵把尖锐的苹果酸转成更柔和的乳酸，通常降低总酸、提高 pH。这一过程由[发酵](ref:fermentation)阶段的乳酸菌活动完成，是否进行取决于风格与法规。对高酸产区的白葡萄酒，苹果酸乳酸发酵可以柔化口感；对追求清爽果香的酒款，则可能刻意避免。

## 在酒业中的实际用法

酸度是平衡的核心。糖与酒精带来重量，酸度提供清爽与切割感；没有酸度的酒会显得松散、甜腻。酸度也影响陈年：高酸通常意味着更好的抗氧化能力与更长的陈年潜力。对[白葡萄酒](ref:white-wine)而言，酸度几乎决定了风格的清爽程度；对红葡萄酒而言，酸度与单宁共同构成结构。

在酿造端，酸度决定多项操作。总酸过高时，可以用碳酸钾或碳酸钙降酸；总酸过低时，可以在法规允许范围内加入酒石酸。是否进行苹果酸乳酸发酵、何时接种、是否做带皮浸渍，都会改变最终的酸度与 pH。二氧化硫的添加量也要参照 pH：同样的游离二氧化硫，在较高 pH 下有效性更低。

酸度还影响配餐。高酸酒能切割油脂、平衡咸鲜，也更容易与酸味菜肴相处；低酸酒配酸味食物会显得平淡。理解这一点，比记住“某款酒酸不酸”更有用。

## 易混术语对照

把总酸与 pH 当作同一件事，是最常见的混淆。总酸是可滴定酸的总量，pH 是氢离子活度；总酸高不代表 pH 一定低，因为酸的种类与解离程度不同。挥发性酸与总酸又是另一对容易混用的指标。挥发性酸主要指醋酸等可挥发酸，含量过高会带来醋味，是质量与卫生的信号；它只是总酸的一部分，不能互相替代。

酸度与酸味也常被当成同义词。酸度是化学与结构指标，酸味是感官感受；高酸可以用糖、酒精或温度来平衡，喝起来不一定更酸。酒石酸与苹果酸的区别则落在工艺上。酒石酸较稳定，常作为总酸的折算基准；苹果酸在苹果酸乳酸发酵后减少，乳酸增加，总酸下降而 pH 上升。

## 常见误用与争议

第一，把总酸与 pH 当成同一件事，看到“总酸 7 g/L”就推断 pH 一定低。第二，把“酸”当成缺陷；酸度不足才是许多酒显得乏味的根源。第三，把挥发性酸与总酸混淆，用总酸判断醋化风险。第四，认为所有酒都越酸越好：过度酸涩会掩盖风味，也会让口感显得尖锐。第五，用个人对酸味的敏感度判断酒的客观酸度。

争议主要围绕“高酸是否等于高品质”。在雷司令等高酸品种中，高酸可以支撑甜度与陈年，被视为结构；在低酸品种中，过高的酸可能显得生硬。较稳妥的判断是把酸度放在品种、产区、风格与配餐中一起看，而不是把某个数字当成质量分数。

## 典型数值或例子

- 葡萄酒总酸常见范围：6–9 g/L（以酒石酸计）。
- 葡萄酒 pH 常见范围：3.0–3.8；成品红葡萄酒可为 3.3–3.8。
- OIV 总酸滴定终点：pH 7；酒石酸折算系数：0.075；硫酸折算系数：0.049。
- 红葡萄醪总酸目标：接近 6 g/L；部分品种如黑皮诺可接受 7 g/L。
- pH 每变化 0.1，二氧化硫有效性与微生物环境随之改变。
- [啤酒](ref:beer)的 pH 多在 4.0–4.6，酸味啤酒可以更低；[清酒](ref:sake)的酸度常用滴定法表示，乳酸与琥珀酸带来柔和酸感。
- 典型品种：[雷司令](ref:riesling)的高酸如何支撑甜度与陈年。

这些参数构成一套可比较的口径，酸度不是单一指标，而是总酸、pH、酸种类与工艺共同构成的系统。

## 另见

- [葡萄酒](ref:wine)：理解酸度（acidity）在葡萄酒语境中的类别、年份与产地规则。
- [白葡萄酒](ref:white-wine)：酸度与清爽风格的典型关系。
- [雷司令](ref:riesling)：高酸品种如何支撑甜度与陈年。
- [啤酒](ref:beer)：pH、有机酸与酸味风格。
- [清酒](ref:sake)：滴定酸度与柔和酸感。
- [发酵](ref:fermentation)：苹果酸乳酸发酵与酸度变化。
