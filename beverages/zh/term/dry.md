---
schema_version: 1
id: term:dry
type: term
lang: zh
slug: dry
title: 干型（dry）
summary: 干型是葡萄酒标签上的残糖分级，欧盟通常为不超过 4 g/L，总酸达标时可放宽到 9 g/L；它不描述果味强弱，也不等于质量等级。
status: reviewed
revision: 2
legacy_refs: []
aliases:
  - 干型
  - 干酒
  - dry
tags:
  - term
  - wine
  - labelling
related:
  - relation: about
    target_id: drink-style:wine
  - relation: about
    target_id: drink-style:white-wine
  - relation: about
    target_id: drink-style:sparkling-wine
  - relation: about
    target_id: term:residual-sugar
  - relation: about
    target_id: term:semi-dry
  - relation: about
    target_id: term:sweet
references:
  - key: wine
    target_id: drink-style:wine
  - key: white-wine
    target_id: drink-style:white-wine
  - key: sparkling
    target_id: drink-style:sparkling-wine
  - key: residual-sugar
    target_id: term:residual-sugar
  - key: semi-dry
    target_id: term:semi-dry
  - key: sweet
    target_id: term:sweet
sources:
  - key: eu-wine-labelling
    title: Commission Delegated Regulation (EU) 2019/33 — wine labelling terms
    url: https://eur-lex.europa.eu/eli/reg/2019/33/oj
    publisher: European Union
    note: 用于核对干型及相邻甜度分级的残糖阈值与酸度条件。
    accessed: 2026-11-07
  - key: oiv-definitions
    title: OIV International Code of Oenological Practices — Part I Definitions
    url: https://www.oiv.int/standards/international-oenological-codex/part-i-definitions
    publisher: International Organisation of Vine and Wine (OIV)
    note: 用于核对葡萄酒糖分与酒精度相关定义，未复制原文。
    accessed: 2026-11-07
  - key: oxford-wine
    title: The Oxford Companion to Wine
    publisher: Oxford University Press
    note: 参考其关于干型、甜度与品鉴的条目。
    accessed: 2026-11-07
    url: https://global.oup.com/academic/product/the-oxford-companion-to-wine-9780198871316
  - key: gbt-15037
    title: 国家标准全文公开系统 — GB/T 15037-2006 葡萄酒
    url: https://openstd.samr.gov.cn/bzgk/std/newGbInfo?hcno=7D1FDC42A148D76E6BF379A8CB6D1DF7
    publisher: 国家市场监督管理总局、国家标准化管理委员会
    note: 用于核对以总糖划分的干型、半干、半甜、甜型区间；该标准采标，系统仅提供题录信息，未复制正文。
    accessed: 2026-11-07
  - key: ref
    title: "The Oxford Companion to Wine（Oxford University Press）。"
    publisher: "未注明"
    note: 由原条目末尾参考资料迁移，未逐条复核访问日期。
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写；依据欧盟葡萄酒标签法规与葡萄酒工具书核验，未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方法规文本、商标与图片不在本许可内；来源仅作核验引用。
verification_scope: source-verified
---
# 干型（dry）

干型（dry）是葡萄酒标签上表示残留糖分很低的用语。它回答的是“发酵结束后还剩多少糖”，而不是“这瓶酒有多浓”“多好”或“果味有多足”。把干型读成“没有果味”或“高级”，是读酒标时最常见的偏差之一。

![干型（dry） 类型示意图](/media/photos/theme-wine-spirits.jpg)

图：干型（dry） 类型示意图。图片：Doubao Seedream 5.0 AI 辅助绘制（项目自有），不是干型（dry）的实拍。

## 定义与边界

在欧盟葡萄酒标签规则中，干型的残糖上限通常为 4 g/L；当总酸（以酒石酸计）不低于 7 g/L 时，上限可以放宽到 9 g/L。放宽并非漏洞，而是承认酸度会压低甜感：同样 8 g/L 的糖，在高酸酒里可能几乎尝不出来。超过这一区间，才进入半干、半甜或甜型。

干型的边界是法规阈值，不是“零糖”。发酵中止的时机、酵母种类、过滤方式与是否加甜都会改变最终数值。一瓶标注干型的酒仍可能含 2–3 g/L 的葡萄糖与果糖，这属于正常范围。需要核对的是产品适用的法规与检测口径，而不是凭口感猜测。

[残糖](ref:residual-sugar)是干型定义的核心变量。对[白葡萄酒](ref:white-wine)来说，干型通常意味着酸度清晰、果味直接；对红葡萄酒来说，干型还可能伴随单宁带来的收敛感。两者都叫“干”，感官来源却不同。

## 词源与用法的迁移

英语 dry 源自古英语 drȳge，本义是“干燥、无水”。17 世纪以后，英语酒类写作开始用 dry 形容“不带甜味”的酒，这个词随后进入酒标与酒评。中文“干型”是意译，不是“干燥”的字面移植；在中文语境里，“干”很容易被联想到“干涩”，于是与单宁混淆。

法语用 sec，德语用 trocken，西班牙语用 seco，词根都指向“干”。不同语言的标签体系各自演化，同一个概念在跨境比较时就会出现阈值差异。读原产国标签，通常比读翻译标签可靠。

## 阈值背后的酸度机制

甜感不是糖的单独函数。酸度会与甜味相互抑制：高酸让酒显得更清爽，也更“干”；低酸则让少量糖分显得突出。欧盟把总酸 7 g/L 作为放宽条件，正是把这种感官关系写进法规。总酸与 pH 是两套度量：前者是滴定得到的酸总量，后者是氢离子浓度；一款 pH 偏高的酒未必总酸低，不能只用 pH 判断干不干。

温度也参与其中。低温会抑制甜感、突出酸感，所以同一瓶酒在 8 °C 与 18 °C 下可能给出不同的“干”印象。酒精与甘油则相反，会带来圆润甚至微甜的感觉。把这些变量分开，才能理解为什么“干型”与“喝起来不甜”不能画等号。

## 法规与标签中的实际用法

欧盟的甜度用语与残糖区间绑定，生产者只有在满足条件时才能使用相应术语。中国 GB/T 15037-2006《葡萄酒》同样按总糖划分：干型总糖不超过 4.0 g/L；当总糖与总酸的差值不超过 2.0 g/L 时，上限可到 9.0 g/L。注意中国标准用的是“总糖”，不是严格意义的残糖，两者在检测与换算上并不完全等同。

美国联邦标签规则对仍态葡萄酒的甜度用语约束较松，“dry”更多出现在营销与酒评中，而不是像欧盟那样由残糖加酸度条件直接定义。跨国比较时，先确认标准，再比较数字；不要把一国标签上的“dry”直接套到另一国产品上。[葡萄酒](ref:wine)的标签还可能同时标注酒精度、产地与品种，这些信息与甜度是并列关系，不是替代关系。

## 起泡酒体系：另一套词

[起泡酒](ref:sparkling)的甜度词自成一套：brut、extra dry、sec、demi-sec、doux。它们的残糖来自除渣后加入的调味液（dosage），而不是基酒发酵剩下的糖。brut 通常不超过 12 g/L；extra dry 约 12–17 g/L；sec 约 17–32 g/L；demi-sec 约 32–50 g/L；doux 高于 50 g/L。数值会因法规版本与产品略有差异，但顺序是稳定的。

最容易出错的是“extra dry 比 brut 更干”的字面联想。实际上 extra dry 的残糖高于 brut，这是历史命名留下的结果。中文把 brut 译作“干型”、把 extra dry 译作“超干”，进一步放大了误解。记住区间，比记住译名有用。

## 易混术语对照

第一组：dry 与 tannic／astringent。dry 描述糖分，tannic 描述单宁带来的收敛与涩感。红葡萄酒可以既干又涩，也可以干而不涩；把“涩”说成“干”，会让品鉴记录失去可沟通性。

第二组：dry 与 semi-dry、sweet。三者是同一标签体系内的相邻区间，边界由残糖与酸度共同决定。[半干](ref:semi-dry)位于干型之上，[甜型](ref:sweet)位于更高残糖区间。它们不是口味强度的等级，而是糖分分类。

第三组：仍态酒的 dry 与起泡酒的 brut。前者对应基酒或仍态酒的残糖分级，后者对应调味液加入后的最终甜度；两套词不能直接互换。

## 常见误用与争议

把干型当作“没有果味”是最常见的误用。干型只说明糖少，果味来自品种、成熟度、发酵与陈年，完全可以很浓郁。把干型当作质量等级同样错误：干型是分类，不是评分。把红葡萄酒的涩感说成“干”，则是把两种感官维度混在一起。

争议主要集中在两点。其一，阈值是否应与酸度绑定：支持者认为这更贴近感官，反对者认为规则复杂、消费者难懂。其二，跨国产区与品种的差异是否应被标签统一：目前没有全球统一的甜度定义，比较时只能回到具体法规。另一个常被忽略的事实是，干型酒的配餐优势来自酸度与结构，而不是“无糖”本身；配甜点时，干型酒往往比半干更容易显得尖酸。

## 典型数值与例子

以欧盟规则为例：干型 ≤4 g/L，总酸 ≥7 g/L 时 ≤9 g/L；半干 >4 且 ≤12 g/L，总酸 ≥10 g/L 时上限 18 g/L；半甜 >12 且 ≤45 g/L；甜型 >45 g/L。起泡酒则以 brut ≤12 g/L、extra dry 12–17 g/L、sec 17–32 g/L、demi-sec 32–50 g/L、doux >50 g/L 为常用区间。

日常例子：一款标注干型的阿尔萨斯白葡萄酒，残糖可能只有 2 g/L，但成熟果香让它尝起来圆润；一款 brut 香槟残糖约 10 g/L，却因为高酸与气泡显得非常清爽。反过来，低酸、高酒精的干型酒可能尝起来偏甜。数字与感官并不总是一一对应。

## 另见

- [葡萄酒](ref:wine)
- [白葡萄酒](ref:white-wine)
- [起泡酒](ref:sparkling)
- [残糖](ref:residual-sugar)
- [半干](ref:semi-dry)
- [甜型](ref:sweet)

对照阅读：[葡萄酒](ref:wine)、[起泡酒](ref:sparkling)。

**来源与边界。** 本页关于「干型（dry）」的关键事实，主要由以下来源交叉核对：European Union（干型及相邻甜度分级的残糖阈值与酸度条件）、International Organisation of Vine and Wine (OIV)（葡萄酒糖分与酒精度相关定义）、Oxford University Press（提供关于干型、甜度与品鉴的条目）等 5 条来源。价格、批次与状态会变，涉及这些字段时以页面所列来源的最新版本为准。正文为项目自写，来源只作核验，不复制原文。
