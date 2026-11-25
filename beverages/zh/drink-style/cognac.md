---
schema_version: 1
id: drink-style:cognac
type: drink-style
lang: zh
slug: cognac
title: 干邑
summary: 法国干邑产区以葡萄蒸馏而成的白兰地，1936 年获原产地命名控制；以白玉霓为主，经夏朗德壶式二次蒸馏与法国橡木桶陈年，VS、VSOP、XO、XXO 各有法定最低酒龄。
status: reviewed
revision: 2
legacy_refs: []
parent_style_id: drink-style:brandy
aroma_family: 果香/花香/橡木
aliases:
  - 干邑
  - 干邑白兰地
  - Cognac
tags:
  - curated
  - source-verified
  - style-guide
  - brandy
related:
  - relation: about
    target_id: drink-style:brandy
  - relation: about
    target_id: process:distillation
  - relation: about
    target_id: process:oak-ageing
  - relation: about
    target_id: variety:trebbiano
  - relation: about
    target_id: region:cognac
  - relation: about
    target_id: term:appellation
references:
  - key: brandy
    target_id: drink-style:brandy
  - key: distillation
    target_id: process:distillation
  - key: oak-ageing
    target_id: process:oak-ageing
  - key: trebbiano
    target_id: variety:trebbiano
  - key: cognac
    target_id: region:cognac
  - key: appellation
    target_id: term:appellation
sources:
  - key: bnic
    title: Bureau National Interprofessionnel du Cognac — Cognac Production Rules
    url: https://www.cognac.fr/en/
    publisher: BNIC
    note: 用于核对干邑的产区范围、允许品种、夏朗德壶式蒸馏、陈年与等级规则；未复制原文。
    accessed: 2026-11-08
  - key: eu-spirits
    title: EU Regulation 2019/787 — Spirit Drinks
    url: https://eur-lex.europa.eu/eli/reg/2019/787/oj
    publisher: European Union
    note: 用于核对葡萄白兰地与地理标志烈酒的定义框架；未复制原文。
    accessed: 2026-11-08
  - key: oxford-spirits
    title: The Oxford Companion to Spirits and Cocktails
    url: https://global.oup.com/academic/product/the-oxford-companion-to-spirits-and-cocktails-9780199311132
    publisher: Oxford University Press
    note: 参考其关于干邑、夏朗德蒸馏器与酒龄标示的条目；未复制原文。
    accessed: 2026-11-08
  - key: c-ref-1
    title: BJCP — Beer Style Guidelines
    url: https://www.bjcp.org/
    publisher: BJCP
    accessed: 2026-11-21
    note: 用于补充核对条目背景、术语与制度口径；未复制原文。
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写；依据 BNIC、欧盟烈酒法规与工具书核验，未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方标准文本、商标、图片与引用文本不在本许可内；来源仅作核验引用。第三方图片已在图注中标注作者与许可。
verification_scope: source-verified
---
# 干邑

干邑的核心不是“高级白兰地”四个字，而是一套可以逐项检查的制度：葡萄种在哪个村、用哪些品种、什么时候蒸馏、用什么形状的壶、在什么桶里放多久、瓶中最年轻的原酒几岁。任何一项不达标，酒就不能叫 Cognac。把它当成地理标志来读，比当成品牌来读更接近事实。

![干邑 图像](/media/photos/drink-style-cognac-b2c89cad.jpg)

图：干邑。图片：Didier Descouens，CC BY-SA 3.0，via Wikimedia Commons（[原图页面](https://commons.wikimedia.org/wiki/File:Cognac_glass.jpg)）。

## 从 1936 年的 AOC 说起

干邑是法国最早取得原产地命名控制的烈酒之一，1936 年正式确立 AOC 地位。今天它同时受法国原产地命名体系与欧盟烈酒法规保护，属于[白兰地](ref:brandy)大类下受[原产地命名](ref:appellation)约束的分支。

保护范围不止“Cognac”这个词，还包括一系列产区术语与等级用语。一个常见的误会是“在干邑镇装瓶就算干邑”；实际上，葡萄来源、蒸馏地点与陈年地点都必须落在划定区域内，装瓶只是最后一环。

## 六道关卡

第一道是产区。葡萄必须来自夏朗德省与滨海夏朗德省为主的划定市镇。第二道是品种，以白玉霓为主，另有白福儿、鸽笼白、蒙蒂勒、赛美蓉与福丽酿等允许品种。

第三道是压榨与发酵。采收后尽快压榨，得到酸度高、酒精度低的白葡萄汁，发酵时不加或极少加二氧化硫。第四道是蒸馏，必须在采收后次年 3 月 31 日前完成，用夏朗德壶式蒸馏器二次蒸馏。

第五道是陈年。原酒进入法国橡木桶，在官方监管的酒窖中熟成。第六道是装瓶，酒精度不得低于 40% vol。六道关卡串起来，才是“干邑”这个名称的全部含义。

## 夏朗德壶式蒸馏器

这套器具的特征是带一个预热器（chauffe-vin）。待蒸馏的葡萄酒先流经预热器，被蒸馏器顶部的酒精蒸气加热，再进入壶体；蒸气本身因此冷凝。热量被重复利用，酒液也提前升温，整套流程比普通壶式蒸馏更省燃料。

蒸馏分两次。第一次得到约 27% 至 30% vol 的粗馏酒（brouillis），第二次取中段，得到不超过 72.5% vol 的无色原酒（bonne chauffe）。切酒由蒸馏师凭经验判断：酒头回收再蒸，酒尾回到下一锅，只有酒心进入陈年。关于[蒸馏](ref:distillation)的通用原理，可另见工艺条目。

## 六大 cru

干邑分为六个产区，法语称 cru。大香槟区以白垩土为主，酒体细腻、酸度高、陈年潜力长；小香槟区土壤相近，熟成稍快；边缘区面积最小，常带坚果与紫罗兰；优质林区果味直接、熟成较快；良林区与普通林区受海洋影响更明显，风格朴实。

酒标上的“Fine Champagne”受规则约束：调配中至少一半来自大香槟区，其余来自小香槟区。它和香槟酒无关，“fine”也不是质量形容词，而是历史形成的产区组合称谓。把 cru 当成质量排名，会忽略调配与桶陈在风格里的作用。

## 等级是一条时间线

等级由瓶中最年轻的原酒决定，不是平均年龄。VS 至少 2 年，VSOP 至少 4 年，XO 至少 10 年，XXO 至少 14 年。2018 年起 XO 的最低酒龄从 6 年提高到 10 年，是近几十年最重要的一次调整。

标“Napoleon”的产品在市场上常见，但它不是独立的法定等级；它的酒龄通常高于 VSOP，具体仍要看生产者的说明。读标时应把等级、产区、装瓶商与年份信息分开看，标签只保证“不低于”，不保证“正好”。

## 桶材：利穆赞与特龙赛

法国橡木桶主要来自两个林区。利穆赞橡木纹理宽、单宁与木质素含量高，给酒更明显的丹宁结构与香草、烘烤感；特龙赛橡木纹理细、香气更柔和，常被认为更适合长时间陈年。新桶带来更多木质与香料，旧桶则让果香与陈香更突出。

[橡木桶陈年](ref:oak-ageing)过程中，酒精度会因酒精与水分的挥发而缓慢下降，颜色加深，涩感变圆。酒窖的湿度与温度、桶的容量与摆放位置，都会改变这一过程。颜色深浅因此不能单独作为酒龄证据。

## 调配：把年份藏进风格

干邑几乎都是调配酒。调配师从不同 cru、不同年份、不同桶型的原酒中取样，按香气、酒体与收口组合，目标是让品牌每一批产品的风格稳定。大香槟提供骨架与陈年潜力，边缘区补充花香与坚果，林区提供果味与体积。

单一年份干邑存在，但不是主流产品；多数品牌以“无年份”的稳定风格为核心。这与雅文邑把单一年份当常规产品的传统形成对照。两种做法各有逻辑，没有高下。

## 品鉴与饮用

用郁金香形杯，室温。先看颜色深浅，再闻白花、梨、柑橘与香草，入口注意酸度、酒精与木质的平衡，最后看回味。加一滴水能打开香气，但干邑通常不需要大幅稀释。

VS 与 VSOP 适合加冰或调酒，Sidecar、French Connection 都以干邑为基酒；XO 与更老的版本更适合纯饮，配巧克力、干果与干酪。冰会压低香气释放，是否加冰取决于酒龄与个人偏好。本页关于干邑的内容涉及酒精饮料；过量饮酒有害健康，未成年人不应饮酒。

## 常见误解

- 干邑就是白兰地：它只是白兰地中一个受保护的产区名称。
- XO 是具体年份：XO 是最低酒龄门槛，由瓶中最年轻原酒决定。
- 颜色越深越老：颜色受桶型、烘烤、仓储与焦糖色影响。
- 干邑只用白玉霓：它占主导，但允许名单中还有其他品种。
- Fine Champagne 是香槟：它是干邑内部两个产区的组合术语。
- 装瓶后还会陈年：烈酒在瓶中不再发生有意义的陈化。

对照阅读：[白兰地](ref:brandy)、[橡木桶陈酿](ref:oak-ageing)。

## 延伸阅读

- [白兰地](ref:brandy)：干邑所属的蒸馏酒大类。
- [蒸馏](ref:distillation)：夏朗德壶式蒸馏器与二次蒸馏的作用。
- [橡木桶陈年](ref:oak-ageing)：颜色、香气与质感变化的来源。
- [白玉霓](ref:trebbiano)：干邑最主要的葡萄品种。
- [干邑产区](ref:cognac)：产区范围、气候与土壤。
- [原产地命名](ref:appellation)：理解 AOC 与地理标志制度的入口。

**关键事实。**

| 项目 | 内容 |
| --- | --- |
| 一句话定位 | 法国干邑产区以葡萄蒸馏而成的白兰地，1936 年获原产地命名控制；以白玉霓为主，经夏朗德壶式二次蒸馏与法国橡木桶陈年，VS、VSOP、XO、XXO 各有法定最低酒龄 |
| 上位风格 | 白兰地 |
| 香气家族 | 果香/花香/橡木 |

**来源与边界。** 本页关于「干邑」的关键事实，主要由以下来源交叉核对：BNIC（干邑的产区范围、允许品种、夏朗德壶式蒸馏、陈年与等级规则）、European Union（葡萄白兰地与地理标志烈酒的定义框架）、Oxford University Press（提供关于干邑、夏朗德蒸馏器与酒龄标示的条目）等 4 条来源。价格、批次与状态会变，涉及这些字段时以页面所列来源的最新版本为准。正文为项目自写，来源只作核验，不复制原文。
