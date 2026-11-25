---
schema_version: 1
id: standard:champagne-aoc-decree
type: standard
lang: zh
slug: champagne-aoc-decree
title: 香槟原产地命名法令（Champagne AOC）
issuer: 法国国家原产地与质量研究所（INAO）主管，法令由法国政府颁布
standard_code: AOC Champagne
effective_date: "1936-06-29"
scope: 香槟法定产区的范围、允许品种、采收与压榨、瓶内二次发酵、最低陈年、瓶内压力、标签与糖度标注
summary: 香槟于 1936-06-29 获原产地命名，产区范围由 1927-07-22 法律划定，现由 INAO 管理；现行产区规范规定七个主要品种、瓶内二次发酵、无年份至少陈年 15 个月、年份至少 36 个月，并约束压力、产量与标签。
status: reviewed
revision: 1
legacy_refs: []
aliases:
  - Champagne AOC
  - 香槟 AOC
  - 香槟原产地命名
  - Appellation Champagne
tags:
  - curated
  - source-verified
  - standard
  - wine
  - champagne
  - france
  - appellation
related:
  - relation: about
    target_id: region:champagne
  - relation: about
    target_id: drink-style:sparkling-wine
  - relation: about
    target_id: term:appellation
  - relation: about
    target_id: historical-event:aoc-1935
  - relation: about
    target_id: historical-event:champagne-delimitation-1927
  - relation: about
    target_id: region:france
references:
  - key: champagne
    target_id: region:champagne
  - key: sparkling
    target_id: drink-style:sparkling-wine
  - key: appellation
    target_id: term:appellation
  - key: aoc-1935
    target_id: historical-event:aoc-1935
  - key: delimitation-1927
    target_id: historical-event:champagne-delimitation-1927
  - key: france
    target_id: region:france
sources:
  - key: cahier-des-charges
    title: Cahier des charges de l'appellation d'origine contrôlée « Champagne » (homologué par l'arrêté du 30 novembre 2022)
    url: https://www.sgv-champagne.fr/wp-content/uploads/2023/01/Cahier-des-charges-AOC-Champagne.pdf
    publisher: Comité interprofessionnel du vin de Champagne / Ministère de l'Agriculture
    published: "2022-12-10"
    note: 用于核对 1936 年初始承认、品种名单、17 个大区级村庄与 42 个一级村庄、陈年与标签规则；未复制原文。
    accessed: 2026-11-08
  - key: inao
    title: Institut national de l'origine et de la qualité — appellations d'origine contrôlée
    url: https://www.inao.gouv.fr/
    publisher: INAO
    note: 用于核对 AOC 管理体系与 INAO 的监管职责；未复制原文。
    accessed: 2026-11-08
  - key: champagne-fr
    title: Champagne.fr — appellation, ageing and labelling
    url: https://www.champagne.fr/
    publisher: Comité Champagne
    note: 用于核对无年份 15 个月、年份 36 个月的最低陈年与香槟名称使用；未复制原文。
    accessed: 2026-11-08
  - key: dgccrf
    title: Champagne — connaître le langage des étiquettes
    url: https://www.economie.gouv.fr/dgccrf/les-fiches-pratiques/champagne-connaitre-le-langage-des-etiquettes
    publisher: DGCCRF
    note: 用于核对 1927 年划界、五个省、七个主要品种、糖度标示与年份/品种标注规则；未复制原文。
    accessed: 2026-11-08
  - key: maisons-champagne
    title: Union des Maisons de Champagne — aire géographique et appellation
    url: https://maisons-champagne.com/fr/appellation/aire-geographique/
    publisher: Union des Maisons de Champagne
    note: 用于核对约 3.4 万公顷、319 个 crus 与 17+42 个村庄的行业统计；未复制原文。
    accessed: 2026-11-08
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写，依据法国产区规范、INAO、DGCCRF 与香槟行业公开资料核验；未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 产区规范原文、INAO 与香槟行业标识不在本许可内；仅作事实核验引用。
verification_scope: source-verified
---
# 香槟原产地命名法令（Champagne AOC）

香槟不是“起泡酒的通用名”，而是一个受法国原产地命名（AOC）与欧盟原产地保护（PDO）双重约束的法定产区。它的法律身份由三层文件叠成：1927 年法律划定葡萄产区，1936 年法令承认香槟原产地命名，现行产区规范（cahier des charges）再由部长令批准，规定品种、栽培、压榨、二次发酵、陈年、压力和标签。行政上，法国国家原产地与质量研究所（INAO）负责命名体系的认定与监督；行业端，香槟专业委员会（Comité Champagne）负责推广与统计。理解香槟，先要理解这套“地名—地块—工艺”的绑定关系。

![香槟原产地命名法令（Champagne AOC） 类型示意图](/media/photos/theme-wine-spirits.jpg)

图：香槟原产地命名法令（Champagne AOC） 类型示意图。图片：Doubao Seedream 5.0 AI 辅助绘制（项目自有），不是香槟原产地命名法令（Champagne AOC）的实拍。

## 从 1927 年划界到 1936 年 AOC

香槟的现代边界不是自然形成的。1927-07-22 的法律正式划定香槟葡萄产区，把“哪些市镇可以种、哪些地块可以收”的问题从省界之争转为地块之争；这项划界与 1908 年以来的多次调整一脉相承，也为此后的产区收缩埋下伏笔。1935 年，法国建立原产地控制命名制度并设立全国委员会；1936-06-29，香槟正式获得 AOC 承认。这两个时间点常被混写：1935 年是制度诞生，1936 年是香槟获得命名。

现行产区规范由 2022-11-30 的部长令批准，刊登于 2022-12-10 的《官方公报》，取代 2010 年的旧法令。规范把香槟限定为在划定区域内、按传统方法酿造的起泡酒，并把“Champagne”作为受保护的销售名称。它与法国国内的[原产地命名](ref:appellation)体系、欧盟的 PDO 登记以及 1935 年建立的 [AOC 制度](ref:aoc-1935)相互衔接；香槟之所以能在全球市场获得强保护，靠的不是单一条文，而是国内法、欧盟法与国际地理标志谈判的叠加。

## 产区、村庄与品种

香槟产区位于巴黎以东约 150 公里，横跨马恩、埃纳、奥布、上马恩与塞纳-马恩五个省，葡萄园约 3.4 万公顷，分布在 300 余个市镇（crus）。行业资料常引用 319 个 crus；历史文献在 1927 年划界后曾出现 407 个市镇的主张，最终收缩到约 3.4 万公顷、300 余个市镇。产区分为四个主要地带：兰斯山、马恩河谷、白丘与巴尔丘。村庄分级中，17 个村庄可标“grand cru”，42 个可标“premier cru”；这套分级源于历史上的 cru 评分，2010 年 INAO 取消评分表，但保留了两个名称的使用。

允许品种以七个为主：霞多丽（Chardonnay）、黑皮诺（Pinot Noir）、莫尼耶（Meunier），以及阿尔班（Arbane）、小美夜（Petit Meslier）、白皮诺（Pinot Blanc）、灰皮诺（Pinot Gris）。前三个占绝大多数；后四个是历史品种，种植面积很小，常见于少数坚持传统的老酒庄。现行规范还允许 Voltis 作为应对气候变化的适应性品种，在严格比例与协议约束下使用；具体比例以规范文本为准。采收必须人工进行，以保持果串完整、避免氧化和提前破皮。

## 二次发酵：把气泡留在瓶里

香槟的气泡来自瓶内二次发酵，而不是像多数低价起泡酒那样在大罐中完成。采收后，葡萄经轻柔压榨，只取头汁与尾汁，按规范上限控制出汁率；第一次发酵得到干型基酒，通常在不锈钢罐或橡木桶中完成。随后进行调配（assemblage），把不同村庄、品种、年份的基酒组合起来，形成酒庄风格。无年份香槟正是靠调配保持稳定风格，年份香槟则只使用单一年份的葡萄。

调配完成后装瓶，加入由酒、糖和酵母组成的“发酵液”（liqueur de tirage），密封后进行二次发酵。发酵在瓶中进行，产生二氧化碳并溶解在酒里，形成气泡；这一阶段通常持续六到八周。随后酒液与酵母残渣（酒泥）一起陈年，酵母自溶带来面包、饼干和奶油般的香气。陈年结束后，通过转瓶（remuage）把沉淀聚到瓶口，再经除渣（dégorgement）排出，最后按糖度要求加入调味液（dosage），塞上软木塞并加铁丝网。

## 陈年、压力与产量框架

最低陈年时间是最容易被简化的数字。无年份香槟从装瓶起至少陈年 15 个月，其中至少 12 个月与酒泥接触；年份香槟至少陈年 36 个月。这里的“至少”很重要：多数酒庄会延长陈年，高端 cuvée 常见三到十年甚至更久。陈年时间从装瓶（tirage）起算，不是从采收或第一次发酵起算；把“36 个月”理解成“三年桶陈”是错的，香槟的主体陈年发生在瓶中。

压力方面，按欧盟起泡酒规则，起泡酒在 20℃ 下的二氧化碳过压不得低于 3 bar；香槟作为优质起泡酒，产区规范的门槛更高，成品实际压力通常在 5 至 6 bar。具体最低值以现行产区规范与欧盟规则为准，不宜用一个孤立的数字概括所有瓶型。产量则由产区规范设定上限，并可在年份不利时由 INAO 按程序调整；规范还规定修剪方式、种植密度、最大产量和压榨比例，把“风土”转成可核查的农业参数。

## 标签：香槟这个词与糖度

“Champagne”是法定销售名称，必须清晰出现在标签上，不能只用“sparkling wine”代替。酒标还必须标明酒精度、净含量、批号、生产商或品牌、原产国（“Produit de France”）、过敏原提示以及法国要求的健康信息。年份标注要求瓶中所有葡萄都来自所标年份；品种标注要求该品种占 100%；“blanc de blancs”只能使用白葡萄品种，“blanc de noirs”只能使用黑葡萄品种，“rosé”则按规范允许的方式着色或混酿。

糖度标注是香槟标签的另一套语言。按补糖量（dosage）从低到高，常见术语包括：brut nature（低于 3 克/升，也称 non dosé）、extra brut（0 至 6 克/升）、brut（低于 12 克/升）、extra sec（12 至 17 克/升）、sec（17 至 32 克/升）、demi-sec（32 至 50 克/升）、doux（50 克/升以上）。这些数字是标签规则，不是甜味感知的全部；酸度、酒体和陈年都会改变实际口感。把“brut”理解成“完全不甜”并不准确。

## 与其他起泡酒的区别

香槟与[起泡酒](ref:sparkling)是“种”与“属”的关系：所有香槟都是起泡酒，但不是所有起泡酒都能叫香槟。核心区别有三点。第一是产地：只有在法国[香槟产区](ref:champagne)划定村庄、按规范种植和酿造的产品，才能使用这个名称。第二是工艺：香槟必须瓶内二次发酵，并在瓶中带泥陈年；西班牙卡瓦也用传统法，但产区、品种和陈年规则不同；意大利普罗塞克多在大罐中二次发酵，风格更偏向新鲜果香。第三是名称保护：“méthode champenoise”这一表述在欧盟受限制，其他产区的传统法起泡酒通常写“traditional method”或“méthode traditionnelle”。

对消费者而言，最实用的判断不是“有没有气泡”，而是看标签上的产区、品种、糖度和生产商信息。对写作者而言，最需要避免的是把香槟当成泛称，或把“传统法”与“香槟法”混为一谈。香槟的独特性来自一整套可核查的规则，而不是某个单一步骤；这也是[法国](ref:france)原产地命名体系最典型的样本之一。

## 另见与参考资料

- [香槟产区](ref:champagne)：村庄、地形与酒庄分布。
- [起泡酒](ref:sparkling)：传统法、罐式法与主要风格。
- [原产地命名](ref:appellation)：AOC 与 PDO 的法律结构。
- [AOC 制度（1935）](ref:aoc-1935)：法国命名体系的制度起点。
- [香槟区划界（1927）](ref:delimitation-1927)：边界如何被法律划定。
- [法国](ref:france)：葡萄酒法规与产区体系的整体背景。

- Cahier des charges de l'AOC « Champagne », arrêté du 30 novembre 2022, https://www.sgv-champagne.fr/wp-content/uploads/2023/01/Cahier-des-charges-AOC-Champagne.pdf
- INAO, https://www.inao.gouv.fr/
- Champagne.fr, https://www.champagne.fr/
- DGCCRF, « Champagne : connaître le langage des étiquettes », https://www.economie.gouv.fr/dgccrf/les-fiches-pratiques/champagne-connaitre-le-langage-des-etiquettes
- Union des Maisons de Champagne, aire géographique, https://maisons-champagne.com/fr/appellation/aire-geographique/
