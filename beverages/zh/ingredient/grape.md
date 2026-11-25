---
schema_version: 1
id: ingredient:grape
type: ingredient
lang: zh
slug: grape
title: 葡萄
summary: 葡萄科葡萄属的藤本植物果实；酿酒用的欧洲葡萄以糖、酸、色素与单宁的组合决定葡萄酒的潜力，与鲜食葡萄的选育目标不同。
status: reviewed
revision: 2
legacy_refs: []
aliases:
  - 酿酒葡萄
  - Vitis vinifera
tags:
  - curated
  - source-verified
  - ingredient
  - fruit
  - wine
related:
  - relation: about
    target_id: drink-style:wine
  - relation: about
    target_id: drink-style:red-wine
  - relation: about
    target_id: drink-style:white-wine
references:
  - key: wine
    target_id: drink-style:wine
  - key: red-wine
    target_id: drink-style:red-wine
  - key: white-wine
    target_id: drink-style:white-wine
sources:
  - key: oiv-definitions
    title: OIV International Code of Oenological Practices — Part I Definitions
    url: https://www.oiv.int/standards/international-oenological-codex/part-i-definitions
    publisher: International Organisation of Vine and Wine (OIV)
    note: 用于核对葡萄酒必须来自新鲜葡萄或葡萄汁的定义；未复制原文。
    accessed: 2026-11-04
  - key: oiv-varieties
    title: OIV Descriptor List of Grape Vine Varieties and Vitis Species (3rd edition, Resolution OIV-VITI 702-2023)
    url: https://www.oiv.int/node/3028/download/pdf
    publisher: International Organisation of Vine and Wine (OIV)
    note: 用于核对葡萄品种描述与 Vitis 物种框架；未复制原文。
    accessed: 2026-11-04
  - key: oxford-wine
    title: The Oxford Companion to Wine
    publisher: Oxford University Press
    note: 参考其关于葡萄果实结构、品种与酿造关系的条目；未复制原文。
    accessed: 2026-11-04
    url: https://global.oup.com/academic/product/the-oxford-companion-to-wine-9780198871316
  - key: ref
    title: "《The Oxford Companion to Wine》葡萄果实结构、品种与酿造关系条目"
    publisher: "Oxford University Press"
    note: 由原条目末尾参考资料迁移，未逐条复核访问日期。
  - key: q2-oiv
    title: "国际葡萄与葡萄酒组织（OIV）— 葡萄与葡萄酒科学和技术参考"
    url: https://www.oiv.int/
    publisher: "国际葡萄与葡萄酒组织（OIV）"
    note: "用于核对葡萄品种、葡萄酒分类与国际技术口径；未复制原文。"
    accessed: 2026-11-23
  - key: q2-cornell-grape-varieties
    title: "康奈尔大学 — 葡萄品种资源"
    url: https://blogs.cornell.edu/grapes/production/cornell-grape-varieties/
    publisher: "康奈尔大学"
    note: "用于核对葡萄品种的命名、亲本与栽培背景；未复制原文。"
    accessed: 2026-11-23
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写；依据 OIV 公开标准与葡萄酒工具书核验，不复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方标准、商标与图片不在本许可内；来源仅作核验引用。第三方图片已在图注中标注作者与许可。
verification_scope: source-verified
---
# 葡萄

葡萄是葡萄科葡萄属的藤本植物果实。用于酿酒的欧洲葡萄（Vitis vinifera）与超市里的鲜食葡萄并不是同一套选育目标：酿酒葡萄更看重糖酸平衡、色素、单宁和香气前体，鲜食葡萄更看重颗粒大小、口感与耐储运。OIV 对[葡萄酒](ref:wine)的定义要求它完全来自新鲜葡萄或葡萄汁的发酵，这说明葡萄既是原料，也是酒种边界的一部分。

![葡萄 图像](/media/photos/ingredient-grape-2d929148.jpg)

图：葡萄。图片：Vyacheslav Argenberg，CC BY 4.0，via Wikimedia Commons（[原图页面](https://commons.wikimedia.org/wiki/File:Grapes,_Rostov-on-Don,_Russia.jpg)）。

## 定义与身份

葡萄是果实，葡萄酒是它的发酵产物。OIV 的定义把葡萄酒限定为以新鲜葡萄或葡萄汁为原料、经发酵得到的饮料，因此“葡萄汁加酒精”或“其他水果发酵酒”不能称为葡萄酒。原料身份决定了酒种边界，也决定了标签与法规的适用范围。

在内容组织上，葡萄属于原料层，葡萄酒属于酒种层，具体酒款属于产品层。原料页回答“用的是什么”，酒种页回答“它属于哪一类”，酒款页回答“这一瓶是什么”。三层信息互相引用，但不应该混写。

## 酿酒葡萄与鲜食葡萄

酿酒葡萄通常果粒较小、皮相对厚、种子较多，糖分与酸度都较高。厚皮意味着更多的色素与单宁，适合[红葡萄酒](ref:red-wine)的带皮浸渍；较高的酸度则让酒在发酵和陈年后仍有结构。鲜食葡萄则通过选育追求大粒、少籽、皮薄和甜度高，这些特征在酿酒中往往不是优点。

用鲜食葡萄自酿葡萄酒并非绝对不行，但风味与稳定性通常难以达到酿酒葡萄的水平。鲜食葡萄的酸度偏低、香气前体较少，发酵后容易显得单薄；此外，家庭自酿的卫生条件与二氧化硫管理也更难控制。理解两种选育目标的差异，可以避免“甜葡萄一定出好酒”的误判。

## 果实结构与酿酒

葡萄果实的可发酵部分主要是果肉，果肉含水、糖和有机酸；果皮携带色素、单宁和香气物质；种子含有单宁与油脂；果梗也含单宁。红葡萄酒的浸渍过程让酒液与果皮接触，从而提取颜色和单宁；[白葡萄酒](ref:white-wine)通常尽早压榨，减少果皮接触，因此颜色浅、单宁少。

果皮上的天然蜡质与附着酵母也是发酵的起点之一，并不等同于农药残留。现代酿造多使用筛选酵母，但部分生产者仍保留野生酵母发酵，以追求更复杂的香气。果梗与种子的单宁较粗糙，压榨与去梗方式会影响最终口感，因此工艺选择需要与原料状态匹配。

## 主要品种

常见酿酒品种包括赤霞珠、梅洛、品丽珠、西拉、黑皮诺、霞多丽、长相思、雷司令、白诗南等。红品种与白品种的果皮色素与单宁含量不同，酿造路线也不同；同一品种在不同产区与工艺下可以呈现完全不同的风格。

品种只是起点。赤霞珠在凉爽产区可能带草本气息，在温暖产区则更成熟饱满；霞多丽本身香气中性，风格更多取决于橡木、酒泥与苹果酸乳酸发酵。品种名提供预期，但不提供保证。

## 主要产区

Vitis vinifera 的栽培历史可以追溯到高加索与地中海周边，如今在欧洲、美洲、大洋洲、非洲和亚洲都有规模种植。法国、意大利、西班牙是传统产区；美国、澳大利亚、智利、阿根廷、南非和新西兰形成了现代产区；中国的宁夏、新疆、山东、河北、云南等地也有葡萄酒产业。

不同产区的热量、降水、昼夜温差和土壤排水性，会改变葡萄的成熟曲线与风味走向。凉爽产区强调酸度与细腻香气，温暖产区强调成熟果味与酒体。产区故事需要与气候、土壤和栽培事实一起理解，不能只凭地名判断品质。

## 采收与成熟度

采收决策要同时考虑糖分、酸度、色素、单宁和香气。糖分上升通常伴随酸度下降；成熟度不足时，单宁可能粗糙、香气偏青；过熟时，酸度不足、果味显得沉闷。生产者还会根据天气预报、病害压力和目标酒种调整采收时间。

起泡酒基酒通常更早采收，以保留较高酸度；甜酒则可能延迟采收，或等待贵腐菌发展。白天与夜间的温差、降雨与风力都会影响采收窗口。同一地块不同批次也可能分开采收，以便把不同成熟度的果实用于不同产品。

## 栽培方式与果实质量

葡萄的栽培方式会改变果实质量。产量控制、叶幕管理、通风与光照、灌溉方式，都会影响糖分积累、酸度保留和酚类成熟。过度追求产量往往稀释风味；过度控产则可能让果实过熟或酸度不足。

有机与生物动力栽培强调减少化学投入、改善土壤与生物多样性，但它们不是质量保证，最终仍要看果实状态与酿造选择。嫁接、砧木选择与病虫害管理也会影响植株寿命与稳定性。栽培是一个连续决策过程，而不是某一项措施就能决定品质。

## 常见误区

第一，认为葡萄越甜越适合酿酒。葡萄酒需要糖与酸的平衡，单纯高糖并不等于高质量。

第二，认为葡萄皮上的白霜一定是农药。白霜多为天然蜡质和附着的酵母，是发酵的自然来源之一。

第三，认为所有葡萄都能酿出同样的酒。品种、产区、年份和工艺都会改变结果，葡萄只是其中一个变量。

第四，把“酿酒葡萄”当成一个植物学分类。它是对用途的描述，实际涉及多个品种与栽培体系。

第五，认为有机栽培必然更好喝。栽培方式影响原料状态，但酿造与陈年同样决定最终风味。

酿酒葡萄并非越大越甜越好；小粒、皮厚的果实往往能提供更高的风味与色素浓度，鲜食葡萄的选育目标则相反。

## 延伸阅读

- [葡萄酒](ref:wine)：葡萄酒的定义、类别与产地规则。
- [红葡萄酒](ref:red-wine)：带皮浸渍、单宁与颜色的形成。
- [白葡萄酒](ref:white-wine)：尽早压榨与低温发酵的路线。

相关条目：[葡萄酒](ref:wine)、[红葡萄酒](ref:red-wine)。

**关键事实。**

| 项目 | 内容 |
| --- | --- |
| 一句话定位 | 葡萄科葡萄属的藤本植物果实；酿酒用的欧洲葡萄以糖、酸、色素与单宁的组合决定葡萄酒的潜力，与鲜食葡萄的选育目标不同 |
| 原料身份 | 葡萄科葡萄属的藤本植物果实 |
| 加工用途 | 酿酒用的欧洲葡萄以糖、酸、色素与单宁的组合决定葡萄酒的潜力，与鲜食葡萄的选育目标不同 |
