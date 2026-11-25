---
schema_version: 1
id: drink-style:sherry
type: drink-style
lang: zh
slug: sherry
title: 雪莉
summary: 西班牙赫雷斯地区的加强葡萄酒，以帕洛米诺为主，经生物陈酿（菲诺、曼萨尼利亚）或氧化陈酿（奥罗索、阿蒙蒂亚多、PX）形成从极干到极甜的风格，并以索莱拉系统调配。
status: reviewed
revision: 1
legacy_refs: []
parent_style_id: drink-style:fortified-wine
aroma_family: 氧化/坚果/酵母
aliases:
  - 雪莉
  - 雪利
  - Sherry
  - Jerez
  - Xérès
tags:
  - curated
  - source-verified
  - style-guide
  - fortified-wine
related:
  - relation: about
    target_id: drink-style:fortified-wine
  - relation: about
    target_id: process:fortification
  - relation: about
    target_id: term:solera
  - relation: about
    target_id: term:flor
  - relation: about
    target_id: variety:palomino
  - relation: about
    target_id: region:jerez
references:
  - key: fortified-wine
    target_id: drink-style:fortified-wine
  - key: fortification
    target_id: process:fortification
  - key: solera
    target_id: term:solera
  - key: flor
    target_id: term:flor
  - key: palomino
    target_id: variety:palomino
  - key: jerez
    target_id: region:jerez
sources:
  - key: sherry-do
    title: Consejo Regulador — Jerez-Xérès-Sherry y Manzanilla-Sanlúcar de Barrameda
    url: https://www.sherry.wine/
    publisher: Sherry DO
    note: 用于核对雪莉的法定产区、品种、加强酒精度、生物陈酿与氧化陈酿类别、索莱拉及 VOS/VORS 标注；未复制原文。
    accessed: 2026-11-08
  - key: eu-wine
    title: EU Regulation 1308/2013 — Common Market Organisation for Wine
    url: https://eur-lex.europa.eu/eli/reg/2013/1308/oj
    publisher: European Union
    note: 用于核对加强葡萄酒、地理标志与标签框架；未复制原文。
    accessed: 2026-11-08
  - key: oxford-wine
    title: The Oxford Companion to Wine
    publisher: Oxford University Press
    note: 参考其关于雪莉、酒花、索莱拉与赫雷斯产区的条目；未复制原文。
    accessed: 2026-11-08
    url: https://global.oup.com/academic/product/the-oxford-companion-to-wine-9780198871316
  - key: oiv-definitions
    title: OIV International Code of Oenological Practices — Part I Definitions
    url: https://www.oiv.int/standards/international-oenological-codex/part-i-definitions
    publisher: International Organisation of Vine and Wine (OIV)
    note: 用于核对利口酒型葡萄酒与加强工艺的相关定义；未复制原文。
    accessed: 2026-11-08

rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写；依据 EU 法规/产区协会/工具书核验，未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 本页配图为维基共享资源的 Lustau 酒窖实拍照片，按 CC BY-SA 4.0 使用，具体见图片图注。图片仅作尺寸压缩，未作构图裁剪。第三方商标与引用文本不在本许可内。
verification_scope: source-verified
---
# 雪莉

雪莉（Sherry）是西班牙南部赫雷斯地区的加强葡萄酒。它的特殊之处不在于“加了酒精”，而在于加强之后的两条陈酿路径：一条在酒花（flor）覆盖下进行生物陈酿，得到极干、轻盈、带面包与杏仁香气的菲诺；另一条在氧气中陈酿，得到颜色深、带坚果与焦糖风味的奥罗索。再加上索莱拉系统的逐级调配，雪莉形成了一套与普通葡萄酒完全不同的时间逻辑。

![Lustau 酒窖内的雪莉酒桶与拱廊](/media/photos/drink-style-sherry-876c72cd.jpg)

图：赫雷斯 Lustau 酒窖内的雪莉酒桶与拱廊。图片：Anual，CC BY-SA 4.0，via [原图页面](https://commons.wikimedia.org/wiki/File:Lustau_003An2019.jpg)。

## 定义与法规

雪莉是受原产地命名保护的加强葡萄酒，法定产区集中在西班牙安达卢西亚的赫雷斯-赫雷斯-雪莉（Jerez-Xérès-Sherry）与曼萨尼利亚-桑卢卡尔（Manzanilla-Sanlúcar de Barrameda）两个 DO。只有在规定区域内酿造、加强并在当地陈年的酒，才能使用“Sherry”“Jerez”或“Xérès”名称。

雪莉的基酒是干型白葡萄酒，发酵完成后才开始[加强](ref:fortification)。这一点与波特不同：波特在发酵中途加酒精以保留糖分，雪莉则在发酵结束后加酒精，因此天然风格多为干型。加强后的酒精度按类型区分：菲诺与曼萨尼利亚通常为 15%–15.5% vol，奥罗索为 17%–18% vol 或更高；甜型雪莉则会加入甜酒或浓缩葡萄汁。

欧盟葡萄酒法规为加强葡萄酒、地理标志与标签提供框架，具体的最低酒精度、品种、陈年与甜度规则由 DO 产品规范规定。标签上的“Fino”“Oloroso”“PX”不是风格形容词，而是有法规含义的类别词。

## 历史

赫雷斯的葡萄种植可以追溯到腓尼基人与罗马人时期。中世纪，赫雷斯在摩尔人统治下发展了灌溉与葡萄园；13 世纪基督教势力收复该地后，葡萄酒贸易逐渐与英国市场连接。16 至 17 世纪，雪莉以“sack”之名进入英国文学与餐桌，成为莎士比亚笔下常见的酒。

18 至 19 世纪，英国商行在赫雷斯建立酒庄与陈年仓库，雪莉的出口规模扩大；19 世纪末的葡萄根瘤蚜几乎摧毁产区，随后通过嫁接与重新种植恢复。1933 年，赫雷斯获得法定产区地位，索莱拉与酒花的管理逐渐制度化。20 世纪后期，雪莉消费经历起伏，但菲诺与曼萨尼利亚在西班牙本地餐饮中始终保持地位。

## 风土与品种

雪莉产区的核心是“雪莉三角”：赫雷斯-德拉弗龙特拉、圣玛丽亚港与桑卢卡尔-德巴拉梅达。这里夏季炎热、冬季温和，受大西洋与地中海气流交替影响；来自大西洋的潮湿西风（poniente）与来自内陆的干热东风（levante）塑造了葡萄的成熟节奏。

土壤以 albariza 白垩土最著名，表层浅、保水性强，能在干旱夏季为葡萄提供水分。主要品种是[帕洛米诺](ref:palomino)（Palomino Fino），酸度低、香气中性，正好适合在加强后被酒花或氧化主导；甜型雪莉使用 Pedro Ximénez 与 Moscatel，前者经晒干浓缩，带有葡萄干与无花果风味。

## 基酒与加强

葡萄采收后压榨，进行酒精发酵。发酵完成的基酒酒精度通常在 11%–13% vol，干型、酸度不高。酒庄会对酒液进行分级：轻盈、干净的酒液适合培养酒花，厚重、香气更深的酒液则走向氧化陈酿。

加强使用葡萄蒸馏酒。菲诺与曼萨尼利亚加至约 15% vol，这个酒精度足以抑制醋酸菌，又低到让酒花酵母存活；奥罗索加至 17%–18% vol，酒花无法生长，酒液直接进入氧化陈酿。阿蒙蒂亚多的路径更复杂：先作为菲诺进行生物陈酿，酒花死亡后再加度并转入氧化陈酿，因此同时具有面包与坚果两类香气。

## 生物陈酿与氧化陈酿

生物陈酿的关键是[酒花](ref:flor)。酒花是一层漂浮在酒液表面的酵母膜，消耗酒精与氧气，产生乙醛与少量酯类，赋予菲诺面包、杏仁、青苹果与咸鲜感，同时保护酒液不被过度氧化。酒花的生长依赖温度、湿度、酒精度与酒液营养；桑卢卡尔气候更凉爽、湿度更高，酒花更厚，曼萨尼利亚因此带有更明显的海水与咸味。

氧化陈酿则让酒液与氧气接触，颜色从浅黄逐渐变为琥珀、红木色，香气转向核桃、榛子、焦糖、橙皮与香料。奥罗索、阿蒙蒂亚多、Palo Cortado 与甜型 PX 都属于这一路径。生物陈酿与氧化陈酿不是等级高低，而是两种不同的风格方向。

## 索莱拉系统

雪莉的另一核心是[索莱拉](ref:solera)系统。酒桶按层级叠放：最底层是索莱拉，存放准备装瓶的最老酒液；上面若干层是 criaderas，存放较年轻的酒液。每次从索莱拉取出部分酒液装瓶，再从上一层补入等量酒液，逐层向上，最后用新酒补充顶层。

这种“取老补新”的方式让成品没有单一年份，风格长期稳定。索莱拉不是“把不同年份混在一起”的随意勾兑，而是一套有层级、有记录、有固定取酒比例的制度。法规还设有 VOS（至少 20 年平均年龄）与 VORS（至少 30 年平均年龄）标注，用于标示长期陈酿的雪莉。

## 分类

按陈酿路径与甜度，雪莉可以分为几类：

- **菲诺（Fino）**：生物陈酿，极干，酒体轻，面包、杏仁与咸鲜感。
- **曼萨尼利亚（Manzanilla）**：桑卢卡尔产的菲诺型，酒花更厚，咸味更明显。
- **阿蒙蒂亚多（Amontillado）**：先生物后氧化，琥珀色，干型，榛子与橙皮。
- **奥罗索（Oloroso）**：氧化陈酿，深色，干型，核桃、焦糖与香料。
- **Palo Cortado**：罕见的中间风格，兼具阿蒙蒂亚多的细腻与奥罗索的厚度。
- **Pedro Ximénez（PX）**：甜型，晒干葡萄酿造，葡萄干、无花果与糖浆。
- **Moscatel**：甜型，花香与蜜饯。
- **奶油雪莉（Cream）**：奥罗索加甜酒或 PX，甜度高。
- **Medium / Pale Cream**：以阿蒙蒂亚多或菲诺为基酒加甜，甜度介于干型与奶油雪莉之间。

## 感官风格

菲诺呈淡稻草色，香气以面包、杏仁、青苹果、海盐与酵母为主，入口干、酒体轻，收口干净；曼萨尼利亚的咸味与矿物感更突出。阿蒙蒂亚多颜色更深，香气从面包转向榛子、橙皮与烟草，仍是干型。奥罗索呈红木色，核桃、焦糖、咖啡与香料明显，酒体厚。PX 呈深棕色，葡萄干、无花果、糖浆与咖啡，甜度高但酸度足以支撑。

雪莉的甜度与颜色不是一一对应的：阿蒙蒂亚多可以是干型却颜色较深，奶油雪莉颜色深且甜。判断风格应看类别词，而不是只看颜色。

## 产区

雪莉产区的法定范围包括赫雷斯-德拉弗龙特拉、圣玛丽亚港、桑卢卡尔-德巴拉梅达等地。赫雷斯是行政与酒庄中心，圣玛丽亚港靠近海港，历史上是出口枢纽；桑卢卡尔以曼萨尼利亚闻名，气候更凉爽、湿度更高。

产区内部的海岸距离、土壤与酒窖微气候都会影响酒花与陈年。把“雪莉”当成一个单一风格，会忽略菲诺与奥罗索之间的巨大差异，也会忽略桑卢卡尔与赫雷斯之间的细微差别。

## 代表产品

代表性产品可以按类型理解：菲诺常以 Tío Pepe 这类经典品牌为参照；曼萨尼利亚常见 La Gitana 等桑卢卡尔酒庄；阿蒙蒂亚多与奥罗索在 Lustau、Osborne、Barbadillo 等酒庄都有长期陈年版本；PX 则常作为甜型雪莉单独装瓶，也用于调配奶油雪莉。

这些品牌只是风格坐标，不是质量排名。购买时应看类别、酒精度、陈年标注与甜度，而不是只看酒庄名气。

## 品鉴与饮用

菲诺与曼萨尼利亚应冷藏至 6–8°C，开瓶后尽快饮用，避免长时间接触空气；阿蒙蒂亚多与奥罗索适合 12–15°C，可以提前开瓶醒酒；PX 与奶油雪莉可以冷藏或常温，小杯慢饮。使用郁金香形杯或雪莉杯，先闻香气，再小口判断干度、酒体与回味。

佐餐方面，菲诺适合橄榄、杏仁、海鲜与火腿；曼萨尼利亚适合咸味小食与炸物；阿蒙蒂亚多适合汤、蘑菇与禽肉；奥罗索适合红肉、野味与陈年奶酪；PX 适合蓝纹奶酪、巧克力与甜点。本页关于雪莉的内容涉及酒精饮料；过量饮酒有害健康，未成年人不应饮酒。

## 常见误区

第一，认为雪莉都是甜酒。菲诺、曼萨尼利亚、阿蒙蒂亚多与奥罗索都可以是极干的。第二，把雪莉当成餐后酒。菲诺在西班牙常作为开胃酒。第三，认为“雪莉桶威士忌”里装的是雪莉。威士忌只是使用曾装过雪莉的桶。第四，把索莱拉当成单一年份。索莱拉是逐级调配系统，成品没有年份。第五，认为颜色越深越甜。阿蒙蒂亚多可以颜色深却是干型。第六，认为雪莉可以像普通葡萄酒一样长期开瓶存放。菲诺尤其怕氧化，应尽快喝完。

## 延伸阅读

- [加强葡萄酒](ref:fortified-wine)：雪莉所属的总体类别。
- [加强](ref:fortification)：加酒精的时机与酒精度如何决定风格。
- [索莱拉](ref:solera)：逐级取补的陈年与调配系统。
- [酒花](ref:flor)：生物陈酿的核心酵母膜。
- [帕洛米诺](ref:palomino)：雪莉的主要葡萄品种。
- [赫雷斯](ref:jerez)：雪莉的法定产区与风土背景。
