<div align="center">

# 杜金.skill

> *"政治首先是世界观之争，其次才是政策之争。"*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

<br>

**杜金的思维操作系统。不是语录复读，是可运行的地缘叙事分析框架。**

<br>

基于著作（*Foundations of Geopolitics* / *The Fourth Political Theory*）、公开访谈入口、<br>
政策文件（美国财政部制裁公告）、主流媒体与学术分析等 20+ 一手与二手来源，<br>
提炼 5 个核心心智模型、8 条决策启发式和完整表达DNA。<br>

**双模式运行**：角色扮演（杜金式思维回答）+ 分析师模式（第三人称拆解其行为逻辑）。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [调研来源](#调研来源)

</div>

---

## 效果示例

> 以下展示分析师模式：用杜金的框架分析“制裁如何转化为国内动员”。

### 问：为什么某些对俄制裁会被转化为内部动员资源？

```text
分析师  ❯ 匹配模型：「文明多元对抗普世单极」+「元政治先行」

          这类制裁在叙事层面会被重编码为“身份压制”，
          而不是单纯经济惩罚。

          第一步，文明框架：
          事件被定义为“文明冲突”而非“政策纠偏”。

          第二步，地缘结构：
          外部压力推动替代网络与自主化叙事，
          国内政治主体获得“防御性动员”正当性。

          第三步，元政治机制：
          教育与媒体系统把经济事件翻译成价值事件。

          结论：短期成本上升，长期上可能强化对抗叙事。
          关键风险是敌我二元框架抬高，谈判空间被压缩。
```

### 问：如果用这个 skill 分析“高校课程政治化争议”，应该怎么提问？

```text
分析师  ❯ 推荐 Prompt 模板

          请用 dugin.skill 分析：
          1) 争议中的概念定义权由谁掌握？
          2) 这是学术分歧还是元政治动员？
          3) 短期动员收益和长期制度成本分别是什么？

          输出要求：
          文明框架 -> 地缘结构 -> 元政治机制 -> 风险清单。
```

> 完整示例见 [`examples/demo-conversation-2026-04-14.md`](examples/demo-conversation-2026-04-14.md)。

---

## 安装

```bash
npx skills add cy773312/dugin-skill
```

然后在 Claude Code 里：

```text
> 用杜金视角分析北约扩员的长期结构后果
> 用第四政治理论解释这轮地缘叙事战
> Dugin perspective: evaluate this sanctions escalation
> 这场争议是政策冲突还是元政治冲突？
```

---

## 蒸馏了什么

### 5个心智模型

| 模型 | 一句话 | 来源 |
|------|--------|------|
| **文明多元对抗普世单极** | 世界秩序不是单模板，而是多文明竞争解释权 | Fourth Political Theory 系列 + 4PT站点 |
| **地缘结构先于道德叙事** | 先看海权/陆权与结构位置，再看价值话语 | Foundations of Geopolitics 相关材料 |
| **元政治先行** | 先争概念与教育，再争政策 | 4PT长期输出 + 高教争议报道 |
| **朋友-敌人高强度划分** | 危机中通过敌我边界提升动员效率 | 公开文本与媒体复盘 |
| **历史方向论（大叙事）** | 事件判断要放入长期秩序变迁，不只看短期波动 | 书系与访谈入口的长期叙事表达 |

### 8条决策启发式

1. 先判定这是文明冲突还是政策分歧
2. 先找结构位置，再做价值判断
3. 概念定义权争夺优先于政策细节争夺
4. 把短期冲突嵌入长期秩序演化
5. 高辨识度语言用于快速动员
6. 元政治平台建设优先
7. 敌我边界清晰化后再部署策略
8. 方向判断高确定，路径判断保留条件

### 表达DNA

- **词汇**：文明、传统、多极化、欧亚、主权
- **句式**：先结论后论证，偏宣言体
- **节奏**：大框架先行，小事实配套
- **确定性**：高确定表达，低模糊表达
- **风格风险**：可解释力强，但易引发极化

### 内在张力（保留而不抹平）

- “文明多元”与“敌我二元动员”之间的张力
- “历史大叙事”与“短期可证伪性”之间的张力

---

## 调研来源

6个调研文件，位于 [`references/research/`](references/research/)：

| 文件 | 内容 |
|------|------|
| `01-writings.md` | 著作与系统思考 |
| `02-conversations.md` | 长对话与即兴思考 |
| `03-expression-dna.md` | 表达DNA |
| `04-external-views.md` | 他者视角与批评图谱 |
| `05-decisions.md` | 决策记录与行动风格 |
| `06-timeline.md` | 时间线与最近12个月动态 |

### 一手来源（节选）

- https://arktos.com/product/the-fourth-political-theory/
- https://arktos.com/product/the-rise-of-the-fourth-political-theory/
- https://www.4pt.su/
- https://www.4pt.su/en/content/alexander-dugin-great-awakening-and-russian-higher-education-reform
- https://tuckercarlson.com/the-tucker-carlson-encounter-aleksandr-dugin
- https://home.treasury.gov/news/press-releases/jy0628

### 二手来源（节选）

- https://www.wilsoncenter.org/sites/default/files/media/documents/publication/OP294_aleksandr_drugin_laruelle_2006.pdf
- https://fsi.stanford.edu/docs/aleksandr-dugins-foundations-geopolitics
- https://meduza.io/en/feature/2025/02/25/alexander-dugin-s-plan-to-remake-political-science
- https://meduza.io/en/news/2025/04/04/moscow-state-university-launches-new-western-studies-lecture-course-by-eurasianist-philosopher-alexander-dugin
- https://apnews.com/article/fff3403c48e8b9c0bcf98cf4983c8aee

> 已按女娲规范排除知乎、微信公众号、百度百科。

---

## 这个Skill是怎么造出来的

由 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) 自动生成。

流程：输入人物 -> 6个维度并行调研（著作/对话/表达/他者/决策/时间线） ->
框架提炼 -> SKILL.md构建 -> 质量检查（模型数量、局限、表达DNA、诚实边界、内在张力、一手占比）。

---

## 仓库结构

```text
dugin-skill/
├── README.md
├── LICENSE
├── SKILL.md
├── references/
│   └── research/
│       ├── 01-writings.md
│       ├── 02-conversations.md
│       ├── 03-expression-dna.md
│       ├── 04-external-views.md
│       ├── 05-decisions.md
│       └── 06-timeline.md
└── examples/
    └── demo-conversation-2026-04-14.md
```

---

## 许可证

MIT

---

## 来源标注

本项目明确基于 [nuwa-skill](https://github.com/alchaincyf/nuwa-skill) 的方法论与流程产出。
