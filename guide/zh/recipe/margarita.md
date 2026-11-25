---
schema_version: 1
id: recipe:margarita
type: recipe
lang: zh
slug: margarita
title: 玛格丽特配方（IBA 版本）
summary: 50 毫升百分之百龙舌兰酒、20 毫升橙皮酒与 15 毫升鲜榨青柠汁摇和，滤入预冷杯，可选半圈盐边；本文说明酸甜平衡、盐边与摇和稀释如何决定成品。
status: reviewed
revision: 1
product_id: cocktail:margarita
source_version: IBA Official Cocktails（2026 年 10 月核对）
method: shake
yield:
  amount: 1
  unit: 杯
  serves: 1
ingredients:
  - ingredient_key: tequila
    name: 百分之百龙舌兰酒
    amount: 50
    unit: 毫升
  - ingredient_key: triple-sec
    name: 橙皮酒
    amount: 20
    unit: 毫升
  - ingredient_key: lime-juice
    name: 鲜榨青柠汁
    amount: 15
    unit: 毫升
  - ingredient_key: ice
    name: 冰
  - ingredient_key: salt
    name: 细盐（可选盐边）
steps:
  - 提前把酒杯冰镇；如需盐边，用青柠汁润湿杯口外沿后蘸细盐，只做半圈。
  - 把龙舌兰酒、橙皮酒与鲜榨青柠汁放入摇酒壶。
  - 加冰摇和，直到壶身明显变冷。
  - 滤入预冷的杯中，按需在杯口放一片青柠。
vessel_refs:
  - vessel:martini-glass
tool_refs: []
technique_refs:
  - technique:shaking
garnish: 半圈盐边、青柠片（可选）
legacy_refs: []
aliases:
  - Margarita recipe
tags:
  - classic-cocktail
related: []
references:
  - key: cocktail
    target_id: cocktail:margarita
  - key: vessel
    target_id: vessel:martini-glass
  - key: technique
    target_id: technique:shaking
  - key: tequila
    target_id: drink-style:tequila
  - key: cocktails-guide
    target_id: guide:cocktail-basics
  - key: ice
    target_id: guide:ice-and-temperature
  - key: abv
    target_id: term:alcohol-by-volume
sources:
  - key: iba-margarita
    title: IBA Official Cocktails — Margarita
    url: https://iba-world.com/iba-cocktail/margarita/
    publisher: International Bartenders Association
    note: 用于核对配方用量、摇和方法与盐边选项；未复制原文。
    accessed: 2026-11-04
  - key: oxford-spirits
    title: The Oxford Companion to Spirits and Cocktails
    publisher: Oxford University Press
    note: 用于核对玛格丽特的来历叙述、龙舌兰与橙皮酒的作用；未复制原文。
    accessed: 2026-11-04
    url: https://global.oup.com/academic/product/the-oxford-companion-to-spirits-and-cocktails-9780199311132
  - key: liquid-intelligence
    title: Liquid Intelligence
    publisher: Dave Arnold / W. W. Norton
    note: 用于核对摇和、冰型与稀释对酸甜平衡的影响；未复制原文。
    accessed: 2026-11-04
  - key: iba-list
    title: IBA 官方鸡尾酒名单
    url: https://iba-world.com/iba-official-cocktails/
    publisher: International Bartenders Association
    note: 用于确认该饮品属于 IBA 官方鸡尾酒名单；未复制原文。
    accessed: 2026-11-07
  - key: r16-thebar
    title: The Bar — Classic Margarita
    url: https://www.thebar.com/en-us/recipes/classic-margarita
    publisher: The Bar (Diageo)
    note: 用于核对龙舌兰、橙味利口酒、青柠与糖浆的比例；未复制原文。
    accessed: 2026-11-07

rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写配方说明；用量与成品依据 IBA 公开配方，步骤与解释为项目整理，不复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方标准、商标、图片与引用文本不在本许可内；来源仅作核验引用。本页未使用第三方图片。
verification_scope: source-verified
---
# 玛格丽特配方（IBA 版本）

这是[玛格丽特](ref:cocktail)的一个有明确出处的配方版本。玛格丽特的结构是“烈酒 + 橙皮酒 + 鲜榨酸”，酸甜比例决定它是否成立；盐边不是装饰口号，而是风味结构的一部分。本页记录 IBA 的公开版本，并把酸甜、摇和与盐边讲清楚。

![玛格丽特配方（IBA 版本） 类型示意图](/media/photos/theme-ingredients.jpg)

图：玛格丽特配方（IBA 版本） 类型示意图。图片：Doubao Seedream 5.0 AI 辅助绘制（项目自有），不是玛格丽特配方（IBA 版本）的实拍。

## 这是一份有出处的配方

IBA（国际调酒师协会）的公开配方使用 50 毫升百分之百龙舌兰酒、20 毫升橙皮酒和 15 毫升鲜榨青柠汁，加冰摇和后滤入预冷的杯中，可选半圈盐边。本页采用这一版本，并在每一步说明目的，方便在家复现时判断问题出在哪一环。

玛格丽特配方（IBA 版本）的配方版本与鸡尾酒身份分开记录，是为了可追溯。玛格丽特在不同地区有差别很大的做法：有的用糖浆补甜，有的用龙舌兰糖浆；有的加果汁做成冰沙；有的做整圈盐边，有的完全不加盐。这些差异不是谁“正宗”，而是版本不同。

## 原料与比例

- 百分之百龙舌兰酒 50 毫升
- 橙皮酒 20 毫升
- 鲜榨青柠汁 15 毫升
- 冰 适量
- 细盐 适量（可选，用于半圈盐边）

比例约为 50:20:15。橙皮酒既提供甜度，也提供柑橘香气；青柠汁提供酸度与清香。这个比例不是唯一答案：青柠的酸度会随成熟度变化，橙皮酒的甜度也因品牌而异，因此毫升数只是起点。

用量是起点，不是法律。杯型、冰量与摇和时间都会改变结果。第一次做时先按本页数字，之后按入口平衡微调，并一次只改一个变量，才能判断变化来自哪里。

## 每味原料在做什么

[龙舌兰酒](ref:tequila)是主体，提供植物香气、矿物感与酒精骨架。百分之百龙舌兰酒意味着全部糖分来自龙舌兰，风味更完整；混合型龙舌兰酒可能添加其他糖源，风味与口感不同。换基酒会明显改变成品。

橙皮酒提供甜度与柑橘香气，是酸甜平衡的连接件。用量太少，成品会尖；用量太多，甜味会盖住龙舌兰。它同时影响酒精度与口感厚度，不能只当作“糖水”。

鲜榨青柠汁提供酸度、清香与新鲜感。瓶装青柠汁的香气和酸度通常不同，能鲜榨时应优先鲜榨。青柠汁的酸度会随品种与成熟度变化，配方中的 15 毫升只是起点。细盐用于盐边，增强咸鲜感，也会改变入口的酸感。

## 调制步骤

先冰镇酒杯。如需盐边，用青柠汁润湿杯口外沿，再蘸细盐，只做半圈；盐不要撒进杯中。盐边要在摇和前完成，否则杯口的水分会渗出，影响外观。

把龙舌兰酒、橙皮酒与鲜榨青柠汁放入摇酒壶，加冰摇和，直到壶身明显变冷。摇和后立即滤入预冷杯中，避免酒液继续浸泡在冰水中。摇和的一般原理可参考[摇酒](ref:technique)与[调酒基础](ref:cocktails-guide)。

## 摇和与冰

玛格丽特通常摇和，而不是搅拌：鲜榨果汁需要与酒液充分混合，摇和能快速降温、稀释并把空气带入液体，使口感更轻盈。摇和时间过长会稀释过多，过短则冷却与融合不足。

冰的质量直接影响成品。大而干的冰融化慢，稀释较可控；碎冰或湿冰降温快，但稀释也快。摇和后应立即滤冰，否则冰块会在杯中继续融化，几分钟内就把酸甜平衡冲淡。

成品的实际强度取决于龙舌兰酒的[酒精度](ref:abv)、橙皮酒的甜度与摇和带来的稀释，不能只按配方毫升数判断。关于冰型与温度，可参考[加冰与温度](ref:ice)。

## 盐边

盐边是可选项，IBA 配方写作“半圈盐边”。盐能增强咸鲜感、压低苦味，也会改变入口的酸感。盐太多会盖住龙舌兰与青柠的细节，太少则几乎没有作用。

只做半圈，是为了让饮用者可以选择“有盐”或“无盐”的入口。做盐边时用细盐而不是粗盐，杯口外沿润湿后轻轻蘸取，避免盐块落入酒液。盐边完成后再滤入酒液，保持杯口干净。

## 杯型与温度

IBA 配方使用预冷的鸡尾酒杯。杯型应能聚拢香气、方便手持而不传递体温。传统上也有更宽、更矮的玛格丽特杯，但杯型不是定义的一部分；关键是预冷、容量合适、杯口不过宽。

没有专用杯时，可以使用杯口略收的小型杯子。杯子不冷，成品会迅速回温，酸度与香气都会变化。关于杯型与温度的关系，可参考[马天尼杯](ref:vessel)与[如何选杯](ref:cocktails-guide)。

## 常见错误

第一，用瓶装青柠汁替代鲜榨。香气与酸度都不同，成品会显得平。

第二，盐边做满整圈。满圈会让每一口都过咸，半圈更可控。

第三，盐撒进杯内。盐落入酒液会持续溶解，越喝越咸。

第四，摇和时间随意。过长会稀释过多，过短则冷却与融合不足。

第五，用温杯。杯子不冷，成品迅速回温，酸甜平衡随之改变。

## 版本差异与变体

以其他橙皮酒替代，会改变甜度与柑橘方向；加入果汁，会形成更长的饮品；做成冰冻版本，会改变稀释与口感；以其他烈酒替代龙舌兰，则形成不同的变体。盐边、糖边或无边的选择，也会改变入口。

玛格丽特的变体包括用新鲜青柠汁代替柠檬汁、用糖浆代替橙皮利口酒，以及加入水果泥的草莓或芒果版本。冰冻玛格丽特用碎冰搅打，糖与青柠的比例要相应调整；杯口盐边可加可不加，但应在配方中说明。

## 边界

本页的玛格丽特配方（IBA 版本）配方按一个可核对版本记录，不评价具体品牌，也不把某种盐边做法说成唯一正确选择。玛格丽特配方（IBA 版本）的配方是起点，不是法律；任何改动都应标明差异。饮酒应适量，避免空腹快速饮用；驾车、服药或怀孕期间不应饮酒，并遵守当地法律。

**关键事实。**

| 项目 | 内容 |
| --- | --- |
| 一句话定位 | 50 毫升百分之百龙舌兰酒、20 毫升橙皮酒与 15 毫升鲜榨青柠汁摇和，滤入预冷杯，可选半圈盐边；本文说明酸甜平衡、盐边与摇和稀释如何决定成品 |
| 技法 | shake |
| 出品 | 1 杯 |
| 主要配料 | 百分之百龙舌兰酒 50毫升、橙皮酒 20毫升、鲜榨青柠汁 15毫升、冰 undefinedundefined |
