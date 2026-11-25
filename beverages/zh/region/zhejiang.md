---
schema_version: 1
id: region:zhejiang
type: region
lang: zh
slug: zhejiang
title: 浙江省
summary: 中国东部沿海省份，黄酒的核心产区；绍兴酒以糯米、麦曲与鉴湖水为基本组合，摊饭、淋饭与喂饭等投料路线配合加饭等产品类型形成不同风格，金华与湖州也有各自的黄酒传统。
status: reviewed
revision: 1
level: province
parent_id: region:china
country_code: CN
legacy_refs: []
aliases:
  - 浙江
  - Zhejiang
tags:
  - region
  - yellow-wine
  - china
related:
  - relation: about
    target_id: region:china
  - relation: about
    target_id: region:shaoxing
  - relation: about
    target_id: drink-style:yellow-wine
  - relation: about
    target_id: ingredient:glutinous-rice
  - relation: about
    target_id: ingredient:wheat
  - relation: about
    target_id: ingredient:water
references:
  - key: china
    target_id: region:china
  - key: shaoxing
    target_id: region:shaoxing
  - key: yellow-wine
    target_id: drink-style:yellow-wine
  - key: glutinous-rice
    target_id: ingredient:glutinous-rice
  - key: wheat
    target_id: ingredient:wheat
  - key: water
    target_id: ingredient:water
  - key: qu-making
    target_id: process:qu-making
  - key: fermentation
    target_id: process:fermentation
  - key: gbt-13662-2018
    target_id: standard:gbt-13662-2018
sources:
  - key: cada
    title: 中国酒业协会
    url: http://www.cada.cc/
    publisher: 中国酒业协会
    note: 用于核对黄酒产业与产区的公开信息；未复制原文。
    accessed: 2026-11-05
  - key: gbt-13662
    title: 国家标准全文公开系统 — GB/T 13662-2018 黄酒
    url: https://openstd.samr.gov.cn/
    publisher: 国家市场监督管理总局、国家标准化管理委员会
    note: 用于核对黄酒的术语、分类与标签要求；未复制标准原文。
    accessed: 2026-11-05
  - key: gbt-17946
    title: GB/T 17946-2008 地理标志产品 绍兴酒（绍兴黄酒）
    publisher: 国家标准化管理委员会
    published: "2008"
    note: 用于核对绍兴酒的保护范围、原料与工艺要求；未复制标准正文。
    accessed: 2026-11-05
  - key: oxford-wine
    title: The Oxford Companion to Wine — Huangjiu and Shaoxing entries
    publisher: Oxford University Press
    note: 参考其关于中国黄酒与绍兴酒的条目；未复制原文。
    accessed: 2026-11-05
    url: https://global.oup.com/academic/product/the-oxford-companion-to-wine-9780198871316
  - key: ref
    title: 《The Oxford Companion to Wine》黄酒与绍兴酒条目
    publisher: Oxford University Press
    note: 由原条目末尾参考资料迁移，未逐条复核访问日期。
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写；依据中国酒业协会公开信息、国家标准与工具书核验，不复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方标准文本、商标与图片不在本许可内；来源仅作核验引用。第三方图片已在图注中标注作者与许可。
verification_scope: source-verified
---
# 浙江省

浙江省位于中国东南沿海、长江三角洲南翼，境内平原、丘陵与海岛交错。在酒类版图上，浙江是黄酒最核心的产区：绍兴平原上的[绍兴](ref:shaoxing)以糯米、麦曲与鉴湖水酿酒，形成加饭、元红、善酿、香雪等产品体系；金华与湖州也有各自的黄酒传统。本页从省级尺度描述范围与产业，工艺细节以绍兴页为准。

![浙江省 图像](/media/photos/region-zhejiang-44cfa641.jpg)

图：浙江省。图片：EditQ，CC BY-SA 4.0，via Wikimedia Commons（[原图页面](https://commons.wikimedia.org/wiki/File:%E6%9D%AD%E5%B7%9E%E9%92%B1%E6%B1%9F%E6%96%B0%E5%9F%8E_4_(cropped).jpg)）。

## 范围与定义

浙江是[中国](ref:china)东部的一个省，省级产区页覆盖全省，但不构成一个统一的法定产区名称。真正具有地名保护意义的是“绍兴酒”，其保护范围、原料与工艺由地理标志产品标准规定。省级尺度的意义在于把绍兴、金华、湖州等地的黄酒传统放在同一行政与市场框架下观察，而不是把“浙江”当成一个质量等级。本页的 level 为 province，与市级页[绍兴](ref:shaoxing)形成层级关系。

## 历史与产业

浙江的黄酒与稻作、水运和城镇消费紧密相关。唐宋以来，绍兴一带的酿酒记载渐多；明清时期，绍兴酒沿运河与海路销往南北，成为重要的商品酒。20 世纪，公私合营与国营整合把分散的酒坊并入工厂，产量与标准化程度提高；改革开放后，品牌化、年份酒与礼品市场又改变了产品结构。

金华的传统以寿生酒为代表。明代酿酒师以精白糯米为原料，红曲与麦曲并用，采用喂饭法分缸酿制，酒色偏琥珀，风味醇厚。湖州在历史文献中有乌程酒的记载，地方上还有以白米、白面、白水酿制的冬酿白酒传统。这些例子说明，浙江黄酒并非只有绍兴一条线索。

## 自然与工艺条件

浙江属亚热带季风气候，夏季湿热、冬季温和，降水充沛。湿度与温度影响制曲、发酵与陈酿：高温高湿有利于微生物生长，也增加酸败风险，因此曲房与酒缸需要通风、控温与分批投料。

水是浙江黄酒的关键变量。鉴湖水体的硬度与矿物组成适中，被绍兴酿酒业视为核心水源；金华、湖州则依赖本地井水与河湖水。水源差异会改变糖化速度、发酵温度与酒体口感。

原料以[糯米](ref:glutinous-rice)为主，[小麦](ref:wheat)制成麦曲，[水](ref:water)参与糖化与发酵。[制曲](ref:qu-making)培养霉菌与酶系，酒药提供根霉与酵母。传统投料路线包括淋饭法、摊饭法与喂饭法：淋饭法用冷水快速淋凉米饭，多用于制备酒母；摊饭法把蒸饭摊开自然冷却，适合长周期发酵；喂饭法在发酵过程中分次追加米饭，控制糖分释放。加饭酒则是在元红基础上增加米饭比例的产品类型，不是与前三者并列的独立工序。[发酵](ref:fermentation)多在陶缸中进行，靠开耙散热与换气，随后压榨、澄清、煎酒与陶坛陈贮。

## 风格与代表

绍兴酒的产品结构常以元红、加饭、善酿、香雪四类概括：元红偏干，加饭为半干且酒体更厚，善酿以酒代水偏半甜，香雪以糟烧酒代水更甜。花雕多指坛装与彩绘包装形式，具体糖分仍要看标签。浙江黄酒的共同特征是米香、麦曲香与陈香，差异主要来自配料比例、曲种与陈年时间。

金华寿生酒以红曲与麦曲并用，风格偏醇厚；湖州冬酿白酒以“三白”为原料，口感清爽。按 GB/T 13662-2018《黄酒》的分类，产品按糖分与工艺标注类型与酒精度；地理标志产品绍兴酒另有专门标准约束范围与工艺。

## 常见误区

第一，认为浙江只有绍兴黄酒。金华、湖州也有各自的传统。
第二，把加饭当成一种独立酿造法。加饭描述的是增加米饭比例的产品，投料仍走摊饭或喂饭路线。
第三，把花雕当成最高等级。花雕更多是包装与陈酿形式的俗称。
第四，认为颜色越深越老。颜色受曲种、容器、焦糖色与陈年影响，不能单独判断年份。
第五，把地理标志当成质量排名。它证明范围与工艺符合性，不替代品鉴与价格判断。

浙江是黄酒核心产区，绍兴酒以糯米、麦曲与鉴湖水为基本组合，摊饭、淋饭与喂饭等投料路线配合加饭等产品类型形成不同风格；金华与湖州也有各自的黄酒传统。浙江黄酒不是只有绍兴一种，读产品时要看产地、原料、糖分与陈年，而不是只看省名。绍兴之外，金华与湖州也有各自的曲种、饭法与产品类型；把浙江黄酒全部归入绍兴风格，会让产地与工艺差异消失。读标签时先看产地与产品类型，再谈陈年。

## 延伸阅读

- [中国](ref:china)：国家层级的产区与制度背景。
- [绍兴](ref:shaoxing)：绍兴酒的原料、工艺与产品结构。
- [黄酒](ref:yellow-wine)：黄酒的定义、分类与酿造总览。
- [糯米](ref:glutinous-rice)与[小麦](ref:wheat)：浙江黄酒的主料与麦曲原料。
- [水](ref:water)：鉴湖水与地方水源对风格的影响。
- [制曲](ref:qu-making)与[发酵](ref:fermentation)：麦曲与陶缸发酵的核心环节。
- [GB/T 13662-2018《黄酒》](ref:gbt-13662-2018)：通用黄酒产品标准。

**关键事实。**

| 项目 | 内容 |
| --- | --- |
| 一句话定位 | 中国东部沿海省份，黄酒的核心产区；绍兴酒以糯米、麦曲与鉴湖水为基本组合，摊饭、淋饭与喂饭等投料路线配合加饭等产品类型形成不同风格，金华与湖州也有各自的黄酒传统 |
| 层级 | 省/大区 |
| 所属 | 中国 |
| 国家代码 | CN |

**来源与边界。** 本页关于「浙江省」的关键事实，主要由以下来源交叉核对：中国酒业协会（黄酒产业与产区的公开信息）、国家市场监督管理总局、国家标准化管理委员会（黄酒的术语、分类与标签要求；未复制标准原文）、国家标准化管理委员会（绍兴酒的保护范围、原料与工艺要求；未复制标准正文）等 5 条来源。价格、批次与状态会变，涉及这些字段时以页面所列来源的最新版本为准。正文为项目自写，来源只作核验，不复制原文。

**并读。** 把「浙江省」与「中国」、「绍兴市」、「黄酒」放在一起读时，先确认它们是同一层级还是上下游关系：先确认边界与法定分类，再比较气候、土壤、海拔与代表酒款。本页负责给出产区的基本坐标，对照条目补上具体案例与差异；读完再回到本页，才能分清哪些差别属于产区本身，哪些只是产地、批次或品牌选择。

**适用边界。** 对「浙江省」而言，产区边界、面积与法定分类会随法规更新；气候描述是长期趋势，不是某一年的天气预报。
