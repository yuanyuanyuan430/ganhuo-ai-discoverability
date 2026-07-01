# ganhuo-ai-discoverability

帮网站、产品和开源项目建立 AI 可发现性基础，让 ChatGPT、Claude、Perplexity、Gemini 等新时代 AI 系统更容易发现、理解、推荐并引用你的内容。

`ganhuo-ai-discoverability` 是一套面向 AI 时代的网站与项目可发现性优化工作流。过去，网站增长主要围绕搜索引擎排名展开；现在，越来越多用户通过 ChatGPT、Claude、Perplexity、Gemini、Google AI answers 等系统获取答案、比较方案、寻找工具和引用资料。一个项目是否容易被这些系统发现、理解、推荐和引用，正在成为新的基础能力。

这个项目帮助你把“让 AI 看见我”拆成可执行的工程与内容任务：明确实体定位，梳理目标问答场景，检查抓取与索引基础，建立 `llms.txt`、`llms-full.txt`、Markdown 路由、站点地图等 AI 可读入口，并把关键页面打磨成结构清楚、证据充分、语义稳定的引用源。它适合开源项目、SaaS 产品、工具站、内容品牌和知识库，用更系统的方式提升在 AI 答案生态中的被理解和被引用机会。

## 核心优势

- 建立清晰实体画像：统一品牌、项目、受众、类别和差异化表达。
- 映射 AI 问答意图：覆盖推荐、对比、定义、教程、场景等高价值问题。
- 构建 AI 可读入口：规划 `llms.txt`、`llms-full.txt`、Markdown 路由和站点地图。
- 优化抓取与索引基础：让关键页面更便于搜索和检索系统访问、解析、收录。
- 提升引用准备度：把页面打造成结构清楚、信息可信、证据充分、便于摘引的内容源。

## 适用场景

- 开源项目希望被 AI 编程助手更准确理解和推荐。
- SaaS、工具站、独立产品希望进入 AI 搜索和答案场景。
- 内容站希望提升在 ChatGPT、Claude、Perplexity、Gemini 等答案中的出现机会。
- 品牌官网需要统一实体信息、项目说明和可引用资料。
- 做 GEO / AI Search / AEO 前，需要先搭好基础诊断和内容入口。

## 安装

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/yuanyuanyuan430/ganhuo-ai-discoverability.git ~/.codex/skills/ganhuo-ai-discoverability
```

重启 Codex 后，使用 `$ganhuo-ai-discoverability` 触发技能。

## 使用示例

```text
用 ganhuo-ai-discoverability 分析 example.com 的 AI 可发现性，输出实体地图、意图表、入口文件检查和下一步动作。
```

也可以这样问：

```text
请用 ganhuo-ai-discoverability 帮我的开源项目做 GEO 基础优化，让 AI 更容易发现、理解和推荐它。
```

## 输出内容

技能会输出一份紧凑的 `AI Discoverability Brief`：

- Entity Map：实体、官网、受众、类别、差异化。
- Answer Intent Map：推荐、对比、定义、教程、替代品等高价值提问场景。
- Foundation Checklist：抓取、索引、`llms.txt`、Markdown 路由、站点地图等基础项。
- Citation Readiness：哪些页面更适合被 AI 摘引，哪些内容需要补证据。
- Actions：3-5 条最值得立刻执行的优化动作。
- Route：是否进入技术审计、引用增长或 Reddit GEO 等后续流程。

## 文件结构

```text
.
├── SKILL.md
├── README.md
├── manifest.json
├── LICENSE
├── agents/
│   └── openai.yaml
└── references/
    ├── checklist.md
    └── source-map.md
```

## 来源

这个技能基于 Tw93 的《你不知道的 GEO：AI 可见性的原理、实践与取舍》整理，并参考 OpenAI、Anthropic、Perplexity crawler 文档、`llms.txt` 规范和 IndexNow 文档。平台规则会持续变化，具体 bot、WAF、索引配置以执行时的官方文档复核为准。
