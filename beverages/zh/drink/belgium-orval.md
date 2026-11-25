---
schema_version: 1
id: drink:belgium-orval
type: drink
lang: zh
slug: belgium-orval
title: 奥瓦尔
summary: 比利时奥瓦尔圣母修道院出产的唯一一款修道院艾尔，常见 5.2% vol、330 mL，干投啤酒花并瓶内二次发酵；以花香、柑橘、干爽与轻微酸味著称，风格会随瓶陈变化。
status: reviewed
revision: 1
style_refs:
  - drink-style:beer
brand_refs: []
producer_refs: []
region_refs:
  - region:belgium
ingredient_refs:
  - ingredient:barley
  - ingredient:wheat
  - ingredient:water
process_refs:
  - process:fermentation
legacy_refs: []
aliases:
  - Orval
  - Abbaye d'Orval
  - 奥瓦尔啤酒
tags:
  - curated
  - source-verified
related: []
references:
  - key: beer
    target_id: drink-style:beer
  - key: belgium
    target_id: region:belgium
  - key: barley
    target_id: ingredient:barley
  - key: wheat
    target_id: ingredient:wheat
  - key: water
    target_id: ingredient:water
  - key: fermentation
    target_id: process:fermentation
  - key: abv
    target_id: term:alcohol-by-volume
  - key: chimay
    target_id: drink:belgium-chimay-blue
  - key: westmalle
    target_id: drink:belgium-westmalle-tripel
sources:
  - key: orval-site
    title: Abbaye d'Orval — Orval beer
    url: "https://www.orval.be/"
    publisher: Abbaye Notre-Dame d'Orval
    note: 用于核对奥瓦尔产品的酒精度、容量与干投工艺；未复制原文。
    accessed: 2026-11-04
  - key: trappist
    title: International Trappist Association — Trappist products
    url: "https://www.trappist.be/"
    publisher: International Trappist Association
    note: 用于核对修道院产品认证的公开规则；未复制原文。
    accessed: 2026-11-04
  - key: oxford-beer
    title: The Oxford Companion to Beer — Orval and bottle-conditioned ale entries
    publisher: Oxford University Press
    note: 参考其关于奥瓦尔、干投与瓶内二次发酵的条目；未复制原文。
    accessed: 2026-11-04
    url: https://global.oup.com/academic/product/the-oxford-companion-to-beer-9780195367133
  - key: ref
    title: "《The Oxford Companion to Beer》奥瓦尔与瓶内二次发酵条目"
    publisher: "Oxford University Press"
    note: 由原条目末尾参考资料迁移，未逐条复核访问日期。
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写；依据修道院与行业协会公开资料核验，未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方认证标识、商标与图片不在本许可内；来源仅作核验引用。图片按各自许可见图注署名。
verification_scope: source-verified
abv:
  min: 5.2
  max: 5.2
  unit: percent-vol
---
# 奥瓦尔

奥瓦尔是比利时奥瓦尔圣母修道院出产的唯一一款修道院艾尔，常见 5.2% vol、330 mL。它干投啤酒花并在瓶中二次发酵，以花香、柑橘、干爽与轻微酸味著称，风味会随瓶陈时间变化。

![奥瓦尔类别配图](/media/photos/drink-style-abbey-beer-276b4dc3.jpg)

图：奥瓦尔所属的啤酒类别配图。图片：BLloydT，CC BY-SA 4.0，via Wikimedia Commons（[原图页面](https://commons.wikimedia.org/wiki/File:A_wall_of_Belgian_beer_bottles_at_the_Bruges_beer_experience.jpg)）。这张图片用于标识品类，不是奥瓦尔的产品、包装或门店实拍。

## 定义与定位

先分层：啤酒是大类，修道院艾尔是传统与制度背景，比利时是产区，奥瓦尔是修道院、品牌与单一产品。四层分开看，才不会把认证标识、修道院历史与瓶中风味混为一谈。

奥瓦尔只生产一款啤酒，这在修道院酒厂中比较少见。它的风格难以归入单一标签：既有干投带来的花香，又有瓶内微生物带来的酸味与干爽口感，通常被描述为介于淡色艾尔与酸味啤酒之间，本页不强行套用某一种固定分类。

## 生产者与品牌

奥瓦尔啤酒由比利时卢森堡省维莱尔-德旺-奥瓦尔的奥瓦尔圣母修道院生产，修道院历史可追溯到 11 世纪，现代啤酒生产始于 20 世纪 30 年代（具体年份以修道院资料为准）。修道院与酒厂有直接监督关系，属于修道院啤酒体系。

修道院、酒厂与产品是三个层级：修道院回答监督与收益去向，酒厂回答设备与工艺，产品回答酒精度、容量与风格。只有一个产品意味着品牌与产品高度重合，但认证状态仍应逐瓶核对瓶身标识。

## 「奥瓦尔」的产地与原料
产品产自[比利时](ref:belgium)瓦隆地区。比利时啤酒的两条主要传统是修道院艾尔与兰比克自然发酵，奥瓦尔属于修道院体系，但它在瓶内使用额外微生物，使成品带有一点自然发酵的酸味，这一点与多数修道院艾尔不同。

原料是[大麦](ref:barley)、[小麦](ref:wheat)与[水](ref:water)，另加啤酒花与糖。大麦提供糖化所需的淀粉与酶，小麦增加柔顺度，干投使用香型啤酒花，带来花香与柑橘气息。具体配方与比例不公开。

## 「奥瓦尔」怎么做出来
麦芽经糖化得到麦汁，加入酵母进行主[发酵](ref:fermentation)，随后干投啤酒花，再装瓶并加入糖与酵母进行二次发酵。干投指在发酵后期或装瓶前加入啤酒花，主要提取香气而非苦味，因此花香明显而苦味较低。

瓶内二次发酵除普通酵母外，还涉及能在瓶中继续作用的微生物，使酒液随时间变得更干、更酸，泡沫与香气也会变化。瓶底沉淀是正常沉积，倒酒时可留底。具体菌株与工艺参数属于修道院信息，公开程度有限。

## 「奥瓦尔」的瓶型与标签
常见[酒精度](ref:abv)为 5.2% vol，容量常见 330 mL，另有不同市场版本。标签应核对产品名、酒精度、净含量、原料、生产商与批次；修道院认证标识是否存在，也应逐瓶核对。

与多数修道院艾尔不同，奥瓦尔的适饮期与瓶陈状态关系密切：新酒与陈放数年的酒在酸度与香气上差别明显。中文背标、进口商与防伪信息是核对身份的依据，瓶身或背标上的日期信息值得留意。

## 「奥瓦尔」的闻与喝
典型香气是花香、柑橘皮、胡椒与谷物，伴随轻微酸味与草本气息；入口干爽，酒体偏轻，苦味低到中等，余味带酸与花香。随着瓶陈，酸度与干爽感通常增强，花香会变得柔和。

品鉴时建议在 8–10 摄氏度饮用，用郁金香形杯聚拢香气；温度过低会压抑花香，过高则酸味突出。倒酒时注意瓶底沉淀。开瓶后应冷藏并尽快饮用，避免反复回温。

## 「奥瓦尔」的饮用与搭配
适合搭配禽类、猪肉、沙拉、软质干酪与略带酸味的菜肴；干爽与花香能切开油脂，也能衬托食材本味。避免与重甜或重辣食物同饮，容易产生味觉冲突。

酒精度中等，但仍应适量饮用。开瓶后气泡会逐渐流失，建议在数日内喝完；存放时应避光、直立、冷藏。本页关于奥瓦尔的内容涉及酒精饮料；过量饮酒有害健康，未成年人不应饮酒。

## 「奥瓦尔」的购买与保存
购买时优先选择正规渠道，核对防伪、中文背标、进口商与批次编号，并确认瓶身认证标识与日期信息。价格随市场与渠道波动，本页不给出具体数字；由于只有一个产品，版本差异主要来自批次与瓶陈时间，而不是产品线。

未开瓶可避光、阴凉存放，部分饮者会刻意陈放以获得更酸、更干的风味；但瓶陈效果受温度与批次影响，不宜把“越陈越好”当成通则。开瓶后应冷藏并尽快饮用。

## 「奥瓦尔」容易被读错的地方
第一，把奥瓦尔当成普通淡色艾尔。干投与瓶内微生物让它带花香与酸味。
第二，把“修道院风格”当成认证。认证有专门标识与制度要求。
第三，认为所有啤酒都越新鲜越好。奥瓦尔的风味会随瓶陈变化。
第四，把瓶底沉淀当成变质。它是二次发酵的正常沉积。
第五，用包装或故事判断品质。原料、工艺与标签信息更可靠。

对照阅读：[啤酒](ref:beer)、[大麦](ref:barley)。

**关键事实。**

| 项目 | 内容 |
| --- | --- |
| 一句话定位 | 比利时奥瓦尔圣母修道院出产的唯一一款修道院艾尔，常见 5.2% vol、330 mL，干投啤酒花并瓶内二次发酵；以花香、柑橘、干爽与轻微酸味著称，风格会随瓶陈变化 |
| 酒种/风格 | 啤酒 |
| 产区 | 比利时 |
| 酒精度 | 5.2–5.2% vol |

**来源与边界。** 本页关于「奥瓦尔」的关键事实，主要由以下来源交叉核对：Abbaye Notre-Dame d'Orval（奥瓦尔产品的酒精度、容量与干投工艺；由原条目末尾参考资料迁移，未逐条复核访问日期）、International Trappist Association（修道院产品认证的公开规则；由原条目末尾参考资料迁移，未逐条复核访问日期）、Oxford University Press（提供关于奥瓦尔、干投与瓶内二次发酵的条目；由原条目末尾参考资料迁移，未逐条复核访问日期）。价格、批次与状态会变，涉及这些字段时以页面所列来源的最新版本为准。正文为项目自写，来源只作核验，不复制原文。

## 参考资料
- [啤酒](ref:beer)：啤酒的分类与基本工艺。
- [比利时](ref:belgium)：修道院艾尔与兰比克两条传统。
- [大麦](ref:barley)：糖化与发酵的主要原料。
- [小麦](ref:wheat)：小麦啤酒的原料基础。
- [水](ref:water)：水质对发酵与风味的影响。
- [发酵](ref:fermentation)：主发酵、干投与瓶中二次发酵。
- [酒精度](ref:abv)：5.2% vol 在标签上的含义。
- [智美蓝帽](ref:chimay)：深色修道院艾尔的对照阅读。
- [西麦尔三料](ref:westmalle)：浅色三料风格的对照阅读。
