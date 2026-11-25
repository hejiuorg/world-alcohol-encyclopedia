---
schema_version: 1
id: region:provence
type: region
lang: zh
slug: provence
title: 普罗旺斯
summary: 法国东南部地中海沿岸的葡萄酒产区，从罗讷河口延伸到尼斯以西；以桃红葡萄酒最为著名，也生产红白葡萄酒，品种以歌海娜、神索、西拉与慕合怀特为主，邦多勒等法定产区各有独立规则。
status: reviewed
revision: 1
level: other
parent_id: region:france
country_code: FR
legacy_refs: []
aliases:
  - 普罗旺斯产区
  - Provence
tags:
  - region
  - wine
  - france
related:
  - relation: about
    target_id: region:france
  - relation: about
    target_id: drink-style:rose-wine
  - relation: about
    target_id: drink-style:red-wine
  - relation: about
    target_id: drink-style:white-wine
  - relation: about
    target_id: variety:grenache
  - relation: about
    target_id: variety:syrah
references:
  - key: france
    target_id: region:france
  - key: rose-wine
    target_id: drink-style:rose-wine
  - key: red-wine
    target_id: drink-style:red-wine
  - key: white-wine
    target_id: drink-style:white-wine
  - key: grenache
    target_id: variety:grenache
  - key: syrah
    target_id: variety:syrah
  - key: grape
    target_id: ingredient:grape
sources:
  - key: inao
    title: Institut National de l'Origine et de la Qualité — Appellations d'origine contrôlée
    url: "https://www.inao.gouv.fr/"
    publisher: INAO
    note: 用于核对普罗旺斯各法定产区的范围与规则；未复制原文。
    accessed: 2026-11-05
  - key: eu-wine
    title: EU Regulation 1308/2013 — Common Market Organisation for Wine
    url: https://eur-lex.europa.eu/eli/reg/2013/1308/oj
    publisher: European Union
    note: 用于核对欧盟葡萄酒类别、地理标志与标签规则；未复制原文。
    accessed: 2026-11-05
  - key: oxford-wine
    title: The Oxford Companion to Wine — Provence, Côtes de Provence and Bandol entries
    publisher: Oxford University Press
    note: 参考其关于普罗旺斯、普罗旺斯丘与邦多勒的条目；未复制原文。
    accessed: 2026-11-05
    url: https://global.oup.com/academic/product/the-oxford-companion-to-wine-9780198871316
  - key: vinsdeprovence
    title: Vins de Provence — 产区官方介绍
    url: https://www.vinsdeprovence.com/
    publisher: Conseil Interprofessionnel des Vins de Provence
    note: 用于核对普罗旺斯 AOC 体系、桃红比例与市场数据；未复制原文。
    accessed: 2026-11-07
  - key: rose-basics
    title: Vins de Provence — Le B.A.-BA du rosé
    url: https://www.vinsdeprovence.com/le-rose/le-b-a-ba-du-rose
    publisher: Conseil Interprofessionnel des Vins de Provence
    note: 用于核对桃红酿造、颜色与 2024 年 AOP 产量表述；未复制原文。
    accessed: 2026-11-07
  - key: bandol-site
    title: Vins de Bandol — 产区与法规
    url: https://vinsdebandol.com/
    publisher: Syndicat des Vins de Bandol
    note: 用于核对邦多勒 AOC 范围、慕合怀特比例与陈酿要求；未复制原文。
    accessed: 2026-11-07
  - key: ref
    title: "《The Oxford Companion to Wine》普罗旺斯、普罗旺斯丘与邦多勒条目"
    publisher: "Oxford University Press"
    note: 由原条目末尾参考资料迁移，未逐条复核访问日期。
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写；依据法国 INAO、欧盟法规、产区协会与葡萄酒工具书核验，不复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方法规文本、商标与图片不在本许可内；来源仅作核验引用。第三方图片已在图注中标注作者与许可。
verification_scope: source-verified
---
# 普罗旺斯

普罗旺斯是世界上最容易被“桃红”两个字定义的葡萄酒产区，也是被这两个字遮蔽得最厉害的产区之一。它的海岸线从罗讷河口一直延伸到尼斯以西，葡萄园分布在石灰岩丘陵、片岩坡地和沿海平原上；桃红确实占了大头，但邦多勒的慕合怀特红、卡西的白、帕莱特的稀有混酿，才是理解这个产区深度的入口。普罗旺斯不是一个风格统一的品牌，而是一组共享地中海气候、却各有法规与历史的 AOC。

![普罗旺斯 图像](/media/photos/region-provence-bc066643.jpg)

图：普罗旺斯。图片：Robert Brink，CC BY-SA 3.0，via Wikimedia Commons（[原图页面](https://commons.wikimedia.org/wiki/File:Lavender_field_and_Mont_Ventoux.jpg)）。

## 地理：从罗讷河口到蓝色海岸

普罗旺斯产区横跨瓦尔省、罗讷河口省、阿尔卑斯-马里蒂姆省与上普罗旺斯阿尔卑斯省的部分地区。西端接近罗讷河谷，东端到尼斯腹地；沿海有马赛、土伦、戛纳、尼斯，内陆有艾克斯、德拉吉尼昂等城市。葡萄园多分布在沿海丘陵与内陆高地，海拔从海平面到 500 米左右。

## 气候：地中海与密史脱拉风

产区属典型地中海气候：夏季炎热干燥，冬季温和，日照充足，年降水量偏低。密史脱拉风从罗讷河谷向南吹，降低湿度与病害压力，也让葡萄皮更厚、香气更集中。干旱是主要限制因素，灌溉受法规约束；热浪与采收期降雨会显著改变年份风格。

## 土壤与地形

普罗旺斯的土壤类型非常多样：沿海多石灰岩与砾石，排水快、根系深；内陆高地多片岩、砂岩与黏土，保水能力更强。邦多勒的坡地以石灰岩与砾石为主，卡西则多石灰岩崖壁与梯田。土壤与坡向的差异，解释了为什么同为桃红，不同村庄的颜色、酸度与香气可以差很远。

## 法定框架：多个 AOC，各有规则

普罗旺斯的主要 AOC 包括 Côtes de Provence（普罗旺斯丘）、Coteaux d'Aix-en-Provence（艾克斯丘）、Coteaux Varois en Provence（瓦尔丘）、Bandol（邦多勒）、Cassis（卡西）、Palette（帕莱特）、Bellet（贝莱）与 Pierrevert（皮埃尔韦尔）。Côtes de Provence 是面积最大的一个，覆盖瓦尔省与罗讷河口省的大片区域；Bandol 于 1941 年获得 AOC，Cassis 于 1936 年，Palette 于 1948 年。

## Côtes de Provence 的四个补充地理名称

2019 年起，Côtes de Provence 允许在酒标上使用四个补充地理名称（dénominations géographiques complémentaires）：Sainte-Victoire（圣维克多）、Fréjus（弗雷瑞斯）、La Londe（拉隆德）与 Pierrefeu（皮埃尔弗）。它们对应不同的土壤、海拔与海风影响：圣维克多更靠近内陆山地，拉隆德与皮埃尔弗更受海风调节。看到这四个名字，说明酒款来自更具体的地块，而不是整个大区。

## 品种：歌海娜、神索、西拉与慕合怀特

桃红与红葡萄酒以歌海娜、神索、西拉、慕合怀特为主，辅以佳丽酿、神索、蒂布龙（Tibouren）等本地品种。慕合怀特在邦多勒是主角，赋予酒体结构、香料与陈年潜力；歌海娜提供红色水果与酒精度；神索带来轻盈与花香；西拉贡献胡椒与颜色。白葡萄酒以罗尔（Rolle，即 Vermentino）、克莱雷特、白玉霓、玛珊与长相思为主。

## 邦多勒：慕合怀特的最低比例与陈酿

邦多勒是普罗旺斯最有结构感的红葡萄酒产区。AOC 规则要求红葡萄酒中慕合怀特至少占 50%，并与歌海娜、神索等混酿；红葡萄酒须在橡木桶中陈酿至少 18 个月。产区面积约 1550 公顷，基础产量上限为 35 hl/ha。酒款常有黑莓、黑橄榄、皮革、灌木与海风气息，单宁明显，适合中长期陈放。

## 卡西、帕莱特与贝莱：小而不同的白

卡西（Cassis）以白葡萄酒著称，品种包括玛珊、克莱雷特、白玉霓与长相思，风格带柑橘、白花、茴香与海盐感，适合配海鲜。帕莱特（Palette）面积极小，红白桃红都产，以克莱雷特、歌海娜、慕合怀特等混酿，历史可追溯至古代。贝莱（Bellet）位于尼斯腹地，以 Rolle 与霞多丽白、布拉克（Braquet）红著称，产量很小。

## 代表生产者

普罗旺斯丘的代表包括 Domaines Ott、Château d'Esclans（Whispering Angel）、Château de Berne 与 Domaines Bunan；邦多勒有 Domaine Tempier、Château Pradeaux、Domaine du Gros'Noré 与 Château de la Bégude；卡西有 Clos Sainte-Magdeleine 与 Domaine du Bagnol。它们分别代表商业化桃红、传统邦多勒与精品小产区三条路线。

## 年份与市场

普罗旺斯 AOC 桃红约占产区产量的 85% 左右，2024 年 AOP 桃红产量约 1.34 亿瓶，普罗旺斯占法国桃红产量的 40%-45%。市场从 8-20 欧元的日常桃红，到 20-40 欧元的名庄桃红，再到邦多勒的 30 欧元以上红葡萄酒，层次分明。年份差异主要来自干旱、热浪与采收期降雨；桃红通常宜在 1-3 年内饮用，邦多勒红则可以陈放 10 年以上。

## 饮用与配餐

桃红适合 8-10℃ 饮用，配海鲜、沙拉、普罗旺斯炖菜与地中海前菜；邦多勒红适合 16-18℃，配烤肉、野味与硬质奶酪；卡西白配生蚝、海鱼与茴香类菜肴。开瓶后应冷藏并尽快饮用；本页关于普罗旺斯的内容涉及酒精饮料；过量饮酒有害健康，未成年人不应饮酒。

## 常见误区

第一，认为普罗旺斯只产桃红。它也生产有结构的红与精致白。第二，认为桃红颜色越浅质量越好。颜色主要反映浸皮时间与品种。第三，把普罗旺斯与罗讷河谷混为一谈。两者相邻，但 AOC 与品种比例不同。第四，认为桃红不能陈年。少数结构型桃红可以短期存放，但多数宜早饮。第五，只看“Côtes de Provence”而不看补充地理名称。具体村庄往往更能说明风格。

对照阅读：[法国](ref:france)、[红葡萄酒](ref:red-wine)。

## 延伸阅读

- [法国](ref:france)：法国葡萄酒法规与产区体系。
- [桃红葡萄酒](ref:rose-wine)：普罗旺斯最具代表性的类型。
- [红葡萄酒](ref:red-wine)与[白葡萄酒](ref:white-wine)：产区的另外两个类型。
- [歌海娜](ref:grenache)与[西拉](ref:syrah)：普罗旺斯混酿的主要品种。
- [葡萄](ref:grape)：普罗旺斯所用葡萄的成熟度、酸度与单宁判断。

**关键事实。**

| 项目 | 内容 |
| --- | --- |
| 一句话定位 | 法国东南部地中海沿岸的葡萄酒产区，从罗讷河口延伸到尼斯以西；以桃红葡萄酒最为著名，也生产红白葡萄酒，品种以歌海娜、神索、西拉与慕合怀特为主，邦多勒等法定产区各有独立规则 |
| 层级 | 其他 |
| 所属 | 法国 |
| 国家代码 | FR |

**来源与边界。** 本页关于「普罗旺斯」的关键事实，主要由以下来源交叉核对：INAO（普罗旺斯各法定产区的范围与规则；由原条目末尾参考资料迁移，未逐条复核访问日期）、European Union（欧盟葡萄酒类别、地理标志与标签规则）、Oxford University Press（提供关于普罗旺斯、普罗旺斯丘与邦多勒的条目；由原条目末尾参考资料迁移，未逐条复核访问日期）等 8 条来源。价格、批次与状态会变，涉及这些字段时以页面所列来源的最新版本为准。正文为项目自写，来源只作核验，不复制原文。
