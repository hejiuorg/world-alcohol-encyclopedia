---
schema_version: 1
id: drink-style:stout
type: drink-style
lang: zh
slug: stout
title: 世涛
summary: 以烘焙大麦赋予深色与咖啡可可风味的上面发酵啤酒，名称源自更烈的波特，都柏林干世涛为代表，内部还分化出甜世涛、燕麦世涛与帝国世涛。
status: reviewed
revision: 1
parent_style_id: drink-style:beer
aroma_family: 烘焙麦芽
legacy_refs: []
aliases:
  - Stout
  - Stout beer
  - 司陶特
tags:
  - beer
  - ale
  - ireland
  - roasted-malt
related:
  - relation: about
    target_id: drink-style:beer
  - relation: about
    target_id: region:ireland
  - relation: about
    target_id: drink:ireland-guinnessdraughtstout
  - relation: about
    target_id: ingredient:barley
  - relation: about
    target_id: process:fermentation
  - relation: about
    target_id: term:craft-beer
references:
  - key: beer
    target_id: drink-style:beer
  - key: ireland
    target_id: region:ireland
  - key: guinness
    target_id: drink:ireland-guinnessdraughtstout
  - key: barley
    target_id: ingredient:barley
  - key: fermentation
    target_id: process:fermentation
  - key: craft-beer
    target_id: term:craft-beer
sources:
  - key: bjcp-2021
    title: BJCP 2021 Beer Style Guidelines
    url: https://www.bjcp.org/style/2021/beer/
    publisher: Beer Judge Certification Program
    note: 用于核对干世涛、甜世涛、燕麦世涛与帝国世涛的强度、苦度与风味边界；未复制原文。
    accessed: 2026-11-05
  - key: guinness-site
    title: Guinness — Official Site
    url: https://www.guinness.com/
    publisher: Guinness
    note: 用于核对都柏林酿造历史、产品类型与酒精度等公开信息；未复制原文。
    accessed: 2026-11-05
  - key: brewers-association
    title: Brewers Association — Beer Styles and Definitions
    url: https://www.brewersassociation.org/
    publisher: Brewers Association
    note: 用于核对美国精酿行业对世涛及其变体的公开表述；未复制其文案。
    accessed: 2026-11-05
  - key: oxford-beer
    title: The Oxford Companion to Beer
    publisher: Oxford University Press
    note: 参考其关于波特与世涛历史、都柏林酿造与帝国世涛的条目；未复制原文。
    accessed: 2026-11-05
    url: https://global.oup.com/academic/product/the-oxford-companion-to-beer-9780195367133

rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写；依据风格指南、酒厂公开信息、行业协会资料与工具书核验，未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方风格指南、商标、图片与引用文本不在本许可内；来源仅作核验引用。第三方图片已在图注中标注作者与许可。
verification_scope: source-verified
---
# 世涛

世涛（stout）是一类深色上面发酵啤酒，以烘焙大麦带来的咖啡、可可与烘烤香气为特征。名称源自 18 世纪的“stout porter”，即更烈的波特；19 世纪在都柏林形成以干世涛为代表的形态，20 世纪又分化出甜世涛、燕麦世涛与帝国世涛。世涛不是“最烈的啤酒”的同义词，其内部强度差异很大。

![世涛 图像](/media/photos/drink-style-stout-5ced0da8.webp)

图：世涛。图片：55belgianbeerfan，CC0，via Wikimedia Commons（[原图页面](https://commons.wikimedia.org/wiki/File:A_Pint_of_English_Imperial_Stout.png)）。

## 定义与标准

在[啤酒](ref:beer)的风格体系中，世涛通常被分为干世涛、甜世涛、燕麦世涛与帝国世涛等条目。干世涛酒精度常见 4.0–5.0%，苦度约 30–45 IBU；帝国世涛酒精度常在 8% 以上，风味更浓、更甜，酒体更厚。分类依据是配方目标与强度，不是颜色深浅。

颜色范围从深棕到近乎黑色，但色度本身不构成风格定义。一款加了大量黑麦芽的烈性艾尔未必叫世涛，而一款颜色较浅的干世涛仍可能属于这一家族。读标签时，酒精度、配方描述与发酵度比色卡更有参考价值。

## 产地与风格/历史

18 世纪初，伦敦的波特（porter）以深色麦芽与较长的陈放赢得市场，随后出现更烈的“stout porter”，即世涛的前身。18 世纪后期，都柏林的酿酒业开始规模化生产波特与世涛。1759 年，阿瑟·健力士（Arthur Guinness）租下圣詹姆斯门酿酒厂，此后公司逐步把波特与世涛做成面向海外市场的产品。今日的[健力士生啤](ref:guinness)是干世涛最常见的样本，产自[爱尔兰](ref:ireland)。

19 世纪，帝国世涛（Russian imperial stout）作为高酒精度、重酒花的出口啤酒，运往波罗的海与俄罗斯市场。20 世纪，英国本土又发展出添加乳糖的甜世涛与添加燕麦的燕麦世涛。风格的分化，往往来自原料可得性、运输条件与消费口味的变化。

## 原料与工艺

[大麦](ref:barley)是世涛的主体。基础淡色麦芽提供酶与可发酵糖，未发芽的烘焙大麦（roasted barley）带来深色、咖啡与可可风味，也可以使用黑麦芽。烘焙程度与谷物比例决定色度、苦味与焦香质量。高比例烘焙谷物会增加糖化与过滤的难度，因此配方需要平衡。

[发酵](ref:fermentation)为上层发酵，温度通常在 18–22°C。干世涛追求较高的发酵度，让酒体保持轻到中等、收口干爽；甜世涛添加乳糖，因乳糖不可被酿酒酵母发酵，残留甜味与顺滑口感得以保留。氮气侍酒通过细密气泡改变泡沫质感，但风味主体仍来自麦芽与发酵。

现代[精酿啤酒](ref:craft-beer)把世涛扩展到桶陈、加咖啡、加巧克力、加香草或乳糖的版本。这些增味做法属于配方创新，不改变世涛的基本结构：深色烘焙谷物、上层发酵与相对完整的麦芽骨架。

## 风味特征

酒液呈深棕至黑色，逆光观察常见红宝石色边缘。香气以咖啡、黑巧克力、烘烤面包为主，可能带坚果、果干或轻微焦糖；酒花通常只提供背景苦味。干世涛入口轻快，烘焙苦味清晰，收口干净；帝国世涛酒体厚，甜感、酒精温暖与苦味同时存在；甜世涛则更柔滑、更甜。

优质世涛的烘焙味应当干净，不应出现焦糊、烟熏刺鼻或纸板味。后两者通常指向原料处理或氧化问题，而不是风格特征。温度升高后，酒精感与甜感都会更明显，这也是品鉴时需要控制温度的原因。

## 品鉴与饮用

干世涛适饮温度约 6–10°C，帝国世涛可以稍高至 12–16°C。温度过低会压住咖啡与可可香气，过高则让酒精感变得突出。杯型影响泡沫与香气聚集，郁金香杯或收口杯都适用；氮气版本的泡沫更细密，倒酒时应让泡沫自然形成。

佐餐时，干世涛适合生蚝、烤肉与硬质奶酪，帝国世涛适合重口味炖菜与黑巧克力甜点。保存应避光、阴凉，瓶装产品注意生产日期。低酒精度的干世涛宜趁新鲜饮用，高酒精度的帝国世涛在合适条件下可以适度陈放。乳糖甜世涛不适合乳糖不耐受者。

## 常见误区

第一，认为世涛一定最烈、最厚重。干世涛的酒精度常与普通拉格接近。
第二，把世涛与波特当成对立面。二者共享深色麦芽基础，差别在强度、甜度与烘焙程度。
第三，认为颜色越黑就越焦苦。色度来自烘焙，苦味质量取决于工艺。
第四，相信世涛营养丰富或可以补铁。这类民间说法缺乏可靠依据。
第五，认为所有世涛都适合长期陈放。只有高酒精度、结构完整的版本才有陈放价值。

对照阅读：[啤酒](ref:beer)、[健力士世涛啤酒](ref:guinness)。

## 延伸阅读

- [啤酒](ref:beer)：理解世涛在啤酒风格体系中的位置。
- [爱尔兰](ref:ireland)：都柏林酿造传统与干世涛的产地。
- [健力士生啤](ref:guinness)：干世涛最常见的代表性产品。
- [大麦](ref:barley)：烘焙大麦与深色风味的来源。
- [发酵](ref:fermentation)：上层发酵与发酵度对酒体的影响。
- [精酿啤酒](ref:craft-beer)：当代世涛增味与桶陈版本的背景。

**关键事实。**

| 项目 | 内容 |
| --- | --- |
| 一句话定位 | 以烘焙大麦赋予深色与咖啡可可风味的上面发酵啤酒，名称源自更烈的波特，都柏林干世涛为代表，内部还分化出甜世涛、燕麦世涛与帝国世涛 |
| 上位风格 | 啤酒 |
| 香气家族 | 烘焙麦芽 |

**来源与边界。** 本页关于「世涛」的关键事实，主要由以下来源交叉核对：Beer Judge Certification Program（干世涛、甜世涛、燕麦世涛与帝国世涛的强度、苦度与风味边界）、Guinness（都柏林酿造历史、产品类型与酒精度等公开信息）、Brewers Association（美国精酿行业对世涛及其变体的公开表述；未复制其文案）等 4 条来源。价格、批次与状态会变，涉及这些字段时以页面所列来源的最新版本为准。正文为项目自写，来源只作核验，不复制原文。

**并读。** 把「世涛」与「啤酒」、「爱尔兰」、「健力士世涛啤酒」放在一起读时，先确认它们是同一层级还是上下游关系：先确认定义与工艺，再比较原料、产区与代表品牌。本页负责给出酒类风格的基本坐标，对照条目补上具体案例与差异；读完再回到本页，才能分清哪些差别属于酒类风格本身，哪些只是产地、批次或品牌选择。

**适用边界。** 对「世涛」而言，法定定义、原料比例与地域风格会随法规和行业分类更新；品牌案例不等于整个风格。

**更新提示。** 「世涛」最近核对于 2026-11-05；价格、状态与公开信息会变，引用前以本页来源的最新版本为准。
