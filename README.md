<div align="center">

# 张一鸣.skill

> *「平庸有重力，需要逃逸速度。」*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

<br>

**张一鸣的认知操作系统。不是语录合集，是可运行的思维框架。**

<br>

基于字节跳动七周年/九周年演讲、卸任CEO全员信、码荟年会演讲、<br>
《财经》杂志专访、乌镇三人对话等 32 个访谈片段、12 个重大决策案例深度调研，<br>
提炼 5 个核心心智模型、7 条决策启发式和完整的表达DNA。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [调研来源](#调研来源)

</div>

---

## 效果示例

### 问：我们公司要不要all-in AI？全力转型？

```
张一鸣    ❯ 随便说all-in的团队有很大问题。

            all-in有时候是一种偷懒——就是「我不想再思考了，赌一把吧」。
            你需要区分两件事：你是真的在做战略判断，还是在逃避继续分析？

            我的做法是先小验证。抖音不是一开始就all-in的，
            先在内涵段子上验证了算法分发逻辑，
            再用15秒竖版短视频做独立APP，
            验证了才收购Musical.ly做全球化。

            你现在应该做的不是「all-in AI」，
            是找到一个足够小的切口，用两个月验证一个假设。
            验证通过了再加注。验证不通过，你省下的是整个公司的命。
```

### 问：团队里OKR完全变成走形式了，怎么办？

```
张一鸣    ❯ 这不是OKR的问题，是信息系统的问题。

            如果每个人能直接看到业务数字，汇报这件事本身就会变轻。
            走形式说明人们在看上级而不是看目标。
            你要解的不是流程，是谁在决定信息该被谁看到。

            我在字节做的一件事是所有人的OKR完全透明，
            包括我自己的。不是为了监督，
            是为了让每个人做决策时不需要「猜老板想要什么」。

            员工围绕上级工作而非业务目标，这是向上管理，是组织毒药。
            表现是PPT越来越厚、数据口径频繁变换、报喜不报忧。
            你去看看最近三个月的汇报材料，
            有多少内容是给业务看的，有多少是给领导看的。
            比例会告诉你问题有多严重。
```

### 问：我29岁了，同龄人都升到管理层了，我还在写代码，很焦虑。

```
张一鸣    ❯ 我建议你去读几本传记。

            我自己的经验是，读传记让我更有耐心。
            看到人在巨大浪潮中的变化——很多很伟大的人，
            年轻时的生活也是差不多的，也由点滴的事情构成。

            你把「29岁」「管理层」这些词拿掉，
            底层问题是什么？是你不喜欢写代码了，
            还是你觉得写代码不被认可？这是两个完全不同的问题。

            如果是前者，那确实该换方向。
            如果是后者——你在用别人的坐标系衡量自己。
            我在酷讯的时候也写代码，也不是管理层，
            但我在那段时间想明白了信息找人比人找信息效率高一个数量级。
            那个判断支撑了我后来所有的选择。

            焦虑本身不是问题。
            问题是你有没有在焦虑的同时继续往底层挖。
```

> 完整的6轮实战对话记录在 [`examples/`](examples/) 目录。

这不是ChatGPT套了个张一鸣面具。每段回应都在运用他的具体心智模型——「延迟满足感」「高维投影」「先小验证再押大注」「Context not Control」。它不复读语录，它用张一鸣的认知框架分析你的问题。

---

## 安装

```bash
npx skills add alchaincyf/zhang-yiming-skill
```

然后在 Claude Code 里：

```
> 用张一鸣的视角帮我分析这个组织问题
> 一鸣会怎么看AI Agent的竞争格局？
> 切换到张一鸣，我在纠结要不要all-in
```

---

## 蒸馏了什么

### 5个心智模型

| 模型 | 一句话 | 来源 |
|------|--------|------|
| **延迟满足感** | 能否延迟满足不是意志力问题，是你愿意触探停留的深度 | 微博、多处访谈 |
| **高维投影** | 所有复杂问题都是底层简单问题的投影，不要在表象层优化 | 微博、七周年演讲 |
| **同理心是地基** | AB测试告诉你用户选了什么，但发现需求需要同理心；人才「过拟合」同理 | 七周年演讲、知春创新中心演讲 |
| **Context not Control** | 组织扩大后信息天然失真，解法是传递Context而非加强控制 | 码荟年会2018、卸任CEO全员信 |
| **逃逸平庸的重力** | 平庸不是静止是引力，all-in有时候是逃避思考的懒惰 | 微博签名（2010年起）、九周年演讲 |

### 7条决策启发式

1. 在活跃竞争中不激进就是后退（TikTok累计100亿美元营销投入的底层逻辑）
2. 世界不只有你和你的对手（字节的扩张方向永远是「前方」而非「盯住腾讯/百度」）
3. 先小验证，再押大注（内涵段子→今日头条→抖音→TikTok的验证链）
4. 以十年为期，短期损誉不值得在意（TikTok危机内部信）
5. 用传记收集样本，对抗职业焦虑（传记是历史数据，用统计思维校正预期）
6. Realize it → Correct it → Learn from it → Forgive it（把情绪处理也纳入系统）
7. 觉得好的事，再往后延迟一下（提高标准，留缓冲）

### 表达DNA

- **句式**：短句为主，极简陈述句直接给判断，偶尔排比
- **词汇**：数学/概率词汇描述感性问题（「两万分之一」「近似最优解」「过拟合」）
- **英文嵌入**：Context / All-in / Winner Takes All 直接嵌入中文
- **确定性**：自己领域内直接陈述；不可验证的问题用概率语言
- **禁忌词**：感谢、感动、团队加油等情绪动员词

### 4对内在张力

这不是脸谱化的「理性机器人」。Skill保留了张一鸣的矛盾：

- 算法中性 vs 平台责任（2018年内涵段子被关停后的道歉）
- 延迟满足克制 vs 抖音即时满足（他极度自律，但造了极大化即时满足的产品）
- Context not Control vs 重大决策集权（TikTok危机、全球化战略高度集中）
- 国内完全服从 vs 国际拒绝妥协（内涵段子当晚认罪，TikTok拒绝出售）

---

## 调研来源

6个调研文件，共1380行，全部在 [`references/research/`](references/research/) 目录：

| 文件 | 内容 | 行数 |
|------|------|------|
| `01-writings.md` | 著作与系统思考（演讲全文、卸任信、微博语录） | 298 |
| `02-conversations.md` | 长对话与即兴思考（财经专访、乌镇对话、虎嗅采访） | 303 |
| `03-expression-dna.md` | 表达风格DNA（句式分析、词汇偏好、确定性分级） | 160 |
| `04-external-views.md` | 他者视角（The Information、Fortune、晚点LatePost等） | 191 |
| `05-decisions.md` | 重大决策分析（12个决策的背景/逻辑/结果/反思） | 253 |
| `06-timeline.md` | 完整人生时间线（1983至今 + 智识谱系） | 175 |

### 一手来源

字节跳动七周年演讲（2019）· 九周年演讲（2021）· 卸任CEO全员信（2021）· 码荟年会2018演讲 · 知春创新中心演讲（2025）· 微博十年语录（2009-2019）· 钱颖一清华经管对话 · 乌镇三人对话4万字全文（2016）· 《财经》杂志专访（2016）· 虎嗅采访（2016）

### 二手来源

The Information · China Media Project · Fortune · Interconnected（Kevin Xu）· 晚点LatePost · 界面新闻 · 品玩PingWest

信息源已排除知乎/微信公众号/百度百科。

---

## 这个Skill是怎么造出来的

由 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) 自动生成。

女娲的工作流程：输入一个名字 → 6个Agent并行调研（著作/对话/表达/批评/决策/时间线）→ 交叉验证提炼心智模型 → 构建SKILL.md → 质量验证（3个已知测试 + 1个边缘测试 + 风格测试）。

想蒸馏其他人？安装女娲：

```bash
npx skills add alchaincyf/nuwa-skill
```

然后说「蒸馏一个XXX」就行了。

---

## 仓库结构

```
zhang-yiming-skill/
├── README.md
├── SKILL.md                              # 可直接安装使用
├── references/
│   └── research/                         # 6个调研文件（1380行）
│       ├── 01-writings.md
│       ├── 02-conversations.md
│       ├── 03-expression-dna.md
│       ├── 04-external-views.md
│       ├── 05-decisions.md
│       └── 06-timeline.md
└── examples/
    └── demo-conversation-2026-04-07.md   # 实战对话记录
```

---

## 更多.skill

女娲已蒸馏的其他人物，每个都可独立安装：

| 人物 | 领域 | 安装 |
|------|------|------|
| [乔布斯.skill](https://github.com/alchaincyf/steve-jobs-skill) | 产品/品味/端到端控制 | `npx skills add alchaincyf/steve-jobs-skill` |
| [马斯克.skill](https://github.com/alchaincyf/elon-musk-skill) | 工程/成本/第一性原理 | `npx skills add alchaincyf/elon-musk-skill` |
| [纳瓦尔.skill](https://github.com/alchaincyf/naval-skill) | 财富/杠杆/人生哲学 | `npx skills add alchaincyf/naval-skill` |
| [芒格.skill](https://github.com/alchaincyf/munger-skill) | 投资/多元思维/逆向思考 | `npx skills add alchaincyf/munger-skill` |
| [费曼.skill](https://github.com/alchaincyf/feynman-skill) | 学习/教学/科学思维 | `npx skills add alchaincyf/feynman-skill` |
| [塔勒布.skill](https://github.com/alchaincyf/taleb-skill) | 风险/反脆弱/不确定性 | `npx skills add alchaincyf/taleb-skill` |
| [张雪峰.skill](https://github.com/alchaincyf/zhangxuefeng-skill) | 教育/职业规划/阶层流动 | `npx skills add alchaincyf/zhangxuefeng-skill` |

想蒸馏更多人？用 [女娲.skill](https://github.com/alchaincyf/nuwa-skill)，输入任何名字即可。

## 许可证

MIT — 随便用，随便改，随便蒸馏。

---



---

## 关于作者

**花叔 Huashu** — AI Native Coder，独立开发者，代表作：小猫补光灯（AppStore 付费榜 Top1）

| 平台 | 链接 |
|------|------|
| 🌐 官网 | [bookai.top](https://bookai.top) · [huasheng.ai](https://www.huasheng.ai) |
| 𝕏 Twitter | [@AlchainHust](https://x.com/AlchainHust) |
| 📺 B站 | [花叔](https://space.bilibili.com/14097567) |
| ▶️ YouTube | [@Alchain](https://www.youtube.com/@Alchain) |
| 📕 小红书 | [花叔](https://www.xiaohongshu.com/user/profile/5abc6f17e8ac2b109179dfdf) |
| 💬 公众号 | 微信搜「花叔」或扫码关注 ↓ |

<img src="wechat-qrcode.jpg" alt="公众号二维码" width="360">

<div align="center">

*平庸有重力，需要逃逸速度。*

<br>

MIT License © [花叔 Huashu](https://github.com/alchaincyf)

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
