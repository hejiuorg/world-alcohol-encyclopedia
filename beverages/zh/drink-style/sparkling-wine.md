---
schema_version: 1
id: drink-style:sparkling-wine
type: drink-style
lang: zh
slug: sparkling-wine
title: 起泡酒
summary: 含有源自发酵的内源二氧化碳、开瓶后持续冒泡的葡萄酒；按二次发酵方式分为传统法、罐式法与古法，香槟只是其中一种。
status: reviewed
revision: 1
legacy_refs: []
aliases:
  - 起泡酒
  - 气泡酒
  - sparkling wine
  - mousseux
tags:
  - style-guide
  - wine
related:
  - relation: about
    target_id: drink-style:wine
  - relation: about
    target_id: drink:france-domperignon
  - relation: about
    target_id: region:champagne
  - relation: about
    target_id: term:disgorgement
references:
  - key: wine
    target_id: drink-style:wine
  - key: dom-perignon
    target_id: drink:france-domperignon
  - key: c-extra-1
    target_id: region:champagne
sources:
  - key: oiv-definitions
    title: OIV International Code of Oenological Practices — Part I Definitions
    url: https://www.oiv.int/standards/international-oenological-codex/part-i-definitions
    publisher: International Organisation of Vine and Wine (OIV)
    note: 用于核对起泡酒的压力阈值、二氧化碳来源与甜度等级，未复制原文。
    accessed: 2026-11-04
  - key: champagne
    title: Comité Champagne — Champagne production rules and appellation
    url: https://www.champagne.fr/
    publisher: Comité Interprofessionnel du vin de Champagne
    note: 用于核对香槟产区、法定工艺与标签框架。
    accessed: 2026-11-04
  - key: eu-wine
    title: EU Regulation 1308/2013 — Common Market Organisation for Wine
    url: https://eur-lex.europa.eu/eli/reg/2013/1308/oj
    publisher: European Union
    note: 用于核对欧盟起泡酒类别与地理标志规则。
    accessed: 2026-11-04
  - key: c-ref-1
    title: BJCP — Beer Style Guidelines
    url: https://www.bjcp.org/
    publisher: BJCP
    accessed: 2026-11-21
    note: 用于补充核对条目背景、术语与制度口径；未复制原文。
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写，依据 OIV、香槟行业组织与欧盟法规公开信息核验；未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方文本、商标与图片不在本许可内；来源仅作核验引用。
verification_scope: source-verified
---

# 起泡酒

起泡酒是含有二氧化碳、开瓶后产生持续气泡的葡萄酒。气泡可以来自发酵，也可以来自人工充气；按 OIV 的定义，真正的起泡酒，其二氧化碳应完全来自发酵（内源），并在 20°C 时瓶内过剩压力至少达到 3.5 bar。这个压力阈值把“起泡酒”和仅有一点微气泡的静止酒区分开来。

![起泡酒 图像](/media/photos/drink-style-sparkling-wine-acf0412f.jpg)

图：起泡酒。图片：bgvjpe，CC BY 2.0，via Wikimedia Commons（[原图页面](https://commons.wikimedia.org/wiki/File:Glass_of_champagne.jpg)）。

## 气泡从哪里来

最常见的方法是二次发酵。基酒先完成第一次发酵，得到干型、酸度较高的静止酒；随后加入糖和酵母，在密闭容器中启动第二次发酵。酵母把糖转化为乙醇和二氧化碳，二氧化碳被封闭在酒中，形成气泡。发酵结束后，酵母残渣（酒泥）可以继续与酒接触，带来面包、饼干和坚果类香气，这个过程常被称为“酒泥陈酿”。

传统法（traditional method）让二次发酵在瓶中进行，随后通过转瓶、吐泥、补液等步骤去除酵母残渣并调整甜度。香槟、法国部分克雷芒、西班牙卡瓦、意大利法兰恰科尔塔的部分产品都采用这一方法。罐式法（tank method，也称 Charmat）让二次发酵在加压罐中进行，成本更低、果香更直接，普罗塞克常采用这种方法。古法（ancestral method）则让第一次发酵在瓶中完成，保留部分糖分继续发酵，风格更原始、气泡可能更粗犷。人工充气法不属于发酵起泡，标签和法规通常会有区别。

## 香槟不是起泡酒的同义词

香槟是法国香槟地区生产的起泡酒，受原产地命名保护。只有在香槟区、按法定品种、法定工艺和法定标签规则生产的起泡酒，才能使用“Champagne”这一名称。其他地区生产的同类酒可以叫“起泡酒”“传统法起泡酒”等，但不能叫香槟。把“香槟”当成所有起泡酒的统称，既不准确，也不符合标签法规。

香槟的风格也很多样。无年份香槟通常由多个年份、多个基酒调配，强调一致性；年份香槟只在特定年份生产，强调该年的特征。甜度从极干到甜型都有，酒标上的 Brut、Extra-Dry 等词对应不同的残糖范围。以[唐·培里侬](ref:dom-perignon)为例，它是酩悦香槟旗下的年份香槟品牌，而不是一个独立的产区类别。

## 甜度与标签

OIV 对起泡酒的甜度给出了可核查的阈值。以 Brut 为例，残糖最高为 12 g/L，允许 3 g/L 的容差；其他等级从 Extra-Brut 到 Doux 依次对应不同的残糖范围。甜度标签描述的是残糖，不是主观甜感；酸度、气泡压力和香气都会改变感知。

酒标上的“传统法”“瓶内二次发酵”“酒泥陈酿”等表述，反映的是工艺信息；“Blanc de Blancs”指只用白葡萄酿造，“Blanc de Noirs”指只用深色葡萄酿造但果汁不带皮发酵。这些术语各有定义，不能只看字面猜测。

## 产区与风格

除了香槟，常见的起泡酒还包括西班牙卡瓦、意大利普罗塞克和阿斯蒂、法国阿尔萨斯和勃艮第的克雷芒、德国塞克特、南非开普经典等。不同产区的法规、品种和工艺差异很大：有的强调瓶中陈年带来的复杂度，有的强调新鲜果香和易饮性，有的甜度跨度很大。

气候和基酒选择会塑造风格。冷凉产区的基酒通常酸度更高，适合长时间酒泥陈酿；温暖产区的基酒果味更成熟，更适合快速消费的罐式法。同一产区内部，生产者的基酒调配、酵母选择和补液甜度也会造成明显差异。

## 怎么喝

起泡酒通常需要充分冰镇，但也不是越冷越好。温度过低会压抑香气，温度过高则会让气泡迅速散失、酒精感突出。宽口杯或郁金香杯比窄长的笛形杯更容易释放香气，具体选择可以根据酒的复杂度调整。

开瓶时避免剧烈摇晃，按住瓶塞慢慢旋转，让压力平稳释放。倒酒时沿杯壁缓慢倒入，可以减少泡沫溢出。起泡酒适合作为餐前酒，也可以搭配油炸食物、海鲜、咸味小吃和部分甜点；高酸度和气泡能切开油脂、清理口腔。

## 压力、温度与气泡寿命

气泡的持久性与瓶内压力、溶解的二氧化碳量和温度有关。温度越低，二氧化碳在酒中的溶解度越高，气泡释放越慢；温度升高，溶解气体更容易逸出，气泡变得急促。开瓶后的起泡酒与空气接触面积增大，二氧化碳会逐渐散失，因此通常建议尽快饮用，或用专用瓶塞减少气体流失。

杯型也影响体验。窄杯有利于保留气泡，宽口杯有利于释放香气，二者是取舍关系，而不是绝对优劣。理解这一点，比记住“必须用某种杯”更有用。

## 常见误区

第一，气泡越多不等于质量越高。气泡的细腻度、持久性和与酒体的协调，比数量更重要。

第二，香槟不等于所有起泡酒。只有在法国香槟区按规定生产的起泡酒才能使用这一名称。

第三，起泡酒不只能做餐前酒。它也可以搭配正餐，尤其是油炸、咸鲜和部分甜点。

## 参考边界

本页描述起泡酒的类别、工艺与标签框架，不评价具体酒庄、年份或价格。具体酒款的基酒比例、残糖、酒精度、陈年时间和适饮期，应以酒标、生产者资料和专业评审为准。起泡酒属于[葡萄酒](ref:wine)的一个类别，但与静止酒在工艺和标签规则上有明显区别。

## 延伸阅读

- [葡萄酒](ref:wine)：葡萄酒的总览，包括静止酒、起泡酒、加强酒与甜酒。
- [唐·培里侬](ref:dom-perignon)：年份香槟的具体酒款实例。

补充阅读：[香槟](ref:c-extra-1)。

相关条目：[香槟](ref:c-extra-1)、[葡萄酒](ref:wine)、[唐·培里侬香槟](ref:dom-perignon)。

**来源与边界。** 本页关于「起泡酒」的关键事实，主要由以下来源交叉核对：International Organisation of Vine and Wine (OIV)（起泡酒的压力阈值、二氧化碳来源与甜度等级）、Comité Interprofessionnel du vin de Champagne（香槟产区、法定工艺与标签框架）、European Union（欧盟起泡酒类别与地理标志规则）等 4 条来源。价格、批次与状态会变，涉及这些字段时以页面所列来源的最新版本为准。正文为项目自写，来源只作核验，不复制原文。

**并读。** 把「起泡酒」与「葡萄酒」、「唐·培里侬香槟」、「香槟」放在一起读时，先确认它们是同一层级还是上下游关系：先确认定义与工艺，再比较原料、产区与代表品牌。本页负责给出酒类风格的基本坐标，对照条目补上具体案例与差异；读完再回到本页，才能分清哪些差别属于酒类风格本身，哪些只是产地、批次或品牌选择。

## 相关图像

![香槟](/media/photos/region-champagne-acf0412f.jpg)

图：香槟。图片：bgvjpe，CC BY 2.0，via Wikimedia Commons（[原图页面](https://commons.wikimedia.org/wiki/File:Glass_of_champagne.jpg)）。关联图像：起泡酒。
