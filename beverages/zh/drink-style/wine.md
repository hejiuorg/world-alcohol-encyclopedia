---
schema_version: 1
id: drink-style:wine
type: drink-style
lang: zh
slug: wine
title: 葡萄酒
summary: 以新鲜葡萄或葡萄汁发酵而成的酒精饮料，按颜色、甜度、气泡与产地法规形成不同类别；风土与年份只是部分变量。
status: reviewed
revision: 3
legacy_refs: []
aliases:
  - Wine
tags:
  - style-guide
related:
  - relation: about
    target_id: drink-style:red-wine
  - relation: about
    target_id: drink-style:white-wine
  - relation: about
    target_id: drink-style:sparkling-wine
  - relation: about
    target_id: drink-style:fortified-wine
  - relation: about
    target_id: drink:france-chateaulafiterothschild
  - relation: about
    target_id: drink:france-domperignon
references:
  - key: red-wine
    target_id: drink-style:red-wine
  - key: white-wine
    target_id: drink-style:white-wine
  - key: sparkling
    target_id: drink-style:sparkling-wine
  - key: fortified
    target_id: drink-style:fortified-wine
  - key: lafite
    target_id: drink:france-chateaulafiterothschild
  - key: dom-perignon
    target_id: drink:france-domperignon
sources:
  - key: oiv-definitions
    title: OIV International Code of Oenological Practices — Part I Definitions
    url: https://www.oiv.int/standards/international-oenological-codex/part-i-definitions
    publisher: International Organisation of Vine and Wine (OIV)
    note: 用于核对葡萄酒、特种葡萄酒、起泡酒与利口酒型葡萄酒的定义和阈值，未复制原文。
    accessed: 2026-11-04
  - key: eu-wine
    title: EU Regulation 1308/2013 — Common Market Organisation for Wine
    url: https://eur-lex.europa.eu/eli/reg/2013/1308/oj
    publisher: European Union
    note: 用于核对欧盟葡萄酒类别、地理标志与标签规则。
    accessed: 2026-11-04
  - key: gbt-17204
    title: GB/T 17204-2021 饮料酒术语和分类
    url: https://openstd.samr.gov.cn/bzgk/std/newGbInfo?hcno=B8F9CD37320835EEF17458CBA5962881
    publisher: 国家市场监督管理总局、国家标准化管理委员会
    published: "2021-05-21"
    accessed: 2026-11-04
    note: 用于核对公开信息与页面事实；未复制原文。
  - key: oxford-wine
    title: The Oxford Companion to Wine
    publisher: Oxford University Press
    note: 参考其关于葡萄品种、酿造、产区与品鉴的条目。
    accessed: 2026-11-04
    url: https://global.oup.com/academic/product/the-oxford-companion-to-wine-9780198871316
  - key: ref
    title: "The Oxford Companion to Wine（Oxford University Press）。"
    publisher: "未注明"
    note: 由原条目末尾参考资料迁移，未逐条复核访问日期。
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写；依据政府间组织、法规与工具书资料核验，未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方标准、商标、图片与引用文本不在本许可内；来源仅作核验引用。
verification_scope: source-verified
---
# 葡萄酒

葡萄酒是新鲜葡萄或葡萄汁经酵母发酵得到的酒精饮料。OIV 的定义要求它完全来自新鲜葡萄（可经破碎或不破碎）或葡萄汁的部分或完全酒精发酵，实际酒精度不低于 8.5% vol；在特定气候、土壤、品种或地方传统的条件下，部分产区法规允许把最低总酒精度降到 7% vol。这个定义划出了“葡萄酒”的边界，但边界之内仍有巨大的风格差异。

![葡萄酒 图像](/media/photos/drink-style-wine-bbcaddfe.jpg)

图：葡萄酒。图片：André Karwath，CC BY-SA 2.5，via Wikimedia Commons（[原图页面](https://commons.wikimedia.org/wiki/File:Red_and_white_wine_in_glass.jpg)）。

## 主要类别

按是否含气泡，葡萄酒首先可以分为静止酒和起泡酒。静止酒的二氧化碳含量通常较低；起泡酒则要求二氧化碳完全来自发酵，并在 20°C 时瓶内过剩压力至少达到 3.5 bar。按颜色，静止酒又分为[红葡萄酒](ref:red-wine)、[白葡萄酒](ref:white-wine)和桃红葡萄酒。红葡萄酒通常带皮发酵，从果皮提取颜色和单宁；白葡萄酒通常尽早压榨、减少果皮接触；桃红葡萄酒则通过短暂浸渍获得浅色。

按酒精度和添加物，还有[起泡酒](ref:sparkling)、[加强葡萄酒](ref:fortified)和甜酒。加强葡萄酒在发酵过程中或之后加入葡萄蒸馏酒，OIV 把这类酒称为利口酒型葡萄酒，获得酒精度通常在 15% 至 22% 之间。甜酒的甜度可以来自晚收、贵腐菌、冰酒或中止发酵，并不等同于加糖。

## 从葡萄到酒

葡萄酒的基本流程包括采收、分选、破碎或压榨、发酵、压榨（红葡萄酒）、苹果酸-乳酸发酵（可选）、陈年、澄清与装瓶。酵母把葡萄汁中的糖转化为乙醇和二氧化碳，发酵温度、酵母菌株、氧气接触和营养条件都会影响香气与口感。

红葡萄酒的浸渍时间可以从几天到数周，生产者通过压帽、淋皮和压榨力度控制颜色、单宁和香气的提取。白葡萄酒通常在不带皮的情况下发酵，温度较低，以保留细腻香气；是否进行苹果酸-乳酸发酵、是否带酒泥陈酿、是否使用橡木桶，都会改变质地和风味。桃红葡萄酒的关键是短暂浸渍，颜色深浅取决于浸渍时间和品种。

## 甜度与酒精度

OIV 对静止葡萄酒的糖分等级给出了可核查的阈值：干型最高为 4 g/L 糖，或在总酸度比糖分低不超过 2 g/L 时可到 9 g/L；半干型可到 12 g/L，或在特定酸度条件下到 18 g/L；半甜型可到 45 g/L；甜型最低为 45 g/L。起泡酒的 Brut 等级残糖最高为 12 g/L，允许 3 g/L 的容差。甜度标签描述的是残糖范围，不是主观甜感。

酒精度由发酵糖分、酵母耐受能力和是否加强共同决定。多数静止葡萄酒在十几度左右，加强酒和部分甜酒更高。酒精度不是质量指标；同一酒种内部，风格定位不同，酒精度也会不同。

## 年份、产区与标签

年份指葡萄采收年，不是装瓶年。天气会影响某一年的成熟度、产量和病害压力，但酿造调整能力强的生产者可以在不同年份之间保持相对稳定的风格。把“好年份”当成绝对结论，容易忽略具体酒款和生产者。

AOC、PDO、DOC 等标签首先是法规与地理归属，不是质量评分。欧盟的 PDO/PGI 体系、法国的 AOC、意大利的 DOCG 等，会把允许品种、最低种植密度、采收量、酿造方法和标签用语写进规范。具体酒款可以看[拉菲古堡](ref:lafite)这样的波尔多混酿，或[唐·培里侬](ref:dom-perignon)这样的年份香槟。同一产区内部仍有大量差异，村庄、地块、年份和生产者都会影响结果。

## 风土与酿造

风土通常指气候、土壤、地形与人的长期实践共同作用，使产品呈现地域特征。它是一个有用的解释框架，但不是万能公式。土壤通过水分、养分和成熟度间接影响果实；气候决定酸度与糖分的平衡；人的选择——采收时间、发酵温度、浸渍长度、陈年容器——同样塑造风格。把风土简化为“某种土壤决定某种味道”，既忽略科学证据，也忽略生产者选择。

## 怎么喝

白葡萄酒和轻酒体红葡萄酒通常适合较低温度，浓郁红葡萄酒与加强酒温度可以稍高。温度过高会让酒精感突出，过低则会让香气闭塞。醒酒主要帮助年轻、单宁重的酒接触空气，或分离老酒沉淀；并非所有酒都需要醒。品饮时先看颜色与澄清度，再闻香气，最后判断酸度、单宁、酒体与余味。

配餐时，高酸度的酒适合与酸味或油炸食物搭配，高单宁的红葡萄酒适合与蛋白质和脂肪含量较高的食物搭配，甜酒与甜点搭配时酒的甜度最好不低于甜点。比起机械套用“红酒配红肉、白酒配白肉”，更可靠的做法是看酒的结构与菜肴的调味。

## 参考边界

本页描述类别与基本方法，不评价具体酒庄、年份或价格。具体酒款的葡萄比例、残糖、酒精度、陈年潜力和适饮期，应以酒标、生产者资料和专业评审为准。葡萄酒的定义与类别可以参考 OIV 与 GB/T 17204-2021，但具体产品的合规性还要看适用市场的法规。

## 延伸阅读

- [红葡萄酒](ref:red-wine)：带皮发酵、颜色与单宁的主要来源。
- [白葡萄酒](ref:white-wine)：去皮发酵、酸度与酒泥处理。
- [起泡酒](ref:sparkling)：二次发酵、气泡压力与甜度等级。
- [加强葡萄酒](ref:fortified)：加入葡萄蒸馏酒、酒精度与甜度变化。

**来源与边界。** 本页关于「葡萄酒」的关键事实，主要由以下来源交叉核对：International Organisation of Vine and Wine (OIV)（葡萄酒、特种葡萄酒、起泡酒与利口酒型葡萄酒的定义和阈值）、European Union（欧盟葡萄酒类别、地理标志与标签规则）、国家市场监督管理总局、国家标准化管理委员会等 5 条来源。价格、批次与状态会变，涉及这些字段时以页面所列来源的最新版本为准。正文为项目自写，来源只作核验，不复制原文。

**并读。** 把「葡萄酒」与「红葡萄酒」、「白葡萄酒」、「起泡酒」放在一起读时，先确认它们是同一层级还是上下游关系：先确认定义与工艺，再比较原料、产区与代表品牌。本页负责给出酒类风格的基本坐标，对照条目补上具体案例与差异；读完再回到本页，才能分清哪些差别属于酒类风格本身，哪些只是产地、批次或品牌选择。

**适用边界。** 对「葡萄酒」而言，法定定义、原料比例与地域风格会随法规和行业分类更新；品牌案例不等于整个风格。

**更新提示。** 「葡萄酒」最近核对于 2026-11-04；价格、状态与公开信息会变，引用前以本页来源的最新版本为准。
