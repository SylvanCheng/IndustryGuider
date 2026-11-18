# 《比特城漫游记》绘本 Prompt 手册

Nov 18, 2026 · @Sylvan

## 使用说明

这本绘本把整个计算机行业画成一座城市——**比特城**。一位外行访客“Sylvan”跟着向导机器人“比特”，从地基一路走到塔顶，再认识城里的各种工种。全书 45 页，每页分三部分：

- **配文**：印在绘本上的中文文字，讲清这一页的本质。
- **画面要点**：这幅图必须让人一眼看懂的那件事，用来检查出图是否合格。
- **Prompt**：直接复制给绘图模型的英文提示词。每段都已包含画风和角色描述，可以单独使用。用英文是因为各家绘图模型对英文的理解最稳定。

### 出图步骤

1. **先定妆**：用下一节的两段“定妆图 prompt”分别生成Sylvan和比特。满意后，把这两张图作为参考图，在每一页出图时一起上传——多数主流绘图模型都支持参考图，这是保持角色前后一致的最有效办法。
2. **逐页复制 Prompt**：按页码顺序生成。如果模型支持在同一个对话里连续出图，尽量在同一个对话里完成一整章，风格更统一。
3. **文字后期加**：所有 prompt 都要求“不画文字、上方留白”。绘图模型画汉字容易出错，配文建议用排版工具放进留白区。如果你用的模型汉字渲染很好，也可以在 prompt 末尾加一句：`Render this Chinese title in the blank area at the top: “（本页标题）”`。
4. **画幅**：内页统一 4:3 横版，封面和封底 3:4 竖版。
5. **修改原则**：不满意时只改 prompt 前半段的场景描述，不动最后的 Style 段，全书画风就不会跑偏。
6. **读法**：绘本里的比喻是为了抓住本质，不是完整定义。想看严谨说法，配合《计算机行业速通手册》一起读。

### 全书目录

| 页 | 主题 | 城市里的比喻 |
| --- | --- | --- |
| P1 | 封面 | 一座分层的城市 |
| P2 | 这个行业在做什么 | 一山纸件瞬间变成光 |
| P3 | 原理一：说得清就能自动化 | 给机器人的菜谱 |
| P4 | 原理二：算力越来越便宜 | 从房间大小缩到指甲盖的机器 |
| P5 | 原理三：复制零成本 | 一本书化作百万本 |
| P6 | 原理四：AI 学会说不清的事 | 看过一万只猫的学徒 |
| P7 | 城市全景：价值链 | 剖面城市 |
| P8 | 离散数学 | 规则石砖与地下迷宫 |
| P9 | 微积分 | 蒙眼下山的探险者 |
| P10 | 线性代数 | 整齐方阵的批量变形 |
| P11 | 概率与统计 | 雾中的天气预报员 |
| P12 | 编程 | 给最死板的厨师写菜谱 |
| P13 | 管理复杂度 | 积木模块工厂 |
| P14 | 数据结构 | 仓库货架的摆法 |
| P15 | 算法 | 快递员找最短路线 |
| P16 | 芯片 | 亿万开关组成的微缩城市 |
| P17 | CPU 与 GPU | 一位教授与一千个小学生 |
| P18 | 操作系统 | 大管家 |
| P19 | 计算机网络 | 套娃信封的邮政系统 |
| P20 | 编译器 | 翻译官 |
| P21 | 数据库 | 巨型档案馆 |
| P22 | 软件工程 | 工地与蓝图 |
| P23 | 前端与后端 | 餐厅前厅与后厨 |
| P24 | 分布式系统 | 千只蚂蚁搬一块大饼 |
| P25 | 云计算 | 像用电一样用算力 |
| P26 | 大数据 | 数据河流与自来水厂 |
| P27 | 信息安全 | 城墙、警察与白帽 |
| P28 | 两种造机器的方法 | 写规则 vs 看例子 |
| P29 | 训练 | 猜、对答案、微调，重复亿次 |
| P30 | 深度学习 | 层层流水线认出一只猫 |
| P31 | 大模型 | 读完整座图书馆的学者 |
| P32 | RAG | 先查档案再回答 |
| P33 | 智能体 | 带工具腰带的管家 |
| P34 | 算力与数据中心 | AI 的发电厂 |
| P35 | 工种大地图 | 全城职业分布 |
| P36 | 造产品的人 | 规划师、橱窗设计师、后厨、质检员 |
| P37 | 让城市运转的人 | 消防员、修路工、档案馆长、地基工程师 |
| P38 | 挖掘价值的人 | 侦探、自来水工、预报员 |
| P39 | AI 的人 | 媒人、配工具的人、探险家、发电厂工程师 |
| P40 | 守护与连接的人 | 警察、外交官、指挥 |
| P41 | 市场规律 | 金河与深矿 |
| P42 | 技术是工具 | 一面工具墙 |
| P43 | 学习之路 | 从地基分叉的道路 |
| P44 | 塔顶俯瞰 | 一句话看懂全城 |
| P45 | 封底 | 夜晚亮灯的比特城 |

## 全局画风与角色设定

下面四段是全书的“定海神针”。每页 prompt 里已经嵌入了它们的内容；单独列出来，是为了你先生成定妆图，或以后自己加页时复用。

### 风格段（每页 prompt 的结尾都是它）

```text
Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### 主角定妆图：Sylvan（外行访客，代表读者）

他不懂技术，但很聪明、爱追问“这到底是干嘛的”。他的反应就是读者的反应。

```text
Character design sheet of Sylvan, a handsome Chinese man in his late twenties with short, neat, slightly textured black hair, warm brown eyes, clean-shaven, no glasses, a tall athletic build, a black leather coat over a white shirt, dark trousers, brown ankle boots and a brown leather satchel with a small notebook sticking out. Show him in front view, side view and back view, plus four facial expressions in small bust portraits: curious, puzzled, surprised, delighted. Plain cream paper background, even spacing, no props. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, no text, no letters, no logos, 4:3 landscape.
```

### 向导定妆图：比特（向导机器人）

它是比特城的导游。它的屏幕脸会变换表情，用来提示读者“看这里”。

```text
Character design sheet of Bit, a small floating egg-shaped white robot about the size of a house cat, with a rounded dark teal screen for a face showing two simple glowing friendly eyes, a short antenna with a glowing coral tip, two tiny stubby arms, and a soft blue hover-glow underneath instead of legs. Show front view, side view, three-quarter view, plus five screen-face expressions: happy eyes, thinking (three dots), pointing (a small arrow shape), surprised (wide circles), proud (closed smiling eyes). Plain cream paper background, even spacing. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, no text, no letters, no logos, 4:3 landscape.
```

### 城市设定：比特城长什么样

全书的城市均按这个分层结构画，每一层对应行业价值链的一段：

| 层 | 画面元素 | 代表什么 |
| --- | --- | --- |
| 岩床 | 刻着几何花纹、微微发光的石砖 | 数学 |
| 地下发电厂 | 无数微小开关组成的巨大发光机房 | 芯片与算力 |
| 街道与管道 | 气动信管、邮政小车、穿梭的信封 | 网络 |
| 市政厅 | 一位调度一切的管家 | 操作系统 |
| 彩色楼房 | 商店、餐厅、工地 | 软件产品 |
| 档案馆与水厂 | 巨型档案馆、发光的数据运河和水塔 | 数据 |
| 中央高塔 | 细长的玻璃塔，塔顶一盏柔和发光、像大脑纹路的灯笼 | AI |
| 城墙 | 环绕全城的矮墙和巡逻岗亭 | 安全 |
| 天空 | 飘着可以租用的“云工厂” | 云计算 |

### 通用反向提示词（模型支持时填入）

```text
text, letters, numbers, captions, watermark, logo, real brand names, photorealistic, glossy 3D render, dark or gloomy mood, cluttered unreadable composition, distorted hands, extra limbs, inconsistent character design
```

## 序章 · 走进比特城

### P1 · 封面

**配文**：《比特城漫游记》——一座城市，看懂整个计算机行业。这本书写给觉得“计算机”离自己很远的人，也写给被技术细节困住、看不见全局的人。我们不讲代码，只讲这座城为什么存在、靠什么运转、城里的人在忙什么。

**画面要点**：一眼看出“这是一座分层的城市”，从地下岩床到中央高塔层层可见。

```text
Book cover illustration, 3:4 portrait. A grand cross-section view of Bit City at dawn, built in clearly visible layers: at the bottom a bedrock of softly glowing stone tiles carved with geometric patterns; above it an underground power plant made of countless tiny glowing switches; above that, streets full of pneumatic tubes, little postal carts and flying envelopes; then colorful buildings — shops, restaurants, construction sites, a giant archive library — with canals of glowing blue water flowing between them; at the very center a tall slender glass tower crowned with a softly glowing lantern patterned like brain folds; small cloud-shaped factories float in the pale sky. In the foreground on a grassy hill, Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands looking at the city in wonder, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) floats beside him, pointing toward the tower. Leave a large clean empty band across the top third for the book title. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle dawn light, no text, no letters, no logos, 3:4 portrait.
```

### P2 · 这个行业到底在做什么

**配文**：Sylvan抱着一大摞纸来到城门口：账单、地图、信件、照片。比特说：“这座城里的所有人，其实只在做一件事——让处理信息变得几乎不要钱。”过去，算一笔账要会计忙一下午，寄一封信要走一个月，找一张旧照片要翻遍整个抽屉。今天，这些事在一瞬间完成，而且几乎免费。计算机行业的全部价值，就藏在这个“几乎免费”里：当一件事的成本降到接近零，人类就会把它做一万倍、一亿倍，新的产业就此诞生。

**画面要点**：城门外是缓慢的旧世界，城门内是瞬间流动的光；纸张穿过城门变成光点。

```text
A wide scene split by a tall stone city gate in the middle. Left side, outside the gate: a slow old-world landscape in faded sepia tones — a clerk hunched over an abacus and ledger at a wooden desk, a postman on horseback riding down a long dusty road, a woman rummaging through an overflowing drawer of old photos. Right side, inside the gate: bright and lively Bit City streets where the same kinds of things move as swift streams of tiny glowing light particles flowing along the streets and into buildings. At the gate, Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) carries a tall wobbly stack of papers — bills, maps, letters, photographs — and as each sheet passes through the archway it dissolves into a ribbon of glowing light. Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) floats beside him with a proud expression. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P3 · 原理一：说得清的事，就能交给机器

**配文**：比特递给Sylvan一张长长的菜谱，又指了指一位厨师机器人。“这位厨师什么都不懂，但绝不会出错——只要菜谱写得足够清楚。”这是计算机的根本：凡是能被说清楚步骤的事，都能交给机器做。算工资、转账、订票、排班，本质都是“按规则处理信息”。但机器也极度死板：菜谱里少写一步“先把蛋壳剥掉”，它就会连壳一起下锅。程序员的工作，就是把人的意图翻译成机器绝不会误解的菜谱。那说不清楚的事呢？很长一段时间里，机器做不了——直到后面我们会遇到的 AI。

**画面要点**：机器严格照菜谱做事；少一步就闹笑话。

```text
A bright cutaway kitchen inside Bit City. A boxy, literal-minded chef robot with a flat face and many precise mechanical arms follows a very long unrolled paper scroll recipe that drapes across the counter and onto the floor; the recipe is drawn as a sequence of small pictogram icons only (egg, crack, bowl, whisk, pan, flame), no words. The robot performs each step with perfect precision. In a small inset vignette on the right, a second identical robot whose recipe is missing one icon cheerfully drops a whole uncracked egg, shell and all, into a sizzling pan, with a tiny puff of smoke. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) watches with an amused, thoughtful expression, while Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) holds the top end of the scroll. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P4 · 原理二：算力越来越便宜

**配文**：博物馆的长廊里陈列着一排机器。第一台大得像一整间房子，要一群人伺候；下一台像衣柜，再下一台像书桌，然后是笔记本、手机——最后一颗芯片小到放在Sylvan的指尖上，却比第一台强大不止百万倍。这是第二条原理：同样一次计算，成本每隔几年就便宜一大截。芯片上的开关越做越小、越做越多，几十年来从未停止。昨天贵到做不起的事，今天变得随手可做——智能手机、视频通话、大模型，都是算力便宜到某个临界点后才突然出现的。理解这一点，就能理解为什么科技行业总在“突然”变天。

**画面要点**：机器一台比一台小，旁边代表价格的金币堆也一堆比一堆矮。

```text
A long sunlit museum gallery hall seen in perspective, with a gently curving path on the floor leading from left to right. Along the path stands a row of computing machines shrinking step by step: first a room-sized machine of glowing vacuum tubes and cables tended by several tiny technicians on ladders; then a refrigerator-sized mainframe with spinning tape reels; then a beige desktop computer; then a laptop; then a smartphone; and at the far right end, a single tiny glowing chip resting on the fingertip of Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel), who stares at it in astonishment. Beside each machine sits a stack of gold coins on a small pedestal, the stacks getting dramatically shorter from left to right, the last one just a single small coin. Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) points along the path. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P5 · 原理三：复制一份几乎不要钱

**配文**：比特翻开一本发光的书，书页飞出去，在空中变成成千上万本一模一样的书，飞向世界各地的窗口。“造第一本很贵，复制后面的一百万本几乎不要钱。”这是软件和传统工厂最大的不同：造一辆车要一份钢铁，造第二辆还要一份；一份软件写好之后，却可以无限复制。所以科技公司能在短短几年里服务几亿人，也容易出现“赢家通吃”——最好的产品可以低成本地买到所有人手上。这也解释了为什么好的工程师值钱：一个人写下的东西，可以被放大到全世界。

**画面要点**：右边一本书变成漫天的书，左边每辆车都要各自的一堆钢铁，形成对比。

```text
A wide scene with a strong left-right contrast. Left third: a traditional car factory where each car on the assembly line needs its own heavy pile of steel beams, rubber and glass, workers straining to haul materials, every car identical but each costing a full pile. Right two-thirds: on a hilltop pedestal, Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) opens a single glowing book; its pages lift off and multiply into a vast swirling flock of thousands of identical small books flying out over a landscape of towns, cities, farms and distant coastlines, gliding into the windows of homes, offices, schools and into the screens of tiny phones held by tiny people. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) shields his eyes and watches the flock spread toward the horizon. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P6 · 原理四：AI 学会了“说不清的事”

**配文**：城里有一位学徒机器人，它面前堆着山一样的猫和狗的照片。没有人告诉它猫的定义——“尖耳朵？可有的狗也是尖耳朵。”它只是一张张看、一次次猜，猜错了就调整自己。看完之后，它能认出一只从没见过的猫。这是第四条原理，也是这个时代最大的变化：有些事人做得到，却说不清怎么做到——认人脸、听懂话、写文章、看懂一张 X 光片。AI 不靠人写规则，而是从大量例子里自己学出规则。自动化的边界，第一次从“规则明确的事”推到了“需要判断的事”。

**画面要点**：没有菜谱，只有堆积如山的例子；学徒通过分拣例子学会了辨认。

```text
A cozy cutaway study room piled high with towering stacks of photographs of cats and dogs of every breed, color and pose. In the middle sits an apprentice robot, taller than Bit, made of warm brass and teal panels with large round camera-lens eyes, sorting photos one by one into two big woven baskets, one marked only with a small cat silhouette and the other with a small dog silhouette. A few photos in the wrong basket glow softly coral as if being gently corrected. Through a large window on the right, a real fluffy cat the robot has never seen walks along a garden wall, and the apprentice robot points at it confidently, a tiny warm glow above its head. There is no recipe scroll anywhere in this room, to contrast with the kitchen robot. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) leans in the doorway, impressed, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) floats beside him with a thinking face. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P7 · 城市全景：一张图看懂价值链

**配文**：爬上山坡，Sylvan第一次看清比特城的全貌。它像一块分层的蛋糕：最底下是数学的岩床；岩床之上是芯片组成的地下发电厂，为全城提供算力；发电厂之上是四通八达的网络街道；街道上盖满了软件的楼房——商店、餐厅、档案馆；数据像水一样在运河里流动，被水厂净化后送到每一栋楼；城市中央的高塔是 AI，它从流过的数据里学习，让整座城越来越聪明；城墙和巡逻岗亭守护着一切；天上飘着可以按小时租用的“云工厂”。比特说：“记住这张图。之后的每一门学问、每一种职业，都只是这座城的某一层、某一个角落。”

**画面要点**：层次分明的剖面图，每一层都能被认出来；这张图是全书的“地图”，后面反复回到它。

```text
A grand panoramic cross-section of Bit City, cut open like a layered cake so every level is visible from the side. From bottom to top: a bedrock layer of softly glowing stone tiles carved with geometric patterns; an underground power plant hall made of countless tiny glowing switches with little engineers walking catwalks; a street level with pneumatic tubes, postal carts and flying envelopes zipping between buildings; colorful buildings on top — a shop with a big display window, a restaurant with a busy back kitchen, a construction site with blueprints, a huge domed archive library; canals of glowing blue water running from a water-treatment plant into every building; a low city wall with small watchtowers and patrolling guards around the edge; at the center a tall slender glass tower crowned with a softly glowing lantern patterned like brain folds, drawing faint streams of light up from the canals; small cloud-shaped factories with tiny chimneys floating in the sky above. On a grassy lookout hill in the left foreground, Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) looks through brass binoculars, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) gestures across the whole city. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

## 第一章 · 地基：数学

比特带Sylvan坐升降梯下到城市最底层。这一章讲清一件事：数学不是用来考试的，它是机器描述世界的语言。离散数学描述规则，是传统软件的地基；微积分、线性代数、概率统计描述变化和不确定，是 AI 的地基。

### P8 · 离散数学：规则的石砖

**配文**：升降梯一路往下，停在城市的最底层。这里没有楼房，只有一块块严丝合缝的石砖，每块砖上都刻着简单的规则：“是”或“否”、“如果……就……”、“连着”或“不连着”。比特说：“计算机的世界里没有模糊，只有一个个分开的东西和它们之间的规则。描述这些的数学，叫离散数学。”石砖拼成了一座地下迷宫，迷宫的走法就是“图论”：导航怎么找最短的路、社交网络里谁认识谁、快递网怎么连，都是这张由点和线组成的网。石砖之间精巧的锁扣，是密码学的源头。这一层没人看得见，但整座城都压在它上面。

**画面要点**：地基由刻着规则的石砖组成，石砖拼出一张“点和线”的网络迷宫；头顶就是繁忙的城市。

```text
A vast underground cavern at the very bottom of Bit City, lit by a soft glow rising from the floor. The floor and walls are made of perfectly fitted stone tiles, each carved with simple geometric symbols only — a filled circle and an empty circle, an arrow from one shape to another, two shapes joined by a line or separated by a gap — no letters. Seen from slightly above, the tiles form a giant maze whose paths connect glowing round stone nodes like a network of dots and lines; one shortest route between two distant nodes is highlighted in warm coral light, with a tiny courier walking along it. In one corner, interlocking tiles with intricate puzzle-like locks hint at secret-keeping. Massive stone pillars rise from the tiles toward the ceiling, through which the busy city layers above are faintly visible. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) descends in an open brass elevator cage together with Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow), both looking down at the maze in awe. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P9 · 微积分：蒙眼下山的探险者

**配文**：穿过迷宫，前方出现一片起伏的山谷。一位蒙着眼睛的探险者正在下山。他看不见谷底在哪，只能用脚感受：哪边更陡，就往哪边迈一小步。走一步、再摸一摸、再迈一步……最后稳稳地到了谷底。比特说：“这就是微积分在 AI 里的作用。”微积分研究“变化”——这里挪一点，那里跟着变多少。AI 学习时就像这位探险者：它不知道最好的答案在哪，只知道“自己现在错了多少”，于是算出哪个方向能让错误变小，挪一小步，再算，再挪，重复上亿次。山谷的谷底，就是错误最小的地方。

**画面要点**：蒙眼、一步一步往低处走；谷底代表“错误最小”。

```text
A sweeping landscape of smooth rolling hills and a deep valley under a soft sky, the terrain drawn like a gentle curved surface. A blindfolded explorer with a walking stick and a small backpack carefully steps downhill, testing the slope with one foot. A dotted trail of small footprints winds from a high peak down toward the lowest point of the valley, where a small glowing pool sits. At several footprints, a tiny arrow of light on the ground points in the steepest downhill direction. Mist covers the far hills, showing the explorer cannot see the whole map. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) watch from a rocky ledge partway down, Bit's screen face showing a small downward arrow. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P10 · 线性代数：整齐的方阵

**配文**：山谷尽头是一座大广场。成千上万的小人排成整齐的方阵，一声号令，整个方阵同时转身、拉伸、变形，像一个整体。“一个一个指挥太慢了，”比特说，“线性代数就是把一大堆数当成一个整体，一次性批量变换。”在 AI 眼里，一张照片是一个巨大的数字方阵，一句话、一位用户、一件商品也都被变成一串数。神经网络的每一层，本质就是一次“整个方阵同时变换”。而 GPU 之所以成为 AI 时代最被争抢的资源，正是因为它最擅长同时指挥巨大的方阵。

**画面要点**：整个方阵同步变形，对比一个一个指挥的低效；照片被拆成格子。

```text
A grand open parade square seen from above at an angle. Thousands of tiny identical figures in teal and mustard uniforms stand in a perfect rectangular grid formation. The formation is shown in three successive stages across the square from left to right: first a neat rectangle, then the whole grid rotated together, then the whole grid stretched and slanted into a parallelogram, every figure moving in perfect unison. A conductor on a tall podium raises a single baton that controls the entire formation at once. In a small vignette at the bottom left, a lone harried sergeant tries to move figures one at a time and is falling far behind. On an easel nearby, a framed photograph of a landscape dissolves at its edge into a grid of tiny colored squares, hinting that pictures become grids of numbers. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) watch from the edge of the square. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P11 · 概率与统计：雾中的天气预报员

**配文**：广场外起了雾。一位天气预报员站在塔上，手里捧着厚厚的旧日记：过去无数个这样的早晨，大多数都下了雨。她没法确定今天会不会下，但她可以说：“带伞吧，很可能下雨。”比特说：“概率与统计，就是在信息不全时做出有把握的判断。”机器学习的本质就是统计：从过去的样本推断未来。大模型写字时，也是在问“下一个词最可能是什么”，按概率一个个挑出来。商业里的 A/B 实验、风控、保险定价，背后都站着这位预报员。

**画面要点**：雾中看不清未来，但凭历史记录能做出判断；不确定，但有把握。

```text
A misty morning town square, soft fog drifting between the buildings so the far distance is hidden. On top of a small round observation tower stands a weather forecaster in a long coat holding a huge open ledger filled with rows of tiny weather pictograms (sun, cloud, raindrops) recorded over many past days, no writing. Beside the tower, a long shelf of glass jars shows many jars filled with rain-blue marbles and only a few with sun-yellow marbles, visually showing that rain came more often. Below, townspeople calmly take umbrellas from a stand she has set out. A pair of dice and a small balance scale rest on the tower railing as quiet symbols of chance and judgment. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) holds an umbrella and looks up at the forecaster, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) floats beside him with a thinking expression. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, soft misty light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

## 第二章 · 语言：编程、数据结构与算法

回到地面，比特把Sylvan带进一座叫“语言学院”的大楼。这里教的不是外语，而是怎么对机器说话。这一章讲清：编程是一种精确表达的能力；数据结构和算法决定事情做得快不快、能不能扛住规模。

### P12 · 编程：人和机器之间的翻译

**配文**：教室左边坐着一位客户，她说：“我想要一个让顾客开心的点餐系统。”右边站着一台机器，它只听得懂“第一步、第二步、如果……就……”。中间的程序员把“开心”这个模糊的愿望，拆成了几百张精确的小卡片：顾客点了什么、库存够不够、不够时怎么办、付款失败又怎么办。比特说：“编程本质上不是技术活，而是一种极度精确的表达。”各种编程语言就像不同的方言，核心本事是一样的：把一件事想到没有任何歧义。在 AI 已经能帮忙写代码的今天，这种“把问题说精确”的能力反而更值钱——因为你要告诉 AI 的，也是同一件事。

**画面要点**：模糊的愿望 → 程序员拆解 → 精确的步骤链 → 机器执行。

```text
A bright classroom in a building called the Language Academy, shown in cutaway. On the left, a client sits in an armchair with a soft dreamy thought bubble showing a cozy cafe full of smiling customers. On the right stands a rigid boxy machine with a slot for cards and a single attentive eye, waiting. In the middle, a programmer at a large wooden drafting desk translates between them: she takes the fuzzy cloud-like wish from the client and turns it into a long chain of hundreds of small, crisp, neatly linked cards, each showing one simple pictogram (a cup, a checkmark, a fork in the road, a coin, a warning triangle), no text; the chain snakes across the floor and feeds into the machine's slot. Some cards show branching paths, as if handling what-if situations. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands behind the programmer looking over her shoulder, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) points at the chain. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P13 · 管理复杂度：积木模块工厂

**配文**：隔壁车间里，几十个小组正在合力搭一台巨大的机器。没有人能看懂整台机器，但没关系：每个小组只负责一个模块，模块外壳上留着标准的插口，只要插口对得上，就能稳稳拼在一起。比特说：“真实的软件动辄几十万行、上百人维护很多年。让它不崩的办法，和管理一家大公司一样：分工、各管各的事、部门之间只通过说好的方式打交道。”大学里叫它“面向对象”和“模块化”，本质都是管理复杂度。插口（接口）一旦定下来，模块内部怎么改都不会影响别人。这也是大公司能组织成千上万工程师同时工作的秘密。

**画面要点**：大机器由标准模块拼成；每个小组只管自己的一块；插口是关键。

```text
A huge cutaway factory hall where dozens of small teams in different colored overalls each work at their own bench on one boxy module — a gear box, a lantern box, a pump box, a clock box. Every module has the same standardized plugs and sockets on its sides, drawn clearly and highlighted in coral. In the center of the hall, a giant intricate machine is being assembled by fitting these finished modules together like building blocks, with a crane lowering one module into place where its plugs line up perfectly. Inside one open module, a team is rebuilding its internal gears while the plugs on the outside stay unchanged. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands on a catwalk overlooking the hall, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) holds up a single plug to show him. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P14 · 数据结构：仓库货架怎么摆

**配文**：两座一模一样的仓库，存着一模一样的货。左边的仓库里货物随手乱堆，工人打着手电筒翻了半天也找不到；右边的仓库按编号分区摆放，工人抬手就拿到。比特说：“信息在机器里怎么摆放，叫数据结构。摆法不同，速度可以差几千倍。”仓库里还有各种专门的摆法：先到先得的传送带（队列），只能从顶上拿的一摞盘子（栈），按大小分叉的滑道（树），每个格子都有对应标记的储物柜（哈希表）。数据库、搜索引擎、导航、社交网络，内部都是这些货架的组合。

**画面要点**：乱堆 vs 有序的对比；右边仓库里展示几种典型摆法。

```text
Two identical warehouses side by side, shown in cutaway. Left warehouse: goods piled in chaotic heaps to the ceiling, a tired worker with a flashlight digging through boxes, cobwebs and a long wait suggested by a large hourglass. Right warehouse: the same goods neatly organized and easy to reach, a cheerful worker grabbing the right box instantly; inside it, several clearly different storage arrangements are visible — a conveyor belt where parcels leave in the order they arrived; a tall spring-loaded stack of plates where only the top plate can be taken; a branching wooden chute that sorts balls left or right at each fork like an upside-down tree; and a wall of small cubbyholes, each marked with a distinct colored shape, with a worker dropping an item straight into its matching cubby; a tiny hourglass here shows almost no waiting. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands in the doorway between the two warehouses comparing them, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) floats above the tidy side. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P15 · 算法：快递员找最短路线

**配文**：两位快递员要在一天里送完一百个地址。第一位把每种走法都试一遍，地图上画满了乱线，累得坐在地上；第二位出发前用一个聪明的方法规划好路线，下午就喝上了茶。比特说：“同一件事，找到最省力的做法，就是算法。”地址少的时候差别不大，但规模一大，好坏算法的差距会从“几秒”变成“几年”。你输入一个词，搜索引擎在海量网页里瞬间给出结果；导航在无数路口中瞬间算出路线；推荐系统在上亿商品中瞬间挑出你可能喜欢的——靠的都是好算法。这也是大公司面试爱考算法的原因：它考的是你面对规模时的思考方式。

**画面要点**：笨办法 vs 聪明办法的强烈对比；一个累倒，一个轻松。

```text
A bird's-eye view of a charming town map spread out like a tabletop diorama, dotted with many little houses marked by small coral flags for delivery stops. On the left half, an exhausted courier sits slumped against his bicycle, surrounded by a tangled chaotic scribble of crisscrossing paths covering the map, a giant hourglass beside him nearly empty, a heap of worn-out shoes nearby. On the right half, a second courier rides a bicycle along a single clean elegant loop that visits every flag once, a small hourglass barely used; at the end of the loop she sits at a little cafe table sipping tea. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) leans over the edge of the diorama table comparing the two, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) traces the clean loop with a beam of light. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

## 第三章 · 机器的内部

比特推开一扇厚重的铁门，带Sylvan走进城市的地下发电厂——也就是机器的内部。这一章回答三个问题：机器为什么能跑、为什么会慢、为什么会崩。懂这一层的人少，所以在任何技术公司里都是“压舱石”。

### P16 · 芯片：亿万个开关组成的微缩城市

**配文**：比特递给Sylvan一把放大镜。镜头下，那颗指甲盖大的芯片展开成一座密密麻麻的微缩城市，街道上排满了小开关，每个开关只会做一件事：开或关。但几个开关组合起来就会做加法，再组合就会记住东西；几十亿个开关一起工作，就是一台计算机。比特说：“整个数字世界，都是从这些开关长出来的。”芯片越做越小，开关就越挤越多，算力就越便宜。制造最先进芯片的工厂全世界屈指可数，造价动辄数百亿美元，所以芯片成了国家之间争夺的战略资源。

**画面要点**：三级放大：指尖芯片 → 微缩城市 → 一个个开关。

```text
A magical zoom illustration in three nested levels. At the bottom left, Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) holds a large brass magnifying glass over a tiny glowing chip resting on a velvet cushion, while Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) floats beside him. Inside the lens, the chip opens up into a sprawling miniature city seen from above, a dense grid of streets lined with countless tiny toggle switches, some up and lit coral, some down and dark, with paths of light flowing between districts. A second circular zoom bubble at the top right shows just a few switches up close, wired together into a small cluster, with tiny workers in hard hats flipping them and a little stream of light passing through. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle warm glow, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P17 · CPU 与 GPU：一位教授与一千个小学生

**配文**：发电厂里有两个房间。左边住着一位全能教授（CPU），再复杂的难题他都能解，但一次只能专心做少数几件事。右边坐着一千个小学生（GPU），每个人只会做简单的算术，但他们可以同时开工。现在来了一万道简单的乘法题——教授还在第一页，小学生们已经交卷了。比特说：“AI 的计算，恰恰就是海量的简单乘法。”这就是为什么在 AI 浪潮里，GPU 成了最稀缺的资源，做 GPU 的公司价值飙升——就像淘金热里卖铲子的人。对外行来说记住一句就够：CPU 擅长“难而少”，GPU 擅长“简单而多”。

**画面要点**：一个聪明人 vs 一大群同时干活的人；一大堆简单题目谁先做完。

```text
A cutaway of two adjoining rooms inside an underground power plant. Left room, small and cozy: a single brilliant elderly professor with wild white hair works intensely at a chalkboard covered in elaborate abstract chalk diagrams (shapes and curves only, no writing), solving one complex puzzle at a time; beside him a towering stack of ten thousand small task cards barely touched. Right room, a vast hall: a thousand small schoolchildren in matching teal uniforms sit in neat rows of tiny desks, each solving one simple card at the same moment; finished cards fly from their desks into a huge basket that is already full, a few children cheering. A wide doorway between the rooms lets the viewer compare both at once. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands in the doorway looking from one room to the other, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) carries one more stack of cards toward the children. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P18 · 操作系统：机器的大管家

**配文**：发电厂上方是一座繁忙的旅馆。几百位客人（程序）同时入住，都想上台演出（用 CPU）、都想要房间（内存）、都要存行李（文件）。谁先谁后？谁住哪间？谁不许进谁的房间？大厅中央的大管家一手安排：每位客人轮流上台几毫秒，快到你感觉大家是同时在演；房间钥匙各发各的，谁也偷看不了别人的行李。比特说：“这就是操作系统。你手机和电脑里的 Windows、macOS、安卓、iOS，还有服务器上的 Linux，都是这位管家。”谁控制了操作系统，谁就决定了哪些客人能入住、要交多少房费——这是整个科技产业里最有权力的位置之一。

**画面要点**：大管家在中央调度一切：轮流上台、分房间、管行李、守门。

```text
A grand old hotel shown in full cutaway, many floors visible. At the center of the lobby, a calm, impeccably dressed butler stands at a round command desk beneath a giant clock dial divided into many tiny colored slices, pointing a baton at a small spotlit stage where one guest at a time performs for a brief moment while a neat queue of other guests waits in the wings, each guest a different playful character holding a small suitcase. Up the floors, rooms are assigned with numbered-looking but symbol-only keys hanging on a key board; one guest tries to peek into another guest's room and is politely stopped by a uniformed doorman. In the basement, a tidy luggage room with labeled-by-color shelves stores suitcases. Bellhops rush between floors carrying luggage. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands at the reception desk watching the butler, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) hovers near the clock dial. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P19 · 计算机网络：套娃信封的邮政系统

**配文**：Sylvan想把一张照片寄给地球另一端的朋友。邮局把照片切成很多小块，每块装进一个信封，外面再套一层写着地址的信封，再套一层……然后交给邮差。信封们各走各的路，有的绕远，有的丢了就重寄一份，最后在朋友那里按顺序拼回原样。比特说：“这就是互联网：在不可靠的线路上，可靠地传东西的一整套约定。”层层套信封的好处是分工：写信的人不用管卡车走哪条路，卡车司机也不用看信里写了什么。这套约定支撑了网购、视频、云服务和远程办公，而铺在海底的光缆把各大洲连在了一起。

**画面要点**：切块 → 层层套信封 → 分头走不同路线 → 对方拼回原样。

```text
A sweeping illustration of a global postal network. On the left, inside a bustling post office, a photograph of a sunny beach is cut into puzzle pieces by clerks; each piece is slipped into a small inner envelope, then into a bigger envelope of a different color, then into a third outer envelope, shown clearly as nested layers in a cutaway of one envelope. The envelopes are sent out through pneumatic tubes, onto little trucks, trains, ships and propeller planes, each taking a different route across a stylized world map; glowing cables run along the ocean floor between continents. One envelope falls off a truck into a puddle, and a fresh copy is already flying out from the post office to replace it. On the right, in a friend's cozy home across the ocean, a person unwraps the layers and reassembles the beach photo piece by piece on a table. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) waves from the post office counter, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) rides along on top of one of the trucks. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P20 · 编译器：会优化的翻译官

**配文**：程序员写的程序，是人能读懂的语言；芯片只认最底层的“机器语言”——一长串开关信号。两者之间，坐着一位翻译官：编译器。它不只是逐句翻译，还会把啰嗦、重复的地方精简掉，让机器跑得更快。比特说：“没有这位翻译官，就没有各种编程语言。”今天它还有一个新战场：同一个 AI 模型，要在不同厂商的芯片上都跑得快，靠的就是好的翻译官。开发者习惯了哪家的翻译工具，就很难离开哪家的芯片——这是芯片公司争夺开发者的隐形战场。

**画面要点**：人类友好的圆润图标 → 翻译官 → 一串明暗珠子（开关信号）；纸篓里是被精简掉的多余步骤。

```text
A cozy cutaway translator's booth set between two worlds. On the left, a programmer hands over a scroll covered in friendly rounded pictogram icons (no letters). In the booth sits a translator with half-moon spectacles surrounded by tall stacks of thick reference books, rapidly converting the scroll into a long ribbon of tiny glass beads, each either bright coral (on) or dark slate (off), that feeds out of the booth into the slot of a huge humming machine on the right whose lights blink in rhythm with the beads. Under the desk, a wastebasket is filled with crossed-out duplicate icon cards that the translator removed to make the ribbon shorter and faster. A second, different-shaped machine waits behind the first, and the translator has a different ribbon spool ready for it. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) peeks into the booth, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) holds one end of the bead ribbon. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

## 第四章 · 盖楼：把零件变成真正的系统

回到地面，城里到处是工地和店铺。前几章是零件，这一章看零件怎么盖成真正的楼。每一栋楼，都对应着产业里的一类大生意。

### P21 · 数据库：全城的档案馆

**配文**：城中心有一座圆顶档案馆，里面存着全城的记忆：每个人的银行余额、每一笔订单、每一件库存。档案馆要做好三件事：存得下——再多也不能丢；找得快——几十亿条记录里瞬间找到你那一条；多人同时改也不出错——两个人同时抢最后一张票，只能有一个人成功，另一个必须被告知“卖完了”，账目绝不能对不上。比特说：“数据库就是每家企业的账本和记忆。”有公司单靠卖数据库就成了全球巨头；而对一家公司来说，数据库出事，往往就是公司级的灾难。

**画面要点**：海量档案、快速索引、“最后一张票”只给一个人、地下备份金库。

```text
A magnificent domed archive library shown in cutaway, with endless curved rows of wooden filing cabinets rising many stories high and librarians gliding on rolling ladders. Near the entrance, a large brass card-catalog index desk where a librarian instantly pulls out exactly the right drawer for a visitor. At the front counter, two customers reach for the very last concert ticket at the same instant; the librarian calmly stamps it for one customer while gently showing the other an empty slot, both looking fair and orderly. Below the floor, a cutaway basement shows a steel vault holding neat duplicate copies of the archive as a backup. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands at the index desk amazed, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) points down toward the backup vault. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P22 · 软件工程：工地与蓝图

**配文**：一栋摩天楼正在一层层往上盖。规划师拿着蓝图，工头拿着清单，验收员每盖好一层就上去敲一敲；客户走进已经盖好的两层，说“窗户再大一点”，于是下一层就按新意见盖。比特说：“软件也是这样盖出来的。”很多软件项目失败，不是因为技术不行，而是需求说不清、协作混乱、改了这里坏了那里。软件工程就是软件行业的管理学：版本管理让每一次修改都有记录、随时能退回；测试就是验收；“敏捷开发”就是先盖一层、给客户看、再盖下一层，而不是闷头盖三年才发现盖错了。

**画面要点**：一层层盖、每层验收、客户中途给意见；一面墙按顺序钉着历版蓝图。

```text
A lively construction site of a tall skyscraper being built floor by floor, shown in cutaway. The lower floors are finished and furnished; the middle floors have workers installing windows; the top is bare scaffolding with a crane. A planner unrolls a large blueprint on a table at the base, a foreman holds a clipboard checklist, and an inspector in a white hard hat taps the walls of a just-finished floor with a small hammer. On one finished floor, a client in a suit gestures toward a window, suggesting it be bigger, while a worker takes a note, and the floor above already shows bigger windows. On the side of the site office, a long wall displays a neat row of pinned blueprint versions in order, one older version being pulled back down from a drawer as if restored. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) wears a borrowed hard hat and walks the site, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) floats near the wall of blueprints. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P23 · 前端与后端：餐厅的前厅和后厨

**配文**：Sylvan和比特走进一家餐厅。前厅明亮温馨：装修、菜单、服务员的笑容——这是前端，用户看得见、摸得着的部分。后厨热火朝天：备料、烹饪、记账、管库存——这是后端，用户看不见，却决定了能不能吃上饭。两边之间的传菜窗口就是“接口”，单子递进去，菜递出来。另一侧还有一个外卖窗口，给手机 App 下单的顾客出餐，用的是同一个后厨。比特说：“前厅漂亮后厨乱，顾客等一小时；后厨厉害前厅破，没人进门。”这就是为什么软件公司既要前端工程师，也要后端工程师。

**画面要点**：前厅（看得见）、后厨（看不见）、中间的传菜窗口、外卖窗口共用后厨。

```text
A cutaway of a charming restaurant split into two halves by a wall with a central pass-through window. Left half, the dining room: warm lights, elegant decor, a beautifully illustrated picture menu, smiling waiters taking orders from happy diners at tables. In the middle, the pass-through window where order tickets with simple food pictograms slide in and finished plates slide out, highlighted with a soft coral glow. Right half, the back kitchen: a bustling team of chefs chopping, frying and plating, a pantry storeroom with neatly stocked shelves, a cashier at a small desk keeping a ledger of pictograms, steam and motion everywhere. On the far right wall, a takeaway window serves delivery riders on scooters whose customers are shown in small thought bubbles holding phones, all served by the same kitchen. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) sits at a dining table, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) peeks through the pass-through window into the kitchen. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P24 · 分布式系统：千只蚂蚁搬一块大饼干

**配文**：购物节零点一到，全城的人同时下单。一位力士想独自举起这块巨大的饼干，挣得满脸通红也举不动。旁边，一千只蚂蚁分成小队，每队负责一块，稳稳地把饼干搬回家——中途有几只累倒了，立刻有新的补上，饼干一点没停。比特说：“一台机器再强也有上限。分布式系统就是让成千上万台普通机器分工合作，像一台超级机器一样工作，坏几台也不停。”难点在于：怎么分工、怎么让大家的账对得上、有人掉队怎么办。所有超大规模的互联网服务、所有大模型的训练，都建立在这套“蚁群法则”之上。

**画面要点**：一个巨人举不动 vs 蚁群分工搬走；有蚂蚁倒下也有替补。

```text
A playful street-level scene in Bit City at night under festive lanterns, crowds of tiny shoppers holding glowing phones. On the left, a muscular strongman in a striped leotard strains and sweats trying to lift an enormous round cookie alone, his knees buckling. In the center and right, the same kind of giant cookie is being carried smoothly across the street by thousands of cheerful ants organized into color-coded teams, each team carrying its own section, small foreman ants with tiny flags coordinating at the edges. A few ants have sat down exhausted, and fresh replacement ants are already stepping into their places so the cookie keeps moving without stopping. The ants march toward a large anthill-shaped warehouse. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) crouches on the curb watching the ants, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) shines a gentle light on the replacement ants. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, warm festive evening light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P25 · 云计算：像用电一样用算力

**配文**：一百多年前，每家工厂都得自己建发电机房；后来有了电网，插上插头、按度付费就行。云计算是同样的故事：以前公司要自己建机房、买服务器、养运维团队；现在向亚马逊 AWS、微软 Azure、阿里云这样的公司按小时租用算力和存储，用多少付多少。比特说：“于是一家三个人的创业公司，从第一天起就能用上和大公司一样的基础设施。”云厂商成了数字时代的“电力公司”：赚的是规模的钱，客户越多、成本越低。今天，训练和运行 AI 的算力也大多是从云上租来的。

**画面要点**：旧时代各家自建发电机 vs 新时代插上插头从天上的云工厂取电、按量计费。

```text
A wide scene split diagonally between past and present. Upper left, in faded sepia: an old-fashioned factory with its own smoky generator shed in the yard, workers shoveling coal, a nervous owner counting heavy coins for the machinery. Lower right, in bright color: a modern street of small shops and tiny startup offices in garages, each simply plugging a cable into a wall socket; the cables rise along poles into the sky, where large friendly cloud-shaped floating factories with glowing windows and gentle propellers supply power to everyone below. Beside each shop, a small round brass meter with a needle spins slowly, showing pay-as-you-use. One tiny garage with three young founders is lit just as brightly as a big corporate tower. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) plugs a cable into a socket, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) floats up toward the cloud factories. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P26 · 大数据：数据河流与自来水厂

**配文**：城里的每一次点击、每一笔交易、每一辆车的位置，都变成一滴水，汇成一条条河。但河水是浑的：有重复、有错误、格式五花八门，不能直接喝。得先收集、过滤、净化、存进大水库，再通过管道送到每一栋楼：给分析师做报表、给推荐系统用、给 AI 训练。比特说：“数据不是石油，是自来水——不净化就没法用。”当水量大到一个水厂处理不了，就要很多个水厂一起工作，这就是“大数据”技术。负责这套自来水系统的人，叫数据工程师。

**画面要点**：浑水 → 水厂净化 → 水库 → 管道分送到分析师、商店和 AI 高塔。

```text
A panoramic cutaway of a city water system made of data. From the bustling city on the left, countless tiny glowing droplets, each containing a miniature icon (a shopping cart, a car, a heart, a coin, a footprint), stream out of buildings and vehicles into murky, tangled rivers. The rivers flow into a large water-treatment plant in the center with settling tanks, rotating filters catching debris and duplicate droplets, and tall purification towers where the water turns clear blue. Clean water is stored in a huge round reservoir, then distributed through neat pipes to the right side: an analyst's office where clean droplets form simple bar shapes on a wall, a shop window that lights up with personalized items, and the base of the tall glass AI tower drinking through a thick pipe. Plant workers in teal overalls monitor valves and gauges with needles. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands on a walkway over the filters, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) holds up a single clear droplet. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P27 · 信息安全：城墙、警察与白帽

**配文**：有财富的地方就有小偷。比特城的安全是一层层叠起来的：城门核验身份（登录认证）；每扇门有不同的钥匙，不该进的人进不去（权限）；保险箱里的东西就算被偷走，打开也只是一堆乱码（加密）；巡逻队和监控室日夜盯着异常（安全运营）；还有一群受雇的“白帽小偷”，专门试着闯进来，抢在坏人之前找到墙上的松砖（渗透测试）。比特说：“安全不产生收入，但一次数据泄露就可能带来巨额罚款和信誉崩塌。”越是重要的行业——银行、医院、能源——越舍得在安全上花钱。

**画面要点**：多层防护一目了然；白帽用粉笔圈出松砖；小偷偷到的只有乱码。

```text
A cutaway view of Bit City's protective layers. A sturdy low city wall with a gatehouse where guards check visitors' glowing badges before letting them through. Inside, a corridor of doors, each with a differently shaped lock and a matching colored key on a guard's ring. In a vault room, a cloaked thief in a dark corner has pried open a treasure chest, but its contents are a meaningless jumble of scrambled puzzle pieces, and he scratches his head. Up on the wall, a friendly white-hat tester wearing a white cap and a vest climbs with a rope and a checklist, marking a loose brick with a bright coral chalk circle for the builders to fix. In a watchtower, a monitoring room with round abstract glowing panels shows a guard spotting the thief and pressing a bell. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) shows his badge at the gate, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) points up at the white-hat tester. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

## 第五章 · 会思考的城市：AI

比特带Sylvan乘玻璃电梯登上城市中央的高塔。这一章是全书的高潮：传统软件是人写规则，AI 是机器从例子里自己学规则。它改变的不只是“软件能做什么”，而是“哪些工作还需要人”。

### P28 · 两种造机器的方法：写规则 vs 看例子

**配文**：高塔一楼有两间工作室，都在做同一件事：挑出垃圾邮件。左边的工程师一条条写规则：“出现‘中奖’就拦截”“出现‘汇款’就拦截”……规则贴满了一面墙，可骗子一换说法就溜过去了。右边的工程师一条规则也不写，只把十万封已经标好“正常”或“垃圾”的邮件喂给机器，让它自己找规律——它连乔装打扮的垃圾邮件也能认出来。比特说：“这就是机器学习：人提供数据和目标，机器提供规则。”代价是：你得有大量好数据；机器学到的规则，人往往说不清它为什么这么判。信用评分、广告投放、反欺诈、销量预测，都是右边这间工作室的生意，而且很多公司的利润直接取决于它准不准。

**画面要点**：左边规则墙越写越多仍被绕过；右边喂例子得到一道聪明的分拣门。

```text
Two side-by-side cutaway workshops on the ground floor of a tall glass tower, both sorting a stream of envelopes on conveyor belts. Left workshop: a tired engineer with ink-stained sleeves pins yet another card to an enormous wall already covered with hundreds of rule cards connected by tangled red strings, each card showing a tiny pictogram; meanwhile a sneaky envelope wearing a fake mustache and hat slips past her sorting gate unnoticed. Right workshop: a relaxed engineer pours big baskets of envelopes, each pre-stamped with either a green leaf seal or a red cross seal, into a large funnel-shaped learning machine full of softly glowing gears; out of the machine comes a smart glowing sorting gate that catches the same disguised envelope and drops it into a red bin. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands in the hallway between the two rooms, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) points at the caught envelope. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P29 · 训练：猜、对答案、拧旋钮，重复亿次

**配文**：高塔里一台机器正在“上课”。老师举起一张卡片，机器猜“狗”，老师亮出答案“猫”。于是机器身上成千上万个小旋钮各自拧一点点——往哪边拧、拧多少，就是第一章里那位蒙眼下山的探险者算出来的。然后下一张，再下一张……亿万次之后，旋钮停在了最好的位置。比特说：“这些旋钮叫参数，大模型有数千亿个甚至更多。”训练很贵：要海量数据、大量 GPU 和很长的时间。但训练好之后，每一次使用（推理）都便宜得多——这又回到了序章的第三条原理：造一次很贵，用无数次几乎不要钱。

**画面要点**：猜 → 对答案 → 微调旋钮的循环；一面巨大的旋钮墙。

```text
A cutaway classroom high inside the glass tower. A patient teacher holds up a flash card showing a cat while a large friendly learning machine, its speech bubble showing a small dog silhouette, realizes its mistake as the teacher flips the card to reveal a glowing cat silhouette answer. The back of the machine is an enormous wall covered with thousands of tiny brass knobs, and a crew of miniature technicians on rolling ladders give each knob a tiny twist, their adjustments shown by small curved arrows. A glowing loop of light runs from the answer card, through the knob wall, and back to the machine, showing the cycle of guess, check, adjust. Behind the teacher, a mountain of flash cards stretches up out of view, and a large hourglass and a turning wheel suggest an immense amount of repetition. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) sits at a student desk taking notes, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) helps turn one knob. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P30 · 深度学习：层层流水线认出一只猫

**配文**：一张猫的照片被送进一条多层流水线。第一层的工人只看得见明暗的边缘；第二层把边缘拼成圆圈和尖角；第三层认出眼睛、耳朵、胡须；最顶层宣布：这是一只猫。没有人教过他们“眼睛长什么样”，每一层关注什么，都是在训练里自己学会的。比特说：“这就是深度学习，‘深’指的是层数多。”它让机器第一次能处理照片、声音、文字这类人类的数据：人脸识别、语音助手、自动驾驶、医疗影像、AI 生图，都从这条流水线长出来。它是这一轮 AI 浪潮的发动机。

**画面要点**：从下往上，每层看到的东西越来越具体：线条 → 形状 → 部件 → 整只猫。

```text
A tall cutaway factory building with four floors, a conveyor belt carrying a photograph of a tabby cat upward through each floor like a vertical assembly line. Ground floor: workers with lamps trace only light-and-dark edges and simple lines from the photo onto transparent sheets. Second floor: workers assemble those lines into curves, circles and pointed corners. Third floor: workers hold up recognizable parts — a cat eye shape, a pointed ear shape, a set of whiskers, a striped tail. Top floor: a single worker raises a clear cat silhouette placard and rings a small brass bell in triumph. Each floor is a slightly warmer color than the one below, showing the idea becoming clearer as it rises. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) climbs a spiral staircase alongside the floors, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) floats near the top floor with a proud face. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P31 · 大模型：读完整座图书馆的学者

**配文**：高塔顶层住着一位学者，他读过的文字比一座城的图书馆还多。他练习的本事其实只有一个：给出前半句，猜下一个词最可能是什么。但当这件事做到极致，他就顺带学会了语法、常识、推理、写代码、翻译——因为要猜准下一个词，就得理解这段话在说什么。比特说：“这就是大语言模型。”它像一位可以按需雇佣的通用实习生：能读、能写、能分析。但它也有三个弱点：它的知识停在读完书的那一天；不知道的时候可能一本正经地编造（“幻觉”）；它也没读过你公司内部的资料。接下来两页，就是人们怎么弥补这些弱点的。

**画面要点**：巨大的图书馆、中央的学者、卷轴上“下一个词”从几个候选里被挑出；角落暗示三个弱点。

```text
The top floor of the glass tower: an immense circular library whose bookshelves spiral upward into soft clouds, millions of books on every level, with tiny librarians flying between them on paper-wing gliders. At a round desk in the center sits a gentle, wise scholar whose robe and beard are woven from soft glowing threads of light, writing on a long scroll. At the end of the scroll, several faint floating tiles hover as candidates for the next piece of the sentence, and one tile glows brightly as it is chosen and placed (tiles show only dots and simple shapes, no letters). Three subtle details around the room: the library's great front door is sealed with a ribbon and wax seal, showing no new books arrive after a certain day; a small thought cloud above the scholar shows a confidently drawn but slightly wrong map with an extra island; and a locked private cabinet in the corner bearing a company-like emblem shape remains closed and unread. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) sits across the desk asking a question, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) peers at the extra island in the thought cloud. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P32 · RAG：先查档案，再回答

**配文**：Sylvan问学者：“我们公司今年的退货政策是什么？”学者没读过这家公司的文件。于是一位跑腿员冲进隔壁的档案馆，按“意思相近”而不是“字面相同”找出最相关的几份文件，摊在学者桌上。学者读完再回答，还在答案里夹上书签，标明每句话出自哪份文件。比特说：“这就是 RAG，检索增强生成。不改造学者本人，只在回答前把对的资料递到他手里。”它同时弥补了大模型的三个弱点：资料可以是最新的、可以是公司内部的，而且有据可查、少编造。这是今天企业把大模型用起来最常见的方式之一。“按意思找东西”的那套档案柜，叫向量数据库。

**画面要点**：问题 → 跑腿员按意思找资料 → 学者读资料 → 带书签（出处）的回答。

```text
A cutaway of two connected rooms linked by a short glass bridge. On the right, the wise scholar woven from glowing light-threads sits at his round desk facing Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel), who has just asked a question shown as a small speech bubble containing a company building icon and a returned-parcel icon. On the left, inside a private company archive, a quick-footed runner with a satchel searches shelves where folders glow when their color and pattern resemble the question's icons, as if attracted by meaning rather than identical labels; he pulls out three glowing folders. In the middle, the runner dashes across the glass bridge with the three folders. On the scholar's desk, the three folders lie open, and his answer scroll has small colored ribbon bookmarks linking each part of the answer back to a specific folder. Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) holds the archive door open for the runner. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P33 · 智能体：带工具腰带的管家

**配文**：光会回答问题还不够。比特给学者系上一条工具腰带：日历、计算器、电话、地图、钥匙、账本……然后给他一个目标：“帮Sylvan安排下周的出差。”学者自己拆步骤：查日历 → 订机票 → 订酒店 → 发确认信；遇到酒店客满，就换一家；最后回来汇报。比特说：“这就是智能体（Agent）：大模型 + 工具 + 分步办事的能力。”AI 从“回答问题”升级成了“把事办成”。难点在于可靠：一步错可能步步错，花钱和发信这类动作还要有人把关。所以做智能体的工程师，大部分功夫花在设计检查点、权限和评测上。谁能把智能体稳稳地放进企业的日常流程，谁就把大模型变成了真正的生产力。

**画面要点**：系着工具腰带的助手沿着一条有检查站的路一站站办事，遇到障碍会绕行，关键步骤有人盖章。

```text
A winding storybook path through the streets of Bit City, seen from slightly above, like a board game. Walking along it is the wise scholar woven from glowing light-threads, now dressed as a capable assistant and wearing a large utility belt hung with tools: a calendar pad, a brass calculator, an old-fashioned telephone receiver, a folded map, a ring of keys and a small ledger. The path has stepping-stone stations: a calendar kiosk, a travel ticket office with tiny airplanes, a hotel with a full-house sign drawn as a closed red door where the path detours with a small curved arrow to a second hotel with an open door, and a post office sending a sealed envelope. Before the ticket office and post office stand small checkpoint gates where Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) presses an approval stamp. At the end of the path, Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) happily receives a neat travel folder with a ticket and hotel key. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P34 · 算力与数据中心：AI 的发电厂

**配文**：高塔为什么能这么聪明？比特带Sylvan来到城外一座望不到头的厂房：一排排机柜里装着成千上万块 GPU，嗡嗡作响；冷却水管像河流一样穿过机房；厂房旁边是专门的发电站。训练一个顶级大模型，要让这样的厂房连续运转很长时间，耗电可以和一座小城相比。比特说：“算力、电力、数据，是 AI 时代的三种‘石油’。”这就是为什么科技巨头竞相投入巨资建数据中心，为什么芯片和电力成了新闻头条；也是为什么能让 AI 跑得更快、更省的工程师，在市场上格外抢手。

**画面要点**：规模感：无尽的机柜、粗大的冷却管和电缆、旁边的发电站，一条粗电缆通向远处的 AI 高塔。

```text
A vast cutaway data center hall stretching to the horizon, with endless parallel rows of tall dark server racks dotted with tiny glowing teal and coral lights. Thick blue cooling pipes run overhead and along the floor like rivers, with little technicians riding scooters down the aisles and checking racks with lanterns. Through the large windows on one side, an adjoining power station with cooling towers, a field of wind turbines and rows of solar panels feeds thick glowing cables into the hall. One very thick glowing cable leaves the far end of the hall and runs across the countryside to the tall glass AI tower of Bit City visible on the horizon, its brain-patterned lantern shining. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands at the entrance, tiny against the scale of the hall, with his hand on his hat against the breeze of the cooling fans, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) floats beside him with a surprised face. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, cool ambient light mixed with warm window light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

## 第六章 · 城里的人

参观完建筑，比特说：“城市是人建的。”这一章认识城里的工种。看懂任何一个岗位，只需问两个问题：它替公司解决什么问题？没有它，公司会怎样？

### P35 · 工种大地图

**配文**：从高空往下看，城里的人按价值链分布在不同的层：地基和发电厂里，是做系统软件和芯片的工程师；街道和水电管线上，是运维、云和网络工程师；楼房里，是产品经理、前端、后端和测试；水厂和档案馆里，是数据工程师和分析师；高塔里，是做 AI 的人；城墙上，是安全工程师；城门口，是连接客户的售前和实施工程师。比特说：“公司花钱雇技术人员，只买三样东西：把产品做出来，让产品稳定便宜地跑，从数据和 AI 里挖出更多价值。”每一个岗位，都能归到这三类之一。

**画面要点**：和 P7 同一张剖面城市，但这次重点是人：每一层的工人穿着不同颜色的制服。

```text
The same grand panoramic cross-section of Bit City as before, cut open like a layered cake, but this time the focus is on the people working in each layer, each zone's workers wearing a distinct uniform color. In the bedrock and underground power plant: engineers in slate-blue overalls reinforcing foundations and tuning switch panels. Along the streets and pipelines: crews in orange vests repairing cables and dispatchers waving flags at cloud factories above. In the colorful buildings: a planner with rolled maps on a rooftop, window designers arranging a shop display, chefs in a back kitchen, inspectors with magnifying glasses at doorways. At the water plant and archive: workers in teal overalls at valves and librarians on ladders. In the glass AI tower: people in coral coats teaching machines and fitting tool belts. On the city wall: guards and a white-capped tester. At the city gate: a diplomat with a briefcase greeting visitors and an installer with a toolbox heading out. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) look down at it all from a hot-air balloon in the sky. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P36 · 造产品的人

**配文**：Sylvan走进一条热闹的商业街。屋顶上的**城市规划师**是产品经理，决定盖什么、为谁盖、先盖哪个——没有他，大家会做出一堆没人要的东西。橱窗里的**陈列设计师**是前端工程师，把产品变成用户看得见、点得动的样子；街角的**移动小摊主**是移动端工程师，把店搬进每个人的口袋。后厨的**主厨**是后端工程师，下单、支付、库存都靠他，前台再漂亮，后厨不出菜也白搭。门口的**质检员**是测试工程师，抢在顾客之前发现问题。巷子里还有两位手艺人：游戏工坊的**造梦师**，把玩法变成能玩的世界；钟表铺的**钟表匠**是嵌入式工程师，给汽车、家电、机器人装上小小的大脑。这条街岗位最多、最热闹，也最拥挤。

**画面要点**：一条街上同时看到六七种工种，每个人的动作一眼就能看懂他的职责。

```text
A lively cutaway of a single busy shopping street in Bit City. On a rooftop, a city planner in a mustard waistcoat unrolls a large map and points, deciding where the next building should go. In a big shop window, a display designer carefully arranges colorful products and lighting for passersby, who press their noses to the glass. On the corner, a cheerful vendor runs a compact mobile cart that folds the whole shop into a tiny pocket-sized booth, handing goods to people holding phones. Behind the shop, in a cutaway back kitchen, a head chef directs cooks, checks the pantry, and passes plates through a window. At the shop's front door, a quality inspector with a magnifying glass examines each item and pulls out one cracked cup before it reaches a customer. In a side alley, a game workshop where an artisan builds a miniature fantasy world with tiny moving figures, and a clockmaker's shop where a craftsman with a loupe fits a tiny glowing chip into a toaster, a toy robot and a model car. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) strolls down the street, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) points out each worker. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P37 · 让城市运转的人

**配文**：入夜，商业街安静了，另一群人却开始忙磌。警铃响起，**消防队**冲向一栋冒烟的机房——他们是运维和 SRE，保证服务全天候不宕机，一次宕机就是实打实的收入损失。街面下的**修路工**是网络工程师；天上云工厂的**调度员**是云架构师，算着怎么把电费送到最省、系统又最稳；档案馆的**馆长**是数据库工程师，守着公司最值钱的资产；地基里的**地基工程师**做操作系统、数据库内核和芯片，是整座城的根。比特说：“这群人做得越好，你越感觉不到他们的存在。”他们不直接做产品，但没有他们，任何产品都站不住。越往地下走，人越少、门槛越高、越难被替代。

**画面要点**：夜景；从天空到地底各层都有人在默默维护城市；越往下人越少。

```text
A night-time vertical cutaway of Bit City from sky to bedrock, lit by warm lamps and moonlight. In the sky, a dispatcher in a glass control gondola beneath the floating cloud factories moves levers to balance the glowing power flowing down to the city. On the street, an alarm bell rings and a brigade of firefighters in orange uniforms races a small red engine toward a building with a puff of smoke from its server room, already unrolling hoses. Under the street, in a cutaway tunnel, a road crew with headlamps splices glowing cables. Inside the domed archive, an archivist in a long coat locks the backup vault and checks the shelves by lantern. Deep in the bedrock, a few foundation engineers with hard hats and tiny lamps reinforce glowing stone pillars and tune the switch panels of the power plant; there are noticeably fewer people at this depth. The streets above are calm and peaceful with sleeping houses, unaware of the work below. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) watches the firefighters from a balcony in his pajamas under his black leather coat, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) glows softly like a night light. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of deep blue, teal, mustard yellow and coral, warm lamplight at night, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P38 · 挖掘价值的人

**配文**：水厂旁边有三间办公室。第一间住着**侦探**——数据分析师。墙上钉满了线索和图表，她用数据回答老板的问题：哪个店在赚钱、哪里在漏钱、上个月为什么客人变少了。没有她，老板只能凭感觉决策。第二间是**自来水工**——数据工程师。他修管道、建水库、保证水源源不断又干净，分析和 AI 都靠他供水。第三间是**预报员**——数据科学家。他不只描述过去，还用统计和模型预测未来，设计实验验证“换个包装是不是真的卖得更好”。比特说：“这三位的共同点是：护城河来自懂业务，而不只是懂工具。”

**画面要点**：侦探、水工、预报员三间办公室并排，由同一条清水管道连起来。

```text
A cutaway row of three connected offices beside the data water-treatment plant, linked by one clean glowing blue pipe running through all three. Left office: a sharp detective in a tweed coat and deerstalker-style cap examines a corkboard covered with simple bar shapes, pie shapes and photos connected by red string, holding a magnifying glass over a leaking coin purse icon, while a business owner in a suit listens attentively. Middle office: a sturdy plumber in teal overalls with a big wrench repairs and connects pipes, cleaning out a clogged filter, with blueprints of the pipe network spread on a workbench. Right office: a thoughtful forecaster with a long scarf studies a softly glowing globe-like model, beside two identical product boxes on a test table, one with a new wrapping, and a small balance scale tipping slightly toward the new one. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) peers into the detective's office, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) follows the pipe toward the forecaster. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P39 · AI 的人

**配文**：高塔里的每一层，都有一种做 AI 的人。一楼的**媒人**是搜索、广告、推荐算法工程师，给每个人配上最可能喜欢的内容和商品，配得准不准直接决定平台收入。二楼的**装备师**是大模型应用工程师和智能体工程师，给学者配工具腰带、搬来档案、设好检查站，让他真正进入企业的工作流程——大多数公司不会自己造学者，但都需要这样的人。三楼的**体检医生**是机器学习工程师（MLOps），把实验室里的模型请到真实岗位上，并定期体检，发现它变差就重新训练。顶层的**探险家**是大模型训练工程师和研究员，提升学者本人的能力，人少、门槛极高。城外发电厂里的**电厂工程师**是 AI 基础设施工程师，让训练和运行更快、更省——GPU 太贵，省下的每一分算力都是利润。

**画面要点**：高塔剖面，从下到上五种 AI 工种各占一层，塔底一条电缆通向城外电厂。

```text
A tall cutaway of the slender glass AI tower, showing several floors stacked vertically. Ground floor: a warm matchmaker in a coral scarf pairs townspeople with items and stories drawn from bubbling streams, sliding a perfectly chosen book toward a smiling reader, while a coin chute beside her fills with gold. Second floor: outfitters measure and fit the wise scholar woven from glowing light-threads with a utility belt of tools, hand him folders from an archive, and set up small checkpoint gates. Third floor: a clinic where doctors in white coats give a learning machine a check-up with a stethoscope and an eye chart made of shapes, noting a slight decline and sending it back to the classroom for a refresher. Top floor: a few explorers in expedition gear stand at the edge of the circular library looking through telescopes into unknown clouds, sketching new maps. A thick glowing cable runs from the tower's base out a window toward a distant power hall, where engineers in hard hats tune giant humming machines to use less energy. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) rides a glass elevator up the side of the tower, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) floats beside the elevator pointing to each floor. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P40 · 守护与连接的人

**配文**：城门附近是另一群人。城墙上的**警察和白帽**是安全工程师，抢在坏人之前找到漏洞，出事时第一时间止损。城门外的**外交官**是解决方案架构师和售前工程师，把技术翻译成客户听得懂的业务价值，带着方案去谈合作——没有他们，再好的技术也卖不出去。开着小货车的**上门师傅**是实施和技术支持工程师，在客户那里把产品装好、用起来，是技术落地的最后一公里。广场上的**乐队指挥**是技术管理者，让几十个人按时、按质地合奏——没有他，人越多反而做得越慢。比特说：“这些岗位离客户和钱都很近，需要的是广度：每一层都懂一点，再加上和人打交道的本事。”

**画面要点**：城门内外四个小场景：守城、谈判、上门安装、指挥乐队。

```text
A wide scene around the main gate of Bit City, divided into four lively vignettes. On the city wall, a guard in a navy uniform and a white-capped tester work side by side, the tester pointing out a loose brick while the guard rings a warning bell at a shadowy figure fleeing outside. Just outside the gate, under a striped canopy, a diplomat in a smart suit with a leather briefcase sits at a negotiation table with a delegation from a neighboring town, unrolling an illustrated plan that shows a bridge between their two towns, both sides shaking hands. On the road leading away, a friendly installer in overalls drives a small van loaded with toolboxes and boxes to a client's building, where another installer on a ladder connects a device and a happy client gives a thumbs up. On the town plaza inside the gate, a conductor on a small podium directs an orchestra of engineers each playing a different instrument from the city's trades (a wrench, a teacup, a lantern, a scroll), all in harmony. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) sits on the gate steps watching the conductor, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) waves at the diplomat. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P41 · 市场规律：金河与深矿

**配文**：比特掀出一张藏宝图，上面画着这座城的“财富地理”。第一，**离钱越近，越受重视**：一条金色的河流经交易、广告、推荐、风控，这些岗位的产出能直接换算成钱。第二，**越往地下，越稀缺**：深处的矿脉是系统软件、芯片、AI 基础设施，矿工少、门槛高、难以替代。第三，**越靠近用户的大街越热闹，也越拥挤**：前端、后端、App 岗位最多，竞争也最激烈，入门级的活也最容易被 AI 写代码的工具挤压。第四，**职业的顶峰有两条山路**：一条通向技术专家和架构师的山顶天文台，一条通向管理者的瞭望塔。架构师不是入门岗位，而是在一条路上走了多年之后才看得到的风景。

**画面要点**：藏宝图风格：金河、地下发光矿脉、拥挤的主街、分叉通向两座山顶的山路。

```text
An illustrated treasure map of Bit City drawn on aged parchment, seen from above with a slight isometric tilt, held open at the corners by Sylvan's hands (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) and by Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow). On the map: a shimmering golden river winds past a marketplace, an advertising billboard plaza, a matchmaker's tower and a bank with guards, tiny people scooping gold from its banks. A cutaway at the map's bottom edge reveals deep underground mineral veins glowing bright teal, with only a few lone miners with lamps working them. The main avenue near the gate is packed with crowds of tiny workers jostling shoulder to shoulder, with a few small mechanical helpers sweeping in to take simple tasks. At the top of the map, a mountain path forks in two: one trail climbs to a peak with a domed observatory and a telescope, the other to a sturdy watchtower with a flag; along both trails, small hikers are drawn at different heights, showing the climb takes years. Decorative compass rose and sea creatures in the corners, no text. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed, aged parchment and soft cream paper texture, muted palette of teal, mustard yellow, coral, gold and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P42 · 技术是工具：一面工具墙

**配文**：旅程快结束时，比特带Sylvan走进一间工具房。整面墙挂满了工具，按工种分区：正中间是所有人共用的基础工具——一门编程语言、版本管理、服务器操作、数据库查询、网络常识；四周是前端区、后端区、运维区、数据区、AI 区、安全区。角落里有个箱子，放着已经退休的旧工具，旁边刚挂上去几件闪亮的新工具。比特说：“新人最常犯的错，是把工具当成目的。”工具每隔几年就换一批，但它们要解决的问题——让处理信息更便宜、更可靠、更聪明——从来没变。看清问题的人，换工具很快；只盯着工具的人，工具一换就迷路。Sylvan放下手里的锤子，先朝窗外的城市看了一眼。

**画面要点**：分区的工具墙 + 退休旧工具箱 + 窗外的城市（工具是为窗外的问题服务的）。

```text
A cozy, sunlit workshop interior with a huge pegboard wall covered in neatly hung tools, organized into clearly separated color-tinted zones: a central common zone of essential everyday tools (a hammer, a wrench, a measuring tape, a lantern, a key ring), surrounded by specialized zones: one with paintbrushes and display props, one with chef knives and ladles, one with fire hoses and pipe wrenches, one with water valves and filters, one with brass knobs and glowing lenses, one with locks and chalk. In the corner, an open wooden crate labeled only with a small hourglass symbol holds old rusty retired tools, while a worker hangs several shiny new tools in their place. A large window beside the wall looks out over the bustling layered Bit City in the sunshine. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) has just set down a hammer on the workbench and turns to gaze out the window at the city, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) floats between the tool wall and the window with a proud smile. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, gentle morning light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

## 尾声 · 看清整座城

### P43 · 学习之路：从同一个广场出发的七条路

**配文**：下山的路上，比特指着城外的道路图。所有的路都从同一个广场出发，广场上铺着六块基石：一门编程语言、版本管理、服务器操作、数据库、网络常识、数据结构与算法。然后分成七条岔路：通向商业街的前端之路、通向后厨的后端之路、通向消防站和云码头的运维之路、通向水厂的数据之路、通向高塔的 AI 之路、通向地下矿井的底层之路、通向城墙的安全之路。岔路之间架着不少小桥：做大模型应用的人，常常要同时走后端和 AI 两条路的前半段。比特说：“不用每条路都走到底，但要知道每条路通向哪里。”这正是这趟旅行的意义：先看全图，再选路。

**画面要点**：中央广场（公共基础）放射出七条路，各通向一个前面出现过的地标，路与路之间有小桥。

```text
A bird's-eye storybook road map of the countryside around Bit City in late afternoon light. In the center, a round stone plaza paved with six large distinct foundation stones, each carved with a simple symbol (a quill, a branching tree, a terminal-like window shape, a filing drawer, an envelope, a maze), with travelers gathering there. From the plaza, seven winding roads radiate outward, each leading to a recognizable landmark from earlier pages: a shopping street with a big display window, a restaurant back kitchen, a fire station next to a dock for floating cloud factories, the data water-treatment plant, the tall glass AI tower with its glowing lantern, the entrance to an underground mine glowing teal, and a stretch of the city wall with a watchtower. Small wooden footbridges connect several neighboring roads, and one traveler crosses a bridge between the kitchen road and the tower road. Tiny travelers with backpacks walk each road at different distances. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) stands at the edge of the plaza studying the map in his notebook, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) points down one of the roads. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue, warm late-afternoon light, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P44 · 塔顶俯瞰：一句话看懂全城

**配文**：最后，Sylvan和比特回到高塔顶端。夕阳下，整座城一览无余：地底的规则石砖、嗡嗡作响的发电厂、穿梭的信封、热闹的店铺和后厨、流淌的数据运河、开始亮灯的高塔。Sylvan在笔记本上写下一句话：“数学是语言，编程是表达，系统是地基，软件和数据是楼房，AI 让楼房自己会思考。”比特问：“现在，你还觉得计算机只是写代码吗？”Sylvan笑了。他看到的是一项伟大的工程：人类把“处理信息”的成本一路压向零，而每一个技术细节，都只是这座城里的一块砖。看清了整座城，才知道自己想在哪一块砖上用力。

**画面要点**：夕阳、全城层次尽收眼底；Sylvan写下总结，与封面呼应。

```text
A golden-hour view from the open balcony at the very top of the slender glass AI tower, the brain-patterned lantern glowing softly just above. Below, the whole of Bit City spreads out in its layered cross-section, every layer visible and gently lit: the glowing stone bedrock, the humming power plant of tiny switches, streets with flying envelopes, shops and restaurants with warm windows, the domed archive, canals of glowing blue data water, the city wall with watchtowers, and cloud factories drifting in an orange-pink sky with flocks of birds. Sylvan (a handsome Chinese man in his late twenties with short neat black hair, no glasses, clean-shaven, black leather coat and brown leather satchel) sits on the balcony ledge writing in his small notebook with a calm, satisfied smile, his satchel beside him, and Bit (a small floating egg-shaped white robot with a dark teal screen face showing friendly glowing eyes, a coral-tipped antenna and a soft blue hover-glow) rests on his shoulder with closed smiling eyes. The composition mirrors the book cover but from above and at sunset. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed isometric cutaway scene, soft cream paper texture, muted palette of teal, mustard yellow, coral and slate blue with warm sunset gold, many tiny busy characters doing specific jobs, one clear visual metaphor, no text, no letters, no numbers, no logos, clean empty space across the top quarter for a caption, 4:3 landscape.
```

### P45 · 封底

**配文**：一座城，七条路，几十种工种。读完这本书，你不一定会写代码，但你会知道：每一行代码，都在为这座城里的某个角落工作；每一个岗位，都在替这座城解决某个问题。

**画面要点**：夜晚亮灯的比特城，两位主角的小小背影走在山路上，下方留白放文字。

```text
Back cover illustration, 3:4 portrait. A peaceful night view of Bit City from a distant hillside, the whole layered city glowing with thousands of warm windows, the canals shimmering blue, the glass AI tower's lantern shining like a soft star, cloud factories drifting with tiny lights against a deep starry sky. In the upper middle of the image, on a winding hill path, the small silhouettes of Sylvan (a handsome young Chinese man with short black hair and a black leather coat, carrying a satchel) and Bit (a small floating egg-shaped white robot with a glowing teal face and a coral-tipped antenna) walk away toward the city, Bit glowing like a little lantern lighting the path. Leave the entire bottom third as clean, calm, dark-blue empty space for back-cover text. Style: warm hand-painted gouache and ink picture-book illustration for adult readers, richly detailed, soft cream paper texture showing through, muted palette of deep blue, teal, mustard yellow and coral, gentle night light, no text, no letters, no numbers, no logos, 3:4 portrait.
```
