---
schema_version: 1
id: drink-style:strong-aroma-baijiu
type: drink-style
lang: zh
slug: strong-aroma-baijiu
title: 浓香型白酒
summary: 以泥窖固态发酵、续糟配料和混蒸混烧等工艺为特征的浓香型白酒，是白酒风格分类中的一类。
status: reviewed
revision: 2
parent_style_id: drink-style:baijiu
aroma_family: 浓香
legacy_refs: []
aliases:
  - 浓香型
  - 泸型
tags:
  - baijiu
  - strong-aroma
related:
  - relation: about
    target_id: drink-style:baijiu
  - relation: about
    target_id: process:qu-making
  - relation: about
    target_id: process:distillation
  - relation: about
    target_id: drink:sichuan-luzhoulaojiao
  - relation: about
    target_id: drink:sichuan-wuliangye
references:
  - key: baijiu
    target_id: drink-style:baijiu
  - key: qu-making
    target_id: process:qu-making
  - key: distillation
    target_id: process:distillation
  - key: luzhoulaojiao
    target_id: drink:sichuan-luzhoulaojiao
  - key: wuliangye
    target_id: drink:sichuan-wuliangye
sources:
  - key: gbt-10781-1
    title: GB/T 10781.1-2021 白酒质量要求 第1部分：浓香型白酒
    url: https://openstd.samr.gov.cn/
    publisher: 国家市场监督管理总局、国家标准化管理委员会
    published: "2021"
    note: 用于核对浓香型白酒的术语、要求与检验规则；未复制标准原文。
    accessed: 2026-11-04
  - key: samr
    title: 国家市场监督管理总局 — 白酒质量与标准公开信息
    url: https://www.samr.gov.cn/
    publisher: 国家市场监督管理总局
    note: 用于核对标准发布机构与白酒质量监管框架；未复制原文。
    accessed: 2026-11-04
  - key: oxford-spirits
    title: The Oxford Companion to Spirits and Cocktails
    publisher: Oxford University Press
    note: 参考其关于中国白酒、固态发酵与风味类型的条目；未复制原文。
    accessed: 2026-11-04
    url: https://global.oup.com/academic/product/the-oxford-companion-to-spirits-and-cocktails-9780199311132
  - key: c-ref-1
    title: BJCP — Beer Style Guidelines
    url: https://www.bjcp.org/
    publisher: BJCP
    accessed: 2026-11-21
    note: 用于补充核对条目背景、术语与制度口径；未复制原文。
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写；依据公开标准信息与工具书资料核验，未复制标准原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方标准、商标、图片与引用文本不在本许可内；来源仅作核验引用。第三方图片已在图注中标注作者与许可。
verification_scope: source-verified
---
# 浓香型白酒

浓香型白酒是[白酒](ref:baijiu)风格分类中的一类，也是中国市场产量与消费面最广的白酒类型之一。GB/T 10781.1-2021《白酒质量要求 第1部分：浓香型白酒》为这一类产品规定了术语、要求与检验规则。理解浓香型，关键是理解“泥窖、续糟、混蒸混烧”这套工艺组合，而不是只记住“窖香浓郁”四个字。

![浓香型白酒 图像](/media/photos/drink-style-strong-aroma-baijiu-1c3af236.jpg)

图：浓香型白酒。图片：Xiaomage de，CC BY-SA 4.0，via Wikimedia Commons（[原图页面](https://commons.wikimedia.org/wiki/File:Vertreter_der_vier_Baijiu_Kategorien.jpg)）。

## 定义与标准

浓香型是按香气特征划分的风格类别，不是产地或品牌。国家标准对浓香型白酒的感官要求、理化指标与检验方法作出规定，产品标签上的执行标准号是判断类别的直接依据。符合标准的产品可以在标签上标注“浓香型”，但“浓香”本身并不构成质量等级。

标准之外还有地理标志产品标准与企业标准。地理标志标准通常对产区、原料与工艺作出更具体的要求；企业标准可能高于或不同于国家标准。购买时应同时看执行标准、生产者与产地，而不是只看香型名称。

## 工艺特征

浓香型白酒通常采用泥窖进行固态发酵，以续糟配料组织多轮发酵，并以混蒸混烧等方式完成取酒。所谓“续糟”，是把上一轮发酵后的部分酒醅保留下来，与新粮、新曲混合后进入下一轮，使窖池中的微生物与风味物质连续积累。

“混蒸混烧”指粮食蒸煮与酒醅蒸馏在同一套流程中配合完成，既提取酒精与香气，也为下一轮发酵准备原料。这套工艺对操作节奏要求很高：入窖温度、酸度、水分与淀粉浓度都会影响出酒率与风味。不同产区、生产者和产品会在曲种、窖池、发酵周期与勾调方式上形成自己的表达。

## 原料与曲

浓香型白酒多以高粱为主粮，常配以小麦、玉米、大米、糯米等，形成多粮或单粮配方。多粮配方可以增加香气层次与甜感，单粮配方则更突出主体粮的干净度。制曲常用小麦，[制曲](ref:qu-making)过程中的温度与湿度决定曲的糖化力、发酵力与香气贡献。

曲是浓香型风味的重要来源之一。中高温大曲带来丰富的酶系与微生物，参与酯类、酸类与醇类的生成。曲的质量不稳定，后续工艺再精细也难以补救，因此制曲被视为浓香生产的第一道关口。

## 窖池与微生物

泥窖是浓香型最具识别性的设施。窖池内壁的窖泥经过长期使用，形成稳定的微生物群落，对己酸菌等产酯微生物的富集尤为关键。老窖池的价值正在于此：连续使用的时间越长，窖泥群落越成熟，主体香越容易稳定。

窖池管理包括窖泥养护、入窖水分与温度控制、发酵期管理。发酵周期通常在数十天量级，具体取决于产区、季节与产品定位。窖池不是“越老越好”的简单公式，维护不当的老窖同样会退化；卫生、配料与温度控制才是稳定的基础。

## 风味结构

浓香型的主体香通常被概括为己酸乙酯，辅以乳酸乙酯、乙酸乙酯等酯类，以及醇类、酸类与醛类。闻香上表现为窖香、粮香、曲香与陈香的组合；入口甜、落口绵、尾净是常见的感官描述。不同产品在“甜、绵、净、香”的配比上差异明显。

这些描述是沟通工具，不是评分公式。规范的做法是记录品鉴者、酒款、温度、杯型与醒酒时间，把主观感受与可核实事实分开。香气的强弱、酒体的厚度与余味的长度，需要结合产品定位与价格带判断。

## 产区与代表产品

浓香型在四川、江苏、安徽、河南等地都有强势产区。四川的泸州、宜宾一带以老窖与多粮工艺见长；[泸州老窖](ref:luzhoulaojiao)与[五粮液](ref:wuliangye)是这一风格的代表性产品页。江苏的洋河、安徽的古井贡酒则在不同价位带形成了各自的表达。

产区差异不只在地理，也在工艺传统与产品结构。比较不同产区的浓香产品时，应把原料配方、发酵周期、酒精度与价格带一起看，避免用单一杯的感官印象给整个产区下结论。

## 品鉴方法

品鉴浓香型白酒，建议用小杯、少量、常温。先静止闻香，再轻轻摇杯，比较窖香、粮香与曲香的层次；入口时让酒液铺满舌面，感受甜度、酒体与酒精刺激；咽下后看余味是否干净、回甜是否自然。

对比品鉴比单杯评价更可靠：同一价位带选两到三款，记录香气、入口、余味与空杯香。空杯留香是浓香型的常见观察点，但留香长短受酒精度、杯型与环境影响，不宜单独作为质量结论。酒精度常见为 52% vol，也有 38% vol 至 52% vol 之间的产品，酒精度的差异会直接改变口感强度。

## 选购与常见误区

第一，把“浓香”当作质量等级。它只是风格类别，质量还要看执行标准、等级标注与感官表现。
第二，认为窖池越老越好。老窖需要持续养护，窖泥退化会直接影响风味。
第三，只看酒精度选酒。高度酒香气更集中，但入口刺激也更强；低度酒更易饮，但对工艺要求并不低。
第四，把“窖香浓郁”当作唯一标准。浓香型同样讲求协调、干净与余味。
第五，忽视标签信息。执行标准、原料、生产者与产地，是判断产品是否符合预期的基本依据。

浓香型不是越香越好：窖香、糟香与陈香有层次，酒精度的刺激也不能替代酒体的完整度；选酒要回到香型标准与标签，而不是只闻第一下。

## 延伸阅读

- [白酒](ref:baijiu)：酒种层面的定义与分类框架。
- [制曲](ref:qu-making)：浓香型风味与微生物基础的关键环节。
- [蒸馏](ref:distillation)：混蒸混烧与取酒工艺的技术背景。
- [泸州老窖](ref:luzhoulaojiao)：四川浓香型的代表性产品页。
- [五粮液](ref:wuliangye)：多粮浓香型的代表性产品页。

**关键事实。**

| 项目 | 内容 |
| --- | --- |
| 一句话定位 | 以泥窖固态发酵、续糟配料和混蒸混烧等工艺为特征的浓香型白酒，是白酒风格分类中的一类 |
| 上位风格 | 白酒 |
| 香气家族 | 浓香 |

**来源与边界。** 本页关于「浓香型白酒」的关键事实，主要由以下来源交叉核对：国家市场监督管理总局、国家标准化管理委员会（浓香型白酒的术语、要求与检验规则；未复制标准原文）、国家市场监督管理总局（标准发布机构与白酒质量监管框架）、Oxford University Press（提供关于中国白酒、固态发酵与风味类型的条目）等 4 条来源。价格、批次与状态会变，涉及这些字段时以页面所列来源的最新版本为准。正文为项目自写，来源只作核验，不复制原文。
