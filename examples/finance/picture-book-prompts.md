# 《金流城漫游记》金融绘本 Prompt 手册

Nov 18, 2026 · @Sylvan

## 使用说明

这本绘本把整个金融行业画成一座城市——**金流城**。在这座城里，**钱是一种会流动的金色的水**：从家家户户的储蓄里汇成水库，经过银行的泵站和央行的水闸，流向工坊和工厂，再以利润的形式回流。比特城的老朋友 Sylvan 和向导机器人比特又出发了。全书 41 页，每页分三部分：

- **配文**：印在绘本上的中文文字，讲清这一页的本质。
- **画面要点**：这幅图必须让人一眼看懂的那件事，用来检查出图是否合格。
- **Prompt**：直接复制给绘图模型的英文提示词，已包含画风和角色描述，每段可单独使用。

### 出图步骤

1. **先定妆**：用下一节的两段定妆图 prompt 生成 Sylvan 和比特。如果你已经为《比特城漫游记》生成过定妆图，直接复用那两张作参考图，两本书的主角就是同一个人。
2. **逐页复制 Prompt**，每页都上传两张定妆参考图。
3. **文字后期加**：所有 prompt 都要求不画文字、不画数字和货币符号。金融场景里的报价屏、账本很容易被模型画出乱码数字，所以一律用箭头、柱形、图标代替。
4. **画幅**：内页 4:3 横版，封面和封底 3:4 竖版。
5. **配色**：本书在比特城的色板上加入了暖金色和深海军蓝，用来表达“金钱的流动”；画笔和质感与上一本保持一致。
6. **读法**：配合《金融行业速通手册》一起读，绘本里的比喻是为了抓住本质，不是完整定义。全书讲行业结构，不构成投资建议。

### 全书目录

| 页 | 主题 | 城市里的比喻 |
| --- | --- | --- |
| P1 | 封面 | 金色水流贯穿的城市 |
| P2 | 金融在做什么 | 把沉睡的水引到干渴的磨坊 |
| P3 | 原理一：时间有价格 | 种子与果树 |
| P4 | 原理二：风险可以定价和转移 | 一万人共撑一把伞 |
| P5 | 原理三：信用是杠杆 | 一根撬起巨石的长杆 |
| P6 | 原理四：价格就是信息 | 万人投票的风向标 |
| P7 | 全景：资金的循环 | 剖面城市 |
| P8 | 概率与统计 | 风险的形状 |
| P9 | 会计三张表 | 一家店的三张照片 |
| P10 | 宏观经济 | 城市的天气与四季 |
| P11 | 货币是什么 | 信任的凭证 |
| P12 | 银行创造货币 | 不断放大的回声 |
| P13 | 央行与利率 | 水闸总管 |
| P14 | 支付清算 | 城市的运河网 |
| P15 | 股票 | 切成小块的果园 |
| P16 | 债券 | 长短不一的借条 |
| P17 | 交易所与价格发现 | 大集市的报价墙 |
| P18 | 衍生品 | 农夫与面包师的约定 |
| P19 | 杠杆与泡沫 | 越吹越大的气球 |
| P20 | 金融危机 | 挤兑与多米诺 |
| P21 | 分散投资 | 鸡蛋和篮子 |
| P22 | 指数与主动 | 买下整片森林 |
| P23 | PE 与 VC | 种子园丁与老宅翻新 |
| P24 | 估值 | 望向未来的望远镜 |
| P25 | 风险管理 | 暴风雨模拟池 |
| P26 | 保险与精算 | 巨大的公共雨伞 |
| P27 | 监管与合规 | 堤坝与裁判 |
| P28 | 行为金融 | 羊群与镜子 |
| P29 | 金融科技 | 手机里的银行 |
| P30 | 量化交易 | 机器交易员 |
| P31 | 区块链 | 人人都有一份的账本 |
| P32 | AI 进入金融 | 不睡觉的助理 |
| P33 | 工种大地图 | 全城职业分布 |
| P34 | 帮企业找钱的人 | 媒人与桥梁工 |
| P35 | 替别人管钱的人 | 园丁、船长与管家 |
| P36 | 交易与量化的人 | 集市里的叫价人和钟表匠 |
| P37 | 守门人 | 堤坝巡逻员、审计师、精算师 |
| P38 | 市场规律 | 潮汐与台阶 |
| P39 | 学习之路 | 从广场出发的七条路 |
| P40 | 塔顶俯瞰 | 一句话看懂全城 |
| P41 | 封底 | 夜晚的金流城 |

## 全局画风与角色设定

### 风格段（每页 prompt 的结尾都是它）

```text
Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### 主角定妆图：Sylvan

他不懂金融，但会追问“钱到底从哪里来、去哪里了”。他的反应就是读者的反应。

```text
Character design sheet of Sylvan, a handsome Chinese man in his late twenties with short, neat, slightly textured black hair, warm brown eyes, clean-shaven, no glasses, a tall athletic build, a black leather coat over a white shirt, dark trousers, brown ankle boots and a brown leather satchel with a small notebook sticking out. Show him in front view, side view and back view, plus four facial expressions in small bust portraits: curious, puzzled, surprised, delighted. Plain cream paper background, even spacing, no props. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, no text, no letters, no logos, 4:3 landscape.
```

### 向导定妆图：比特

```text
Character design sheet of Bit, a small floating egg-shaped white robot about the size of a house cat, with a rounded dark teal screen for a face showing two simple glowing friendly eyes, a short antenna with a glowing coral tip, two tiny stubby arms, and a soft blue hover-glow underneath instead of legs. Show front view, side view, three-quarter view, plus five screen-face expressions: happy eyes, thinking (three dots), pointing (a small arrow shape), surprised (wide circles), proud (closed smiling eyes). Plain cream paper background, even spacing. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, no text, no letters, no logos, 4:3 landscape.
```

### 城市设定：金流城长什么样

全书里，**钱 = 发光的金色水流**。城市按资金的流向分层：

| 层 | 画面元素 | 代表什么 |
| --- | --- | --- |
| 岩床 | 刻着账本格子纹样的石板 | 会计与数学 |
| 万家屋顶的集水槽 | 每户人家屋顶接下的一点金水 | 家庭储蓄 |
| 巨大水库 | 汇集全城金水的水库 | 汇集起来的资金（银行存款、养老金、保险金） |
| 水闸塔 | 城中央控制水位的高塔 | 央行与利率 |
| 泵站大厦 | 把水库的水泵向各处 | 银行 |
| 运河网 | 穿行全城的金色运河和小船 | 支付清算 |
| 大集市广场 | 带巨大报价墙的广场 | 交易所与资本市场 |
| 工坊区 | 被金水驱动的磨坊和工厂 | 企业 |
| 堤坝与巡逻岗 | 环绕水系的堤坝 | 监管 |
| 大雨伞亭 | 可以遮住一片街区的巨伞 | 保险 |
| 齿轮钟塔 | 发光齿轮和屏幕组成的玻璃钟塔 | 金融科技与量化 |

### 通用反向提示词

```text
text, letters, numbers, digits, currency symbols, price tickers with numbers, watermark, logo, real bank or brand names, photorealistic, glossy 3D render, dark or gloomy mood, cluttered unreadable composition, distorted hands, extra limbs, inconsistent character design
```

## 序章 · 走进金流城

### P1 · 封面

**配文**：《金流城漫游记》——一座城市，看懂钱怎么流动。我们不讲公式，也不荐股，只讲钱从哪里来、流到哪里去、谁在中间修渠、谁在守堤。

**画面要点**：一眼看出“金色的水在城里循环流动”。

```text
Book cover illustration, 3:4 portrait. A grand view of Coinflow City at dawn, a city where money is shown as glowing golden water. Golden rain falls softly onto thousands of rooftops, each roof collecting a little golden water into small barrels; pipes carry it down into a vast shimmering reservoir; at the center a tall stone sluice tower with great gates controls the water level; from there golden canals with tiny boats wind through the city into mills and factories whose waterwheels turn; a lively market plaza with a giant board of up and down arrows; sturdy levees with patrol huts line the waterways; a giant umbrella pavilion shelters one district; an elegant glass clock tower full of glowing gears rises above it all. In the foreground on an arched stone bridge, Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) leans on the railing looking at the city, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) floats beside him, pointing toward the sluice tower. Leave a large clean empty band across the top third for the book title. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle dawn light, no text, no letters, no numbers, no logos, no currency symbols, 3:4 portrait.
```

### P2 · 金融到底在做什么

**配文**：Sylvan 在河边看到一幅奇怪的景象：左岸的人家，屋顶的桶里都装着金色的水，静静地躺着；右岸有一座磨坊，面包师拿着扩建的图纸，水轮却因为没水停着。比特说：“金融就是修一条渠，把睡着的水引到能让它转动磨盘的地方。”存钱的人拿到利息，磨坊主扩大了生产，中间修渠的人收一点过路费。银行、券商、基金、保险——所有金融机构，本质上都是这条渠的不同部分。渠修得好，整座城都转得更快；渠修坏了，水就会泛滥。

**画面要点**：左边闲置的金水，右边干渴的磨坊，中间正在修的渠。

```text
A wide riverside scene. On the left bank, a row of cozy houses whose rooftop barrels are full of still, softly glowing golden water, the owners relaxing on porches. On the right bank, a wooden mill with a large waterwheel standing completely still and dry, a hopeful baker in an apron holding up a rolled blueprint of a bigger bakery. In the middle, a team of workers in teal overalls is digging and lining a new canal that connects the barrels to the mill; the very first trickle of golden water has just reached the waterwheel, which is beginning to turn. Beside the canal stands a tiny toll booth where a keeper collects a single drop from the passing stream. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands on the canal bank with a curious expression, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) traces the new canal's path with a beam of light. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P3 · 原理一：时间有价格

**配文**：比特给 Sylvan 两个选择：今天拿一颗金苹果，或者明年拿一颗。他选了今天——因为今天的种子种下去，明年能长出一棵树。今天的钱能拿去生钱，所以比明天的钱值钱；利息，就是“借用时间”的价格。反过来，未来的钱要打一个折才能换成今天的价值，这叫折现。比特说：“一栋楼、一家公司、一张债券值多少钱，算法都一样：把它未来能带来的钱，一笔一笔折回今天。”这是金融最根本的一条规律。

**画面要点**：一颗种子随时间长成果树；远处的苹果看起来更小、更模糊（未来的钱要打折）。

```text
A sunlit orchard path stretching from the foreground into the distance like a timeline. In the foreground, a single glowing golden seed is being planted in fresh soil; a little further along the path stands a young sapling; further still a sturdy tree heavy with many golden apples. Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) holds out a single shining golden apple right here in its tiny hands, while far away on a hazy hilltop another identical golden apple sits on a pedestal, appearing much smaller and slightly faded by the distance and mist, showing that future value looks smaller today. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) kneels by the freshly planted seed with a thoughtful smile, having chosen the apple today. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P4 · 原理二：风险可以被定价、拆分和转移

**配文**：雨季来了。一户人家承受不起房子被冲毁；但一万户人家每家出一点金水，共同撑起一把巨伞，谁家遭了殃，就从伞下的库存里赔给谁。这就是保险：把一个人扛不住的风险，分给很多人一起扛。港口边，一位商人把货分散装上十条船，沉一条也不致命——这就是分散投资。比特说：“风险没法消失，但可以被拆开、被定价，被转移给愿意承担它的人。”而愿意承担更多风险的人，会要求更高的回报——这是整个金融行业的定价铁律。

**画面要点**：很多人共撑一把巨伞（保险）；货物分载十条船（分散）。

```text
A rainy-season scene in a neighborhood of Coinflow City. A gigantic umbrella spreads over the whole district, its canopy held up by dozens of poles, each pole supported by a different family; every family drops a small amount of glowing golden water into a central round vault beneath the umbrella's handle. At the edge of the district, one house has been hit by a fallen tree, and a stream of golden water flows from the vault to help rebuild it. In the background, a harbor where a merchant's cargo is split across ten small sailboats heading out to sea; one boat is sinking in a squall while the other nine sail on safely. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands dry under the giant umbrella watching the rain, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) points toward the ten boats. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, soft rainy light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P5 · 原理三：信用是杠杆

**配文**：一块巨大的金色石头挡在路上，一个人推不动。比特递来一根长杆，Sylvan 轻轻一压，巨石就动了。“信用就是这根杆，”比特说，“别人相信你会还，你就能用一块钱的本金，办十块钱的事。”企业借钱建厂、家庭贷款买房，都是在用杠杆。但杠杆是双向的：支点一滑，巨石会反过来砸下。支点，就是人们之间的信任。几乎每一次金融危机，核心都是杆子太长、信任突然崩塌。

**画面要点**：小力气撬动巨石；角落里另一根更长的杠杆支点正在崩裂。

```text
A mountain road in warm light. A huge glowing golden boulder blocks the path. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) presses down lightly on the end of a long wooden lever resting on a stone fulcrum carved in the shape of two clasped hands, and the massive boulder lifts with ease. Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) hovers near the fulcrum, pointing at the clasped-hands stone. In a small inset vignette on the right, another figure uses an extremely long, thin lever on a fulcrum that is visibly cracking, and the boulder is beginning to tip back toward him, workers nearby running for cover. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P6 · 原理四：价格就是信息

**配文**：集市中央立着一座巨大的风向标。城里的每个人都在往一个透明的大漏斗里扔石子：觉得天要变好的扔金色的，觉得要变坏的扔蓝色的。风向标随着石子的多少不停地转。比特说：“这就是市场价格。它把成千上万人的判断，压缩成一个指针。”谁能更快、更准地看懂天气，谁就能赚到钱；但一个消息一旦人人都知道，它就已经在指针里了。这就是为什么从报纸上看到的“好消息”，往往已经赚不到钱。

**画面要点**：众人投石 → 机关 → 风向标转动；信使带着消息赶到时，人群已经有了反应。

```text
A bustling market square in Coinflow City. At the center rises a tall tower topped with a giant ornate brass weathervane shaped like an arrow. Around its base, crowds of townspeople toss small pebbles into a huge transparent funnel: golden pebbles from those who expect fair weather, deep blue pebbles from those who expect storms; the funnel feeds a visible system of gears that turns the weathervane, which currently points toward the gold side. On the edge of the square, a messenger on a galloping horse arrives waving a sealed letter, but many people near the front have already turned and are reacting, showing the news is already known. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) holds a golden pebble, considering, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) floats beside him watching the weathervane turn. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P7 · 全景：资金的循环

**配文**：爬上山坡，Sylvan 第一次看清了金流城的全貌。金色的雨落在万家屋顶，是家庭的储蓄；屋顶的水汇进巨大的水库，是银行存款、养老金和保险金；城中央的水闸塔是央行，控制着水位；泵站大厦是银行，把水泵向各处；运河网是支付清算；广场上的大集市是交易所；工坊区的水轮是企业，水推动它们生产，再化作金色的雾气升上天空，变成新的雨。堤坝是监管，巨伞是保险，齿轮钟塔是金融科技。比特说：“记住这个循环。之后的每一个概念、每一种职业，都只是这条水路上的某一段。”

**画面要点**：一个完整的闭环：雨 → 屋顶 → 水库 → 水闸 → 泵站 → 运河 → 水轮 → 雾气 → 雨。这张图是全书的“地图”。

```text
A grand panoramic cutaway of Coinflow City showing a complete circular flow of glowing golden water. Golden rain falls onto thousands of rooftops on the left, each roof collecting it into small barrels; pipes carry it down into a vast reservoir; at the center a tall stone sluice tower with adjustable gates controls the water level, a keeper at the top turning a great wheel; next to it, pump-station buildings push the water out into a network of golden canals with tiny boats carrying cargo; the canals run past a lively market plaza with a giant board of up and down arrows, and into an industrial district of mills and factories whose waterwheels turn; above the factories, golden mist rises into the sky, forms clouds, and falls again as rain on the rooftops, closing the loop. Sturdy levees with patrol huts line the waterways, a giant umbrella pavilion shelters one district, and a glass clock tower full of glowing gears stands on a hill. Beneath the city, a bedrock layer of stone slabs carved with ledger-grid patterns. On a grassy lookout hill in the foreground, Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) looks through brass binoculars, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) traces the circular flow in the air with a ribbon of light. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

## 第一章 · 语言：概率、会计与宏观

比特先带 Sylvan 学三种“语言”。概率是描述风险的语言，会计是描述公司的语言，宏观经济是描述整座城市的语言。不懂这三种语言，就听不懂金流城里任何人说话。

### P8 · 概率与统计：风险的形状

**配文**：岩床下有一间“概率工坊”。一块巨大的钉板上，成千上万颗金珠从顶上落下，撞过一排排钉子，最后在底部堆成一座中间高、两边低的小山。“单独一颗珠子落在哪里，谁也说不准；但一万颗珠子堆出的形状，几乎每次都一样。”金融里的风险就是这样：一笔贷款会不会违约说不准，但一万笔贷款里大概有多少会违约，可以算得相当准。银行、保险、量化都靠这一点吃饭。但比特也指着两端那几颗发红光的珠子说：“极端情况出现得比教科书说的更频繁。很多机构就是倒在它们身上的。”

**画面要点**：大量金珠落下后堆成钟形山；两端的少数珠子被特别标出。

```text
A cozy underground workshop carved into stone, lit by warm lanterns. Against the back wall stands a huge wooden pegboard taller than a house, with rows and rows of brass pegs; thousands of glowing golden beads pour in from a hopper at the top, bounce down through the pegs, and settle into vertical slots at the bottom, forming a smooth hill shape that is tallest in the middle and low at both sides. A few beads in the far left and far right slots glow coral red, and a small spotlight shines on them. Tiny workers in aprons tally the beads with abacus-like counters without any numbers. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) watches one bead fall with an uncertain expression, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) points at the coral-red beads at the edges. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, warm lantern light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P9 · 会计：一家店的三张照片

**配文**：街角面包店的老板递给 Sylvan 三幅画。第一幅是此刻店里的全部家当：烤炉、面粉、柜台里的钱，还有欠供应商的账——这是资产负债表。第二幅是一整年的成绩单：卖了多少面包、花了多少成本、最后赚了多少——这是利润表。第三幅是钱包的流水：哪天真金白银进来、哪天付出去——这是现金流量表。比特说：“利润表上赚钱，不代表钱包里有钱。很多公司是‘赚着钱倒闭’的：货卖出去了，款还没收回来，工资却要先发。”三张表一起看，才能看清一家公司的真相。会计是商业世界的通用语言，也是识破财务造假的第一道防线。

**画面要点**：三幅画并排：此刻的家当、一年的进出、钱包的流动；第三幅里货架满但钱包空。

```text
A warm cutaway of a charming corner bakery. The cheerful baker in a flour-dusted apron holds up three large framed paintings side by side for the viewer. Painting one: a still-life snapshot of everything in the shop at this moment — ovens, sacks of flour, a cash drawer of glowing golden water, and a pinned IOU note to the flour supplier — all resting on a perfectly balanced brass scale. Painting two: a long horizontal scroll showing a full year passing from spring to winter, with loaves going out the door and flour sacks coming in, ending in a modest pile of gold at the far end. Painting three: a leather wallet with golden water flowing in and out over the seasons, and at one moment the wallet is almost empty even though the shelves behind it are full of bread and an unpaid delivery cart is still on the road. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) studies the third painting with a surprised look, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) points from the full shelves to the empty wallet. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P10 · 宏观经济：城市的天气与四季

**配文**：在屋顶气象台上，比特给 Sylvan 看一台巨大的“天气仪”：经济增长是阳光，通胀是气温，利率是风，失业是雨。经济像四季一样有周期：繁荣时大家借钱扩张，热过头就通胀；水闸总管把闸门抬高，经济降温，有时降过了头就进入寒冬。比特说：“没有一家公司能脱离天气做生意。”再好的公司，在寒冬里也会受冻；很多投资者赔钱，不是选错了公司，而是看错了季节。宏观经济学，就是这座城的天气学。

**画面要点**：一台四件套的天气仪（太阳、温度计、风向标、雨量筒），背景是经历四季循环的同一座城。

```text
A rooftop weather observatory high above Coinflow City. In the center stands a grand brass weather instrument with four parts, each drawn as a pure symbol without markings: a glowing sun dial for growth, a tall glass thermometer for inflation, a spinning wind vane for interest rates, and a rain gauge for unemployment. Behind it, the city panorama is shown divided into four seasonal segments arranged in a great circle: spring with cranes building new factories, summer bustling and overheated with steam rising and shop prices on chalk boards replaced by flame symbols, autumn with leaves falling and fewer boats on the canals, winter with snow, quiet streets and some shuttered shops. The stone sluice tower is visible at the center of the circle. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) holds his coat collar against the wind, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) taps the thermometer. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

## 第二章 · 钱的源头：货币、银行、央行与支付

比特带 Sylvan 来到水库和水闸。这一章回答三个问题：钱到底是什么、从哪里来、谁在管它的多少。

### P11 · 货币是什么：信任的凭证

**配文**：在货币博物馆里，Sylvan 看到一排展品：贝壳、金块、银币、纸币、银行卡、手机上的一串光点。比特说：“它们本身几乎都不值钱。钱的本质，是一种大家都愿意接受的信任凭证。”今天绝大多数钱只是银行账本上的数字，背后靠的是国家信用和所有人的共同相信。信任在，钱就是钱；信任崩了——比如恶性通胀的时候——一推车纸币也买不到一个面包。

**画面要点**：从贝壳到手机的一排展柜，由一条“信任”的金线串起；角落里一车纸只换一个面包。

```text
A quiet, elegant museum gallery with a row of glass display cases along a long hall, each lit by a soft spotlight: a cluster of seashells, a rough gold nugget, a stack of silver coins with plain blank faces, a bundle of paper notes with no markings, a plain bank card with no logo, and finally a smartphone displaying a few glowing dots. A single thread of golden light runs through all the cases from one end to the other, passing through a small carved emblem of two clasped hands at the center of the hall. In a small side vignette, a person pushes a wheelbarrow overflowing with bundles of paper notes up to a bakery counter and receives just one small loaf of bread. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) walks along the cases with his hands behind his back, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) follows the golden thread with a thinking face. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle museum light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P12 · 银行如何“创造”货币

**配文**：在泵站大厦里，Sylvan 看到一个神奇的循环：一位储户存入一桶金水，银行留下一小部分备用，把大部分贷给磨坊主；磨坊主付给木匠，木匠又把钱存回银行；银行再留一点、再贷出去……一桶水，在账本上变成了好几桶。比特说：“这就是银行创造货币。今天经济里大部分的钱，都是在放贷的那一刻被‘创造’出来的。”这台放大器让经济转得更快，也让它更脆弱：如果所有储户同时来取水，没有一家银行拿得出那么多。这就是银行需要央行和监管的原因。

**画面要点**：存 → 留一点 → 贷出 → 付款 → 再存的循环，每圈都多出一个账本上的“回声”水桶。

```text
A cutaway of a grand pump-station building with brass pipes and gauges. A looping conveyor of wooden buckets runs in a circle through the hall. At the first station, a saver pours a full bucket of glowing golden water into the bank; a clerk pours a small portion into a modest reserve tank and sends the rest along the conveyor to a miller, who passes it to a carpenter, who walks it right back to the deposit window, where the cycle repeats. Above each loop, translucent ghostly copies of buckets appear in a tall ledger-like shelf, showing more and more buckets recorded than the single bucket of real water that started the loop. The small reserve tank glows in the corner, clearly much smaller than the shelf of recorded buckets. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) watches from a catwalk with his eyebrows raised, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) points from the tiny reserve tank to the tall shelf of buckets. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P13 · 央行与利率：水闸总管

**配文**：城中央的水闸塔里，总管转动一个大轮盘，控制整座城的水位。经济太冷时，他把闸门放低（降息），水流得又多又快，借钱变便宜，工厂开工；经济太热、物价飞涨时，他把闸门抬高（加息），水流放慢，借钱变贵，大家收手。比特说：“利率是钱的价格，也是所有资产价格的地心引力。”闸门一动，房价、股价、汇率、工资都会跟着动。央行还是“最后的贷款人”：银行一时取不出水，水闸可以紧急放水。所以全世界的投资者都盯着几个央行的一举一动。

**画面要点**：总管转轮盘；左边闸门低、水流大、城市热闹，右边闸门高、水流小、城市安静；四周的人都在用望远镜盯着轮盘。

```text
A tall stone sluice tower at the heart of Coinflow City, shown in cutaway. At the top, a calm, wise keeper in a deep navy uniform turns a giant brass wheel connected by chains to massive gates at the base. The scene is split: on the left side, the gates are lowered and golden water gushes out abundantly into a lively district with busy factories and full canals; on the right side, the gates are raised and the golden flow slows to a gentle stream into a calmer district where people are saving and fewer cranes are working. On rooftops and balconies all around the tower, tiny traders and townspeople peer through telescopes and spyglasses, watching the keeper's wheel intently. A small emergency spillway glows on one side, ready to release water to a struggling pump-station building. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands beside the keeper at the wheel, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) watches the telescopes pointed at them with a surprised face. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P14 · 支付清算：城市的运河网

**配文**：Sylvan 买了一杯咖啡，手机“嘀”一声。看起来一瞬间就完成了，背后却有一整套运河：他的银行、咖啡店的银行、卡组织、清算中心，像一道道水闸和船坞，一站站对账，确保每一滴水不多不少地到达。比特说：“支付清算是金融的血管。它不起眼，但停一分钟，整座城就会瘫痪。”跨国汇款更像远洋航行，要过好几道关口，所以又慢又贵——这也是金融科技公司最想重做的部分之一。

**画面要点**：一滴金水从手机出发，穿过好几道核对关口才到达咖啡店；远处是更长更慢的远洋航线。

```text
A bird's-eye cutaway of a network of golden canals beneath and between the streets of Coinflow City. In the bottom left, inside a cozy cafe, Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) taps his phone at the counter; a single glowing golden droplet riding in a tiny boat leaves from beneath the counter. The droplet's journey is traced along the canals through several small lock gates and checkpoint docks, where clerks in teal uniforms compare two matching ledgers and press approval stamps, before arriving at the cafe owner's bank building in the bottom right. In the upper part of the scene, a much longer ocean route leads to a distant foreign harbor, with several customs gates, slower cargo ships and waiting queues, showing international transfers. Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) rides along in the tiny boat with the droplet. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

## 第三章 · 资本的集市

比特带 Sylvan 走进城中心的大集市。这一章看钱在市场上以什么形式被买卖：份额、借条、对未来的约定；以及当所有人都借钱去买时，会发生什么。

### P15 · 股票：切成小块的果园

**配文**：果园主想扩建却缺钱，于是把果园切成一千份，卖给城里的人。买到一份的人，就拥有果园的千分之一：丰收时分到果子（分红），果园越来越值钱时份额也跟着涨；歉收时也一起承担。这就是股票。比特说：“上市，就是把份额拿到大集市上公开卖，让任何人都能买。”股东不能要求果园主还钱，但能投票决定大事。股票的价格，长期取决于果园未来能结多少果子；只是短期里，它更多取决于集市里人们的情绪。

**画面要点**：果园被划成很多小块，每个人手里拿着一块的凭证；丰收时大家一起分果子。

```text
A sunny hillside orchard of golden-fruited trees, neatly divided into a grid of small plots by thin colored ribbons. Many different townspeople each hold a small carved wooden token matching one plot, some standing proudly beside "their" tree. At harvest baskets in the center, golden fruit is being shared out to all the token holders in equal portions. The orchard owner, wearing a straw hat, shakes hands with a crowd and points to a new section being planted with the money raised. A winding path leads from the orchard down to the busy market plaza in the distance, where tokens are being traded between people. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) holds one wooden token up to the light, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) floats over the grid of plots. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P16 · 债券：长短不一的借条

**配文**：集市一角的长桌上摊着一排借条，有的短、有的长。政府和大公司需要借很多钱时，就把一张大借条切成很多标准的小借条卖出去：约定每年付多少利息、几年后还本，这就是债券。比特说：“借给越可靠的人，利息越低；借得越久，变数越多，通常利息越高。”债券价格和利率像跷跷板：水闸一抬（加息），新借条的利息更高，旧借条就不值钱了。全世界的债券市场和股市规模相当，它是政府、银行、保险公司和养老金最重要的市场。

**画面要点**：长短不一的借条按时滴下利息；一个跷跷板一端是抬起的水闸，另一端是下沉的旧借条。

```text
A long wooden table under a striped market awning, displaying a row of rolled scrolls of many different lengths, from short to very long, each tied with a ribbon and sealed with wax; the most trustworthy scrolls bear heavy stone-like seals, the riskier ones bear small cracked seals. From each scroll, small golden drops drip at regular intervals into little cups placed beneath, showing interest payments, with the riskier scrolls dripping faster. Next to the table stands a large playground seesaw: on one raised end sits a small model of the sluice tower with its gates lifting, on the lowered end a stack of old scrolls sinking down. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) unrolls one long scroll curiously, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) sits on the seesaw beam pointing at its tilt. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P17 · 交易所：大集市的报价墙

**配文**：大集市广场上人声鼎沸。想买的人举起金旗喊出愿意出的价，想卖的人举起蓝旗喊出愿意接受的价，中间的叫价人把两边撮合在一起。广场中央的报价墙上，箭头不停地上下翻动。比特说：“交易所做的事很简单：让买卖双方在同一个地方、按同一套规则碰面。”有了集市，果园份额和借条才能随时换成钱——这叫流动性。没有流动性的东西，再值钱也很难变现。而价格，就是在这一次次买卖中被“发现”的。

**画面要点**：金旗（买）和蓝旗（卖）两群人，中间的叫价人把他们配成对，背景是翻动箭头的巨墙。

```text
A vibrant, crowded market plaza in Coinflow City. On the left, a crowd of buyers raise small golden flags; on the right, a crowd of sellers raise small deep blue flags. On a raised wooden podium in the middle, lively auctioneers in matching vests point at pairs from each side and bring them together with a handshake, swapping carved orchard tokens and rolled scrolls for bowls of glowing golden water. Behind the podium rises a giant mechanical wall made of hundreds of small flip panels, each showing only an arrow pointing up in gold or down in blue, constantly flipping; tiny runners on ladders adjust the panels. Messengers dash in and out with sealed letters. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands on the steps of the podium taking in the noise, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) hovers between a buyer and a seller as they shake hands. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P18 · 衍生品：农夫与面包师的约定

**配文**：春天，农夫担心秋天麦价暴跌，面包师担心秋天麦价暴涨。于是两人现在就签一份约定：不管秋天市价如何，都按今天说好的价格交易——这是期货。另一位面包师更灵活：他付了一小笔订金，换来“秋天可以按约定价买，也可以不买”的权利——这是期权，像给自己买了一份保险。比特说：“衍生品本身不生产任何东西，它是对未来的约定，把风险从怕它的人转给愿意承担它的人。”但同样的工具也能用来下巨额赌注：用得好是保险，用不好是炸药。

**画面要点**：春天握手签约，秋天不管丰收还是干旱都按约定交易；一张金色的“可以不买”票券；角落里玩火药的人。

```text
A split-season illustration. On the left, a spring wheat field: a farmer in overalls and a baker in an apron shake hands over a rolled contract tied with a wheat-stalk seal, a calm clerk witnessing. A path leads to the right side, which shows autumn in two stacked versions: above, a bumper harvest with mountains of wheat; below, a drought with a few thin stalks; in both versions the same farmer and baker meet at the same little exchange stand and trade at exactly the same handshake, unaffected. In the middle foreground, a second baker hands a single small golden drop to a clerk and receives a shiny golden ticket shaped like a key, representing the right but not the obligation to buy. In a small inset vignette at the bottom right, a reckless figure juggles several lit sticks of dynamite shaped like rolled contracts, sparks flying. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) watches the handshake, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) points warily at the dynamite juggler. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P19 · 杠杆与泡沫：越吹越大的气球

**配文**：广场上升起一个金色的巨型气球。大家看它越升越高，纷纷借钱来给它打气，气球被吹得越来越大，所有人都觉得它会一直升下去。比特说：“当价格上涨的唯一理由是‘它一直在涨’，泡沫就出现了。”杠杆让泡沫胀得更快：借来的钱推高价格，价格上涨又让人借更多。直到某一天，一个小小的消息像一根针——气球破了，借钱买的人不仅赔光本金，还欠着债。郁金香、股市、房地产，历史上反复上演的都是同一个故事。

**画面要点**：人们从泵站借来金水、不停给气球打气；一根针正在靠近。

```text
The market plaza at golden hour. An enormous shimmering golden balloon floats above the crowd, tethered by many ropes, already showing thin stretch marks on its surface. Long lines of eager townspeople carry buckets of glowing golden water borrowed from a pump-station window (clerks handing out buckets and noting debts in ledgers), and pour them into a large hand pump that inflates the balloon even further; the crowd below cheers and points upward. At the edge of the scene, a tiny glinting sewing needle drifts on the breeze toward the balloon. A few cautious figures near the plaza's edge step back and shield their eyes. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands among the cautious ones with folded arms and a skeptical look, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) points at the approaching needle with a surprised face. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, warm golden-hour light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P20 · 金融危机：挤兑与多米诺

**配文**：一个谣言在城里传开：某家泵站的水不够了。储户们涌到窗口排起长队，泵站真的被取空了。恐慌像多米诺骨牌一样传到下一家泵站、再下一家。比特说：“银行用的是借来的水，靠的是信任。信任一旦崩塌，再健康的银行也撑不住大家同时取水。”危机中，水闸总管紧急放水，堤坝上的人加固防线——这就是现代金融离不开央行和监管的原因。危机往往起于杠杆，传于恐慌，止于信任重建。

**画面要点**：泵站窗口排长队；一排泵站建筑像多米诺一样倾倒；水闸塔紧急放水、堤坝上有人加固。

```text
A dramatic but not frightening storybook scene under gray rain clouds. In the foreground, long anxious queues of townspeople with empty buckets stretch from the windows of a pump-station building whose reserve tank is visibly running dry; whispers are shown as small swirling wind lines passing from ear to ear. Across the city behind, a long row of pump-station buildings tilt into each other like a line of dominoes, the nearest ones toppling while the furthest are still upright. In the center, the stone sluice tower opens a special emergency gate, releasing a bright stream of golden water toward the struggling buildings, and workers on the levees stack sandbags to hold the line. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands in a queue holding an umbrella, looking concerned, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) points toward the emergency gate at the sluice tower. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, overcast rainy light with a warm glow from the emergency gate, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

## 第四章 · 管钱的人

比特带 Sylvan 登上一艘运河上的船。这一章看替别人管钱的人：他们怎么决定钱该去哪里，又怎么判断一样东西值多少钱。

### P21 · 分散投资：鸡蛋和篮子

**配文**：码头上，两位商人运送金色的鸡蛋。第一位把所有鸡蛋装进一个精美的篮子，一个踉跄，全碎了。第二位把鸡蛋分装进很多篮子，交给不同的船，偶尔碎一篮，大部分安然到岸。比特说：“这是投资学里少有的‘免费午餐’：在不牺牲平均回报的前提下，把风险摊薄。”但分散也有极限：如果整片海都起了风暴，所有船都会摇晃——这种全市场一起下跌的风险，叫系统性风险，靠分散躲不掉。

**画面要点**：一个篮子全碎 vs 多个篮子大部分安全；天边有一场覆盖整片海的风暴。

```text
A busy harbor dock at morning. On the left, a merchant in fine clothes has tripped on a loose plank, and his single ornate basket of glowing golden eggs is smashing on the boards, eggs cracking everywhere. On the right, a second merchant calmly hands many small baskets of golden eggs to the crews of many different small boats; one boat in the distance has a single broken basket, while the rest sail on safely toward the far shore. On the horizon, a vast dark storm front spans the entire sea, hinting that a big enough storm would rock every boat at once. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) helps the second merchant load a basket, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) points toward the distant storm. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P22 · 指数与主动：买下整片森林

**配文**：森林边，一位猎人花大价钱雇向导，想找出最高的那棵树；另一位干脆买下整片森林的一小份。几十年后，后者往往过得更好：挑树的人要付向导费，而且大多数时候挑不准。比特说：“指数基金就是买下整片森林。成本低、透明，长期来看跑赢了大多数主动挑选的基金。”这让资产管理行业发生了巨变：资金大量流向低成本的指数产品，主动管理的人必须证明自己值那份费用。

**画面要点**：左边花钱雇向导挑树，右边轻松地拥有整片森林的缩影。

```text
The edge of a vast golden-leafed forest, split into two halves. On the left, a determined hunter in a feathered hat studies maps with an expensive guide, who holds out an open palm full of golden drops as his fee; together they push through dense trees searching for the single tallest one, looking tired, while many tall trees they passed tower behind them unnoticed. On the right, a relaxed person sits on a bench holding a small glass dome containing a perfect miniature of the entire forest, sipping tea, the real forest behind growing steadily taller as seasons pass across the background. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) sits beside the relaxed person examining the glass dome, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) glances back at the struggling hunter. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P23 · PE 与 VC：种子园丁与老宅翻新师

**配文**：城郊有两种特别的投资人。一位是种子园丁——风险投资（VC）：他在十片空地里各种下一颗种子，大多数不会发芽，但只要有一颗长成参天大树，就足够把其他的损失赚回来好几倍。另一位是老宅翻新师——私募股权（PE）：他买下整栋有潜力但破旧的老房子，换管理、改结构、重新装修，几年后高价卖出。比特说：“他们投的都是还没上市的公司，钱一放就是好几年，赚的是‘看得准’和‘改得好’的钱。”

**画面要点**：左边十块地里只有一棵长成大树；右边一栋老宅一半破旧、一半翻新。

```text
A split scene on the outskirts of Coinflow City. Left half: a garden of ten small plots tended by a gardener in a wide hat with a watering can; most plots are bare soil or tiny wilted sprouts, one has a small sapling, and one has grown into an enormous towering golden tree whose canopy shades the whole garden and drops golden fruit into baskets. Right half: an old townhouse shown in two halves, the left side shabby with a sagging roof, peeling paint and broken shutters, the right side freshly renovated with a new roof, bright paint and flower boxes; a renovation crew on scaffolding works on the boundary, while a foreman reviews plans and a new buyer arrives at the gate holding a heavy chest of glowing golden water. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands between the two halves looking from the giant tree to the renovated house, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) waters one of the bare plots. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P24 · 估值：望向未来的望远镜

**配文**：一家公司值多少钱？比特递给 Sylvan 一架特制的望远镜。从镜筒里能看到这家公司未来每一年会结出的果子，越远的果子越小、越模糊。把这些果子按“时间的价格”一颗颗打折、折回今天、加在一起，就是公司的内在价值——这叫现金流折现（DCF）。另一种方法更简单：看看隔壁几家差不多的果园卖多少钱，按比例推算——这叫可比公司法。比特说：“估值不是算出一个正确答案，而是把你对未来的假设说清楚。”假设稍微一变，结果就可能差很多。所以真正值钱的是判断，不是公式。

**画面要点**：望远镜里的未来果园一个比一个小；果子顺着丝带流回天平，越远的越小；旁边是可以比较的邻居果园。

```text
A breezy hilltop at sunset with a large ornate brass telescope on a tripod. Through an enlarged circular view from the lens, a series of future orchards recede toward the horizon, each one smaller and hazier than the last. From each future orchard, a stream of golden fruit flows back along a glowing ribbon path to a large balance scale beside the telescope, the fruit shrinking more the further away it came from, and settling into one pan of the scale. Along the hill to one side, a row of three neighboring orchards each has a heap of golden water beside its gate, for comparison. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) looks through the telescope's eyepiece, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) nudges a small dial on the telescope, causing the scale to swing noticeably. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, warm sunset light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

## 第五章 · 风险与规则

水流得越快，堤坝就越重要。这一章看金流城里那些“不直接赚钱、却决定城市能不能活下来”的人和规则。

### P25 · 风险管理：暴风雨模拟池

**配文**：泵站大厦地下有一个巨大的模拟水池。风控团队在里面造出微缩版的金流城，然后用机器模拟各种暴风雨：利率暴涨、股市暴跌、大客户违约、所有人同时取水。他们观察哪道堤会先垮，然后提前加固。比特说：“风险管理不是让机构不亏钱，而是保证它在最坏的日子里也死不了。”平时他们常常不受欢迎——总是拦着业务部门多赚钱；危机来临时，他们决定了机构能不能活下来。

**画面要点**：水池里的微缩城市正在经历人造风暴，风控人员标出会先垮的堤段；门口有人拦住急着下注的交易员。

```text
A vast basement hall beneath a pump-station building, lit by hanging lamps. In the center lies a large pool containing a detailed miniature model of Coinflow City with its canals, levees and pump stations. Around the pool, wave machines, large fans and overhead sprinklers create an artificial storm over the miniature city. A risk team in deep navy uniforms with clipboards and lanterns watches closely, planting small coral flags on the miniature levee sections that are about to fail, while builders reinforce those exact sections on a full-size blueprint table nearby. At the hall's entrance door, a risk officer calmly holds out an arm to stop an eager trader in a sharp vest who is trying to rush out carrying a huge stack of betting slips. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) kneels at the pool's edge watching a miniature levee crack, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) operates one of the wave machines. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, warm lamp light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P26 · 保险与精算：巨大的公共雨伞

**配文**：保险公司的大厅就在那把巨伞下面。一位精算师站在一面巨大的黑板前，计算这座城一年大概会有多少房子着火、多少人生病、多少车出事故。他据此算出每户该交多少保费：既不能少到赔穿，也不能多到没人买。保险公司先收钱、很多年后才赔，中间攒下的巨额资金，又让它们成了金融市场上最大的长期投资者之一。比特说：“精算师是给‘意外’定价的人。这是一份门槛极高、也极其稳定的工作。”

**画面要点**：精算师在黑板上统计各种意外；居民交一点保费；大厅下方攒下的资金顺着管道流向集市。

```text
A grand insurance hall built directly beneath the shelter of the giant umbrella pavilion, its ribs forming a domed ceiling. In the center, an actuary in a tweed waistcoat stands before a huge chalkboard covered with rows of tally marks beside simple icons — houses, flames, cars, hearts — and smooth bell-curve chalk shapes, no numbers or letters. At a long counter, townspeople each drop a small portion of glowing golden water into collection funnels. A cutaway beneath the hall reveals a deep vault where a large pool of golden water has accumulated over many years; a thick pipe carries part of it out toward the distant market plaza and orchards. In one corner, a clerk pours golden water to a family whose house was damaged by fire. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) studies the chalkboard thoughtfully, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) peers down into the deep vault. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P27 · 监管与合规：堤坝与裁判

**配文**：金色的水流得越快，越需要堤坝。堤坝上的巡逻员是监管者：规定每家泵站必须留多少备用水（资本要求）、必须公开自己的账本（信息披露）、不许拿别人的水去赌（利益冲突）。每家泵站门口还有自己的合规官，像场边的裁判，确保每一笔交易守规矩，并拦住想把脏水混进来的人（反洗钱）。比特说：“金融是监管最严的行业之一，因为它用的是别人的钱，而且一家倒下可能拖垮一串。”规则会让业务变慢，但没有规则的金融，最后总会把整座城淹掉。

**画面要点**：巡逻员测量备用水箱；合规官拦住往金水里倒脏水的人；公开的账本摆在告示栏上。

```text
A sunny scene along a major golden canal lined with sturdy stone levees. Patrol officers in deep navy coats walk the levee tops with measuring rods and brass gauges, one of them inspecting the reserve tank of a pump-station building and nodding approvingly at its water level. At the pump-station's front door, a compliance officer in a referee-style striped vest with a whistle firmly blocks a shadowy cloaked figure who is trying to pour a bucket of murky dark water into the clean golden canal. Nearby, a large public notice board displays several open ledger books with blank pages so any townsperson can read them. In the background, a pump station without levees has flooded a small street, showing what happens without rules. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) reads the open ledgers on the notice board, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) watches the compliance officer stop the cloaked figure. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P28 · 行为金融：羊群与镜子屋

**配文**：集市上，一群人看到别人在抢购，也跟着冲上去；价格一跌，又一窝蜂地抛售。比特带 Sylvan 走进一间镜子屋：镜子里每个人都看到一个更聪明、更有把握的自己。比特说：“经济学过去常假设人是理性的，行为金融学研究的是：人其实会追涨杀跌、跟风、过度自信，怕亏钱的程度远超喜欢赚钱。”这些毛病解释了泡沫和崩盘为什么反复发生，也解释了为什么很多个人投资者会亏钱。最难管理的风险，常常是自己的情绪。

**画面要点**：一边是一群人像羊群一样涌向、又逃离同一个摊位；一边是镜子里被放大的自信倒影。

```text
A split scene. Left half: a market street where a crowd of townspeople, each wearing a fluffy woolly hat that makes them look like a flock of sheep, stampede together toward one small stall where a single golden item is displayed; behind them, faded ghost images show the same crowd an hour later stampeding away from the stall in panic, dropping their purchases. Right half: a carnival hall of curved mirrors, where Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands facing a mirror that shows a taller, glowing, overconfident version of himself in a grand gilded suit holding a crown; beside him, Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) holds up a small plain hand mirror showing Sylvan's true, ordinary reflection. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

## 第六章 · 金融遇上技术

比特带 Sylvan 登上山丘上的齿轮钟塔。金融从一开始就是“信息业”——价格、信用、账本都是信息，所以它最先被技术重塑。这一章也是连接《比特城》和《金流城》的桥。

### P29 · 金融科技：手机里的银行

**配文**：过去开个户，要跑到泵站柜台排队、填一堆表；现在，Sylvan 在公园长椅上用手机几分钟就开好了户、转了账、买了基金。比特说：“金融科技做的事，是把金融服务的成本压低，让过去够不着的人也能用上。”在一些国家，手机支付让从没进过银行的人第一次有了账户。但金融科技的难点不在技术，而在牌照和风控：做支付、放贷款都要监管许可，用的是别人的钱，出了错就是大事。

**画面要点**：左边传统柜台排长队，右边一部手机里弹出一座微型银行；入口处有人检查牌照。

```text
A split scene. Left: an old-fashioned pump-station banking hall with high ceilings, a long winding queue of tired people holding stacks of paper forms, clerks behind brass grilles stamping documents. Right: a sunny park where Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) sits on a bench holding a smartphone, from which a miniature pump station, a tiny canal and a little bank counter unfold upward like a magical pop-up book, a golden droplet sailing across it in seconds. In the distant hills, a farmer in a small remote village also holds a phone and receives a glowing golden droplet, smiling. At the entrance of the pop-up bank, a tiny gatekeeper in navy carefully checks an official-looking scroll with a wax seal before letting the droplet pass. Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) peers into the pop-up bank with delight. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P30 · 量化交易：机器交易员

**配文**：集市上的叫价人越来越少，取而代之的是一排排安静的机器。它们一秒钟能读完成千上万条报价和新闻，按事先写好的规则自动买卖。钟塔里的量化研究员用数学和历史数据寻找可以重复的规律，写成程序；工程师则把程序做得更快——快到连钟塔和交易所之间的距离都要计较。比特说：“在很多成熟市场，相当一部分交易已经由程序完成。”量化的核心不是预测未来，而是在成千上万次下注里，让赢的概率稍微大于输的。

**画面要点**：集市里一排自动交易机器人；钟塔里有人研究规律、有人拼命缩短通往交易所的线缆。

```text
The market plaza now noticeably quieter, with only a few human auctioneers left. Along the stalls stand neat rows of elegant brass-and-glass automaton traders with gear-shaped faces, each reading a fast-flowing stream of glowing arrow tiles at lightning speed and flicking small golden or blue flags in perfect rhythm. On a hill beside the plaza, the glass clock tower is shown in cutaway: on one floor, quant researchers stand at chalkboards filled with abstract curves, scatter-dot patterns and shapes (no numbers), comparing them with thick books of past market records; on a lower floor, engineers in work aprons lay a glowing cable straight from the tower to the exchange building, trimming it shorter and shorter, one of them holding a stopwatch. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) watches an automaton trader closely, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) waves at the automaton, who does not look up. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P31 · 区块链：人人都有一份的账本

**配文**：在金流城的郊外，有一个没有泵站的村庄。这里每户人家都保存着一本一模一样的账本，每发生一笔交易，所有人同时记上一笔；谁想偷偷改自己那一本，都会和其他人的对不上。比特说：“这就是区块链的想法：不靠中心机构，而靠大家共同记账来建立信任。”支持者看重它的开放和效率，批评者担心投机、能耗和监管缺口。各国态度差异很大，它仍是一个在争论中演进的领域。

**画面要点**：没有中心建筑的村庄；一笔交易发生时，光线连到每一户的账本；有人偷改的那一页发红。

```text
A charming hilltop village with no central bank or tower, just a ring of cottages around an open square. In each cottage window sits an identical open ledger book glowing softly. In the square, two villagers exchange a glowing golden drop, and at that moment thin beams of light shoot from the square to every cottage, and every ledger simultaneously turns a new page and receives a matching stamp. In one cottage, a sneaky villager with a quill tries to scribble an extra entry into his own ledger; his page glows coral red and the light beams from neighboring cottages show a clear mismatch. Some villagers debate animatedly by a well, some excited, some skeptical with folded arms. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands in the square watching the beams spread, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) floats near the red-glowing page with a thinking face. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P32 · AI 进入金融：不睡觉的助理

**配文**：钟塔顶层，一位由光线织成的助理日夜不停地工作：一夜之间读完上千份财报和合同，标出可疑的交易，替客服回答问题，帮研究员起草报告初稿。比特说：“过去一个团队要做一周的整理工作，现在几分钟就能拿出初稿。”这正在改变金融的人才结构：重复性的整理、初级研究、合规审核最容易被压缩；而能提出好问题、判断 AI 的答案对不对、并为结果负责的人，变得更值钱。在强监管的金融里，“谁来负责”这件事，AI 替代不了。

**画面要点**：光线助理被海量文件环绕、标出一条可疑线索；一位人类分析师审阅初稿并盖下确认印章。

```text
The top floor of the glass clock tower at night, glowing gears turning slowly overhead. In the center, a calm assistant figure woven from soft glowing light-threads works tirelessly, surrounded by floating stacks of documents and contracts that flip open and close by themselves; a trail of transactions drawn as a chain of linked golden droplets is highlighted in coral where one suspicious link stands out; a long draft scroll unrolls from the assistant's hands. At a desk beside it, a human analyst in shirtsleeves reviews the draft scroll with a pen, crossing out one line, then pressing a heavy wax approval seal onto it. Through the tall windows, the city sleeps under the stars. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) leans on the desk holding a cup of coffee, watching the human sign off, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) points at the highlighted suspicious link. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, warm lamplight at night, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

## 第七章 · 城里的人

前六章看的是“水”怎么流，这一章看“人”：金流城里每一种职业站在价值链的哪个位置、靠什么挣钱、需要什么本事。这一章对应手册里的岗位地图。

### P33 · 工种大地图：全城职业分布

**配文**：比特在钟塔顶层铺开一张全城地图，每个角落都有一群人在干不同的活。水库和果园一带是替别人管钱的人：资产管理和财富顾问。泵站和桥梁一带是银行家和投行家，替缺钱的企业找钱。集市里是交易员，钟塔里是量化和技术人员。堤坝和雨伞下是风控、合规、审计和精算。比特说：“看任何一个金融岗位，只问三个问题：你站在钱的哪一头？你是在承担风险，还是在帮别人转移风险？你的收入和业绩挂得有多紧？”直接面对客户和市场的叫前台，收入弹性大；保证整台机器不出错的叫中后台，收入稳定。

**画面要点**：一张铺满桌面的立体城市沙盘，按区域分布着不同职业的小人，每一区都用一种颜色的光圈标出。

```text
The top floor of the glass clock tower, where a huge isometric tabletop model of the entire Coinflow City fills a round wooden table. Each district of the model is softly ringed by a different colored glow: around the reservoir and orchards, tiny gardeners and butlers tend trees and households; around the pump stations and a half-built bridge, tiny bankers and engineers in suits carry blueprints and briefcases; in the market plaza, tiny traders wave colored flags; inside a miniature clock tower, tiny engineers and mathematicians work at desks; along the levees and under the giant umbrella pavilion, tiny patrol officers, inspectors with magnifying glasses and an actuary with a chalkboard keep watch. The model is divided by a faint line into a busy outer ring facing the canals and a calm inner ring of back offices. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) leans over the table studying the districts, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) hovers above the model pointing a beam of light at each district in turn. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P34 · 帮企业找钱的人：媒人与桥梁工

**配文**：投行家像媒人兼桥梁工。企业要上市、发债或者被收购时，他们负责算出公司值多少钱、准备厚厚的材料、找到愿意出钱的买家，然后把桥搭起来。通宵改模型和材料是常态，收入也在行业顶端。旁边是商业银行的信贷员，正在磨坊里检查机器和账本，判断这家工厂借了钱能不能还上。远处的苗圃里是 PE 和 VC 投资人：他们直接拿钱换公司的股份，陪它长几年，再卖出去。比特说：“这群人的核心本事是同一件事：看懂一家公司值多少钱，并且说服别人相信。”

**画面要点**：一座正在修建的金色桥梁连接水库和磨坊；信贷员在磨坊里检查；远处苗圃里有人在给小树苗浇金水。

```text
A busy riverside construction scene. A team of investment bankers in rolled-up shirtsleeves and loosened ties, some holding thick binders and glowing lanterns as if they have worked through the night, builds an elegant golden bridge across a canal, connecting a large reservoir on one side to a growing mill company on the other; a matchmaker-like lead banker in the middle of the bridge introduces a wealthy investor in a top hat to the mill owner, both shaking hands. Inside the mill, shown in cutaway, a careful credit officer in a navy vest with a magnifying glass inspects the waterwheel machinery and an open ledger book while the mill owner waits nervously. In a nursery garden in the background, venture investors in gardening aprons water rows of tiny saplings with glowing golden water, each sapling labeled only by a small blank wooden tag, while one sapling has grown into a tall tree being admired by a crowd. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands on the bank watching the bridge go up, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) carries a single golden brick toward the bridge. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P35 · 替别人管钱的人：园丁、船长与管家

**配文**：资产管理人像园丁：把养老金、保险公司的钱和普通人的储蓄种进不同的果园，有的种股票，有的种债券，挑选哪些树会长大。基金经理是船长，决定这艘船往哪里开；研究员是瞭望员，深入调研每一个行业和公司。财富顾问像管家，替一户人家安排花多少、存多少、怎样传给下一代。比特说：“管钱的人通常不靠一次成交赚钱，而是按管理的规模收一小份费用，所以信任和长期业绩就是一切。”这一行也在变：越来越多人选择费用低廉、直接买下整个市场的指数基金，主动管钱的人必须证明自己比这种做法更好。

**画面要点**：一片层次分明的果园，园丁打理；水渠上一艘船，船长掌舵，瞭望员举望远镜；一位管家陪着一家人在树下规划。

```text
A lush terraced orchard fed by golden canals. Gardeners in green aprons carefully tend rows of different fruit trees — tall sturdy trees, small fast-growing trees, slow steady trees — pruning, grafting and deciding which saplings to plant, while barrels from rooftop savings flow into the orchard's irrigation channels. Along the main canal sails a handsome boat: a captain in a navy coat stands at the wheel choosing a direction, and a lookout high in the crow's nest scans distant orchards and mills with a brass telescope, a research notebook tucked under his arm. In the shade of a large tree, a gentle butler-like wealth advisor sits at a picnic table with a three-generation family, arranging glowing golden droplets into small jars for spending, saving and passing down to a child. On a nearby hillside, a huge simple machine automatically plants a seed of every kind of tree in tidy rows, quietly watched by the gardeners. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) walks between the fruit trees, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) rides on the boat's bow beside the lookout. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P36 · 交易与量化的人：集市里的叫价人和钟表匠

**配文**：集市里有两种人。一种是交易员和做市商，整天报价、成交、控制自己手里的仓位，像嗓门洪亮的叫价人；做市商还要一直挂着买价和卖价，让任何人随时都能成交。另一种在钟塔里：量化研究员、量化开发、数据工程师，像钟表匠，把发现的规律做成自己会走的机器。比特说：“这是金融里最接近纯手艺的地方：成绩当天就看得见，赚就是赚，亏就是亏。”这条路看重数学、统计和编程，很多人来自物理、数学和计算机专业；团队小，人均产出高，收入差距也极大。

**画面要点**：画面下半是热闹集市里的叫价人和做市商摊位；上半是钟塔剖面里的钟表匠精细组装机器。

```text
A vertical two-level cutaway. Lower half: the lively market plaza, where energetic traders in colorful vests shout and gesture with hand signals, and a market maker stands at a double-sided stall holding up a gold flag on one side for buying and a blue flag on the other side for selling, constantly ready for anyone who walks up; beside each trader is a small balance scale they glance at to keep their pile of goods from tipping too far. Upper half: inside the glass clock tower, quiet watchmaker-like quants in leather aprons and magnifying loupes assemble intricate brass mechanisms from tiny gears, springs and glowing threads, testing each finished mechanism on a miniature market model, while a data engineer feeds long ribbons of patterned tape into the machines. A single glowing cable runs from the tower down to the plaza. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands at the boundary on a spiral staircase looking down at the traders and up at the watchmakers, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) holds a tiny gear up to a watchmaker. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P37 · 守门人：堤坝巡逻员、审计师、精算师

**配文**：风控、合规、审计和精算不直接赚钱，却决定一家机构的生死。风控人员盯着每个部门押了多少、押在哪里；合规人员保证每笔业务合法；审计师来自外部的会计师事务所，每年把一家公司的账本从头核对一遍，然后签字为它的真实性负责；精算师给保险定价，并算清楚未来要准备多少钱赔付。比特说：“这些岗位成长慢一些，收入稳一些，但它们靠证书和经验积累，越老越值钱；而监管越严，需求就越大。”

**画面要点**：四组守门人沿堤坝分布：巡逻员看水位，合规官把关闸门，审计师在灯下逐页核对账本，精算师在伞下计算。

```text
A long panoramic view along a great stone levee at the edge of Coinflow City. Four groups of gatekeepers work along it: risk patrol officers in deep navy coats read water-level gauges on every canal outlet and mark warnings on a tide chart drawn with simple wave lines; a compliance officer in a referee-striped vest checks each boat passing through a sluice gate against a thick rule book with blank pages; inside a lamplit stone guardhouse shown in cutaway, outside auditors in grey suits with green visors and magnifying glasses compare a company's ledger page by page against stacks of receipts, one of them pressing a large wax seal at the end; beneath the giant umbrella pavilion, an elderly actuary and a young apprentice calculate on a chalkboard of tally marks and bell curves. The gatekeepers grow older and wiser-looking along the levee, the eldest wearing many small medal ribbons. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) walks along the levee top, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) peeks over an auditor's shoulder. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P38 · 市场规律：潮汐与台阶

**配文**：比特带 Sylvan 来到城外的海边，看潮水漫过一道道石台阶。潮水是行业周期：行情好的时候人人招人、奖金翻倍；行情差的时候裁员缩编，最靠前的岗位被冲得最狠。台阶是证书和资历，CFA、CPA、FRM、精算师考试一级一级往上爬，站得越高，潮水越难够到你。比特总结了三条规律：“离钱越近，收入弹性越大；牌照和信任是这一行的护城河；AI 正在压缩中后台和初级岗位里的重复劳动。”给新人的建议是：先想清楚自己要站在钱的哪一头，再选你能承受多大的潮汐。

**画面要点**：海边一段宽阔的石台阶，潮水涨落；低处有人被浪打湿；高处的人手持卷轴；一只钟表机械臂在台阶中段清扫成堆的纸。

```text
A wide seaside staircase of ancient stone steps descending into a golden-tinted sea at sunset. A large tide of glowing golden water surges up the lower steps: on the lowest steps, people in front-office sharp suits ride the waves on small sleek boats, some lifted high and celebrating with armfuls of golden droplets, others knocked over and soaked as the tide pulls back. Higher up, steady figures sit calmly on dry steps, each holding a rolled certificate scroll tied with a ribbon, the scrolls getting larger and more ornate on higher steps. On a middle landing, a gentle brass clockwork arm extending from a small glass machine sweeps up tall piles of repetitive paperwork that junior clerks used to sort by hand; the clerks step aside, some picking up new tools to direct the machine. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands on a middle step deciding where to climb, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) hovers above the waterline, its hover-glow tracing the high-tide mark on the stone. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, warm golden sunset light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

## 尾声

走完整座城，Sylvan 回到出发时的广场。最后三页把全书收拢：先回答“从哪里开始学”，再用一句话装下整个行业，最后合上书。

### P39 · 学习之路：从广场出发的七条路

**配文**：广场中央铺着六块基石：会计三张报表、货币时间价值与估值、Excel 建模、统计与 Python/SQL、宏观常识、写作。比特说：“不管走哪条路，这六块石头都要先踩稳。会计是这一行的语言，估值是这一行的数学，写作是你说服别人的工具。”从广场放射出七条路，分别通向投行的桥、资管的果园、PE/VC 的苗圃、交易与量化的集市和钟塔、风控合规精算的堤坝和雨伞、银行与财富管理的泵站，以及金融科技的玻璃工坊。这几条路在半途常常交叉，很多人走了几年会换到隔壁那条。

**画面要点**：俯视的圆形广场，六块带图案的基石；七条路放射出去，尽头各有一处前文出现过的地标；路与路之间有小径相连。

```text
A bird's-eye isometric view of a round sunlit plaza at the heart of Coinflow City. Six large carved foundation stones are set into the plaza floor in a ring, each with a simple pictorial carving: an open ledger book with three pages, an hourglass filled with golden water, a neat grid of empty tiles, a magnifying glass over scattered dots beside a little snake curled around a stack of drawers, a weather vane on a globe, and a quill pen. Seven cobblestone roads radiate outward from the plaza like sun rays, each ending at a familiar landmark: a golden bridge with bankers, a terraced orchard with gardeners, a nursery of saplings, the market plaza beside the glass clock tower, a stone levee with the giant umbrella pavilion, a pump station surrounded by family homes, and a glowing glass workshop with tiny phones on its workbenches. Small footpaths cross between neighboring roads, and a few tiny travelers switch from one road to another. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands on the six stones looking out at the roads, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) floats at the start of one road beckoning. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P40 · 塔顶俯瞰

**配文**：傍晚，Sylvan 和比特坐在钟塔顶上，看全城的金色水流在渠道里闪光。屋顶的水桶、水库、闸门、泵站、集市、磨坊、堤坝和雨伞，现在连成了一张完整的网。比特说：“如果整本书只记一句话，那就是：会计是语言，利率是时间的价格，风险是唯一的商品，信用是杠杆，市场是处理信息的机器。”Sylvan 想起上一次去过的比特城：计算机处理的是信息，金融处理的是信任和时间。两座城其实早已连在一起，钟塔的光正顺着金色的水渠流进每一条街。

**画面要点**：钟塔顶部的两个身影背对观众，眼前是全书出现过的所有地标；金色水流把它们连成一张网。

```text
A breathtaking wide view at dusk from the very top of the glass clock tower. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) sits on the edge of the tower's balcony seen from behind, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) floats beside his shoulder. Spread below them is the whole of Coinflow City: rooftop barrels, the great reservoir, the sluice tower with its keeper, pump stations, the bustling market plaza, mills with turning waterwheels, terraced orchards, the giant umbrella pavilion and the long stone levees, all linked by shimmering golden canals that together form one glowing connected network like veins of light. On the far horizon, a faint distant city of glowing circuit-like towers is visible, joined to Coinflow City by a single long bridge of light. The first lamps are coming on in windows. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, soft violet-and-gold dusk light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P41 · 封底

**配文**：（封底可只放一句话，排在画面下方三分之一的空白处）“钱是会流动的时间，金融是让它流到该去的地方。”

**画面要点**：金流城的夜景，金色水渠在黑夜里发光；画面下三分之一留空给文字。竖版 3:4。

```text
A quiet night view of Coinflow City from a distant hill, composed in portrait orientation. The city's golden canals glow softly through the darkness like rivers of light, the glass clock tower shines gently at the center, and the giant umbrella pavilion and stone levees are silhouetted against a deep navy starry sky. Tiny warm lights glow in windows of pump stations and homes. On the hilltop in the foreground, very small, Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) walks away along a path with his satchel over his shoulder, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) floats beside him, its blue glow a tiny point of light. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed scene, soft cream paper texture, muted palette of teal, deep navy, warm gold and coral, calm moonlit night, one clear visual metaphor, no text, no letters, no numbers, no logos, no currency symbols, the bottom third of the image left as calm, simple dark sky-and-hill space with no details for a caption, 3:4 portrait.
```
