---
schema_version: 1
id: drink:sichuan-langjiu
type: drink
lang: zh
slug: sichuan-langjiu
title: 郎酒
summary: 产自四川古蔺赤水河畔的白酒品牌，兼有酱香与浓香产品；青花郎、红花郎是酱香主线，郎牌特曲等覆盖浓香与宴席场景，产地与茅台镇隔河相望。
status: reviewed
revision: 3
style_refs:
  - drink-style:baijiu
brand_refs: []
producer_refs: []
region_refs: []
ingredient_refs: []
process_refs: []
legacy_refs:
  - liquor:sichuan_langjiu
aliases:
  - Langjiu
  - Hongyun Lang
tags:
  - curated
  - source-verified
related:
  - relation: about
    target_id: process:qu-making
  - relation: about
    target_id: process:distillation
  - relation: about
    target_id: term:alcohol-by-volume
references:
  - key: baijiu
    target_id: drink-style:baijiu
  - key: qu-making
    target_id: process:qu-making
  - key: distillation
    target_id: process:distillation
  - key: abv
    target_id: term:alcohol-by-volume
sources:
  - key: langjiu-site
    title: 四川郎酒股份有限公司官方网站
    publisher: 四川郎酒股份有限公司
    note: 用于核对产地、产品系列与公开信息；未复制原文。
    accessed: 2026-11-04
  - key: gbt-15109
    title: 国家标准全文公开系统 — GB/T 15109-2021 白酒工业术语
    url: https://openstd.samr.gov.cn/bzgk/std/newGbInfo?hcno=D2F1ED3F0BAA0EBE99AEE34293C0BC43
    publisher: 国家市场监督管理总局、国家标准化管理委员会
    note: 用于核对酱香型与浓香型白酒术语；未复制原文。
    accessed: 2026-11-04
  - key: gbt-17204
    title: 国家标准全文公开系统 — GB/T 17204-2021 饮料酒术语和分类
    url: https://openstd.samr.gov.cn/bzgk/std/newGbInfo?hcno=B8F9CD37320835EEF17458CBA5962881
    publisher: 国家市场监督管理总局、国家标准化管理委员会
    note: 用于核对白酒在饮料酒分类中的位置；未复制原文。
    accessed: 2026-11-04
  - key: oxford-spirits
    title: The Oxford Companion to Spirits and Cocktails — Baijiu entries
    publisher: Oxford University Press
    note: 参考其关于中国白酒与酱香风格的条目；未复制原文。
    accessed: 2026-11-04
    url: https://global.oup.com/academic/product/the-oxford-companion-to-spirits-and-cocktails-9780199311132
  - key: ref
    title: "《The Oxford Companion to Spirits and Cocktails》白酒条目"
    publisher: "Oxford University Press"
    note: 由原条目末尾参考资料迁移，未逐条复核访问日期。
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写；依据生产者、国家标准与工具书核验，未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方标准、商标、图片与引用文本不在本许可内；来源仅作核验引用。图片按各自许可见图注署名。
verification_scope: source-verified
---
# 郎酒

郎酒产自四川古蔺二郎镇，位于赤水河畔，产品兼有酱香型和浓香型，其中青花郎等酱香产品较为知名。常见酱香产品酒精度为 53% vol。

![郎酒类别配图](/media/photos/drink-style-light-aroma-baijiu-1c3af236.jpg)

图：郎酒所属的白酒类别配图。图片：Xiaomage de，CC BY-SA 4.0，via Wikimedia Commons（[原图页面](https://commons.wikimedia.org/wiki/File:Vertreter_der_vier_Baijiu_Kategorien.jpg)）。这张图片用于标识品类，不是郎酒的产品、包装或门店实拍。

## 定义与定位

郎酒是[白酒](ref:baijiu)中的一个品牌，产品线横跨酱香与浓香两种风格。品牌名、香型与产地需要分开看：二郎镇是产地，郎酒是品牌，酱香或浓香是工艺与风味类别。同属赤水河谷，也不意味着所有产品都是同一种香型。

酱香产品属于蒸馏酒，酒精度以[体积分数](ref:abv)标示，常见为 53% vol。不同产品线的度数、酒体与勾调目标不同，比较时应先确认香型，再谈风格。

## 产区与环境

二郎镇位于赤水河中游，河谷深切、湿度较高，夏季炎热，冬季相对温和。这样的气候有利于开放式制曲、堆积发酵与长期贮存中的微生物活动。当地水源与河谷空气被视为酱香风格的环境条件之一。

郎酒的一大特点是利用天然溶洞贮存基酒。溶洞内温度与湿度相对稳定，陶坛中的酒液在较恒定的环境中缓慢变化。洞藏不是神秘化概念，它本质上是一种贮存环境管理；效果仍取决于基酒质量、容器与时间。

赤水河谷的水质与紫色砂页岩地层，常被当地酒业视为酿造条件。这类说法有地域经验基础，但不宜当作唯一解释；原料、曲、窖池与勾调同样决定成品风格。

## 原料与制曲

酱香产品以高粱为原料，用小麦制作高温大曲。高粱需要耐得住多轮蒸煮，支链淀粉比例高的糯高粱更合适。小麦制曲后经过堆积与翻曲，形成细菌、霉菌与酵母共存的群落，为后续发酵提供酶与香气前体。

[制曲](ref:qu-making)是酱香风格的基础。高温大曲的曲香、焦香与焙烤香，会在发酵和蒸馏中转化为成品中的复合香气。浓香产品则更依赖泥窖与续糟配料，曲种与窖池管理不同，风味走向也不同。

## 「郎酒」怎么做出来
酱香产品的公开工艺与茅台镇一带的做法相近：一年一个生产周期，两次投料，多轮蒸煮、发酵与取酒。每一轮次取得的基酒风格不同，需要分型贮存，再经勾调形成成品。取酒之后的陈贮是风格形成的重要阶段。

浓香产品采用泥窖固态发酵、续糟配料与混蒸混烧。两种工艺对设备、窖池与时间的要求不同，因此同一品牌下的酱香与浓香产品，不能简单用“郎酒风格”一概而论。产品标签上的香型标注是判断工艺路线的第一手信息。

## 「郎酒」的闻与喝
酱香产品通常具有酱香、焦香和花果香，酒体较厚，回味较长；浓香产品则更强调窖香和粮香，入口甜感更明显。赤水河谷的气候与水源被视为其酿造条件之一，但不同厂区和产品线的风格并不相同。

品鉴酱香产品时，用小杯静置闻香，再小口品尝，注意酱香、焦香与花果香的次序，以及酒精是否被酒体托住。品鉴浓香产品时，重点看窖香是否干净、粮香是否清晰。两者适用不同的评价框架，不宜用同一把尺子。

## 产品体系与标签

郎酒有青花郎、红花郎等酱香产品线，也有浓香与兼香类产品。不同系列的定位、价格与酒体设计不同，酒标上的香型、酒精度、生产商与执行标准是核对身份的关键。市场上存在相似命名与仿冒产品，应通过正规渠道购买。

“洞藏”“年份”等表述需要结合企业说明与标签理解。洞藏描述的是贮存环境，不等于瓶中酒液的准确年龄；年份酒的具体规则也应由企业标准说明，不能只凭包装推断。

## 「郎酒」的饮用与搭配
酱香产品适合小杯纯饮，常温饮用即可；浓香产品可以按个人习惯纯饮或搭配菜肴。佐餐时，酱香适合酱味、卤味与烧烤，浓香适合川菜与家常菜。高度酒不宜快速饮用，餐前少量、慢饮更能体会层次。

郎酒也可以用于调制，但 53% vol 的强度会显著改变成品平衡。加冰或大量兑水并非传统方式，会稀释香气并改变结构。开瓶后应避光、阴凉存放，并尽量在合理时间内喝完。

## 「郎酒」容易被读错的地方
第一，把郎酒全部当成酱香酒。品牌下同时有浓香与兼香产品，需看标签。
第二，认为赤水河畔的酒都一样。产区共享环境，但工艺与产品设计不同。
第三，把洞藏等同于年份保证。洞藏是贮存条件，不是具体酒龄。
第四，认为酒精度越高越好。度数服务于酒体设计，低度版本也有完整目标。
第五，用包装或价格判断真伪。防伪、渠道与标签核对才可靠。

对照阅读：[白酒](ref:baijiu)、[蒸馏](ref:distillation)。

**关键事实。**

| 项目 | 内容 |
| --- | --- |
| 一句话定位 | 产自四川古蔺赤水河畔的白酒品牌，兼有酱香与浓香产品，青花郎等酱香产品较为知名 |
| 酒种/风格 | 白酒 |

**来源与边界。** 本页关于「郎酒」的关键事实，主要由以下来源交叉核对：四川郎酒股份有限公司（产地、产品系列与公开信息）、国家市场监督管理总局、国家标准化管理委员会（酱香型与浓香型白酒术语；白酒在饮料酒分类中的位置）、Oxford University Press（提供关于中国白酒与酱香风格的条目；由原条目末尾参考资料迁移，未逐条复核访问日期）。价格、批次与状态会变，涉及这些字段时以页面所列来源的最新版本为准。正文为项目自写，来源只作核验，不复制原文。

**并读。** 把「郎酒」与「白酒」、「制曲」、「蒸馏」放在一起读时，先确认它们是同一层级还是上下游关系：先确认酒种与产区，再比较年份、酒精度、价格与饮用场景。本页负责给出酒款的基本坐标，对照条目补上具体案例与差异；读完再回到本页，才能分清哪些差别属于酒款本身，哪些只是产地、批次或品牌选择。

## 参考资料
- [白酒](ref:baijiu)：郎酒所属的大类与工艺背景。
- [制曲](ref:qu-making)：高温大曲如何塑造酱香。
- [蒸馏](ref:distillation)：白酒取酒与分级的基础工序。
- [酒精度](ref:abv)：比较不同产品强度的指标。
