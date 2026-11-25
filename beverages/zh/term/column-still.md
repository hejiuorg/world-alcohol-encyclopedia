---
schema_version: 1
id: term:column-still
type: term
lang: zh
slug: column-still
title: 塔式蒸馏器（column still）
summary: 塔式蒸馏器是连续蒸馏设备，通过多层塔板实现反复气液交换，可产出高纯度酒精；塔板数、回流比与进料位置决定馏出物的纯度与风味保留。
status: reviewed
revision: 2
legacy_refs: []
aliases:
  - 塔式蒸馏器
  - 连续蒸馏器
  - column still
  - continuous still
tags:
  - term
  - spirits
  - distillation
related:
  - relation: about
    target_id: process:distillation
  - relation: about
    target_id: drink-style:whisky
  - relation: about
    target_id: drink-style:rum
references:
  - key: distillation
    target_id: process:distillation
  - key: whisky
    target_id: drink-style:whisky
  - key: rum
    target_id: drink-style:rum
sources:
  - key: britannica-distillation
    title: Distillation — Encyclopaedia Britannica
    url: https://www.britannica.com/technology/distillation
    publisher: Encyclopaedia Britannica
    note: 用于核对连续蒸馏与精馏塔的基本原理，未复制原文。
    accessed: 2026-11-07
  - key: scotch-regulations
    title: Scotch Whisky Regulations 2009 — UK Statutory Instrument 2009/2890
    url: https://www.legislation.gov.uk/uksi/2009/2890/contents
    publisher: The National Archives (UK legislation)
    note: 用于核对谷物威士忌连续蒸馏在法规中的表述，未复制原文。
    accessed: 2026-11-07
  - key: purdue-distillation
    title: AE-117 — Continuous distillation
    url: https://www.extension.purdue.edu/extmedia/AE/AE-117.html
    publisher: Purdue University Extension
    note: 用于核对连续蒸馏的进料、回流与塔内平衡，未复制原文。
    accessed: 2026-11-07
  - key: libretexts-ethanol
    title: Separating Volatile Solutions — Distillation
    url: https://chem.libretexts.org/Courses/University_of_California_Davis/UCD_Chem_4B:_General_Chemistry_for_Majors_II_(Larsen)/Text/Unit_II:_Physical_Equilibria/IV:_Solutions/4.5:_Separating_Volatile_Solutions_-_Distillation
    publisher: Chemistry LibreTexts (UC Davis)
    note: 用于核对乙醇-水共沸物的浓度与沸点上限，未复制原文。
    accessed: 2026-11-07
  - key: chem
    title: "Chemistry LibreTexts — Separating Volatile Solutions: Distillation"
    url: https://chem.libretexts.org/Courses/University_of_California_Davis/UCD_Chem_4B:_General_Chemistry_for_Majors_II_
    publisher: "未注明"
    note: 由原条目末尾参考资料迁移，未逐条复核访问日期。
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写，依据百科条目、英国法规、大学推广资料与化学教材核验；未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方文本、商标与图片不在本许可内；来源仅作核验引用。
verification_scope: source-verified
---
# 塔式蒸馏器（column still）

![塔式蒸馏器（column still） 类型示意图](/media/photos/theme-wine-spirits.jpg)

图：塔式蒸馏器（column still） 类型示意图。图片：Doubao Seedream 5.0 AI 辅助绘制（项目自有），不是塔式蒸馏器（column still）的实拍。

## 定义与边界

塔式蒸馏器（column still，也称连续蒸馏器）是一种可以持续进料、持续出酒的蒸馏设备。它的核心是一根竖直的塔，塔内有多层塔板（或填充层），上升的蒸气与下降的液体在每层塔板上反复接触、交换热量与组分。结果是低沸点组分在塔顶富集，高沸点组分在塔底富集。

这里要先排除两个误解。塔式蒸馏器不等于“低品质蒸馏器”，它只是分离效率更高；是否适合取决于产品目标。它也不等于实验室里的“分馏柱”：工业塔式蒸馏器有进料板、回流系统、再沸器与多段结构，实验室分馏柱通常规模小、塔板少。塔式与壶式是设备结构的分野，不是“现代”与“传统”的道德判断。

## 词源与来源

column 来自拉丁语 columna，意为“柱、圆柱”；still 来自拉丁语 stillare，意为“滴下”。rectification（精馏）来自拉丁语 rectificare，意为“使变正、使纯净”。中文“塔式蒸馏器”强调竖直塔体，“连续蒸馏器”强调运行方式，两个名字描述的是同一设备的不同侧面。

这些词的历史说明，连续蒸馏的概念来自化工与炼油工业的分馏实践，后来被烈酒行业借用。今天的塔式蒸馏器既有数十层塔板的板式塔，也有填充塔与混合设计，不能用一个词概括所有形态。

## 机制或参数

壶式蒸馏器一次只能处理一锅酒液；塔式蒸馏器把“反复蒸馏”压缩进同一根塔内。每一层塔板相当于一次理论上的简单蒸馏，塔板越多，分离越充分。蒸气从塔底上升，回流液从塔顶下降，二者在塔板上接触：蒸气中的高沸点成分冷凝进入液相，液相中的低沸点成分被蒸气带走。

进料位置很关键：进料板以上的部分称为精馏段，负责提高纯度；进料板以下称为提馏段，负责把酒精从残液中提出。回流比指返回塔内的液体量与取出产品量之比。回流比越高，产品纯度越高，但产量下降、能耗上升。塔板数、回流比、进料位置与加热功率共同决定馏出物的组成。

高纯度意味着更多风味物质被分离出去。乙醇与水在常压下形成共沸物，共沸点约 78.2°C，乙醇质量分数约 95.6%，因此普通精馏得到的酒精浓度上限约为 95% vol。这也是为什么连续蒸馏常被用于中性酒精、伏特加基酒与工业酒精的生产。若保留更多风味，则需要降低回流比、减少塔板或采用其他设计。

## 在酒业中的实际用法

在[威士忌](ref:whisky)生产中，塔式蒸馏器主要用来生产谷物威士忌，作为调和威士忌的组成部分；苏格兰的谷物威士忌通常采用连续蒸馏，法规对单一谷物威士忌的定义并不要求壶式设备；所有苏格兰威士忌的蒸馏酒度必须低于 94.8% abv。壶式蒸馏则多用于麦芽威士忌。两者不是替代关系，而是产品结构中的不同角色。

[朗姆酒](ref:rum)的生产中，塔式蒸馏器常用于轻质朗姆，产出干净、清爽的基酒；重质朗姆则多采用壶式或带特殊设计的蒸馏设备，以保留酯类与香气。同一产区可以同时存在两种路线，并用于不同产品线。金酒、伏特加等以中性酒精为基础的烈酒，也依赖连续蒸馏获得高纯度基酒，再通过浸泡、复蒸或调配形成风格。

在运行层面，连续蒸馏要求稳定的进料组成、温度与压力。进料中断、回流比波动或塔板液泛都会影响产品纯度与风味。与壶式蒸馏的“逐批切酒”不同，塔式蒸馏的质量控制更依赖连续监测与参数稳定。

## 易混术语对照

塔式与壶式的差别，先体现在分批与连续上。壶式是分批操作，回流主要靠塔颈几何与自然冷凝，风味保留较多但效率低；塔式是连续操作，分离能力强、效率高，适合大规模生产。精馏段与提馏段则是塔内两个功能相反的区域。精馏段在进料板以上，负责提高轻组分浓度；提馏段在进料板以下，负责把酒精从残液中提出。

连续蒸馏与分批蒸馏属于运行方式的对照。连续蒸馏持续进料、持续出酒；分批蒸馏一锅一锅处理。塔式蒸馏器与实验室分馏柱的差别则在规模与结构上。前者是工业设备，有回流控制与多段结构；后者规模小，常用于教学与实验室分离。把两者当成同一件事，会低估工业塔的复杂度。

## 常见误用与争议

第一，塔式蒸馏不等于低品质。它只是分离效率高，是否适合取决于产品目标。第二，塔式蒸馏器并非只有一种形态，塔板式、填充式与混合设计都存在。第三，高纯度不等于没有风味，风味仍可来自原料、发酵与后续处理。第四，连续蒸馏不等于所有产品都一样，回流比与进料位置仍可调出差异。

争议主要围绕“高纯度是否牺牲风格”。支持者认为连续蒸馏提供了稳定、可扩展的基酒，是调和型产品的必要组成；反对者认为过度精馏会抹去原料与发酵的细节。较稳妥的表述是：塔式蒸馏是一种效率与纯度的工具，风格保留取决于如何运行它，而不是设备本身。

## 典型数值或例子

- 乙醇-水共沸点：约 78.2°C；共沸物乙醇质量分数：约 95.6%。
- 普通精馏酒精浓度上限：约 95% vol。
- 苏格兰威士忌蒸馏酒度上限：低于 94.8% abv。
- 塔式蒸馏器可含数十层塔板；回流比越高，纯度越高、产量越低。
- 典型用途：谷物威士忌、轻质朗姆、伏特加与金酒的中性基酒。
- 对比例子：同一产区的轻质朗姆用塔式蒸馏，重质朗姆用壶式或特殊设计。

这些参数解释了塔式蒸馏器的风格不是由“连续”一个词决定的，而是由塔板、回流比、进料位置与后续处理共同塑造。

相关条目：[蒸馏](ref:distillation)。

## 另见

- [蒸馏](ref:distillation)：蒸馏的基本原理与设备类型。
- [威士忌](ref:whisky)：谷物威士忌与麦芽威士忌的差异。
- [朗姆酒](ref:rum)：轻质与重质朗姆的生产路线。

对照阅读：[蒸馏](ref:distillation)、[朗姆酒](ref:rum)。
