---
schema_version: 1
id: drink-style:abbey-beer
type: drink-style
lang: zh
slug: abbey-beer
title: 修道院啤酒
summary: 由修道院酿造或借用修道院名义与授权的啤酒统称；特拉普斯特啤酒必须在特拉普斯特修道院内、由修士监督酿造，修道院啤酒多为商业授权产品，dubbel、tripel、quadrupel 指强度层级而非独立风格。
status: reviewed
revision: 1
parent_style_id: drink-style:beer
aroma_family: 麦芽与酵母
legacy_refs: []
aliases:
  - Abbey beer
  - Abdijbier
  - Monastery beer
tags:
  - beer
  - belgium
  - monastery
  - trappist
related:
  - relation: about
    target_id: drink-style:beer
  - relation: about
    target_id: region:belgium
  - relation: about
    target_id: ingredient:water
  - relation: about
    target_id: ingredient:barley
  - relation: about
    target_id: process:fermentation
  - relation: about
    target_id: term:original-gravity
references:
  - key: beer
    target_id: drink-style:beer
  - key: belgium
    target_id: region:belgium
  - key: water
    target_id: ingredient:water
  - key: barley
    target_id: ingredient:barley
  - key: fermentation
    target_id: process:fermentation
  - key: original-gravity
    target_id: term:original-gravity
  - key: craft-beer
    target_id: term:craft-beer
sources:
  - key: trappist
    title: International Trappist Association — Official Site
    url: https://www.trappist.be/
    publisher: International Trappist Association
    note: 用于核对特拉普斯特啤酒的产地与监督要求，以及协会公布获准酒厂名单的方式；未复制原文。
    accessed: 2026-11-05
  - key: bjcp-2021
    title: BJCP 2021 Beer Style Guidelines
    url: https://www.bjcp.org/style/2021/beer/
    publisher: Beer Judge Certification Program
    note: 用于核对 dubbel、tripel 与 quadrupel 的强度、苦度与风味边界；未复制原文。
    accessed: 2026-11-05
  - key: brewers-association
    title: Brewers Association — Beer Styles and Definitions
    url: https://www.brewersassociation.org/
    publisher: Brewers Association
    note: 用于核对精酿行业对修道院风格与比利时艾尔的公开表述；未复制其文案。
    accessed: 2026-11-05
  - key: oxford-beer
    title: The Oxford Companion to Beer
    publisher: Oxford University Press
    note: 参考其关于特拉普斯特修会、修道院酿造与比利时修道院啤酒的条目；未复制原文。
    accessed: 2026-11-05
    url: https://global.oup.com/academic/product/the-oxford-companion-to-beer-9780195367133

rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写；依据协会公开信息、风格指南与工具书核验，未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方风格指南、商标、图片与引用文本不在本许可内；来源仅作核验引用。第三方图片已在图注中标注作者与许可。
verification_scope: source-verified
---
# 修道院啤酒

修道院啤酒（abbey beer）是一个宽泛的说法，指由修道院酿造、或由商业酒厂以修道院名称与授权酿造的啤酒。它涵盖两类关系：一类是修道院内部的酿造，另一类是商业酒厂与修道院之间的名称授权。读者最需要分清的是特拉普斯特（Trappist）与修道院（abbey）两个概念：前者有严格的地点和监督要求，后者更接近商业与历史的关联。

![修道院啤酒 图像](/media/photos/drink-style-abbey-beer-276b4dc3.jpg)

图：修道院啤酒。图片：BLloydT，CC BY-SA 4.0，via Wikimedia Commons（[原图页面](https://commons.wikimedia.org/wiki/File:A_wall_of_Belgian_beer_bottles_at_the_Bruges_beer_experience.jpg)）。

## 定义与标准

特拉普斯特啤酒必须在特拉普斯特修道院内、由修士本人或在其监督下酿造，收益用于修道院自养与慈善。符合条件的产品可以使用特拉普斯特标识，标识由 International Trappist Association 管理。具体有哪些酒厂获准使用，由该协会公布名单并随时更新，因此不宜引用一个固定数字，应以官网为准。

修道院啤酒的范围更宽。商业酒厂可以使用修道院名称、历史故事或授权来命名产品，部分国家还有各自的认可标识与授权规则，具体以当地规定为准。授权关系说明的是名称来源，不直接说明质量。

dubbel、tripel、quadrupel 描述的是强度层级，而不是独立风格。dubbel 常见 6–8% 酒精度，tripel 常见 7.5–10%，quadrupel 常在 10% 以上；这些是命名习惯，并无统一的法定分级。也有酒厂使用 single 或 enkel 指更轻的基础款。颜色与强度并不绑定：tripel 多为淡色，dubbel 与 quadrupel 多为深色。

## 历史与产地

修道院酿造在中世纪已是日常：修士自用、待客与施舍都需要啤酒，酿造也因此成为修道院经济的一部分。特拉普斯特修会源于 1664 年的拉特拉普（La Trappe）改革，强调回归隐修规则，其后在法国与低地国家建立多座修道院。

法国大革命与两次世界大战让许多修道院停产或迁址，20 世纪才陆续恢复。与此同时，商业酒厂开始借用修道院名称与形象销售啤酒，逐渐形成 abbey beer 这一宽泛类别。[比利时](ref:belgium)是最集中的产地，荷兰、德国、奥地利与英国也有各自的修道院风格产品。

比利时的特拉普斯特酒厂，如 Westmalle、Chimay、Orval、Rochefort 与 Westvleteren，多以瓶中二次发酵与高碳酸著称；修道院啤酒的名单与身份会随时间变化，查证时应回到协会与酒厂的公开信息。

## 原料与工艺

[水](ref:water)、[大麦](ref:barley)麦芽是基础，部分配方加入小麦或燕麦以调整酒体与泡沫。深色版本使用深色麦芽或焦香麦芽，带来干果、焦糖与可可。dubbel 与 tripel 常添加 candi sugar，即甜菜或蔗糖制成的转化糖浆，用来提高酒精度而不显著增加麦芽风味；quadrupel 的浓度更高。

[发酵](ref:fermentation)为上层发酵，温度通常 18–22°C。酵母是风格的重要变量，酯香的高低、收口的干湿都与菌株和发酵度有关。装瓶时加入糖与酵母进行二次发酵，是许多修道院啤酒产生细密气泡的方式。修道院酒厂通常使用自有水源，规模不大，批次之间允许存在差异。

高酒精度的版本在瓶中还会继续变化，因此[原麦汁浓度](ref:original-gravity)与酒精度是判断陈年潜力的实用指标。低酒精度的 single 或浅色版本则宜趁新鲜饮用。

## 风味特征

dubbel 呈深棕至红褐色，香气以葡萄干、无花果、焦糖、可可与香料为主，酒体中等，收口偏干。tripel 多为淡金至金黄，香气带胡椒、丁香、柑橘与轻微香蕉，酒精度高但口感不应甜腻。quadrupel 颜色更深、风味更浓，甜感、酒精温暖与苦味同时出现。

共同点是酵母表达突出、碳酸充足、收口干净。修道院啤酒并不等于“甜酒”，发酵度不足导致的笨重甜感通常是配方或发酵问题。判断质量要看平衡、发酵完成度与香气复杂度，而不是酒精度高低。

## 品鉴与饮用

适饮温度约 8–14°C，温度过低会压住酯香。郁金香杯或宽口圣杯有助于聚拢香气。瓶中二次发酵的产品常有沉淀，倒酒时可按个人偏好决定是否混入。

佐餐时，dubbel 适合炖肉、野味与硬质奶酪；tripel 适合海鲜、禽肉与带辛香的菜肴；quadrupel 适合重口味主菜与黑巧克力甜点。保存应避光、阴凉、直立，避免反复升温。高酒精度产品适合适量饮用，陈年时应定期检查瓶塞与液面。

## 常见误区

第一，把所有修道院啤酒都当作特拉普斯特。只有满足地点与监督要求并获得标识的才是。
第二，认为修道院授权产品一定更差。授权说明名称来源，质量仍需按酒评判断。
第三，相信特拉普斯特酒厂有一个固定的数字。名单由 International Trappist Association 公布并会变动，应查官网。
第四，认为酒精度越高越好。dubbel 也可以做得非常出色。
第五，认为修道院啤酒都很甜。多数产品的收口偏干。
第六，认为所有修道院啤酒都适合长期陈放。低酒精度版本不宜久存。

对照阅读：[啤酒](ref:beer)、[水](ref:water)。

## 延伸阅读

- [啤酒](ref:beer)：修道院啤酒在啤酒风格体系中的位置。
- [比利时](ref:belgium)：特拉普斯特与修道院啤酒最集中的产地。
- [水](ref:water)：修道院酒厂水源对风格的影响。
- [大麦](ref:barley)：麦芽与深色风味的来源。
- [发酵](ref:fermentation)：上层发酵与瓶中二次发酵。
- [原麦汁浓度](ref:original-gravity)：判断强度与陈年潜力的指标。
- [精酿啤酒](ref:craft-beer)：当代修道院风格产品的市场背景。

**关键事实。**

| 项目 | 内容 |
| --- | --- |
| 一句话定位 | 由修道院酿造或借用修道院名义与授权的啤酒统称；特拉普斯特啤酒必须在特拉普斯特修道院内、由修士监督酿造，修道院啤酒多为商业授权产品，dubbel、tripel、quadrupel 指强度层级而非独立风格 |
| 上位风格 | 啤酒 |
| 香气家族 | 麦芽与酵母 |

**来源与边界。** 本页关于「修道院啤酒」的关键事实，主要由以下来源交叉核对：International Trappist Association（特拉普斯特啤酒的产地与监督要求，以及协会公布获准酒厂名单的方式）、Beer Judge Certification Program（dubbel、tripel 与 quadrupel 的强度、苦度与风味边界）、Brewers Association（精酿行业对修道院风格与比利时艾尔的公开表述；未复制其文案）等 4 条来源。价格、批次与状态会变，涉及这些字段时以页面所列来源的最新版本为准。正文为项目自写，来源只作核验，不复制原文。

**并读。** 把「修道院啤酒」与「啤酒」、「比利时」、「水」放在一起读时，先确认它们是同一层级还是上下游关系：先确认定义与工艺，再比较原料、产区与代表品牌。本页负责给出酒类风格的基本坐标，对照条目补上具体案例与差异；读完再回到本页，才能分清哪些差别属于酒类风格本身，哪些只是产地、批次或品牌选择。
