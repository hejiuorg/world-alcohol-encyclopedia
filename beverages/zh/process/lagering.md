---
schema_version: 1
id: process:lagering
type: process
lang: zh
slug: lagering
title: 拉格低温贮酒
summary: 主发酵之后的低温贮酒工序：酵母回收双乙酰、悬浮物沉降、硫化物逸散并完成自然碳酸化；温度曲线、时间与溶氧共同决定拉格啤酒的干净度与保质期。
status: reviewed
revision: 2
legacy_refs: []
aliases:
  - 低温贮酒
  - 拉格陈贮
  - Lagering
tags:
  - curated
  - source-verified
  - process
  - beer
related:
  - relation: about
    target_id: drink-style:beer
  - relation: about
    target_id: process:fermentation
  - relation: about
    target_id: process:malting
references:
  - key: beer
    target_id: drink-style:beer
  - key: fermentation
    target_id: process:fermentation
  - key: malting
    target_id: process:malting
  - key: c-extra-1
    target_id: process:blending
sources:
  - key: oxford-beer
    title: The Oxford Companion to Beer — Lagering entries
    publisher: Oxford University Press
    note: 参考其关于拉格酵母、低温贮酒与双乙酰还原的条目；未复制原文。
    accessed: 2026-11-05
    url: https://global.oup.com/academic/product/the-oxford-companion-to-beer-9780195367133
  - key: britannica-brewing
    title: Encyclopaedia Britannica — Brewing
    url: https://www.britannica.com/technology/brewing
    publisher: Encyclopaedia Britannica
    note: 参考其关于底部发酵与低温贮存的描述；未复制原文。
    accessed: 2026-11-05
  - key: brewers-association
    title: Brewers Association — Brewing resources
    url: https://www.brewersassociation.org/
    publisher: Brewers Association
    note: 用于核对拉格发酵、双乙酰还原与低温贮酒的行业表述；未复制原文。
    accessed: 2026-11-07
  - key: ref
    title: The Oxford Companion to Beer — Lagering entries（Oxford University Press）。
    publisher: 未注明
    note: 由原条目末尾参考资料迁移，未逐条复核访问日期。
rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写，依据酿造工具书与百科资料核验，未复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方文本、商标与图片不在本许可内；来源仅作核验引用。
verification_scope: source-verified
applies_to_refs:
  - drink-style:beer
---
# 拉格低温贮酒

拉格贮酒（lagering）排在主[发酵](ref:fermentation)结束之后、过滤与灌装之前。德语 lagern 的原意是“存放”，这个工序把酒液送入接近冰点的环境，让仍在进行的酵母代谢、胶体沉降与碳酸化慢慢收尾。它既不是单纯的降温，也不是陈酿的同义词，而是一段有明确终点判据的工艺窗口。

![拉格低温贮酒 图像](/media/photos/process-lagering-7d0e4091.jpg)

图：拉格低温贮酒。图片：Lars Curfs ( Grashoofd )，CC BY-SA 3.0 nl，via Wikimedia Commons（[原图页面](https://commons.wikimedia.org/wiki/File:Bitburger_Glass.JPG)）。

## 工序定位

在拉格啤酒的流程里，主发酵负责把麦汁中的糖转化为乙醇与二氧化碳，贮酒负责处理主发酵遗留的中间产物：双乙酰、乙醛、硫化物，以及悬浮的酵母与蛋白质-多酚复合物。工序起点通常在主发酵降糖接近终点、酵母开始絮凝之时；终点则由双乙酰含量、澄清度与碳酸化水平共同判定。把它与艾尔的暖区熟成混为一谈，会误判温度与时间的取值逻辑。

## 步骤与参数

典型流程是：主发酵在 8–12 °C 下进行约 7–14 天，随后升温至 12–18 °C 做 1–3 天的双乙酰还原，也称暖休止，再降至 −1 至 4 °C 贮酒 2–6 周；部分高浓度或深色产品会延长到 8–12 周。上述区间取自本页参考资料所列酿造工具书与行业协会资料的常见表述，具体酒厂仍会按酵母菌株与罐体传热调整。罐压维持在 0.8–1.2 bar 可让二氧化碳留在酒中；转罐时的溶解氧宜尽量低于 50 μg/L。此阶段 pH 通常落在 4.0–4.6，乙醇体积分数 4–6%。

## 机制：酵母回收与沉降

双乙酰来自缬氨酸合成的旁路。酵母先分泌 α-乙酰乳酸，它出胞后经非酶脱羧生成双乙酰，再被酵母还原酶转化为乙偶姻与 2,3-丁二醇，后两者的风味阈值高得多。低温让还原变慢，因此温度过低而时间不足时，双乙酰会滞留。沉降遵循斯托克斯定律：颗粒半径越大、黏度越低、对流越弱，沉降越快。低温提高黏度，却让酵母絮凝更彻底，两种效应相互抵消，最终仍靠时间取胜。

## 设备与变体

传统酒窖使用卧式木桶或铝桶，靠自然冰水降温；现代工厂多用带冷却夹套的立式锥形罐，一罐完成主发酵与贮酒，锥底收集酵母。变体包括单罐法与两罐法，是否过滤、是否离心、是否用 PVPP 或硅胶吸附多酚，以及德国传统的冷贮加自然碳酸化路线。设备差异主要体现在温度梯度、酵母沉降路径与氧摄入量上：罐体越高，静水压越大，酵母越容易沉降，但冷却夹套造成的上下温差也越明显。

## 失败模式与判断

常见失败有四种。其一，双乙酰残留，闻起来像黄油或爆米花，感官阈值约在 0.02–0.1 mg/L 之间且因人而异；其二，硫化物，硫化氢像臭鸡蛋，二甲基硫像煮玉米，多与酵母营养不足或铜离子缺乏有关；其三，氧化，纸板味来自反式-2-壬烯醛，常因转罐曝气或灌装溶氧过高；其四，澄清不良，表现为过滤压差上升或浊度高于 1 EBC。判断时应把感官、浊度与溶解氧数据放在一起看，而不是只凭“放得够久”。

## 对风味的影响

贮酒让香气从“发酵味”转向“成品味”。双乙酰下降后，麦芽的谷物甜与酒花的草本、柑橘调更清楚；硫化物逸散后，青苹果与蔬菜感减弱；酵母沉降让苦味收得干净，口感更利落。相反，贮酒不足会留下奶油般的黏腻；贮酒过度而溶氧失控，则让酒花香气衰减，出现纸板与雪莉酒般的氧化味。对深色拉格，适度氧化也可能带来坚果与焦糖层次，这属于风格选择，而不是普遍优点。

## 对稳定性的影响

低温让酒石酸氢钾与草酸钙的溶解度下降，部分晶体在罐内析出，减少瓶内冷混浊。蛋白质-多酚复合物在低温下继续聚集，配合硅胶或单宁处理可延长保质期。乙醇与低 pH 本身抑制多数腐败菌，但乳酸菌与野生酵母仍可能在残糖存在时活动，因此贮酒不能替代过滤或巴氏杀菌。碳酸化稳定性取决于压力与温度的平衡，灌装前的压力骤降会造成泡沫粗糙、杀口减弱。

## 常见误区

第一，把贮酒当作“越冷越好”。温度低于冰点会结冰，损伤酵母并改变胶体状态。第二，把双乙酰还原完全寄希望于长时间低温，而忽略暖休止。第三，认为所有拉格都必须贮酒数月，实际上轻酒体淡色拉格数周即可。第四，把“不过滤”等同于“更天然”，忽略澄清度与微生物稳定的取舍。第五，把贮酒罐当作普通储罐，忽视压力控制与氧摄入。

拉格低温贮酒发生在主发酵之后，核心是让酵母回收双乙酰、悬浮物沉降、硫化物逸散，并在低温下完成自然碳酸化。温度过高或时间不足，双乙酰会留下黄油味；时间过长、溶氧控制不好，又可能损失新鲜度。它是拉格干净口感的收尾工序，不是“把酒放冷”那么简单。

相关条目：[调配](ref:c-extra-1)。

## 另见

- [啤酒](ref:beer)：拉格所属的饮料酒类别与风格框架。
- [发酵](ref:fermentation)：乙醇与副产物生成的上游代谢路径。
- [制麦](ref:malting)：麦芽糖谱与酵母可发酵性对贮酒效果的约束。

补充阅读：[调配](ref:c-extra-1)。

对照阅读：[啤酒](ref:beer)、[制麦](ref:malting)。

**关键事实。**

| 项目 | 内容 |
| --- | --- |
| 一句话定位 | 主发酵之后的低温贮酒工序：酵母回收双乙酰、悬浮物沉降、硫化物逸散并完成自然碳酸化；温度曲线、时间与溶氧共同决定拉格啤酒的干净度与保质期 |
| 适用对象 | 啤酒 |

**来源与边界。** 本页关于「拉格低温贮酒」的关键事实，主要由以下来源交叉核对：Oxford University Press（提供关于拉格酵母、低温贮酒与双乙酰还原的条目）、Encyclopaedia Britannica（提供关于底部发酵与低温贮存的描述）、Brewers Association（拉格发酵、双乙酰还原与低温贮酒的行业表述）等 4 条来源。价格、批次与状态会变，涉及这些字段时以页面所列来源的最新版本为准。正文为项目自写，来源只作核验，不复制原文。

**并读。** 把「拉格低温贮酒」与「啤酒」、「发酵」、「制麦」放在一起读时，先确认它们是同一层级还是上下游关系：先确认目的与步骤，再比较设备、温度、时间与副产物。本页负责给出工艺的基本坐标，对照条目补上具体案例与差异；读完再回到本页，才能分清哪些差别属于工艺本身，哪些只是产地、批次或品牌选择。
