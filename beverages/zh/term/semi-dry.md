---
schema_version: 1
id: term:semi-dry
type: term
lang: zh
slug: semi-dry
title: 半干（semi-dry）
summary: 半干指残糖高于干型、又未达到半甜或甜型的中间档；具体克数因品类与法规而异，不能只凭口感判断。
status: reviewed
revision: 2
legacy_refs: []
aliases:
  - 半干
  - 半干型
  - semi-dry
  - medium dry
tags:
  - term
  - wine
  - labelling
related:
  - relation: about
    target_id: drink-style:wine
  - relation: about
    target_id: drink-style:sparkling-wine
  - relation: about
    target_id: term:residual-sugar
references:
  - key: wine
    target_id: drink-style:wine
  - key: sparkling
    target_id: drink-style:sparkling-wine
  - key: residual-sugar
    target_id: term:residual-sugar
sources:
  - key: eu-wine-labelling
    title: Commission Delegated Regulation (EU) 2019/33 — wine labelling terms
    url: https://eur-lex.europa.eu/eli/reg/2019/33/oj
    publisher: European Union
    note: 用于核对欧盟葡萄酒甜度术语与残糖区间，未复制原文。
    accessed: 2026-11-07
  - key: oiv-definitions
    title: OIV International Code of Oenological Practices — Part I Definitions
    url: https://www.oiv.int/standards/international-oenological-codex/part-i-definitions
    publisher: International Organisation of Vine and Wine (OIV)
    note: 用于核对残糖、甜度与葡萄酒类型相关定义，未复制原文。
    accessed: 2026-11-07
  - key: dgccrf-champagne
    title: "Champagne : connaître le langage des étiquettes — DGCCRF"
    url: https://www.economie.gouv.fr/dgccrf/les-fiches-pratiques-et-les-faq/champagne-connaitre-le-langage-des-etiquettes
    publisher: Direction générale de la concurrence, de la consommation et de la répression des fraudes (France)
    note: 用于核对香槟 brut、extra dry、sec、demi-sec 与 doux 的残糖区间，未复制原文。
    accessed: 2026-11-07
  - key: oxford-wine
    title: The Oxford Companion to Wine
    publisher: Oxford University Press
    note: 参考其关于残糖、甜度与品鉴的条目。
    accessed: 2026-11-07
    url: https://global.oup.com/academic/product/the-oxford-companion-to-wine-9780198871316
  - key: ref
    title: "The Oxford Companion to Wine（Oxford University Press）。"
    publisher: "未注明"
    note: 由原条目末尾参考资料迁移，未逐条复核访问日期。
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写；依据欧盟葡萄酒标签法规、OIV、法国 DGCCRF 与葡萄酒工具书核验，未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方法规文本、商标与图片不在本许可内；来源仅作核验引用。
verification_scope: source-verified
---
# 半干（semi-dry）

半干（semi-dry，欧盟标签常写作 medium dry）是残糖档位中的中间一档：它高于干型，又低于半甜与甜型。这个“中间”没有全球统一的克数，因为静止酒、起泡酒与不同国家的法规各有自己的区间；同一句“半干”，在香槟和普通葡萄酒里可能指向完全不同的甜度。

![半干（semi-dry） 类型示意图](/media/photos/theme-wine-spirits.jpg)

图：半干（semi-dry） 类型示意图。图片：Doubao Seedream 5.0 AI 辅助绘制（项目自有），不是半干（semi-dry）的实拍。

## 定义与边界

半干的核心是[残糖](ref:residual-sugar)处在干型与半甜之间。以欧盟静止葡萄酒的标签体系为例，干型上限为 4 g/L；半干通常指高于 4 g/L 且不超过 12 g/L，若总酸不低于 10 g/L，上限可放宽到 18 g/L；再往上则进入半甜与甜型。这个区间说明“半干”不是单一数字，而是带条件的范围。

边界还要看品类。起泡酒的“半干”对应 demi-sec，残糖约 32–50 g/L，远高于静止酒的半干；香槟的 brut 只要低于 12 g/L，甚至比静止酒的半干上限还低。把静止酒的“半干”标准套到香槟上，会得出错误结论。判断时必须先确认品类与适用法规。

## 词源与来源

“semi-”来自拉丁语，意为“一半、部分”；“dry”在酒类语境中表示“不甜”。合起来就是“部分干、略带甜”。中文“半干”是这一外来讲法的直译；欧盟官方术语使用 medium dry，中文有时也译作“中等干型”。同一个概念在不同语言里有不同措辞，标签上的用词比字面翻译更重要。

半干不是自然界的固定类别，而是法规与市场共同塑造的标签。早期葡萄酒没有现代残糖检测，甜与不甜常凭口感描述；后来糖度可以精确测量，各国才把甜度档位写进法规。今天看到的区间，是测量技术、消费习惯与贸易规则长期磨合的结果。

## 机制与参数

残糖是半干的第一参数，但感知甜度还受酸度、酒精、温度、二氧化碳与香气影响。酸度高会让同量残糖显得更干；酒精高会增强甜感与厚重感；低温与气泡会压制甜感；浓郁的水果香也可能让酒“闻起来更甜”。因此，8 g/L 的酒在一种条件下可能显得干，在另一种条件下可能显得半干。

测量上，残糖通常以葡萄糖计，单位 g/L；不同方法（酶法、高效液相、折光估算）会给出略有差异的数值。标签区间一般以法规规定的检测方法为准。总酸与 pH 也必须同时记录，因为欧盟的半干上限在总酸达到 10 g/L 时可以放宽到 18 g/L；只看糖不看酸，会误判档位。

## 在酒业中的实际用法

在静止[葡萄酒](ref:wine)中，半干常用于日常饮用、配餐与部分甜型风格的入门产品；生产者会在发酵尚未完全结束时停止发酵，或通过添加少量甜味剂/未发酵葡萄汁来达到目标残糖。欧盟标签对“medium dry”的使用有明确条件，生产者在设计背标时必须同时核对残糖、总酸与品类。

在[起泡酒](ref:sparkling)中，半干对应 demi-sec，常见于甜度较高的香槟与起泡酒；它的残糖区间与静止酒完全不同。香槟的甜度还涉及除渣后的调味液（dosage），brut nature 要求低于 3 g/L 且除渣后不加糖，brut 低于 12 g/L。把这些术语与半干混用，会让配餐与选购出现偏差。

## 易混术语对照

第一组是半干与干型。干型的上限通常为 4 g/L，半干从 4 g/L 以上开始；两者之间不是口感差异，而是可测量的残糖界线。第二组是半干与半甜。欧盟静止酒的半甜通常从 12 g/L 起（总酸高时为 18 g/L 起），半干止于同一界线；中文“半干”和“半甜”不能凭印象互换。

第三组是半干与香槟的 demi-sec。前者是静止酒的中间档，后者是起泡酒的高甜档；同一中文译名“半干”可能对应不同的克数。第四组是半干与“不甜”。一款酒可能因为酸度高而喝起来干，但残糖仍落在半干区间；标签与口感不一致时，以检测值为准。第五组是半干与“甜型”。甜型通常高于 45 g/L，半干远低于此。

## 常见误用与争议

第一，只凭口感判断半干；酸度、温度与气泡都会欺骗舌头。第二，把静止酒的半干区间套到香槟。第三，把“半干”当成“半甜”。第四，忽略总酸对上限的影响。第五，认为残糖越低质量越高；甜度是风格选择，不是质量指标。

争议主要集中在标签与感知的落差。消费者常把“喝起来不甜”理解为“干”，但法规看的是残糖；一款高酸、低温、带气泡的酒可能喝起来很干，残糖却高于 4 g/L。另一个争议是“半干”在不同国家的实际用法不一致，进口酒的中文背标可能与原标签术语并不完全对应，购买时应以原标签与官方分类为准。

半干的克数标准因品类而异：葡萄酒、清酒与起泡酒的残糖区间并不统一；只凭不甜的口感判断，容易把半干与干型混淆，也会忽略酸度对甜感的掩盖。

## 典型数值与例子

以欧盟静止酒为例：干型不超过 4 g/L；半干高于 4 g/L 且不超过 12 g/L，总酸不低于 10 g/L 时上限可到 18 g/L；半甜通常为 12–45 g/L，甜型高于 45 g/L。以 8 g/L 残糖、总酸 6 g/L 的酒为例，它落在半干；同样是 8 g/L，总酸 11 g/L 也仍是半干，因为上限没有超过 12 g/L。

真正体现“酸度放宽”的例子是 15 g/L 残糖：若总酸为 11 g/L，它可以仍标半干；若总酸只有 6 g/L，则进入半甜。香槟方面，brut 低于 12 g/L，extra dry 为 12–17 g/L，sec 为 17–32 g/L，demi-sec 为 32–50 g/L，doux 高于 50 g/L。把这些数字并列，能直观看到“半干”在两类酒中的差距。

## 另见

- [葡萄酒](ref:wine)：理解半干（semi-dry）在葡萄酒语境中的类别、年份与产地规则。
- [起泡酒](ref:sparkling)：香槟甜度档位与气泡的影响。
- [残糖](ref:residual-sugar)：甜度标签的测量基础。

对照阅读：[葡萄酒](ref:wine)、[残糖（residual sugar）](ref:residual-sugar)。

**来源与边界。** 本页关于「半干（semi-dry）」的关键事实，主要由以下来源交叉核对：European Union（欧盟葡萄酒甜度术语与残糖区间）、International Organisation of Vine and Wine (OIV)（残糖、甜度与葡萄酒类型相关定义）、Direction générale de la concurrence, de la consommation et de la répression des fraudes (France)（香槟 brut、extra dry、sec、demi-sec 与 doux 的残糖区间）等 5 条来源。价格、批次与状态会变，涉及这些字段时以页面所列来源的最新版本为准。正文为项目自写，来源只作核验，不复制原文。

**并读。** 把「半干（semi-dry）」与「葡萄酒」、「起泡酒」、「残糖（residual sugar）」放在一起读时，先确认它们是同一层级还是上下游关系：先确认定义与计量口径，再比较相邻术语与常见误用。本页负责给出术语的基本坐标，对照条目补上具体案例与差异；读完再回到本页，才能分清哪些差别属于术语本身，哪些只是产地、批次或品牌选择。

**适用边界。** 对「半干（semi-dry）」而言，术语在不同法规与行业语境中含义不同；先看定义来源，再看用法。
