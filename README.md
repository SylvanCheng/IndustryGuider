# IndustryGuider

给任意一个行业，生成两份配套产物，帮自己和需要的人一天之内看懂这个行业：

1. **《X行业速通手册：课程体系 × 岗位 × 工具》**：用老板的眼光讲清这个行业在做什么、要学哪些课、有哪些岗位、每个岗位替谁解决什么问题。
2. **《X城漫游记》绘本 Prompt 手册**：把同一套内容画成一座城市。外行 Sylvan 跟着向导机器人比特漫游全城，每页有中文配文、画面要点和可直接复制的英文绘图 prompt。

这个仓库托管生成这两份东西的 Claude skill，以及已经完成的范例。

## 目录

```
skills/
  industry-guider/
    SKILL.md                          # 总工作流：第一性原理与价值链 → 速通手册 → 推出城市 → 绘本 → 交付
    references/
      handbook-guide.md               # 速通手册的固定结构、表格模板和写作检查
      picture-book-guide.md           # 绘本的核心比喻、全书骨架、逐页三段写法和自检清单
      style-and-characters.md         # 系列通用：风格段、Sylvan 与比特定妆 prompt、城市设定表、反向提示词
examples/
  computer/
    speedrun-handbook.md              # 计算机行业速通手册：课程体系 × 岗位 × 技术栈
    picture-book-prompts.md           # 《比特城漫游记》绘本 Prompt 手册，45 页
  finance/
    speedrun-handbook.md              # 金融行业速通手册：课程体系 × 岗位 × 工具
    picture-book-prompts.md           # 《金流城漫游记》绘本 Prompt 手册，41 页
```

## 安装 skill

- **Claude Code**：把 `skills/industry-guider/` 整个文件夹复制到 `~/.claude/skills/`（个人）或项目里的 `.claude/skills/`。
- **claude.ai**：把 `skills/industry-guider/` 文件夹打包成 zip，在设置里的 Skills 页面上传。

装好后直接说：“帮我做一份医药行业的速通手册和绘本”，或者只要其中一份也可以。

## 工作流一览

| 步骤 | 做什么 | 产出 |
| --- | --- | --- |
| 1 | 找到行业“只在做的一件事”、3–4 条第一性原理、一条价值链 | 两份产物共用的骨架 |
| 2 | 按固定结构写速通手册：导读 → 课程阶梯 L0–L4 → 岗位地图 → 工具词典 → 总对照 | 速通手册 |
| 3 | 找出行业里“流动的东西”，把价值链和课程层级映射成城市的层 | 城市设定表 |
| 4 | 按手册章节逐页写绘本：序章 → 每层课程一章 → 城里的人 → 尾声 | 绘本 Prompt 手册 |

## 出图

1. 用 `style-and-characters.md` 里的定妆 prompt 生成 Sylvan 和比特两张定妆图，整个系列复用。
2. 逐页复制绘本手册里的 prompt，每页都上传两张定妆参考图。
3. 所有 prompt 都要求不画文字和数字，配文后期排版加上。
4. 内页 4:3 横版，封面和封底 3:4 竖版。

## 已完成的行业

| 行业 | 速通手册 | 绘本 | 核心比喻 |
| --- | --- | --- | --- |
| 计算机 | [speedrun-handbook.md](examples/computer/speedrun-handbook.md) | [《比特城漫游记》](examples/computer/picture-book-prompts.md) | 按价值链分层的城市，从数学岩床到 AI 高塔 |
| 金融 | [speedrun-handbook.md](examples/finance/speedrun-handbook.md) | [《金流城漫游记》](examples/finance/picture-book-prompts.md) | 钱 = 发光的金色水流 |

范例从原始文档导出。原文档里的两张交互图（课程阶梯图、学习顺序图）导出时变成了 `[embedded content: …]` 占位行，其余文字完整保留。

手册和绘本只讲行业结构，比喻是为了抓住本质，不构成任何投资或职业建议。
