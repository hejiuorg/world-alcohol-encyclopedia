---
schema_version: 1
id: drink-style:awamori
type: drink-style
lang: zh
slug: awamori
title: 泡盛
summary: 冲绳县以米与黑曲为原料、全量制曲并单式蒸馏得到的米制蒸馏酒；酒税法上属于单式蒸馏烧酒，常见 30% vol，贮藏三年以上按行业惯例称为古酒，可长期陈年。
status: reviewed
revision: 2
legacy_refs: []
parent_style_id: drink-style:shochu
aroma_family: 米香/陈香
aliases:
  - 泡盛
  - Awamori
  - 琉球泡盛
tags:
  - curated
  - source-verified
  - style-guide
  - shochu
related:
  - relation: about
    target_id: drink-style:shochu
  - relation: about
    target_id: process:distillation
  - relation: about
    target_id: ingredient:rice
  - relation: about
    target_id: region:japan
  - relation: about
    target_id: process:fermentation
references:
  - key: shochu
    target_id: drink-style:shochu
  - key: distillation
    target_id: process:distillation
  - key: rice
    target_id: ingredient:rice
  - key: japan
    target_id: region:japan
  - key: fermentation
    target_id: process:fermentation
sources:
  - key: jss
    title: Japan Sake and Shochu Makers Association — Shochu and awamori classification
    url: https://www.jss.or.jp/
    publisher: Japan Sake and Shochu Makers Association
    note: 用于核对泡盛与本格烧酒的分类、原料与标示差异；未复制原文。
    accessed: 2026-11-08
  - key: nta-info
    title: 国税庁 — 酒類に関する情報
    url: https://www.nta.go.jp/taxes/sake/
    publisher: 日本国税庁
    note: 用于核对单式蒸馏烧酒的定义、酒精度上限与泡盛的产地条件；未复制原文。
    accessed: 2026-11-08
  - key: nta-hyoji
    title: 国税庁 — 酒類の表示
    url: https://www.nta.go.jp/taxes/sake/hyoji/mokuji.htm
    publisher: 日本国税庁
    note: 用于核对泡盛及古酒的标示规则与地理标志背景；未复制原文。
    accessed: 2026-11-08
  - key: oxford-spirits
    title: The Oxford Companion to Spirits and Cocktails — Awamori entries
    publisher: Oxford University Press
    note: 参考其关于泡盛历史、黑曲与古酒的条目；未复制原文。
    accessed: 2026-11-08
    url: https://global.oup.com/academic/product/the-oxford-companion-to-spirits-and-cocktails-9780199311132

rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写；依据日本国税厅/行业协会/工具书核验，未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方标准、商标、图片与引用文本不在本许可内；来源仅作核验引用。本页未使用第三方图片。
verification_scope: source-verified
---
# 泡盛

泡盛的配方短得惊人：米、黑曲、水，加酵母。它没有二次仕込み，没有连续蒸馏，也不靠低温慢慢磨香。可是这套简单的流程在冲绳的高温高湿里运行了几百年，还长出一条别的日本蒸馏酒少有的传统——把酒封进陶坛，等上三年、十年、三十年，变成“古酒”。

![泡盛 类型示意图](/media/photos/theme-beer.jpg)

图：泡盛 类型示意图。图片：Doubao Seedream 5.0 AI 辅助绘制（项目自有），不是泡盛的实拍。

## 先分清三个邻居

泡盛常被误认成清酒或芋烧酒。它不是清酒：清酒是发酵酒，泡盛是蒸馏酒，酒精度与保存方式完全不同。它也不是芋烧酒：本格烧酒的主原料可以是甘薯、麦、荞麦或黑糖，泡盛的主原料只能是米，曲只能是黑曲。

还有一层容易混的地方是“黑糖”。黑糖是冲绳的甘蔗制品，可以当烧酒原料；黑曲是曲菌，属于微生物。两者名字里都有“黑”，实际毫无关系。

## 酒税法里的位置

日本酒税法把烧酒分成连续蒸馏与单式蒸馏两大类。泡盛归入单式蒸馏烧酒，也就是常说的乙类；它的酒精度上限是 45% vol，市售产品以 30% vol 最常见。

标注“泡盛”还受产地约束：必须在冲绳县内生产，原料为米与黑曲，经单式蒸馏器蒸馏。日本另有“琉球泡盛”的地理标志保护，用来区分本地产品与县外仿制。产地、原料、蒸馏方式三项一起构成它的法律身份。

## 琉球王府与暹罗商路

泡盛的技术源头通常被放在琉球王国与东南亚的贸易线上。稻米蒸馏的知识随商路进入琉球，当地用黑曲适应炎热气候，逐渐形成以米为单一主原料的蒸馏酒。琉球王国时期的文献里已经出现“泡盛”之名，酒造与王府的仪礼、宴飨和日常消费紧密相连。

1879 年琉球处分后，冲绳进入日本近代行政体系。二战后的美军统治时期，泡盛在物资短缺中重建；1972 年冲绳回归日本，日本酒税法全面适用，原料、蒸馏与标示被纳入统一框架。古酒也从地方习俗变成正式的产品线。

## 黑曲：把柠檬酸写进发酵罐

泡盛用的是黑曲菌，学名 Aspergillus luchuensis，旧称 A. awamori。它在蒸米上生长时会分泌大量柠檬酸，把醪液的 pH 迅速压低。这一步在冲绳格外重要：气温高，杂菌繁殖快，靠酸度把环境“锁”住，比靠低温更现实。

黑曲不只负责防腐。它影响糖化速度、氨基酸生成与香气前体，使泡盛常带米香、乳酸感、蘑菇与坚果般的气息。白曲、黄曲也能酿酒，但黑曲是泡盛类别识别的一部分，换曲就等于换了一条风味路线。

## 全量制曲与一次仕込み

本格烧酒的常规做法是二次仕込み：先用水、曲与酵母做酒母，再加入蒸熟的主原料。泡盛走的是全量制曲——所有米都拿去制曲，然后把曲、水与酵母一起下罐，糖化与[发酵](ref:fermentation)在同一次操作里完成。

全量制曲的成本不低：同样米量要全部过制曲工序，曲室容量与温湿度管理成为产能瓶颈。发酵温度多在 30°C 上下，周期约两周，具体随酒藏与季节调整。温度高会加快发酵，也增加香气失控的风险，酒藏靠曲的质量、加水比例与温度曲线维持稳定。

## 单式蒸馏：为什么常见 30 度

发酵完成的醪进入单式蒸馏器，通常只蒸一次。单式蒸馏的分离效率低于连续式，酒液里保留更多高沸点物质与原料香气，酒体比甲类烧酒厚。刚蒸馏出的原酒度数很高，装瓶前加水稀释，市售多为 30% vol，也有 25%、35%、40% 与 43% 的产品。

关于[蒸馏](ref:distillation)的通用原理，可另见工艺条目。切酒同样决定风格：酒头刺激、酒尾杂味重，酒心才是主体。部分酒藏把不同批次、不同蒸馏段落的原酒分开贮存，装瓶前再调合；这类调合不改变类别，只影响风格表达。

## 古酒：陶坛、仕次与时间

古酒（クース）按行业惯例指贮藏三年以上的泡盛。颜色从无色转向琥珀，香气从锐利的米香转向干果、蜂蜜、香木与旧木。它不是法定质量等级，而是时间与仓储的结果。

并非所有泡盛都适合久放。酒体结构不足时，长时间贮存会让木味与苦味占上风；温度、湿度、容器与酒精度都会改变熟成速度。传统的“仕次”做法是把新酒补进装有老酒的陶坛，让新旧酒液持续融合，库底因此形成每个酒藏独有的风格。

## 本岛与离岛

泡盛必须在冲绳县内生产，酒藏主要集中在本岛。那霸的首里与泊一带是传统酒造聚集地；系满、名护、读谷等地也有酒藏。宫古岛、石垣岛等离岛同样生产，海运与气候条件让贮存风格出现差异。

产地不是单一风格保证。同一岛内，酒藏可以选择不同米种、曲菌、蒸馏强度与贮存方式，古酒的仓储年限也由酒藏自行决定。把“石垣岛”直接等同于某种固定风味，会忽略酒厂的技术选择。

## 在冲绳怎么喝

纯饮适合判断米香、黑曲感与蒸馏干净度。水割り最常见，通常按 1 比 1 或 2 比 1 加水，降低刺激，让米香与甜感展开；前割り是提前兑水静置一段时间，让水与酒融合得更柔和。加冰会压低香气、拉长入口；苏打割り提升清爽感，适合佐餐；加热水则在低温季节常见。

冲绳本地还有把岛辣椒泡进泡盛制成的コーレーグース，滴进汤或面里提味。它是一种调味习惯，不是泡盛的必需喝法。品鉴时先闻静止香气，再小口含住，注意甜感、苦味、酸度与收口。本页关于泡盛的内容涉及酒精饮料；过量饮酒有害健康，未成年人不应饮酒。

## 常见误解

- 泡盛是清酒：它是蒸馏酒，清酒是发酵酒。
- 泡盛是甘薯烧酒：原料只有米与黑曲，不用甘薯。
- 黑曲就是黑糖：一个是菌种，一个是甘蔗制品。
- 泡盛越陈越好：古酒需要合适酒体与仓储，不是无限期存放都变好。
- 泡盛必须加辣椒：コーレーグース只是本地调味习惯。
- 度数越高越好：度数只说明稀释程度，风格与平衡才是判断依据。

## 延伸阅读

- [日本烧酒](ref:shochu)：泡盛在酒税法中的上位类别与对照。
- [蒸馏](ref:distillation)：单式蒸馏如何保留原料香。
- [大米](ref:rice)：泡盛的单一主原料。
- [发酵](ref:fermentation)：黑曲、全量制曲与一次仕込み的关系。
- [日本](ref:japan)：冲绳与日本酒类的地理背景。

相关条目：[日本烧酒](ref:shochu)。
