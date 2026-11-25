---
schema_version: 1
id: term:residual-sugar
type: term
lang: zh
slug: residual-sugar
title: 残糖（residual sugar）
summary: 残糖是发酵结束后酒液中未被酵母转化的糖分，通常以 g/L 计；它决定甜度标签，但甜感还受酸度、酒精、温度与气泡影响。
status: reviewed
revision: 2
legacy_refs: []
aliases:
  - 残糖
  - 残余糖分
  - residual sugar
  - RS
tags:
  - term
  - sugar
  - measurement
related:
  - relation: about
    target_id: drink-style:wine
  - relation: about
    target_id: drink-style:sparkling-wine
  - relation: about
    target_id: drink-style:beer
  - relation: about
    target_id: term:dry
  - relation: about
    target_id: term:semi-dry
  - relation: about
    target_id: term:sweet
references:
  - key: wine
    target_id: drink-style:wine
  - key: sparkling
    target_id: drink-style:sparkling-wine
  - key: beer
    target_id: drink-style:beer
  - key: dry
    target_id: term:dry
  - key: semi-dry
    target_id: term:semi-dry
  - key: sweet
    target_id: term:sweet
  - key: gbt-17204
    target_id: standard:gbt-17204-2021
sources:
  - key: oiv-definitions
    title: OIV International Code of Oenological Practices — Part I Definitions
    url: https://www.oiv.int/standards/international-oenological-codex/part-i-definitions
    publisher: International Organisation of Vine and Wine (OIV)
    note: 用于核对葡萄酒中糖分与酒精度相关定义，未复制原文。
    accessed: 2026-11-07
  - key: eu-wine-labelling
    title: Commission Delegated Regulation (EU) 2019/33 — wine labelling terms
    url: https://eur-lex.europa.eu/eli/reg/2019/33/oj
    publisher: European Union
    note: 用于核对干型、半干、半甜、甜型的残糖阈值与酸度条件。
    accessed: 2026-11-07
  - key: gbt-17204
    title: 国家标准全文公开系统 — GB/T 17204-2021 饮料酒术语和分类
    url: https://openstd.samr.gov.cn/bzgk/std/newGbInfo?hcno=B8F9CD37320835EEF17458CBA5962881
    publisher: 国家市场监督管理总局、国家标准化管理委员会
    note: 用于核对饮料酒的分类与术语框架，未复制原文。
    accessed: 2026-11-07
  - key: gbt-15037
    title: 国家标准全文公开系统 — GB/T 15037-2006 葡萄酒
    url: https://openstd.samr.gov.cn/bzgk/std/newGbInfo?hcno=7D1FDC42A148D76E6BF379A8CB6D1DF7
    publisher: 国家市场监督管理总局、国家标准化管理委员会
    note: 用于核对以总糖划分的葡萄酒甜度区间；该标准采标，系统仅提供题录信息，未复制正文。
    accessed: 2026-11-07

rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写；依据 OIV、欧盟葡萄酒标签法规与中国国家标准公开信息核验，未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方法规与标准文本、商标与图片不在本许可内；来源仅作核验引用。
verification_scope: source-verified
---
# 残糖（residual sugar）

残糖（residual sugar，常缩写为 RS）是发酵结束后仍留在酒液中的糖分。酵母把糖转成酒精和二氧化碳，但发酵不一定把糖耗尽：它可能提前停止，也可能被刻意保留。残糖通常以每升克数（g/L）表示，是判断甜度、标签分级与配餐的核心参数。

![残糖（residual sugar） 类型示意图](/media/photos/theme-wine-spirits.jpg)

图：残糖（residual sugar） 类型示意图。图片：Doubao Seedream 5.0 AI 辅助绘制（项目自有），不是残糖（residual sugar）的实拍。

## 定义与边界

残糖的测量对象是可发酵糖，主要是葡萄糖与果糖。它不等于“总糖”：总糖可能包含不可发酵的糖类与结合态糖，残糖强调的是发酵终点还剩多少可发酵糖。多数葡萄酒的残糖以葡萄糖加果糖之和计，但不同实验室、不同方法的口径并不完全一致。

残糖也不等于“甜度”。甜感还受酸度、酒精、甘油、温度、气泡与香气影响。一款 RS 只有 3 g/L 的酒可能因为成熟果香而显得圆润；一款 RS 12 g/L 的酒也可能因为高酸而显得清爽。把数值与感官分开记录，是专业品鉴的基本习惯。

## 术语来源与缩写

“residual sugar”是英语对“发酵后剩余糖分”的描述性叫法，法语作 sucre résiduel，德语作 Restzucker，中文“残糖”是直译。RS 这一缩写在酒评、技术表与实验室报告中广泛使用，但并非所有标签都标注数值；欧盟标签通常用 dry、medium dry 等分级词，而不是直接写 RS。

这种“分级词在前、数值在后”的写法容易让消费者忽略具体糖量。看到“dry”时，最好再找技术资料中的 RS；看到“RS 8 g/L”时，则要确认它对应哪一套分级。术语的来源是描述性的，不附带法律含义，法律含义由各市场的标签规则赋予。

## 糖为什么留了下来：发酵中止与加甜

残糖的形成有几条常见路径。第一，发酵自然结束：糖耗尽，残糖接近零。第二，提前中止：通过降温、添加二氧化硫、过滤或离心移除酵母，让酵母在糖未耗尽时停止工作。第三，加甜：在发酵后加入葡萄汁浓缩物、甜储备（Süssreserve）或糖，直接提高残糖。第四，酒精强化：加入酒精杀死酵母，保留糖分，这是波特、马德拉与部分甜型加强酒的基础。

不同路径带来的风险不同。提前中止的酒仍含活性酵母与可发酵糖，装瓶后可能二次发酵，造成浑浊、产气甚至爆瓶；加甜的酒则需要控制微生物稳定性。对[起泡酒](ref:sparkling)而言，除渣后加入的调味液（dosage）是最终残糖的主要来源，这一步也决定 brut、sec、demi-sec 等标签。

## 测量与检测口径

常见检测方法包括酶法、高效液相色谱与密度法推算。酶法针对葡萄糖与果糖，适合常规酒样；色谱法能分离不同糖组分，适合研究或复杂样品；密度法通过酒精度与密度推算，速度快但受酒精、甘油与 extract 影响。不同方法对“残糖”的覆盖面不同，所以两组数据不能直接横比。

检测口径还涉及单位与换算。RS 以 g/L 表示，总糖常以葡萄糖计；两者在数值上可能接近，但概念不同。啤酒行业更常用发酵度、最终比重（final gravity）与 real extract 描述剩余糖，而不是直接写 RS；因此啤酒的“甜”与葡萄酒的“残糖”不能按同一套数字比较。

## 标签与法规中的用法

欧盟葡萄酒标签规则把甜度词与残糖区间绑定：干型 ≤4 g/L，总酸 ≥7 g/L 时可到 9 g/L；半干 >4 且 ≤12 g/L，总酸 ≥10 g/L 时上限 18 g/L；半甜 >12 且 ≤45 g/L；甜型 >45 g/L。生产者只有在满足条件时才能使用相应术语。[干型](ref:dry)、[半干](ref:semi-dry)与[甜型](ref:sweet)是同一体系的相邻档位。

中国 GB/T 15037-2006《葡萄酒》按总糖划分：干型 ≤4.0 g/L（总糖与总酸差值 ≤2.0 g/L 时可到 9.0 g/L），半干 4.1–12.0 g/L，半甜 12.1–45.0 g/L，甜型 ≥45.1 g/L。注意这里用的是总糖，不是严格意义的残糖。判断标签是否合规，仍要查对应产品标准与标签法规；[GB/T 17204-2021](ref:gbt-17204)提供的是饮料酒分类与术语框架，不替代具体产品标准。

## 甜型酒与起泡酒的残糖

甜型酒的残糖可以来自晚收、贵腐、冰冻、稻草晾晒或加强。晚收让葡萄在藤上积累糖分；贵腐菌浓缩糖与酸；冰酒在冻结状态下压榨，留下高糖浓缩汁；加强酒则靠酒精中止发酵。它们的 RS 常达 50 g/L 以上，部分可达 100–200 g/L，具体取决于风格与法规。

起泡酒的残糖主要来自 dosage。brut 通常 ≤12 g/L，extra dry 约 12–17 g/L，sec 约 17–32 g/L，demi-sec 约 32–50 g/L，doux >50 g/L。这里的数字是最终成品的残糖，不是基酒的残糖；理解这一点，才能解释为什么同一款基酒可以做成 brut 或 demi-sec。[葡萄酒](ref:wine)的甜度标签与起泡酒体系因此不能直接互换。

## 易混术语对照

第一组：残糖与总糖。残糖是可发酵糖的剩余量，总糖是检测得到的糖总量，后者可能包含不可发酵成分。第二组：残糖与甜感。前者是化学量，后者是感官判断，受酸度、酒精、温度、气泡与香气影响。第三组：残糖与 extract。extract 是酒中除酒精与水以外的所有溶解物，包含糖、甘油、酸与矿物质，不等于糖。

第四组：葡萄酒 RS 与啤酒发酵度。啤酒的剩余糖与最终比重、发酵度相关，行业更常用 attenuation 描述；把葡萄酒的 g/L 直接套到啤酒上，会忽略麦芽提取物与二氧化碳的影响。[啤酒](ref:beer)的“干”与葡萄酒的“干”因此只是类比，不是同一指标。

## 常见误用与争议

第一，把残糖等同于甜度。第二，认为残糖越低越好：对某些风格，适量残糖是平衡的一部分；对另一些风格，残糖会带来稳定性风险。第三，把“无糖”当成“无热量”：酒精本身有热量，残糖只是其中一部分。第四，忽视检测口径，把不同实验室的数据直接横比。

争议集中在标签与健康两端。标签端的分歧是阈值是否应与酸度绑定，以及是否应强制标注 RS 数值；健康端的争议是“低糖”宣传是否会让消费者忽略酒精热量。对生产者而言，残糖还关乎二次发酵风险与货架稳定；对消费者而言，最可靠的做法是看标签、查技术资料，而不是只看“干”或“甜”一个字。

## 典型数值与例子

欧盟分级：干型 ≤4 g/L（总酸 ≥7 g/L 时 ≤9 g/L）；半干 >4 且 ≤12 g/L（总酸 ≥10 g/L 时 ≤18 g/L）；半甜 >12 且 ≤45 g/L；甜型 >45 g/L。中国 GB/T 15037-2006：干型 ≤4.0 g/L、半干 4.1–12.0 g/L、半甜 12.1–45.0 g/L、甜型 ≥45.1 g/L。

具体例子：多数干型白葡萄酒的 RS 在 1–3 g/L；brut 香槟通常在 10 g/L 上下；半干雷司令常见 8–12 g/L；贵腐甜酒与冰酒常超过 100 g/L。这些数字只是风格参考，不能替代标签与检测报告。

## 另见

- [葡萄酒](ref:wine)
- [起泡酒](ref:sparkling)
- [啤酒](ref:beer)
- [干型](ref:dry)
- [半干](ref:semi-dry)
- [甜型](ref:sweet)
- [GB/T 17204-2021](ref:gbt-17204)
