---
schema_version: 1
id: term:alcohol-by-volume
type: term
lang: zh
slug: alcohol-by-volume
title: 酒精度（ABV）
summary: 酒精度指 20°C 时酒中乙醇的体积分数，通常写作 % vol；它是标签与配方的基础参数，但不是品质评分。
status: reviewed
revision: 1
legacy_refs: []
aliases:
  - 酒精度
  - 乙醇体积分数
  - alcohol by volume
  - ABV
tags:
  - term
  - measurement
  - labelling
related:
  - relation: about
    target_id: drink-style:baijiu
  - relation: about
    target_id: drink-style:wine
  - relation: about
    target_id: term:original-gravity
  - relation: about
    target_id: standard:gbt-15109-2021
references:
  - key: baijiu
    target_id: drink-style:baijiu
  - key: wine
    target_id: drink-style:wine
  - key: c-extra-1
    target_id: term:original-gravity
sources:
  - key: oiv-definitions
    title: OIV International Code of Oenological Practices — Part I Definitions
    url: https://www.oiv.int/standards/international-oenological-codex/part-i-definitions
    publisher: International Organisation of Vine and Wine (OIV)
    note: 用于核对葡萄酒酒精度的定义与测量口径，未复制原文。
    accessed: 2026-11-04
  - key: eu-fic
    title: Regulation (EU) No 1169/2011 on the provision of food information to consumers, Annex XII
    url: https://eur-lex.europa.eu/eli/reg/2011/1169/oj
    publisher: European Union
    note: 用于核对酒精饮料标签上酒精度标示的规则。
    accessed: 2026-11-04
  - key: gbt-17204-2021
    title: GB/T 17204-2021 饮料酒术语和分类
    url: https://openstd.samr.gov.cn/bzgk/std/newGbInfo?hcno=B8F9CD37320835EEF17458CBA5962881
    publisher: 国家市场监督管理总局、国家标准化管理委员会
    published: 2021-05-21
    accessed: 2026-11-04
    note: 用于核对公开信息与页面事实；未复制原文。
  - key: c-ref-1
    title: Encyclopaedia Britannica — reference entry
    url: https://www.britannica.com/
    publisher: Encyclopaedia Britannica
    accessed: 2026-11-21
    note: 用于补充核对条目背景、术语与制度口径；未复制原文。
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写，依据 OIV、欧盟法规与中国国家标准公开信息核验；未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方标准、法规文本、商标与图片不在本许可内；来源仅作核验引用。
verification_scope: source-verified
---
# 酒精度（ABV）

酒精度（alcohol by volume，常缩写为 ABV）描述一瓶酒里乙醇所占的体积比例。它通常以“% vol”表示，例如 12.5% vol 表示在 20°C 时，每 100 体积单位的酒液中含有 12.5 体积单位的纯乙醇。它是配方、标签、税收和饮用建议的基础参数，但不是质量评分。

![酒精度（ABV） 类型示意图](/media/photos/theme-wine-spirits.jpg)

图：酒精度（ABV） 类型示意图。图片：Doubao Seedream 5.0 AI 辅助绘制（项目自有），不是酒精度（ABV）的实拍。

## 定义与测量口径

OIV 在《国际葡萄酒法典》的定义部分使用“实际酒精度（actual alcoholic strength by volume）”这一表述，测量条件统一到 20°C。之所以规定温度，是因为水和乙醇的热膨胀系数不同，同一瓶酒在不同温度下测得的体积会变化，体积分数也会随之漂移。把温度固定下来，不同实验室、不同年份的数据才有可比性。

中国国家标准体系同样使用体积分数口径。GB/T 17204-2021《饮料酒术语和分类》为饮料酒及其类别提供术语框架，具体产品的酒精度要求则要看对应的产品标准。不同酒种对酒精度的法定范围并不相同：葡萄酒有最低实际酒精度要求，白酒、威士忌、伏特加等蒸馏酒则常见更高的度数区间。

## 酒精度不等于“酒体强度”

酒精度只说明乙醇占多少体积，不说明香气、甜度、酸度、单宁或口感。两款同为 13% vol 的[葡萄酒](ref:wine)，可能一款清爽轻盈，另一款浓郁厚重；两款同为 52% vol 的[白酒](ref:baijiu)，也可能因香型、原料和工艺而呈现完全不同的风味。把酒精度当作“好喝”或“更烈”的唯一指标，会忽略酒体结构。

反过来，低酒精度也不等于“淡”。啤酒、黄酒、清酒可以在较低酒精度下保有复杂的谷物香、酸度和鲜味；利口酒则可能用糖和香气弥补较低的酒精刺激。评价一款酒时，酒精度只是众多变量之一。

## 标签上的酒精度

欧盟《食品信息条例》（Regulation (EU) No 1169/2011）的附件 XII 规定，酒精度超过 1.2% vol 的饮料必须标示实际酒精度，数值保留不超过一位小数，后接“% vol”，测定温度为 20°C。这套规则的目的，是让消费者在同一货架上能够比较不同产品，而不是让生产者用模糊的“高度”“低度”来做营销。

中国市场的预包装饮料酒标签则受食品安全国家标准与相关产品标准约束，标示方式、允许误差和豁免情形需要按具体品类核对。无论在哪一个市场，标签上的数字都应该能与检测报告对应；如果两者差距明显，就值得进一步核实。

## 常见误区

第一，酒精度不是“原料浓度”。发酵只能把糖转化为乙醇，酒精度首先取决于可发酵糖的数量和酵母的耐受能力；蒸馏则是把已有乙醇浓缩，不会凭空产生新的酒精。

第二，酒精度不是“陈年指标”。陈年主要影响香气、颜色和口感结构，未必显著改变酒精度；加强酒和部分甜酒的酒精度反而来自额外加入的葡萄蒸馏酒。

第三，酒精度不是“品质等级”。同一产区、同一酒种的不同产品可以因风格定位而选择不同酒精度；法规只划出允许范围，不替消费者判断好坏。

## 体积分数与质量分数

同样是“含多少酒精”，至少有两种表达。体积分数（% vol）表示乙醇体积占总体积的比例；质量分数（% mas）表示乙醇质量占总质量的比例。两者数值并不相等，因为乙醇的密度低于水：同一瓶酒的体积分数通常略高于质量分数。葡萄酒、啤酒和多数预包装饮料酒采用体积分数，因为体积便于计量、灌装和比较；化学与工程领域有时使用质量分数。阅读技术资料时，先确认用的是哪一种口径，否则会把两个不同的数字当成同一件事。

## 测量方法简述

实验室测定酒精度通常分两步：先用蒸馏或类似方法把乙醇从样品中分离出来，再测量馏出液的密度或折射率，换算成 20°C 下的体积分数。现代仪器也可以直接用振荡管密度计或近红外方法测定，但都需要用标准物质校准。对消费者而言，这些细节不必掌握；重要的是知道标签数字来自检测，而不是来自估算或营销。

## 酒精度与饮用方式

酒精度会影响饮用节奏和分量。烈酒通常以小杯、加冰或加水的方式饮用，加水会稀释酒精度，也会改变香气释放；啤酒和葡萄酒的分量更大，但单位体积的乙醇更少。理解这一点，有助于把“喝得慢一点”“多喝水”“不空腹”这些建议落实到具体场景，而不是只当成笼统的口号。

同一种酒在不同温度下，酒精的挥发和感知强度也不同。温度较高时，乙醇更容易挥发，闻起来更“冲”；温度较低时，香气更收敛，但口感可能显得单薄。这也是为什么不同类型的酒有各自的建议饮用温度。

## 标签误差与核对

不同市场允许的酒精度标示误差并不相同，有的按绝对百分点，有的按相对比例。生产者在灌装时会留出安全余量，检测机构则按标准方法复核。对消费者来说，如果一款酒的标签数字与实际口感差异明显，或同一批次出现较大波动，就值得查看检测报告和批次信息。酒精度是可以用仪器复核的客观参数，不是只能凭感觉争论的主观判断。

对照阅读：[白酒](ref:baijiu)、[原麦汁浓度（original gravity）](ref:c-extra-1)。

## 延伸阅读

- [葡萄酒](ref:wine)：葡萄酒的类别、年份与标签规则。
- [白酒](ref:baijiu)：白酒的原料、工艺与香型概览。

补充阅读：[原麦汁浓度（original gravity）](ref:c-extra-1)。

相关条目：[葡萄酒](ref:wine)。

**来源与边界。** 本页关于「酒精度（ABV）」的关键事实，主要由以下来源交叉核对：International Organisation of Vine and Wine (OIV)（葡萄酒酒精度的定义与测量口径）、European Union（酒精饮料标签上酒精度标示的规则）、国家市场监督管理总局、国家标准化管理委员会等 4 条来源。价格、批次与状态会变，涉及这些字段时以页面所列来源的最新版本为准。正文为项目自写，来源只作核验，不复制原文。

**并读。** 把「酒精度（ABV）」与「白酒」、「葡萄酒」、「原麦汁浓度（original gravity）」放在一起读时，先确认它们是同一层级还是上下游关系：先确认定义与计量口径，再比较相邻术语与常见误用。本页负责给出术语的基本坐标，对照条目补上具体案例与差异；读完再回到本页，才能分清哪些差别属于术语本身，哪些只是产地、批次或品牌选择。
