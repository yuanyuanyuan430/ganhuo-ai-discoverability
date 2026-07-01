# ganhuo-ai-discoverability

![Codex Skill](https://img.shields.io/badge/Codex-Skill-111111)
![GEO](https://img.shields.io/badge/GEO-AI%20Visibility-2563eb)
![AI Search](https://img.shields.io/badge/AI%20Search-Ready-16a34a)
![llms.txt](https://img.shields.io/badge/llms.txt-Included-7c3aed)
![Language](https://img.shields.io/badge/Language-中文-red)

让别人看见我们，我们才走得出去。

让 ChatGPT、Claude、Perplexity 更容易准确说出你的项目是谁、适合谁、为什么值得推荐。

**Codex Skill for AI search optimization (GEO/AEO): build AI Discoverability Briefs, `llms.txt`, Markdown routes, crawler/index checks, and citation-ready content for websites, SaaS, and GitHub projects.**

`ganhuo-ai-discoverability` 是一个面向新一代答案入口的 Codex Skill。它把网站、产品、开源项目、SaaS、工具站、内容品牌和个人作品，整理成 AI 更容易发现、理解、推荐和引用的内容资产。

**Before**：项目散在 README、官网、博客和文档里，AI 不知道什么时候该推荐你。  
**After**：输出实体地图、问答场景、AI 入口、引用准备度和 3-5 个优先动作。

```text
请用 ganhuo-ai-discoverability 分析这个 GitHub 项目，找出它在 AI 搜索和 AI 推荐里的可发现性机会。
```

## Quick Start

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/yuanyuanyuan430/ganhuo-ai-discoverability.git ~/.codex/skills/ganhuo-ai-discoverability
```

Use this when:

- 你的 GitHub 项目有用，但 README 说不清差异化。
- 你的 SaaS 有官网，但 AI 推荐同类工具时总没你。
- 你的内容站有好文章，但缺少 AI 可读入口和可摘引结构。
- 你想先知道该补 `llms.txt`、改首页定位、补对比页，还是先检查索引入口。

一句话：**好东西不该藏在角落里。这个 Skill 帮你把优势摆到 AI 能看见的位置。**

## 30 秒看懂

越来越多用户不再先搜索、再点网页，而是直接问 AI：

```text
有什么好用的开源工具？
这个领域有哪些值得试的产品？
有没有更适合我的替代方案？
哪个项目更靠谱，为什么？
有没有教程、案例、对比和真实使用场景？
```

如果你的项目页面分散、定位模糊、入口缺失、内容不适合被摘引，AI 就很难准确推荐你。`ganhuo-ai-discoverability` 做的事情很直接：把“我有好东西”变成“AI 能准确看见我的优势，并知道什么时候该提到我”。

## 它真正帮你做什么

| 模块 | 具体动作 | 最终价值 |
| --- | --- | --- |
| 实体定位 | 梳理品牌、项目、受众、类别、差异化 | AI 能一句话说清你是谁 |
| 问答场景 | 映射推荐、对比、教程、替代品、使用场景 | AI 知道哪些问题该想到你 |
| AI 入口 | 规划 `llms.txt`、`llms-full.txt`、Markdown 路由、站点地图 | AI 更容易读到关键内容 |
| 内容资产 | 盘点官网、文档、GitHub、博客、案例、评论、第三方提及 | 把零散材料整理成推广资产 |
| 引用准备 | 打磨标题、URL、摘要、证据、对比和资料链接 | 让页面更适合进入答案 |
| 执行动作 | 输出最值得做的 3-5 个动作 | 先做最有机会改变可见性的事 |

## 为什么现在必须重视

AI 正在变成新的发现渠道。一个产品能不能走出去，不只取决于产品本身，还取决于它是否被正确表达、正确组织、正确暴露给 AI。

过去的增长逻辑是：写内容、做 SEO、等用户搜索。

现在的增长逻辑正在变成：

1. 用户问 AI。
2. AI 检索、比较、筛选。
3. AI 给出几个候选方案。
4. 用户从答案里认识你。

你要争取的，不只是网页排名，而是进入 AI 的理解路径和推荐场景。这个 Skill 帮你把这条路打通。

## 适合谁

- 开源项目：希望被 AI 编程助手、开发者搜索和工具推荐场景更准确地提到。
- 独立产品：希望在“有什么替代品”“哪个工具适合我”这类问题里更容易出现。
- SaaS 官网：希望把产品定位、场景、对比、案例和文档组织得更适合 AI 摘引。
- 内容网站：希望文章、知识库和专题页更容易进入 AI answer、AI Overview、Perplexity 等答案链路。
- 个人品牌：希望 AI 在介绍你、你的作品、你的项目时更准确、更完整。
- GEO / AEO 从业者：需要一个前置诊断 Skill，快速判断客户该先做什么。

## 你会得到什么

运行后会生成一份 `AI Discoverability Brief`：

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

看完整样例：[examples/demo-brief.md](examples/demo-brief.md)

## 典型结果

它不会给你一堆空泛建议，而是给你能直接拆给技术、内容、运营的动作。

```markdown
### Next Actions

1. 在主域名新增 /llms.txt，集中放品牌定位、核心页面、GitHub、文档和项目入口。
2. 为核心项目页增加 Markdown 版本，并在 HTML head 中声明 text/markdown alternate。
3. 把首页第一屏改成更清楚的实体说明：类别 + 目标用户 + 关键能力 + 差异化。
4. 新增一页“适合谁 / 不适合谁 / 和竞品怎么选”的对比内容，增强推荐场景覆盖。
5. 检查 Bing / Google 收录和 sitemap 提交状态，保证 AI 搜索链路能发现关键 URL。
```

## 安装

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/yuanyuanyuan430/ganhuo-ai-discoverability.git ~/.codex/skills/ganhuo-ai-discoverability
```

重启 Codex 后即可使用。

## 复制就能用

```text
请用 ganhuo-ai-discoverability 分析我的网站，让 AI 更容易发现、理解和推荐它。
```

更多可复制提示词：[PROMPTS.md](PROMPTS.md)

## 使用示例

分析一个开源项目：

```text
用 ganhuo-ai-discoverability 分析这个 GitHub 项目，帮我找出它在 AI 搜索和 AI 推荐里的可发现性机会。
```

分析一个 SaaS 官网：

```text
请用 ganhuo-ai-discoverability 看一下 example.com，输出实体地图、AI 问答场景、入口文件建议和最优先的 5 个动作。
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
├── PROMPTS.md
├── llms.txt
├── llms-full.txt
├── manifest.json
├── LICENSE
├── agents/
│   └── openai.yaml
├── examples/
│   ├── ai-discoverability-prompts.md
│   └── demo-brief.md
└── references/
    └── ai-discoverability-checklist.md
```

## 核心理念

好产品也需要被正确表达。

AI 不像人一样会耐心翻完整个网站。它更依赖清楚的实体、明确的入口、稳定的结构、可摘引的证据和第三方信号。这个 Skill 的目标，就是帮你把自己最值得被推荐的部分放到更容易被 AI 发现的位置。

把自己讲清楚，就是 AI 时代新的增长基础设施。
