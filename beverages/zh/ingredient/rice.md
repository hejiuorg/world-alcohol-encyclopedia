---
schema_version: 1
id: ingredient:rice
type: ingredient
lang: zh
slug: rice
title: 大米
summary: 稻谷脱壳碾磨后的籽粒，是白酒、黄酒与清酒的重要淀粉原料；粳米与籼米的淀粉结构、黏性与蒸煮表现不同，直接影响糖化与发酵。
status: reviewed
revision: 1
legacy_refs: []
aliases:
  - 稻米
  - Rice
tags:
  - curated
  - source-verified
  - ingredient
  - grain
  - baijiu
related:
  - relation: about
    target_id: drink-style:baijiu
  - relation: about
    target_id: drink-style:strong-aroma-baijiu
  - relation: about
    target_id: drink-style:yellow-wine
  - relation: about
    target_id: drink-style:sake
  - relation: about
    target_id: process:saccharification
references:
  - key: baijiu
    target_id: drink-style:baijiu
  - key: strong-aroma
    target_id: drink-style:strong-aroma-baijiu
  - key: yellow-wine
    target_id: drink-style:yellow-wine
  - key: sake
    target_id: drink-style:sake
  - key: saccharification
    target_id: process:saccharification
sources:
  - key: gbt-15109
    title: 国家标准全文公开系统 — GB/T 15109-2021 白酒工业术语
    url: https://openstd.samr.gov.cn/bzgk/std/newGbInfo?hcno=D2F1ED3F0BAA0EBE99AEE34293C0BC43
    publisher: 国家市场监督管理总局、国家标准化管理委员会
    published: 2021-05-21
    note: 用于核对白酒原料与工艺术语；未复制原文。
    accessed: 2026-11-04
  - key: gbt-17204
    title: 国家标准全文公开系统 — GB/T 17204-2021 饮料酒术语和分类
    url: https://openstd.samr.gov.cn/bzgk/std/newGbInfo?hcno=B8F9CD37320835EEF17458CBA5962881
    publisher: 国家市场监督管理总局、国家标准化管理委员会
    published: 2021-05-21
    note: 用于核对饮料酒类别与原料术语框架；未复制原文。
    accessed: 2026-11-04
  - key: jss-sake
    title: Japan Sake and Shochu Makers Association — Sake brewing information
    url: https://www.jss.or.jp/en/
    publisher: Japan Sake and Shochu Makers Association
    note: 用于核对清酒的原料米、精米与制曲框架；未复制原文。
    accessed: 2026-11-04
  - key: c-ref-1
    title: FAO — Food and Agriculture Organization
    url: https://www.fao.org/
    publisher: FAO
    accessed: 2026-11-21
    note: 用于补充核对条目背景、术语与制度口径；未复制原文。
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写；依据国家标准公开信息与行业机构资料核验，不复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方标准、商标与图片不在本许可内；来源仅作核验引用。第三方图片已在图注中标注作者与许可。
verification_scope: source-verified
---
# 大米

大米是稻谷脱壳、碾磨后的籽粒，属于禾本科稻属（Oryza）。它是亚洲的主要粮食，也是白酒、黄酒和清酒的重要淀粉原料。与小麦、高粱不同，大米蛋白质与脂肪含量较低，淀粉颗粒细小，蒸煮后黏性较强，这些特征决定了它在糖化与发酵中的表现。

![大米 图像](/media/photos/ingredient-rice-0ee2019c.jpg)

图：大米。图片：China News Service，CC BY 3.0，via Wikimedia Commons（[原图页面](https://commons.wikimedia.org/wiki/File:20201102.Hengnan.Hybrid_rice_Sanyou-1.6.jpg)）。

## 定义与形态

按淀粉结构，日常食用的大米主要分为粳米与籼米；糯米因支链淀粉比例极高、黏性突出，通常单独讨论。粳米颗粒较短、黏性适中，籼米颗粒较长、黏性较低。酿酒用米关注淀粉总量、粒形完整度、蛋白质与碎米比例，而不是单纯追求“精白”。

碾米程度会改变籽粒外层物质的保留量。外层含蛋白质、脂肪与灰分，碾得越白，淀粉比例越高，但维生素与风味物质也相应减少。清酒通过“精米步合”控制碾磨比例，白酒与黄酒则根据工艺与成本选择不同等级的大米。

## 主要产地

稻米主产区集中在亚洲，中国、印度、印度尼西亚、孟加拉国、越南和泰国都是重要生产国。中国南方与东北均有稻作，气候、品种与栽培方式影响籽粒的淀粉结构与含水量。不同产区的大米在蒸煮吸水、黏性和糖化表现上存在差异。

同一品种在不同年份也可能因温度与降水不同而呈现不同品质。收获后的干燥与储存条件同样重要；高水分、霉变或虫害会降低原料安全性，也会带来不良风味。规模生产通常会对入厂大米做水分、杂质与霉变粒检测。

## 在白酒中的作用

[白酒](ref:baijiu)中的大米既可作为单粮原料，也可进入多粮配方。[浓香型白酒](ref:strong-aroma)常见高粱、大米、糯米、小麦、玉米并用，大米为酒体带来绵柔与净爽感；部分小曲白酒以大米为主料，配合小曲进行糖化发酵。

大米在白酒中通常需要蒸煮糊化，使淀粉颗粒破裂、便于酶作用。蒸煮过度会导致黏结成团、透气性下降，蒸煮不足则淀粉利用率低。固态发酵对原料的疏松程度要求较高，因此大米常与高粱、稻壳等搭配使用，而不是单独承担全部淀粉来源。

## 在黄酒与清酒中的作用

[黄酒](ref:yellow-wine)以稻米为主要原料，糯米、粳米与大米都可能使用。糯米带来黏性与丰满度，粳米提供较好的发酵稳定性，不同配比形成不同风格的黄酒。黄酒的麦曲或酒药负责[糖化](ref:saccharification)，把米淀粉转化为可发酵糖，再进行酒精发酵。

[清酒](ref:sake)同样以稻米为核心，但强调精米、蒸米与米曲。清酒先用米曲把蒸米淀粉分解为糖，再与酵母进行并行发酵；精米步合越高，外层蛋白质与脂肪去除越多，香气通常更纯净。清酒的原料米与食用米在品种与栽培要求上并不完全相同。

| 酒类 | 原料形态 | 关键工序 |
| --- | --- | --- |
| 白酒 | 大米或碎米 | 蒸煮、糖化、固态或半固态发酵、蒸馏 |
| 黄酒 | 糯米、粳米或大米 | 浸米、蒸煮、糖化、发酵、压榨 |
| 清酒 | 精白米 | 精米、蒸米、制曲、并行发酵、压榨 |

## 淀粉、黏性与工艺匹配

大米的淀粉以支链淀粉和直链淀粉混合存在，粳米与籼米的比例不同。支链淀粉高的米蒸煮后黏性强，糖化时容易结团；直链淀粉较高的米结构更松散，但可能缺少丰满度。工艺需要通过浸泡、蒸煮时间、摊凉与翻拌来控制这些差异。

大米蛋白与脂肪含量较低，发酵时产生的杂味相对少，但也不是“越纯越好”。过度精白会损失部分风味前体，增加成本；保留适量外层物质则可能带来更丰富的香气。评价时应把碾磨程度、蒸煮表现与目标酒种放在一起看。

## 选购与储存

选购大米时可关注粒形完整度、碎米比例、颜色与气味。酿酒用米通常要求新鲜、无霉味、无虫害、杂质少。储存要防潮、防虫、避光，避免与有异味的物品混放；高温高湿环境容易导致品质下降与霉变。

家庭自酿应选择来源清楚、生产日期较近的大米，并注意饮用水与器具卫生。规模生产还会关注农药残留与重金属指标，这些安全项不应被“口感好”所替代。

## 常见误区

第一，大米只能做主食。它在白酒、黄酒与清酒中都是核心原料。

第二，米越白越适合酿酒。过度碾磨会损失风味前体并增加成本。

第三，所有米都能直接互换。粳米、籼米与糯米的淀粉结构和蒸煮表现不同。

第四，清酒用的米就是普通食用米。清酒有专门的酒造好适米与精米要求。

第五，大米酒一定清淡无味。风味取决于曲、发酵、蒸馏与陈年，而不是原料单一因素。

对照阅读：[白酒](ref:baijiu)、[黄酒](ref:yellow-wine)。

## 延伸阅读

- [白酒](ref:baijiu)：大米在白酒原料体系中的位置。
- [浓香型白酒](ref:strong-aroma)：多粮配方中的大米与糯米。
- [黄酒](ref:yellow-wine)：稻米、麦曲与发酵的传统组合。
- [清酒](ref:sake)：精米、米曲与并行发酵的体系。
- [糖化](ref:saccharification)：米淀粉如何转化为可发酵糖。

**关键事实。**

| 项目 | 内容 |
| --- | --- |
| 一句话定位 | 稻谷脱壳碾磨后的籽粒，是白酒、黄酒与清酒的重要淀粉原料；粳米与籼米的淀粉结构、黏性与蒸煮表现不同，直接影响糖化与发酵 |
| 原料身份 | 稻谷脱壳碾磨后的籽粒，是白酒、黄酒与清酒的重要淀粉原料 |
| 加工用途 | 粳米与籼米的淀粉结构、黏性与蒸煮表现不同，直接影响糖化与发酵 |

**来源与边界。** 本页关于「大米」的关键事实，主要由以下来源交叉核对：国家市场监督管理总局、国家标准化管理委员会（白酒原料与工艺术语；饮料酒类别与原料术语框架）、Japan Sake and Shochu Makers Association（清酒的原料米、精米与制曲框架）、FAO（补充核对条目背景、术语与制度口径）。价格、批次与状态会变，涉及这些字段时以页面所列来源的最新版本为准。正文为项目自写，来源只作核验，不复制原文。

**并读。** 把「大米」与「白酒」、「浓香型白酒」、「黄酒」放在一起读时，先确认它们是同一层级还是上下游关系：先确认原料形态与产地，再比较加工、风味与替代关系。本页负责给出原料的基本坐标，对照条目补上具体案例与差异；读完再回到本页，才能分清哪些差别属于原料本身，哪些只是产地、批次或品牌选择。
