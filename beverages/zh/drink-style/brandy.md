---
schema_version: 1
id: drink-style:brandy
type: drink-style
lang: zh
slug: brandy
title: 白兰地
summary: 以葡萄酒或其他水果酒蒸馏而成的烈酒；干邑、雅文邑、卡尔瓦多斯与果渣白兰地各有法定工艺与产区。
status: reviewed
revision: 3
legacy_refs: []
aliases:
  - Brandy
tags:
  - style-guide
related:
  - relation: about
    target_id: process:distillation
  - relation: about
    target_id: process:oak-ageing
  - relation: about
    target_id: drink-style:fruit-wine
  - relation: about
    target_id: drink-style:wine
references:
  - key: distillation
    target_id: process:distillation
  - key: oak-ageing
    target_id: process:oak-ageing
  - key: fruit-wine
    target_id: drink-style:fruit-wine
  - key: wine
    target_id: drink-style:wine
sources:
  - key: bnic
    title: Bureau National Interprofessionnel du Cognac — Cognac Production Rules
    url: https://www.cognac.fr/en/
    publisher: BNIC
    note: 用于核对干邑的产区、葡萄品种、二次蒸馏与陈年要求；未复制原文。
    accessed: 2026-11-04
  - key: bnia
    title: Bureau National Interprofessionnel de l'Armagnac — Armagnac Appellation
    url: https://www.armagnac.fr/
    publisher: BNIA
    note: 用于核对雅文邑的产区、蒸馏方式与年份标示规则；未复制原文。
    accessed: 2026-11-04
  - key: eu-spirits
    title: EU Regulation 2019/787 — Definitions for Spirit Drinks
    url: https://eur-lex.europa.eu/eli/reg/2019/787/oj
    publisher: European Union
    note: 用于核对葡萄白兰地、果渣白兰地与水果白兰地的类别定义与最低要求；未复制原文。
    accessed: 2026-11-04
  - key: oxford-spirits
    title: The Oxford Companion to Spirits and Cocktails
    publisher: Oxford University Press
    note: 参考其关于白兰地蒸馏、陈年与产区的条目；未复制原文。
    accessed: 2026-11-04
    url: https://global.oup.com/academic/product/the-oxford-companion-to-spirits-and-cocktails-9780199311132
  - key: ref
    title: "《The Oxford Companion to Spirits and Cocktails》白兰地条目"
    publisher: "Oxford University Press"
    note: 由原条目末尾参考资料迁移，未逐条复核访问日期。
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写；依据产区协会、法规与工具书核验，未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方标准、商标、图片与引用文本不在本许可内；来源仅作核验引用。第三方图片已在图注中标注作者与许可。
verification_scope: source-verified
---
# 白兰地

白兰地（brandy）是以葡萄酒或其他水果酒为原料，经蒸馏得到的烈酒。以葡萄为原料的葡萄白兰地最常见；以苹果、樱桃、李子等水果为原料的则属于水果白兰地。它和“以谷物为原料的威士忌”“以甘蔗为原料的朗姆酒”是并列的蒸馏酒类别。

![白兰地 图像](/media/photos/drink-style-brandy-b2c89cad.jpg)

图：白兰地。图片：Didier Descouens，CC BY-SA 3.0，via Wikimedia Commons（[原图页面](https://commons.wikimedia.org/wiki/File:Cognac_glass.jpg)）。

## 先划清「白兰地」的边界
白兰地的核心是“先发酵、再蒸馏”。葡萄酒或[果酒](ref:fruit-wine)发酵完成后进入[蒸馏](ref:distillation)，得到酒精度更高的原酒，再经陈年与调配装瓶。它不可能是浸泡酒：把水果泡在烈酒里得到的是配制酒，不是白兰地。

在欧盟烈酒法规中，“Brandy / Weinbrand”是受保护的类别名称，要求以葡萄酒蒸馏物为基、最低酒精度 36% vol，并在橡木容器中陈酿至少一年。干邑与雅文邑是在这一大类之下、受更严格产区规则约束的地理标志产品。水果白兰地则属于另一类别，原料不是葡萄。

## 「白兰地」的时间线
白兰地的出现与蒸馏技术在欧洲的传播有关。中世纪后期，葡萄酒被蒸馏成“烧酒”以便运输与保存，荷兰商人把这类酒称为 brandewijn，意为“燃烧的酒”。17 世纪，海运与贸易让法国西部的葡萄酒蒸馏业扩张，干邑与雅文邑逐渐形成各自的产区传统。

18 至 19 世纪，橡木桶运输与陈年意外地改变了风味：酒液在桶中变柔、上色，并产生香草与香料气息。此后，分级标示、产区法规与地理标志逐步建立。20 世纪，白兰地成为全球化的烈酒品类，同时保留了以产区命名的高端分支。

## 主要类型

- **干邑（Cognac）**：法国干邑产区的葡萄白兰地，主要使用白玉霓等葡萄，经二次蒸馏后在法国橡木桶中陈年。酒标上的 VS、VSOP、XO 对应不同的最低陈年要求。
- **雅文邑（Armagnac）**：法国加斯科涅地区的葡萄白兰地，常用柱式蒸馏器，风格通常更粗犷、香气更集中；也有年份标示传统。
- **卡尔瓦多斯（Calvados）**：法国诺曼底以苹果酒蒸馏得到的苹果白兰地，受产区法规保护。
- **果渣白兰地**：以葡萄皮渣蒸馏，意大利的格拉巴（grappa）和法国的马克（marc）都属于这一传统。
- **水果白兰地**：以樱桃、李子、梨等水果发酵后蒸馏，德语区的樱桃酒（Kirschwasser）和威廉梨酒是常见例子。

## 原料与蒸馏

葡萄白兰地的原料是酿酒葡萄，通常选择酸度高、糖度中等的品种，因为高酸能让蒸馏后的酒体更有活力。压榨、发酵得到白葡萄酒后，必须在酒液未变质前蒸馏。干邑传统使用铜制壶式蒸馏器进行两次蒸馏，雅文邑则多用连续式柱式蒸馏器。

蒸馏的“切酒”决定风格：头段与尾段含有较多杂质，中段才是目标。蒸馏师根据经验判断切换点，不同酒厂的切点差异会直接反映在香气上。果渣白兰地使用压榨后的皮渣加水发酵，因此风味更粗粝，也更依赖原料新鲜度。

## 陈年与调配

[橡木桶陈酿](ref:oak-ageing)会带来香草、焦糖、香料和木质风味，也让酒液从无色变为琥珀色。新桶的影响更强，旧桶更柔和。干邑通常在法国橡木桶中陈年，具体桶型与烘烤程度由酒厂决定。

干邑和雅文邑的年份标示规则不同：前者多为调配酒，瓶上等级对应最低陈年，VS 为至少 2 年、VSOP 为至少 4 年、XO 为至少 10 年；后者可以有单一年份产品。陈年时间越长并不自动等于品质越高，原酒结构和调配目标同样重要。

## 「白兰地」的闻与喝
年轻白兰地偏葡萄、花香与轻微酒精感，陈年后出现香草、干果、焦糖与皮革。干邑通常更精致、层次分明，雅文邑更饱满、香气更集中。水果白兰地强调原料的果香，樱桃酒与梨酒常有明显的杏仁或花香。

品鉴时用郁金香形杯，先观察颜色深浅，再闻香：先找果香，再找桶带来的香草与香料，最后看是否有陈年的干果气息。入口注意酒精与酒体的融合，以及收口是否干爽。加几滴水可以打开香气，但不要一次加太多。

## 「白兰地」的饮用与搭配
纯饮时使用郁金香形或球形杯，室温或稍微加温即可；加冰会降低香气释放，但适合较高酒精度或较年轻的酒款。白兰地也可以用于 Sidecar、Brandy Alexander 等经典鸡尾酒。作为餐后酒，它适合搭配坚果、巧克力与干酪。

佐餐时，干邑的香气与烤禽、蘑菇类菜肴相合；雅文邑的厚度适合红肉与浓郁酱汁；苹果白兰地适合苹果甜点与奶酪。高酒精度会放大辛辣食物的刺激感，搭配时应避免过辣与过酸的菜式。

## 「白兰地」容易被读错的地方
第一，把白兰地等同于干邑。干邑是白兰地中的一个产区类别，其他产区与水果白兰地同样合法。
第二，认为 XO 一定是年份最长的酒。XO 是最低陈年门槛，不是单一陈年数字，瓶中最年轻的原酒才决定标示。
第三，认为颜色越深越老。颜色受桶型、烘烤程度与焦糖色影响，不能单独作为判断依据。
第四，认为水果白兰地都是甜酒。多数水果白兰地是干型，甜感来自果香与陈年，而不是添加糖。
第五，忽视酒精度差异。不同类别与市场版本的最低酒精度不同，应以标签为准。

对照阅读：[蒸馏](ref:distillation)、[果酒](ref:fruit-wine)。

**来源与边界。** 本页关于「白兰地」的关键事实，主要由以下来源交叉核对：BNIC（干邑的产区、葡萄品种、二次蒸馏与陈年要求）、BNIA（雅文邑的产区、蒸馏方式与年份标示规则）、European Union（葡萄白兰地、果渣白兰地与水果白兰地的类别定义与最低要求）等 5 条来源。价格、批次与状态会变，涉及这些字段时以页面所列来源的最新版本为准。正文为项目自写，来源只作核验，不复制原文。

**并读。** 把「白兰地」与「蒸馏」、「橡木桶陈酿」、「果酒」放在一起读时，先确认它们是同一层级还是上下游关系：先确认定义与工艺，再比较原料、产区与代表品牌。本页负责给出酒类风格的基本坐标，对照条目补上具体案例与差异；读完再回到本页，才能分清哪些差别属于酒类风格本身，哪些只是产地、批次或品牌选择。

## 参考资料
- [蒸馏](ref:distillation)：白兰地形成的核心工序。
- [橡木桶陈酿](ref:oak-ageing)：颜色、香气与质感变化的来源。
- [果酒](ref:fruit-wine)：水果白兰地的发酵前身。
- [葡萄酒](ref:wine)：葡萄白兰地的原料基础。
