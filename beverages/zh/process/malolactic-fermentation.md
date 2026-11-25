---
schema_version: 1
id: process:malolactic-fermentation
type: process
lang: zh
slug: malolactic-fermentation
title: 苹果酸-乳酸发酵
summary: 乳酸菌把苹果酸转化为乳酸与二氧化碳的二次发酵；它降低滴定酸度、提高 pH 并软化口感，适量产生奶油气息，失控则带来挥发酸、生物胺与酒体浑浊。
status: reviewed
revision: 2
legacy_refs: []
aliases:
  - 苹乳发酵
  - MLF
  - Malolactic fermentation
tags:
  - curated
  - source-verified
  - process
  - wine
related:
  - relation: about
    target_id: drink-style:wine
  - relation: about
    target_id: term:acidity
  - relation: about
    target_id: process:fermentation
  - relation: about
    target_id: drink-style:sparkling-wine
references:
  - key: wine
    target_id: drink-style:wine
  - key: acidity
    target_id: term:acidity
  - key: fermentation
    target_id: process:fermentation
  - key: sparkling-wine
    target_id: drink-style:sparkling-wine
sources:
  - key: oiv-definitions
    title: OIV International Code of Oenological Practices — Part I Definitions
    url: https://www.oiv.int/standards/international-oenological-codex/part-i-definitions
    publisher: International Organisation of Vine and Wine (OIV)
    note: 用于核对苹果酸-乳酸发酵与酸度相关术语；未复制原文。
    accessed: 2026-11-05
  - key: oxford-wine
    title: The Oxford Companion to Wine
    publisher: Oxford University Press
    note: 参考其关于苹果酸-乳酸发酵、乳酸菌与双乙酰的条目；未复制原文。
    accessed: 2026-11-05
    url: https://global.oup.com/academic/product/the-oxford-companion-to-wine-9780198871316
  - key: awri
    title: The Australian Wine Research Institute — resources
    url: https://www.awri.com.au/
    publisher: The Australian Wine Research Institute (AWRI)
    note: 用于核对苹乳发酵接种、营养与挥发酸风险的行业与研究表述；未复制原文。
    accessed: 2026-11-07
  - key: ref
    title: The Oxford Companion to Wine（Oxford University Press）。
    publisher: 未注明
    note: 由原条目末尾参考资料迁移，未逐条复核访问日期。
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写，依据 OIV 定义文件与葡萄酒工具书核验，未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方文本、商标与图片不在本许可内；来源仅作核验引用。
verification_scope: source-verified
applies_to_refs:
  - drink-style:wine
  - drink-style:sparkling-wine
---
# 苹果酸-乳酸发酵

苹果酸-乳酸发酵（malolactic fermentation，简称 MLF，中文也作“苹乳发酵”）是葡萄酒中的二次发酵。它常与[酒精发酵](ref:fermentation)被混为一谈，实际执行者完全不同：酒精发酵由酵母把糖变成乙醇与二氧化碳，苹果酸-乳酸发酵由乳酸菌把苹果酸变成乳酸与二氧化碳，不产生酒精。两者可以先后进行，也可以在酒精发酵后期同时接种。

![苹果酸-乳酸发酵 图像](/media/photos/process-malolactic-fermentation-2d4ece59.jpg)

图：苹果酸-乳酸发酵。图片：Agne27，CC BY-SA 3.0，via Wikimedia Commons（[原图页面](https://commons.wikimedia.org/wiki/File:Malolactic_spotting.JPG)）。

## 工序定位

苹乳发酵位于酒精发酵之后或尾段，属于降酸与稳定化处理，而不是独立的酒种工艺。它发生在酒液、酒泥与容器壁的微生物群落中，结束后才进入二氧化硫调整、澄清与陈酿。对红葡萄酒，它几乎是常规步骤；对白葡萄酒与起泡酒基酒，是否进行取决于目标酸度与风格。把它称为所有“二次发酵”的同义词，会与起泡酒的瓶内二次发酵混淆。

## 步骤与参数

常见做法是在酒精发酵结束后接种筛选的乳酸菌，温度维持 18–22 °C，历时 2–4 周；pH 宜在 3.3–3.5，低于 3.2 时多数菌株难以启动；游离二氧化硫通常需低于 10–15 mg/L，分子态二氧化硫过高会直接抑制细菌。上述区间取自本页参考资料所列 OIV、葡萄酒工具书与 AWRI 资料的常见表述。也有生产者在酒精发酵后期共接种，以缩短总周期并降低营养竞争风险。完成判据是苹果酸残留低于 0.1–0.2 g/L。

## 机制：苹果酸酶与柠檬酸代谢

乳酸菌的苹果酸酶把 L-苹果酸脱羧为 L-乳酸与二氧化碳，同时消耗一个质子，因此滴定酸度下降、pH 上升，通常升幅在 0.1–0.3 个单位。苹果酸是二元酸，乳酸是一元酸，酸感从尖锐转向柔和。部分菌株还会代谢柠檬酸，生成双乙酰、乙偶姻与 2,3-丁二醇，双乙酰带来黄油与奶油气息。异型发酵菌株则可能把糖转化为乳酸、醋酸、乙醇与二氧化碳，挥发酸因此上升。

## 设备与变体

苹乳发酵不需要专用设备，温控罐、取样阀与二氧化硫计量已足够。变体包括自然发酵、接种筛选菌株、酒精发酵后期共接种、以及用膜过滤或离心在目标节点终止。部分酒厂用橡木桶进行，让微氧与细菌活动同时发生；也有酒厂通过添加细菌营养剂、调整 pH 与温度来提高成功率。容器形状影响温度梯度与酒泥悬浮，进而影响发酵整齐度。

## 失败模式与判断

第一，苹乳不启动：苹果酸迟迟不降，常因 pH 过低、温度过低、游离二氧化硫过高或营养不足。第二，挥发酸升高：闻起来像醋或洗甲水，来自异型乳酸菌或醋酸菌。第三，生物胺积累：组胺与酪胺升高，与长时间带泥和杂菌活动有关。第四，酒体浑浊或发黏：某些菌株产生胞外多糖。判断应结合苹果酸酶法检测、挥发酸、pH 与感官，而不是只看是否“冒过泡”。

## 对风味的影响

最直接的变化是[酸度](ref:acidity)结构：苹果酸下降后，酒体显得更圆、更柔，红葡萄酒的单宁更容易被接受。适量双乙酰带来奶油、黄油与烤面包气息，常见于部分霞多丽；过量则让酒显得沉闷、像人造黄油。在[红葡萄酒](ref:wine)中，苹乳发酵有助于稳定与柔化；在[起泡酒](ref:sparkling-wine)基酒中，生产者常刻意避免，以保留清爽酸度与果味，除非目标是更圆润的风格。

## 对稳定性的影响

苹乳发酵把可被细菌继续利用的苹果酸提前消耗掉，降低瓶中再次发酵的风险，这是红葡萄酒稳定性的重要一环。pH 上升会削弱二氧化硫的抑菌效率，因此结束后必须重新核算游离与分子态二氧化硫。若苹乳未完成就装瓶，残留在瓶中的苹果酸可能被乳酸菌利用，产生浑浊、气压与异味。生物胺一旦形成无法通过过滤去除，控制要靠菌株选择与卫生管理。

## 常见误区

第一，把苹乳发酵当成酒精发酵的一部分，忽略执行者是细菌。第二，认为所有红葡萄酒都必须苹乳，实际上高酸品种与部分清新风格可以不做。第三，把黄油味当成品质标志，过量双乙酰是缺陷。第四，认为接种就万无一失，pH、温度与二氧化硫仍可能让发酵停滞。第五，把起泡酒瓶内二次发酵与苹乳发酵混为一谈，前者由酵母完成并产生酒精与气泡。

苹果酸-乳酸发酵是乳酸菌把较尖锐的苹果酸转成较柔和的乳酸与二氧化碳，降低滴定酸度、提高 pH 并软化口感。适量带来奶油气息，失控则可能产生挥发酸、生物胺与浑浊；它不是“二次酒精发酵”，也不是所有红葡萄酒都必须完成。

## 另见

- [葡萄酒](ref:wine)：红、白与起泡酒的工艺框架。
- [酸度](ref:acidity)：苹果酸、乳酸与滴定酸度的关系。
- [发酵](ref:fermentation)与[起泡酒](ref:sparkling-wine)：酒精发酵与瓶内二次发酵的对照。

对照阅读：[葡萄酒](ref:wine)、[发酵](ref:fermentation)。

**关键事实。**

| 项目 | 内容 |
| --- | --- |
| 一句话定位 | 乳酸菌把苹果酸转化为乳酸与二氧化碳的二次发酵；它降低滴定酸度、提高 pH 并软化口感，适量产生奶油气息，失控则带来挥发酸、生物胺与酒体浑浊 |
| 适用对象 | 葡萄酒、起泡酒 |

**来源与边界。** 本页关于「苹果酸-乳酸发酵」的关键事实，主要由以下来源交叉核对：International Organisation of Vine and Wine (OIV)（苹果酸-乳酸发酵与酸度相关术语）、Oxford University Press（提供关于苹果酸-乳酸发酵、乳酸菌与双乙酰的条目）、The Australian Wine Research Institute (AWRI)（苹乳发酵接种、营养与挥发酸风险的行业与研究表述）等 4 条来源。价格、批次与状态会变，涉及这些字段时以页面所列来源的最新版本为准。正文为项目自写，来源只作核验，不复制原文。

**并读。** 把「苹果酸-乳酸发酵」与「葡萄酒」、「酸度（acidity）」、「发酵」放在一起读时，先确认它们是同一层级还是上下游关系：先确认目的与步骤，再比较设备、温度、时间与副产物。本页负责给出工艺的基本坐标，对照条目补上具体案例与差异；读完再回到本页，才能分清哪些差别属于工艺本身，哪些只是产地、批次或品牌选择。

**适用边界。** 对「苹果酸-乳酸发酵」而言，设备、温度与时间参数随生产商变化；本页说明目的与原理，不是操作手册。

**更新提示。** 「苹果酸-乳酸发酵」最近核对于 2026-11-07；设备、温度、时间与操作细节会因工艺版本不同，实践前以设备说明与专业文献为准。
