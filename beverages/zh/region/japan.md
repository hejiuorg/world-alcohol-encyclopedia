---
schema_version: 1
id: region:japan
type: region
lang: zh
slug: japan
title: 日本
summary: 东亚岛国，以清酒最具代表性；烧酒、威士忌与啤酒也形成规模，清酒的特定名称酒按精米步合与添加物分类，标签由国税厅管理。
status: reviewed
revision: 1
level: country
country_code: JP
legacy_refs: []
aliases:
  - 日本国
  - Japan
tags:
  - region
  - sake
  - whisky
  - asia
related:
  - relation: about
    target_id: drink-style:sake
  - relation: about
    target_id: drink-style:whisky
  - relation: about
    target_id: drink-style:beer
  - relation: about
    target_id: drink-style:wine
  - relation: about
    target_id: ingredient:rice
  - relation: about
    target_id: process:saccharification
references:
  - key: sake
    target_id: drink-style:sake
  - key: whisky
    target_id: drink-style:whisky
  - key: beer
    target_id: drink-style:beer
  - key: wine
    target_id: drink-style:wine
  - key: rice
    target_id: ingredient:rice
  - key: saccharification
    target_id: process:saccharification
  - key: fermentation
    target_id: process:fermentation
  - key: distillation
    target_id: process:distillation
  - key: yamazaki
    target_id: drink:japan-yamazaki
  - key: oak-ageing
    target_id: process:oak-ageing
sources:
  - key: nta
    title: 国税庁 — 酒類の表示・酒税法
    url: https://www.nta.go.jp/
    publisher: 日本国税庁
    note: 用于核对日本酒类标签、清酒特定名称与酒税制度的公开信息；未复制原文。
    accessed: 2026-11-04
  - key: oxford-wine
    title: The Oxford Companion to Wine — Japan entries
    publisher: Oxford University Press
    note: 参考其关于日本葡萄酒产区与品种的条目；未复制原文。
    accessed: 2026-11-04
    url: https://global.oup.com/academic/product/the-oxford-companion-to-wine-9780198871316
  - key: oxford-spirits
    title: The Oxford Companion to Spirits and Cocktails — Sake and Shochu entries
    publisher: Oxford University Press
    note: 参考其关于清酒、烧酒与日本威士忌的条目；未复制原文。
    accessed: 2026-11-04
    url: https://global.oup.com/academic/product/the-oxford-companion-to-spirits-and-cocktails-9780199311132
  - key: maff
    title: 農林水産省 — 日本农林水产省
    url: https://www.maff.go.jp/
    publisher: 農林水産省
    note: 用于核对日本农业与食品产业的公开政策信息；未复制原文。
    accessed: 2026-11-07
  - key: ref
    title: "《The Oxford Companion to Wine》日本条目"
    publisher: "Oxford University Press"
    note: 由原条目末尾参考资料迁移，未逐条复核访问日期。
  - key: ref-2
    title: "《The Oxford Companion to Spirits and Cocktails》清酒与烧酒条目"
    publisher: "Oxford University Press"
    note: 由原条目末尾参考资料迁移，未逐条复核访问日期。
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写；依据日本国税厅公开信息与酒类工具书核验，不复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方法规文本、商标与图片不在本许可内；来源仅作核验引用。图片按各自许可见图注署名。
verification_scope: source-verified
---
# 日本

日本是东亚岛国，酒类版图以清酒为核心，同时有烧酒、威士忌、啤酒与葡萄酒。清酒以米、水、曲与酵母为原料，通过糖化与发酵并行酿成；烧酒与威士忌则依赖蒸馏；啤酒与葡萄酒更多受现代产业与进口文化影响。理解日本酒，需要把原料、工艺与标签制度放在一起。

![日本地区实景](/media/photos/place-kamotsuru-a0074234.jpg)

图：日本地区的一处实景。图片：OS6，CC BY-SA 3.0，via Wikimedia Commons（[原图页面](https://commons.wikimedia.org/wiki/File:Kamotsuru_Sake_Brewing.jpg)）。这张照片来自日本产区内已核实条目，用于说明当地风貌，不是日本的全区域地图。

## 地理与气候

日本列岛南北狭长，气候从北海道的冷凉到冲绳的亚热带。大部分地区受季风与海洋影响，夏季湿热、冬季寒冷，降水充足。清酒产区多分布在有优质水源与稻米的地方，如新潟、兵库、京都与东北地区；葡萄酒产区则集中在山梨、长野、北海道等有山坡与昼夜温差的地方。

水与米是清酒的地理基础。软水、硬水与矿物质组成会影响发酵与风味；酒米（如山田锦）的颗粒大小、心白与吸水特性影响精米与制曲。气候通过稻米品质与发酵温度管理间接影响清酒，而不是像葡萄酒那样直接决定成熟度。

## 历史脉络

日本的清酒酿造可追溯到古代，稻作与发酵技术从大陆传入后逐步地方化。江户时期，酒造与运输网络发展，近代又引入科学分析与温控设备。20 世纪后期，清酒消费结构变化，吟酿风格与地方小酒造获得更多关注。烧酒在九州与冲绳形成传统，威士忌产业则在 20 世纪建立，近年获得国际市场关注。

## 清酒

[清酒](ref:sake)以[稻米](ref:rice)为主要原料，经精米、洗米、浸渍、蒸米、制曲、酒母、发酵、压榨、过滤与杀菌等工序酿成。清酒的糖化与[发酵](ref:fermentation)并行：米曲把蒸米中的淀粉分解为糖，酵母同时把糖转化为酒精。这种“并行复发酵”与啤酒、威士忌先糖化后发酵的路径不同。

清酒的关键指标包括精米步合、日本酒度、酸度与氨基酸度。精米步合表示米被研磨后剩下的比例，数值越低，米心使用比例越高；[糖化](ref:saccharification)与制曲方式影响糖的组成与风味。清酒的“特定名称酒”按精米步合与添加物分类，例如纯米酒、吟酿酒、本酿造等，具体定义以国税厅标签规则为准。

清酒的风格从清淡爽口到浓郁甘甜都有。吟酿风格强调低温发酵与香气，纯米酒更强调米味与醇厚感，生酒与熟成酒则涉及杀菌与贮存选择。饮用温度从冷藏到温热都有，具体取决于酒款与个人偏好。

## 烧酒与其他蒸馏酒

烧酒是日本的重要蒸馏酒，原料包括米、麦、薯类、黑糖等，经[蒸馏](ref:distillation)得到。鹿儿岛与冲绳是主要产区，泡盛是冲绳的米制蒸馏酒，有独立的工艺与法规。烧酒的酒精度通常低于威士忌，风格从清淡到浓郁都有。

日本[威士忌](ref:whisky)在 20 世纪建立产业，近年以水楢桶、雪莉桶与多种桶型组合获得国际关注。[山崎](ref:yamazaki)是日本威士忌的代表性酒款之一，说明日本也能以本地水源、气候与桶陈形成风格。[橡木桶陈年](ref:oak-ageing)对威士忌的香气与结构影响很大，桶型与陈年环境是理解日本威士忌的关键。

## 啤酒与葡萄酒

[啤酒](ref:beer)在日本有大型工业品牌，也有小型精酿酒厂。精酿啤酒以酒花香气、麦芽配方与地方特色为卖点，风格覆盖拉格、艾尔与世涛等。[葡萄酒](ref:wine)产业规模较小，山梨、长野与北海道是主要产区，品种以欧洲葡萄为主，风格受气候与酿造技术影响。

不同酒类的法规与标签不同。清酒与烧酒受国税厅管理，啤酒与葡萄酒也有各自的税制与标签要求；不能把清酒的“特定名称”套用到其他酒类。

## 产区与风格

- 新潟：清酒核心产区，以淡丽辛口风格与优质水源著称。
- 兵库：山田锦酒米的重要产区，清酒与烧酒都有传统。
- 京都与近畿：清酒传统深厚，风格多样。
- 东北：冷凉气候与稻米产区，清酒风格偏清爽。
- 山梨与长野：葡萄酒产区，山坡与昼夜温差影响成熟度。
- 鹿儿岛与冲绳：烧酒与泡盛的核心产区。

## 法规与标签

日本酒类标签由国税厅管理。清酒的特定名称酒按精米步合、添加物与酿造方式分类，酒标上会标注“纯米”“吟酿”“本酿造”等用语。清酒与烧酒的酒精度、原料与制造方法也有相应的标签要求。

阅读酒标时，要区分品牌、酒造、产地、类型与精米步合。“纯米”强调不添加酿造酒精，“吟酿”强调低温发酵与香气，二者不是质量高低的同义词。具体定义以最新法规与酒造说明为准。

## 气候与土壤数据

| 区域 | 气候 | 主要土壤 | 代表酒类 |
| --- | --- | --- | --- |
| 东北与北海道 | 冷凉，冬季多雪 | 火山土、冲积土 | 清酒、葡萄酒 |
| 关东（山梨等） | 大陆性，昼夜温差大 | 火山土、砾石 | 葡萄酒 |
| 中部（新潟、长野） | 冷凉，降水充足 | 冲积土、黏土 | 清酒 |
| 近畿（兵库、京都） | 温暖湿润 | 黏土、砂土 | 清酒 |
| 九州与冲绳 | 温暖 | 火山土 | 烧酒、泡盛 |

这张表是宏观对照，具体酒造的用水、米种与发酵管理仍需看单个产区。把国家气候当成酒款风格保证，会忽略酒造与原料的差异。

## 市场与饮用

日本国内市场以清酒、啤酒与烧酒为主，威士忌与葡萄酒在餐饮与礼品市场也有稳定需求。清酒适合搭配寿司、刺身与清淡料理；烧酒适合餐饮与调酒；威士忌适合纯饮、加水或加冰；啤酒适合日常与餐饮场景。

饮用应遵循适量原则。清酒的保存对温度与光线敏感，开瓶后应尽快饮用；威士忌与烧酒的保存相对稳定，但仍应避免高温与直射光。

## 常见误区

第一，清酒就是“米酒”。清酒的原料、工艺与标签制度与中式米酒不同。

第二，精米步合越低越好。精米步合影响风格与成本，不等于质量高低。

第三，清酒都要温热喝。不同酒款适合不同温度，冷藏饮用也很常见。

第四，日本威士忌都是进口原酒。日本有本地蒸馏与陈年，也有进口原酒的复杂情况，需看标签。

第五，烧酒等于清酒。烧酒是蒸馏酒，清酒是发酵酒，工艺与酒精度不同。

## 延伸阅读

- [清酒](ref:sake)：清酒的原料、工艺与特定名称。
- [稻米](ref:rice)：清酒与烧酒的核心原料。
- [糖化](ref:saccharification)与[发酵](ref:fermentation)：清酒的并行复发酵。
- [蒸馏](ref:distillation)：烧酒与威士忌的酒精浓缩。
- [威士忌](ref:whisky)：日本威士忌的类型与桶陈。
- [山崎](ref:yamazaki)：日本威士忌的代表酒款。
- [啤酒](ref:beer)与[葡萄酒](ref:wine)：日本的其他酒类。
- [橡木桶陈年](ref:oak-ageing)：威士忌风味形成的关键环节。
