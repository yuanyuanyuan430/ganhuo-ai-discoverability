# ganhuo-ai-discoverability

![Codex Skill](https://img.shields.io/badge/Codex-Skill-111111)
![GEO](https://img.shields.io/badge/GEO-AI%20Visibility-2563eb)
![AI Search](https://img.shields.io/badge/AI%20Search-Ready-16a34a)
![Language](https://img.shields.io/badge/Language-中文-red)

让你的项目在 AI 时代更容易被看见。

`ganhuo-ai-discoverability` 是一个面向 ChatGPT、Claude、Perplexity、Gemini、Google AI answers 等新一代答案入口的 Codex Skill。它帮助网站、产品、开源项目、SaaS、工具站和内容品牌建立 AI 可发现性基础，让 AI 更容易发现你、理解你、推荐你，并在合适的回答里引用你。

过去，大家争的是搜索结果前 10。现在，越来越多用户直接问 AI：

```text
有什么好用的开源工具？
这个领域有哪些值得试的产品？
某个问题用什么方案更靠谱？
有没有替代品、对比、教程、案例？
```

如果你的项目说不清、页面分散、AI 抓不到、内容不适合摘引，即使产品本身不错，也可能在答案生态里没有存在感。这个 Skill 要解决的就是这件事：把“我有好东西”变成“AI 能准确看见我的优势”。

## 它帮你推广什么

这个 Skill 不是简单做 SEO 检查，而是把你的项目包装成 AI 更容易理解的内容资产。

| 能力 | 它会帮你做什么 | 对 AI 的价值 |
| --- | --- | --- |
| 实体定位 | 梳理品牌、项目、受众、类别、差异化 | 让 AI 知道你到底是谁 |
| 问答场景 | 映射推荐、对比、教程、替代品、使用场景 | 让 AI 知道什么时候该想到你 |
| AI 入口 | 规划 `llms.txt`、`llms-full.txt`、Markdown 路由、站点地图 | 让 AI 更容易读到关键内容 |
| 抓取基础 | 检查关键页面是否便于访问、解析、收录 | 让 AI 搜索链路更顺 |
| 引用准备 | 打磨标题、URL、摘要、证据、对比和资料链接 | 让页面更适合进入答案 |
| 下一步路线 | 输出最值得做的 3-5 个动作 | 让执行聚焦，不浪费时间 |

## 为什么值得做

AI 正在变成新的发现渠道。用户不一定先进 Google，再点进你的官网；他们可能直接在 AI 里完成搜索、比较、筛选和决策。

这意味着，一个项目要被推荐，不能只靠“我写了很多内容”。它还需要：

- 一个清楚的实体身份：AI 能一句话说清你是谁。
- 一组明确的问题场景：AI 知道哪些问题适合提到你。
- 几个稳定的内容入口：AI 能快速找到最权威的说明。
- 一批可摘引的页面：AI 能从你的内容里拿到清楚、可信、完整的片段。
- 一套后续动作：知道先补入口、先补内容，还是先解决抓取问题。

`ganhuo-ai-discoverability` 把这些拆成一个可执行的 Brief。不是堆术语，不是刷分，而是帮你把优势摆到 AI 能看懂的位置。

## 适合谁

- 开源项目：希望被 AI 编程助手、开发者搜索和工具推荐场景更准确地提到。
- 独立产品：希望在“有什么替代品”“哪个工具适合我”这类问题里更容易出现。
- SaaS 官网：希望把产品定位、场景、对比、案例和文档组织得更适合 AI 摘引。
- 内容网站：希望文章和知识库能进入 AI answer、AI Overview、Perplexity 等答案链路。
- 个人品牌：希望 AI 在介绍你、你的作品、你的项目时更准确、更完整。
- GEO / AEO 从业者：需要一个前置诊断 Skill，快速判断客户该先做什么。

## 它会输出什么

运行后会生成一份 `AI Discoverability Brief`，核心包括：

```markdown
## AI Discoverability Brief

### Entity Map
你的品牌 / 产品 / 项目是谁，面向谁，属于什么类别，最强差异点是什么。

### Answer Intent Map
哪些用户问题最值得争取：推荐、对比、定义、教程、替代品、场景、限制。

### Asset Inventory
官网、文档、GitHub、博客、案例、评论、第三方提及等现有资产盘点。

### Foundation Checklist
robots.txt、sitemap、llms.txt、Markdown 路由、索引、主域名入口等基础项。

### Citation Readiness
哪些页面已经适合被 AI 引用，哪些页面需要补标题、摘要、证据、对比和数据。

### Next Actions
3-5 条最值得立刻执行的动作，按影响力排序。
```

## 一个典型结果

```markdown
### Next Actions

1. 在主域名新增 /llms.txt，集中放品牌定位、核心页面、GitHub、文档和项目入口。
2. 为核心项目页增加 Markdown 版本，并在 HTML head 中声明 text/markdown alternate。
3. 把首页第一屏改成更清楚的实体说明：类别 + 目标用户 + 关键能力 + 差异化。
4. 新增一页“适合谁 / 不适合谁 / 和竞品怎么选”的对比内容，增强推荐场景覆盖。
5. 检查 Bing / Google 收录和 sitemap 提交状态，保证 AI 搜索链路能发现关键 URL。
```

这类输出的价值在于：你不会得到一堆泛泛建议，而是得到一组能立刻执行、能验证、能继续拆给技术或内容团队的动作。

## 安装

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/yuanyuanyuan430/ganhuo-ai-discoverability.git ~/.codex/skills/ganhuo-ai-discoverability
```

重启 Codex 后即可使用：

```text
请用 ganhuo-ai-discoverability 分析我的网站，让 AI 更容易发现、理解和推荐它。
```

## 使用示例

分析一个开源项目：

```text
用 ganhuo-ai-discoverability 分析这个 GitHub 项目，帮我找出它在 AI 搜索和 AI 推荐里的可发现性机会。
```

分析一个 SaaS 官网：

```text
请用 ganhuo-ai-discoverability 看一下 example.com，输出实体地图、AI 问答场景、入口文件建议和最优先的 5 个动作。
```

分析一个内容站：

```text
用 ganhuo-ai-discoverability 帮我的内容站做 AI 可见性诊断，重点看哪些页面更有机会被 AI 引用。
```

为自己的项目做推广：

```text
请用 ganhuo-ai-discoverability 重新梳理我的项目介绍，让 ChatGPT、Claude、Perplexity 更容易理解它的优势。
```

## 文件结构

```text
.
├── SKILL.md
├── README.md
├── llms.txt
├── llms-full.txt
├── manifest.json
├── LICENSE
├── agents/
│   └── openai.yaml
└── references/
    └── checklist.md
```

## 核心理念

好产品也需要被正确表达。

AI 不像人一样会耐心翻完整个网站。它更依赖清楚的实体、明确的入口、稳定的结构、可摘引的证据和第三方信号。这个 Skill 的目标，就是帮你把自己最值得被推荐的部分放到更容易被 AI 发现的位置。

把自己讲清楚，就是 AI 时代新的增长基础设施。
