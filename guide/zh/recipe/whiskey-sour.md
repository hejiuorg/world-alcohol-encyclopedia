---
schema_version: 1
id: recipe:whiskey-sour
type: recipe
lang: zh
slug: whiskey-sour
title: 威士忌酸配方（IBA 版本）
summary: 威士忌酸以 45 毫升波本、25 毫升鲜榨柠檬汁与 20 毫升糖浆构成酸甜骨架，蛋清可选；本文从蛋清的干摇、鲜榨柠檬的香气、摇和程度、杯型与冰，以及吧台常见的偏离讲起。
status: reviewed
revision: 3
product_id: cocktail:whiskey-sour
source_version: IBA Official Cocktails（2026-11-07 核对）
method: shake
yield:
  amount: 1
  unit: 杯
  serves: 1
ingredients:
  - ingredient_key: bourbon
    name: 波本威士忌
    amount: 45
    unit: 毫升
  - ingredient_key: lemon-juice
    name: 鲜榨柠檬汁
    amount: 25
    unit: 毫升
  - ingredient_key: sugar
    name: 白蔗糖糖浆
    amount: 20
    unit: 毫升
  - ingredient_key: egg-white
    name: 蛋清（可选，数滴）
  - ingredient_key: ice
    name: 冰
  - ingredient_key: orange-peel
    name: 橙片（半片）与橙皮（可选）
    amount: 1
    unit: 片
  - ingredient_key: cocktail-cherry
    name: 酒渍樱桃
    amount: 1
    unit: 颗
steps:
  - 把波本威士忌、鲜榨柠檬汁与糖浆量入摇酒壶；使用蛋清时一并加入。
  - 加满冰块，先短促摇几下让蛋清与酸混合，再用力摇至壶壁明显变冷。
  - 用滤冰器把酒液滤入 cobbler 杯；若加冰饮用，则先在大号古典杯中放冰再滤入。
  - 放上半片橙片与酒渍樱桃，需要时再挤橙皮释放香气。
vessel_refs:
  - vessel:highball
  - vessel:rocks-glass
tool_refs:
  - tool:cocktail-shaker
  - tool:jigger
  - tool:strainer
technique_refs:
  - technique:shaking
garnish: 半片橙片与酒渍樱桃，可选橙皮
legacy_refs: []
aliases:
  - Whiskey Sour recipe
tags:
  - curated
  - source-verified
  - recipe
  - classic-cocktail
related:
  - relation: about
    target_id: drink-style:bourbon
  - relation: about
    target_id: drink-style:whisky
  - relation: about
    target_id: guide:cocktail-basics
  - relation: about
    target_id: term:acidity
references:
  - key: cocktail
    target_id: cocktail:whiskey-sour
  - key: vessel
    target_id: vessel:highball
  - key: bourbon
    target_id: drink-style:bourbon
  - key: shaker
    target_id: tool:cocktail-shaker
  - key: strainer
    target_id: tool:strainer
  - key: shaking
    target_id: technique:shaking
  - key: ice
    target_id: guide:ice-and-temperature
  - key: cocktails-guide
    target_id: guide:cocktail-basics
sources:
  - key: iba-whiskey-sour
    title: IBA Official Cocktails — Whiskey Sour
    url: https://iba-world.com/iba-cocktail/whiskey-sour/
    publisher: International Bartenders Association
    note: 用于核对配方比例、摇和方法、杯型与装饰；未复制原文。
    accessed: 2026-11-07
  - key: iba-list
    title: IBA Official Cocktails
    url: https://iba-world.com/iba-official-cocktails/
    publisher: International Bartenders Association
    note: 用于确认该配方所属的官方鸡尾酒名单与类别；未复制原文。
    accessed: 2026-11-07
  - key: oxford-spirits
    title: The Oxford Companion to Spirits and Cocktails
    publisher: Oxford University Press
    note: 用于核对酸类鸡尾酒、蛋清与波本威士忌的一般背景；未复制原文。
    accessed: 2026-11-07
    url: https://global.oup.com/academic/product/the-oxford-companion-to-spirits-and-cocktails-9780199311132
  - key: liquid-intelligence
    title: Liquid Intelligence
    publisher: Dave Arnold / W. W. Norton
    note: 用于核对冰、温度、稀释与摇和对口感的影响；未复制原文。
    accessed: 2026-11-07
  - key: r16-thebar
    title: The Bar — Whiskey Sour
    url: https://www.thebar.com/en-us/recipes/whiskey-sour
    publisher: The Bar (Diageo)
    note: 用于核对波本、柠檬、糖浆与蛋白的配比与干摇步骤；未复制原文。
    accessed: 2026-11-07

rights:
  status: allowed
  license: CC-BY-4.0
  basis: 项目自写配方说明；用量与成品依据 IBA 公开配方，步骤与解释为项目整理，不复制原文。项目所有者于 2026-10-29 声明项目内容采用 CC BY 4.0。
  note: 第三方标准、商标、图片与引用文本不在本许可内；来源仅作核验引用。本页未使用第三方图片。
verification_scope: source-verified
---
# 威士忌酸配方（IBA 版本）

威士忌酸的来历并不出自某一家酒吧的招牌，而是从 19 世纪美国东岸港口的一类“酸酒”里长出来的：水手把烈酒、柠檬与糖混在一起，用手边现成的材料对抗单调的口粮与坏血病。谁先把它写成配方、蛋清又是哪一年被加进去，至今没有定论。本页不判这段公案，只把 IBA 公布的这一版当成可核对的坐标：45 毫升波本、25 毫升鲜榨柠檬汁、20 毫升糖浆，蛋清可选。

![威士忌酸配方（IBA 版本） 类型示意图](/media/photos/theme-wine-spirits.jpg)

图：威士忌酸配方（IBA 版本） 类型示意图。图片：Doubao Seedream 5.0 AI 辅助绘制（项目自有），不是威士忌酸配方（IBA 版本）的实拍。

## 蛋清：干摇与湿摇的分界

蛋清在这杯酒里不是装饰性的奶盖，而是一层结构。IBA 把蛋清标为可选，加与不加分别对应两种摇法：不加蛋清的版本只求降温与混匀；加蛋清的版本最好先做一次不加冰的短摇，也就是干摇，让蛋白与柠檬酸在没有冰稀释的情况下先结合，再加冰完成第二次摇和。干摇通常十几秒，目的是把蛋白打散、起泡，而不是把它打成蛋白霜。省略干摇、直接把蛋清和冰一起摇，泡沫往往薄而松散，静置一两分钟就塌下去。

干摇也有代价：没有冰的壶内摩擦小，密封不严时容易渗漏，蛋白受热也会更早凝固。因此干摇要用结实的摇壶、扣紧壶盖，摇动幅度不必大，频率要快。第二次加冰摇和才是降温主体，它的任务是让成品达到饮用温度，同时把泡沫整理得更细。两次摇和之间不必开壶检查，开盖只会让泡沫消掉。

泡沫的稳定性还取决于蛋清的新鲜度与用量。数滴是 IBA 的写法，实际操作里半枚蛋清约 15 毫升更常见，但那就已经靠近另一个版本，应在记录里注明。蛋清过多会让口感发黏、香气被隔绝；过少则泡沫撑不住杯口。巴氏杀菌蛋清可以用，但起泡能力通常弱于新鲜蛋清，需要更长的干摇。

## 45:25:20 的酸甜结构

三个数字给出的是一个可以复现的骨架：基酒 45、酸 25、甜 20。把它约成 9:5:4，能看出设计意图——酸超过基酒的一半，甜又略低于酸。这个顺序不是随手排的：先有威士忌的重量，再由柠檬把重量切开，最后用糖把切口收拢，于是入口是甜的、中段是酸的、回味又回到谷物与桶味。

比例的意义在于可比较。若你觉得成品太尖，先确认是不是用了 45:25:20；若已经按比例做还是尖，问题多半在柠檬的成熟度、糖浆的浓度或摇和稀释，而不是“比例不对”。反过来，很多酒吧的威士忌酸会做到 45:20:15 甚至 50:25:25，那是另一套酸甜坐标，喝起来更干或更圆。它们都能成立，但不能在同一页里含糊地称为“威士忌酸标准”。

糖浆浓度是一个容易被忽略的变量。以 1:1 糖水熬成的糖浆与 2:1 的浓糖浆，同样 20 毫升带来的甜度差近一倍，带入的水分也不同。IBA 页面只写糖浆 20 毫升，没有规定浓度，所以换糖浆时必须重新试味，而不是把毫升数当成甜度。

## 为什么鲜榨柠檬不可替代

柠檬汁在这杯酒里承担两件事：提供酸，提供香气。瓶装柠檬汁通常只满足前者。它的酸度可以被标定得很准，但果皮精油在加工与储存中大量损失，闻起来平、喝起来直，缺少那种一入口就窜上来的明亮感。威士忌酸的香气结构本来就靠柠檬托住波本的香草与焦糖，少了这层，成品会显得闷。

鲜榨也有讲究。柠檬的品种、成熟度与存放时间都会改变酸度；同一批柠檬里，表皮光滑、手感沉的那几个通常汁多而香。榨汁时不要把籽压破，籽与白瓤带来苦味；榨完过滤一遍果肉，口感会更干净。汁榨好后不宜久放，柑橘汁在空气中氧化，几小时后香气明显下降，最好现榨现用。

用量上还有一个常见误判：觉得酸不够就加柠檬，结果香气过载、酸度失衡。更稳妥的做法是先按 25 毫升做，酸不足时先检查是不是摇和不足导致糖没化开，或冰量太多把味道冲淡，再考虑调整。

## 摇和到什么程度算够

判断标准不该是摇多少下，而是壶壁的温度与手感。装冰后摇和，壶壁会在十几秒内明显变冷；当你握住壶身觉得冷得不想再握，通常就到了。加蛋清的版本还要看泡沫：停止摇和后静置两三秒，透过壶盖缝隙若能看到细密而稳定的泡沫层，说明蛋白已经打发到位。

摇和不足的表现是可预测的：成品偏烈、香气封闭、蛋清浮在表面成块。摇和过度的表现同样可预测：冰融化太多，酒液变薄，泡沫被稀释得站不住，喝到后半杯只剩水感。两者都不是比例错了，而是温度与稀释没控制好。

室温与冰型会改变所需时间。夏天、小冰块、未预冷的壶，都会让降温变慢；冬天、大冰块、预冷过的壶则相反。所以与其记秒数，不如记感觉：壶冷、泡沫细、杯壁起雾，这三件事同时出现就可以出杯。

## 杯型、冰与出杯温度

IBA 的写法是滤入 cobbler 杯；若加冰饮用，则先在大号古典杯里放冰再滤入。cobbler 杯是直身、容量偏大的杯子，杯口宽，适合让泡沫铺开，也方便闻香；古典杯矮而宽，放冰后酒液与冰的接触面大，稀释会持续发生。两种杯型对应两种喝法，不是随便挑一个。

杯子要不要冰镇，取决于你要多快喝完。短饮在室温杯里升温很快，预冷杯子能延缓这个过程；但冰到结霜再倒，低温会把柠檬与威士忌的香气压住，第一口反而闷。比较稳妥的做法是杯子冷藏而非冷冻，出杯前取出、擦干外壁。

冰的选择同样影响结果。摇和用硬质大冰块，融化慢、稀释可控；若用碎冰摇和，降温快但稀释也快，容易在泡沫尚未稳定时就把酒冲薄。加冰饮用的版本，杯中冰要够大够多，让酒液面略高于冰面，避免冰块堆到杯口导致第一口全是冰水。

## 在酒吧里的常见偏离

吧台实践与书面配方之间通常有三处偏离。第一是蛋清：很多酒吧默认加，甚至不询问；这时你喝到的是加蛋清版，与 IBA 的可选标注并不冲突，但要清楚它改变了口感。第二是酸甜：为了迎合本地口味，糖浆常被加到 25 毫升以上，成品更圆但更腻；也有人把柠檬加到 30 毫升，追求更刺激的酸。第三是杯型：cobbler 杯并不常见，多数酒吧用古典杯或高球杯出杯，泡沫的展开与闻香体验因此不同。

还有一类偏离是加料：滴几滴安高天娜苦精、加少量苏打水做成波士顿酸、或在泡沫上滴苦精做装饰。这些都能让成品更有层次，但它们已经越过了 IBA 这一版的边界。判断方法很简单：只要替换或新增了原料，就应该把它当作另一个版本记录，而不是在同一标题下悄悄改变。

理解偏离的意义不是为了纠正别人，而是为了知道自己喝的是什么。同一家店两次喝到不同味道，可能不是调酒师失手，而是他换了糖浆或换了柠檬。

## 失败点排查

按出现频率排，第一是酸甜失衡。柠檬太酸、糖浆太少，入口尖；糖浆太多，波本的香气被盖住。排查顺序应是先核对比例，再核对糖浆浓度，最后才怀疑摇和。

第二是蛋清不起泡。原因通常是蛋清太少、干摇省略、冰加得太早或摇和太轻。逐一排除：先用半枚蛋清、做完整干摇、再补冰摇和。

第三是稀释过度。冰太多、摇太久、杯温太高都会导致。成品表现为颜色偏淡、口感空、泡沫塌陷。

第四是滤冰不净。碎冰与果肉进杯，继续稀释并带出苦味；细网滤冰器能解决大部分问题，滤完后不要挤压壶内残冰。

第五是装饰。橙片与樱桃提前放太久会失去香气，樱桃的糖浆还会渗进酒里改变甜度。出杯前再放，是成本最低的修正。

第六是把蛋清当成必需。IBA 明写可选，不加照样成立；若因为缺蛋清而认为做不了，那是把可选项读成了硬性要求。

## 变体：从波士顿酸到黑麦版

最常被提起的变体是波士顿酸：摇和后往杯里补少量苏打水，泡沫被托起，口感更轻。它与本页版本的区别在于多了一味气泡来源，因此稀释与温度曲线都不同。

换基酒是另一条主线。黑麦威士忌带来胡椒与谷物辛香，成品更干、更有骨架；爱尔兰威士忌更柔，香气偏谷物与蜂蜜；陈年较久的波本桶味重，会压过柠檬。每一次换基酒都应写明是哪一款风格，而不是笼统写威士忌。

甜味来源也能换。蜂蜜糖浆让香气偏花香，枫糖糖浆带木质甜味，两者都会改变回味；用砂糖代替糖浆则要先把糖化开，否则杯底会残留颗粒。还有把柠檬换成青柠的做法，酸更锐、香气更绿，属于另一套柑橘方向。

加冰与不加冰同样算变体。滤冰直饮更浓、更冷、更短；加冰饮用更凉、更长、稀释持续。两者都能叫威士忌酸，但温度曲线与饮用节奏完全不同，记录时应分开。

## 另见

想理解酸甜平衡的一般原则，可以读[调酒基础](ref:cocktails-guide)；想理解冰型、温度与稀释的关系，可以读[加冰与温度](ref:ice)；想理解摇和的动作与节奏，可以读[摇和](ref:shaking)。器具方面，[摇酒壶](ref:shaker)与[滤冰器](ref:strainer)决定温度与干净度；杯型可参考[高球杯](ref:vessel)。基酒风格可以读[波本威士忌](ref:bourbon)，鸡尾酒本体见[威士忌酸](ref:cocktail)。本页的威士忌酸配方（IBA 版本）配方按一个可核对版本记录，不评价具体品牌。饮用威士忌酸配方（IBA 版本）时请适量，并遵守当地法律与安全要求。
