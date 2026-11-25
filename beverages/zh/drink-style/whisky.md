---
schema_version: 1
id: drink-style:whisky
type: drink-style
lang: zh
slug: whisky
title: 威士忌
summary: 以谷物为原料、经发酵蒸馏并在橡木桶中陈年的烈酒；苏格兰、爱尔兰、美国、日本等地各有法规与传统。
status: reviewed
revision: 3
legacy_refs: []
aliases:
  - Whisky
  - Whiskey
tags:
  - style-guide
related:
  - relation: about
    target_id: process:oak-ageing
  - relation: about
    target_id: process:distillation
  - relation: about
    target_id: drink-style:beer
  - relation: about
    target_id: term:alcohol-by-volume
references:
  - key: oak-ageing
    target_id: process:oak-ageing
  - key: distillation
    target_id: process:distillation
  - key: beer
    target_id: drink-style:beer
  - key: abv
    target_id: term:alcohol-by-volume
sources:
  - key: swa
    title: Scotch Whisky Association — Scotch Whisky Regulations and Facts
    url: https://www.scotch-whisky.org.uk/
    publisher: Scotch Whisky Association
    note: 用于核对苏格兰威士忌的法定产区、原料、蒸馏与最低陈年要求；未复制原文。
    accessed: 2026-11-04
  - key: irish-whiskey
    title: Irish Whiskey Association — Protected Status and Production
    url: https://www.irishwhiskeyassociation.ie/
    publisher: Irish Whiskey Association
    note: 用于核对爱尔兰威士忌的地理标志与基本工艺边界；未复制原文。
    accessed: 2026-11-04
  - key: ttb
    title: TTB Beverage Alcohol Manual — Distilled Spirits
    url: https://www.ttb.gov/
    publisher: U.S. Alcohol and Tobacco Tax and Trade Bureau
    note: 用于核对美国威士忌（包括波本与黑麦）的标识与法定类别；未复制原文。
    accessed: 2026-11-04
  - key: oxford-spirits
    title: The Oxford Companion to Spirits and Cocktails
    publisher: Oxford University Press
    note: 参考其关于威士忌蒸馏、陈年与区域风格的条目；未复制原文。
    accessed: 2026-11-04
    url: https://global.oup.com/academic/product/the-oxford-companion-to-spirits-and-cocktails-9780199311132
  - key: ref
    title: "《The Oxford Companion to Spirits and Cocktails》威士忌条目"
    publisher: "Oxford University Press"
    note: 由原条目末尾参考资料迁移，未逐条复核访问日期。
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写；依据协会与法规公开资料核验，未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方标准、商标、图片与引用文本不在本许可内；来源仅作核验引用。第三方图片已在图注中标注作者与许可。
verification_scope: source-verified
---
# 威士忌

威士忌（whisky；爱尔兰与美国常拼作 whiskey）是以谷物为原料，经糖化、发酵、蒸馏，并在橡木桶中陈年的烈酒。谷物、蒸馏器、橡木桶与当地气候共同决定风味；不同产区的法定要求则决定了哪些酒可以合法使用“苏格兰”“波本”等名称。

![威士忌 图像](/media/photos/drink-style-whisky-d84866a3.jpg)

图：威士忌。图片：Guinnog，CC BY-SA 3.0，via Wikimedia Commons（[原图页面](https://commons.wikimedia.org/wiki/File:Whiskyhogmanay2010.jpg)）。

## 先划清「威士忌」的边界
威士忌的工艺链条是“谷物糖化—发酵—蒸馏—桶陈”。糖化后的含糖液体与啤酒的麦芽汁在原理上相近，因此可以把威士忌理解为“把发酵谷物酒再蒸馏并陈年”的产品；但[啤酒](ref:beer)本身是发酵酒，不经过蒸馏。与白兰地相比，威士忌的原料是谷物，而不是葡萄或水果。

“威士忌”在不同国家有不同法定定义，共同点通常包括谷物原料、蒸馏、橡木桶陈年与最低[酒精度](ref:abv)。没有在橡木桶中陈年的谷物蒸馏酒不能叫威士忌；有些市场允许极短的陈年，但标签必须如实标示。

## 「威士忌」的时间线
威士忌的文字记载可追溯到 15 世纪的苏格兰，早期以修道院与地方蒸馏传统为基础。17 至 18 世纪，税收与许可制度推动了合法与非法蒸馏的分化，也促成了蒸馏技术的改良。19 世纪，连续蒸馏器与铁路运输让调和威士忌走向大众市场。

爱尔兰、美国与日本各自发展出不同传统：爱尔兰强调三次蒸馏与壶式蒸馏，美国以玉米与黑麦建立波本与黑麦体系，日本在 20 世纪引入苏格兰工艺并发展出精细调配。21 世纪，单一麦芽与桶陈实验重新成为市场焦点。

## 主要传统

- **苏格兰威士忌**：必须在苏格兰蒸馏并在橡木桶中陈年至少 3 年，瓶装酒精度不低于 40% vol。单一麦芽来自单一蒸馏厂，调和威士忌则由多家酒厂的麦芽与谷物威士忌调配。
- **爱尔兰威士忌**：以爱尔兰岛为地理标志，常见三次蒸馏与壶式蒸馏传统，口感通常较柔和。
- **美国威士忌**：波本以玉米为主要谷物，比例至少 51%，使用新烘烤橡木桶；黑麦威士忌以黑麦为主要谷物。二者都不要求在特定州生产，但都有严格的标识规则。
- **日本威士忌**：受苏格兰工艺影响，强调精细调配；近年日本行业标准对原料、蒸馏与陈年地点提出了更明确的要求。

## 原料与糖化

威士忌的原料包括大麦、玉米、黑麦与小麦。大麦常先发芽，产生淀粉酶以分解淀粉；泥煤烘烤麦芽会带来酚类香气，酚值以 ppm 计量。未发芽谷物则依靠麦芽提供的酶完成糖化。

糖化是把粉碎后的谷物与热水混合，让淀粉转化为糖。过滤后得到澄清麦芽汁，进入发酵。酵母在数十小时内把糖转化为酒精与二氧化碳，产生酯类与高级醇，这些副产物是后续风味的基础。发酵时间与温度会影响酒体的果香与谷物感。

## 蒸馏与陈年

[蒸馏](ref:distillation)在铜制壶式蒸馏器或连续蒸馏器中进行。壶式蒸馏通常进行两次，苏格兰与爱尔兰的差异在蒸馏次数与设备；连续蒸馏效率更高，常用于谷物威士忌。蒸馏师通过“切酒”分离头段、中段与尾段，中段决定最终风格。

新酒必须进入[橡木桶陈酿](ref:oak-ageing)。桶型包括曾装波本的橡木桶、雪莉桶与新桶；桶的尺寸、烘烤程度与仓库温湿度都会改变熟成速度。橡木带来颜色、香草与香料，也允许缓慢氧化。陈年环境在海边或内陆会带来不同的盐感与木质气息。

## 「威士忌」的闻与喝
威士忌的香气分为谷物、泥煤、花果、香料与木质几组。苏格兰单一麦芽常见泥煤烟熏、海盐与果香；波本强调香草、焦糖与玉米甜感；黑麦带胡椒与辛香；爱尔兰威士忌通常更柔和。口感从轻盈到厚重，酒精度与桶陈共同决定结构。

品鉴时先观察颜色，再闻香：先找谷物与桶香，再找泥煤或花果。入口注意酒精与酒体的融合，以及收口是否干净。加少量室温水能降低酒精刺激、打开香气，但水量应逐步增加。对比品鉴时，先确定产区与风格，再判断完成度。

## 「威士忌」的饮用与搭配
纯饮可以完整感受香气；加少量室温水能降低酒精刺激、打开香气，但水量应逐步增加。加冰会降温和稀释，适合较高酒精度或较厚重的酒款。高球（威士忌加苏打水）是另一种合理喝法，不必把纯饮当作唯一“正确”方式。

佐餐时，轻盈的单一麦芽适合海鲜与白肉，泥煤风味适合烤肉与烟熏食物，波本适合烧烤与甜点。高酒精度会放大辛辣感，搭配时应避免过辣菜式。酒杯以郁金香形或高脚杯为宜，能聚拢香气而不至于让酒精过于突出。

## 「威士忌」容易被读错的地方
第一，认为单一麦芽一定优于调和威士忌。二者是不同结构，调和的目标是稳定与平衡。
第二，认为年份越长越好。桶陈过头会带来过多木质与涩感，原酒结构更重要。
第三，认为颜色越深越老。颜色受桶型、烘烤与焦糖色影响，不能单独判断年份。
第四，把“单一麦芽”理解为“单一桶”。单一麦芽指单一蒸馏厂的麦芽威士忌，仍可由多桶调配。
第五，认为威士忌必须来自苏格兰。爱尔兰、美国、日本等地都有成熟的法定传统。

对照阅读：[橡木桶陈酿](ref:oak-ageing)、[啤酒](ref:beer)。

**来源与边界。** 本页关于「威士忌」的关键事实，主要由以下来源交叉核对：Scotch Whisky Association（苏格兰威士忌的法定产区、原料、蒸馏与最低陈年要求）、Irish Whiskey Association（爱尔兰威士忌的地理标志与基本工艺边界）、U.S. Alcohol and Tobacco Tax and Trade Bureau（美国威士忌（包括波本与黑麦）的标识与法定类别）等 5 条来源。价格、批次与状态会变，涉及这些字段时以页面所列来源的最新版本为准。正文为项目自写，来源只作核验，不复制原文。

## 参考资料
- [蒸馏](ref:distillation)：威士忌从发酵谷物酒变为烈酒的关键。
- [橡木桶陈酿](ref:oak-ageing)：颜色、香气与熟成速度的来源。
- [啤酒](ref:beer)：与威士忌共享谷物糖化与发酵原理的饮品。
- [酒精度](ref:abv)：比较不同威士忌强度时的基础指标。
