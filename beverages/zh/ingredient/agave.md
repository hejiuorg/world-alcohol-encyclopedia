---
schema_version: 1
id: ingredient:agave
type: ingredient
lang: zh
slug: agave
title: 龙舌兰（龙舌兰属）
summary: 龙舌兰属是多肉植物，其 heart（piña）富含菊粉类果聚糖；蒸煮水解后发酵蒸馏，成为特基拉与梅斯卡尔的核心原料，品种、成熟年限与烘烤方式决定风味。
status: reviewed
revision: 2
legacy_refs: []
aliases:
  - 龙舌兰
  - 龙舌兰心
  - agave
  - maguey
tags:
  - ingredient
  - plant
  - agave-spirit
related:
  - relation: about
    target_id: drink-style:tequila
  - relation: about
    target_id: drink-style:mezcal
  - relation: about
    target_id: region:tequila
  - relation: about
    target_id: region:oaxaca
  - relation: about
    target_id: process:distillation
  - relation: about
    target_id: process:fermentation
references:
  - key: tequila
    target_id: drink-style:tequila
  - key: mezcal
    target_id: drink-style:mezcal
  - key: tequila-region
    target_id: region:tequila
  - key: oaxaca
    target_id: region:oaxaca
  - key: distillation
    target_id: process:distillation
  - key: fermentation
    target_id: process:fermentation
sources:
  - key: crt
    title: Consejo Regulador del Tequila — Norma Oficial Mexicana NOM-006-SCFI-2012
    url: https://www.crt.org.mx/
    publisher: Consejo Regulador del Tequila (CRT)
    note: 用于核对特基拉法定原料、产区与工艺框架；未复制原文。
    accessed: 2026-11-07
  - key: oxford-spirits
    title: The Oxford Companion to Spirits and Cocktails
    publisher: Oxford University Press
    note: 参考其关于龙舌兰、特基拉与梅斯卡尔的条目。
    accessed: 2026-11-07
    url: https://global.oup.com/academic/product/the-oxford-companion-to-spirits-and-cocktails-9780199311132
  - key: crm
    title: Consejo Regulador del Mezcal — Norma Oficial Mexicana NOM-070-SCFI-2016
    url: https://www.crm.org.mx/
    publisher: Consejo Regulador del Mezcal (CRM)
    note: 用于核对梅斯卡尔的法定定义与允许龙舌兰品种框架；未复制原文。
    accessed: 2026-11-07
  - key: ref
    title: "The Oxford Companion to Spirits and Cocktails（Oxford University Press）。"
    publisher: "未注明"
    note: 由原条目末尾参考资料迁移，未逐条复核访问日期。
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写，依据墨西哥官方标准与烈酒工具书核验；未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方标准、商标与图片不在本许可内；来源仅作核验引用。
verification_scope: source-verified
---
# 龙舌兰（龙舌兰属）

龙舌兰属（Agave）是原产美洲的多年生多肉植物，约有二百余个种。酿酒用的不是叶片，而是茎与叶基膨大形成的“心”（piña）。这块组织储存的是果聚糖而非淀粉，因此糖化不靠麦芽酶，而靠蒸煮或烘烤让果聚糖水解。特基拉与梅斯卡尔的风味差异，很大程度上从这里开始。

![龙舌兰（龙舌兰属） 图像](/media/photos/ingredient-agave-6671c637.jpg)

图：龙舌兰（龙舌兰属）。图片：Marc Ryckaert ( MJJR )，CC BY-SA 3.0，via Wikimedia Commons（[原图页面](https://commons.wikimedia.org/wiki/File:Agave_americana_R01.jpg)）。

## 龙舌兰属与莲座结构

龙舌兰呈莲座状，叶片肥厚、边缘带齿，靠景天酸代谢在夜间固定二氧化碳，白天关闭气孔以减少水分散失。植株生长缓慢，蓝韦伯龙舌兰通常要 6–8 年才达到采收糖度，部分大株需要 10 年以上。采收时割去叶片，挖出茎心，重量从十几公斤到上百公斤不等。

龙舌兰主要靠基生芽（hijuelo）繁殖，母株旁边长出的小苗在移栽后 6–8 年成熟。栽培密度、降雨与土壤会影响果聚糖积累，干旱年份的植株糖度更高但重量偏低。采收工人（jimador）要用刀逐片削去叶片，判断成熟度靠叶色、株型与茎心粗细，经验比仪器更重要。

## 果聚糖与热解

龙舌兰心的干物质中，果聚糖可占 50–70%，主要以菊粉型果聚糖形式存在。果聚糖不能直接被酿酒酵母利用，必须经热解或酸水解为果糖与葡萄糖。蒸煮同时软化纤维、杀菌并浓缩甜味；烘烤则通过美拉德反应与焦糖化产生烟熏、焦糖与香料风味。

传统梅斯卡尔使用土坑烘烤，石头加热后覆盖纤维与泥土，持续数天；特基拉多用高压釜蒸煮，时间短、烟熏味弱。热解方式直接决定酒体的“熟果”与“烟熏”比例。

## 特基拉的法定原料与工艺

墨西哥官方标准 NOM-006 规定，特基拉只能使用蓝韦伯龙舌兰（Agave tequilana Weber var. azul），产区限定在哈利斯科、纳亚里特、瓜纳华托、米却肯与塔毛利帕斯五个州，其中哈利斯科是核心。普通特基拉要求至少 51% 的糖来自龙舌兰，其余可来自其他糖源；“100% 龙舌兰”则要求全部糖来自龙舌兰。

特基拉通常经两次蒸馏，成品酒精度 35–55% vol；陈年类别按时间划分：blanco、reposado、añejo 与 extra añejo。

特基拉委员会（CRT）负责原产地核查与防伪标签，每瓶合规产品都带有 NOM 编号与批次信息；100% 龙舌兰产品还会标注“100% de agave”。梅斯卡尔则由 CRM 等机构监管，但小作坊众多，标准化程度低于特基拉。消费者看到的“龙舌兰酒”标签，可能对应完全不同的原料比例与工艺。

## 梅斯卡尔与产区

梅斯卡尔的标准 NOM-070 允许多种龙舌兰属植物，产区覆盖瓦哈卡、杜兰戈、瓜纳华托等多个州。瓦哈卡是产量与知名度最高的产区，传统上使用 espadín 等品种。不同品种的成熟期差异很大，野生种往往比栽培种更晚采收，产量也低。梅斯卡尔强调土坑烘烤与小型蒸馏器，烟熏味是其识别特征，但并非所有梅斯卡尔都重烟熏。

## 发酵与蒸馏

热解后的龙舌兰心被粉碎、压榨，得到含糖果汁与纤维渣，加水后进入发酵。传统酒坊依靠野生酵母与环境微生物，发酵时间 3–10 天；现代酒厂使用商业酵母，控温发酵，速度更快、稳定性更高。发酵容器的材质（木桶、石槽或不锈钢）会影响微生物群落与温度曲线，传统酒坊常把发酵时间拉长到一周以上，以积累更多酸与酯。发酵完成的醪液经壶式蒸馏器两次蒸馏，掐头去尾取中段。

## 替代与差异

用龙舌兰糖浆替代龙舌兰心，可以快速提供果糖，但缺少植物纤维、矿物质与热解风味，做不出传统特基拉的层次。用玉米或甘蔗糖蜜替代，成本更低，却会改变法定类别与香气。不同龙舌兰品种的果聚糖结构与风味前体不同，espadín 与蓝韦伯不能简单互换。

## 感官影响

龙舌兰酒的核心香气是熟龙舌兰、青椒、柑橘、黑胡椒与矿物感。蒸煮带来甜熟果与焦糖，土坑烘烤带来烟熏、灰烬与香料；发酵温度高时出现香蕉与菠萝酯香，温度低时更保留植物感。陈年在橡木桶中会增加香草、椰子与甜香料，但会削弱龙舌兰本身的青绿调。

## 常见误区

第一，龙舌兰酒就是特基拉。特基拉是梅斯卡尔体系之外的独立受保护类别，只用蓝韦伯龙舌兰。第二，龙舌兰心是果实。它是茎与叶基的膨大组织。第三，所有梅斯卡尔都有浓重烟熏味。烘烤方式与品种差异很大。第四，龙舌兰糖浆等于龙舌兰酒。前者是甜味剂，后者是蒸馏酒。

## 另见

- [特基拉](ref:tequila)：蓝韦伯龙舌兰与法定产区。
- [梅斯卡尔](ref:mezcal)：土坑烘烤与多品种体系。
- [特基拉产区](ref:tequila-region)：哈利斯科等五个州。
- [瓦哈卡](ref:oaxaca)：梅斯卡尔的核心产区。
- [蒸馏](ref:distillation)：壶式两次蒸馏。
- [发酵](ref:fermentation)：野生酵母与控温发酵。

对照阅读：[龙舌兰酒](ref:tequila)、[龙舌兰酒法定产区](ref:tequila-region)。

**关键事实。**

| 项目 | 内容 |
| --- | --- |
| 一句话定位 | 龙舌兰属是多肉植物，其 heart（piña）富含菊粉类果聚糖；蒸煮水解后发酵蒸馏，成为特基拉与梅斯卡尔的核心原料，品种、成熟年限与烘烤方式决定风味 |
| 原料身份 | 龙舌兰属是多肉植物，其 heart（piña）富含菊粉类果聚糖 |
| 加工用途 | 蒸煮水解后发酵蒸馏，成为特基拉与梅斯卡尔的核心原料，品种、成熟年限与烘烤方式决定风味 |

**来源与边界。** 本页关于「龙舌兰（龙舌兰属）」的关键事实，主要由以下来源交叉核对：Consejo Regulador del Tequila (CRT)（特基拉法定原料、产区与工艺框架）、Oxford University Press（提供关于龙舌兰、特基拉与梅斯卡尔的条目）、Consejo Regulador del Mezcal (CRM)（梅斯卡尔的法定定义与允许龙舌兰品种框架）等 4 条来源。价格、批次与状态会变，涉及这些字段时以页面所列来源的最新版本为准。正文为项目自写，来源只作核验，不复制原文。

**并读。** 把「龙舌兰（龙舌兰属）」与「龙舌兰酒」、「梅斯卡尔」、「龙舌兰酒法定产区」放在一起读时，先确认它们是同一层级还是上下游关系：先确认原料形态与产地，再比较加工、风味与替代关系。本页负责给出原料的基本坐标，对照条目补上具体案例与差异；读完再回到本页，才能分清哪些差别属于原料本身，哪些只是产地、批次或品牌选择。

**适用边界。** 对「龙舌兰（龙舌兰属）」而言，原料的品种、加工形态与产地会改变风味；本页说明通用角色，不替代具体配方。
