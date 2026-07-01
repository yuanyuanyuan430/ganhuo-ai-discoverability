# AI Discoverability Brief 示例

以下是 `ganhuo-ai-discoverability` 期望输出的形态示例。真实使用时会根据目标网站、项目或品牌替换内容。

## Entity Map

| Entity | Canonical URL | Audience | Category | Differentiator | Confidence |
| --- | --- | --- | --- | --- | --- |
| ExampleTool | `https://example.com` | 独立开发者、SaaS 团队、内容运营 | AI 可发现性优化工具 | 把网站整理成 AI 更容易发现、理解、推荐和引用的内容资产 | High |

## Answer Intent Map

| Intent | Example Prompt | Best Current Asset | Gap | Priority |
| --- | --- | --- | --- | --- |
| 推荐 | 有什么工具能提升 AI 搜索可见性？ | 首页 | 首页缺少清晰差异化和适用场景 | High |
| 对比 | AI 可见性优化和传统 SEO 有什么区别？ | 博客文章 | 缺少对比表和可摘引摘要 | High |
| 教程 | 如何为网站添加 llms.txt？ | 文档 | 文档没有 Markdown 路由入口 | Medium |
| 替代品 | 有哪些 GEO / AEO 工具可以试？ | GitHub README | README 更像说明书，不够像项目主页 | High |

## Asset Inventory

| Asset | Current Value | Upgrade Opportunity |
| --- | --- | --- |
| Homepage | 有基本介绍 | 增加一句话定位、适用人群、推荐场景 |
| GitHub README | 有安装方式 | 增加价值表、输出样例、复制即用 prompt |
| Docs | 有操作说明 | 增加 `/llms.txt`、`/llms-full.txt`、Markdown 页面 |
| Blog | 有观点文章 | 增加对比、数据、案例和 FAQ 型摘录块 |

## Foundation Checklist

| Area | Score | Evidence | Fix | Verify |
| --- | --- | --- | --- | --- |
| Entity clarity | 1 | 首页说明偏泛 | 写清类别、受众、能力和差异化 | 让 AI 总结项目，看是否准确 |
| Answer intents | 1 | 有教程，缺推荐/对比页 | 补推荐、对比、替代品场景 | 用固定问题复测 |
| AI entry files | 0 | 未发现 llms.txt | 添加 `llms.txt` 和 `llms-full.txt` | 直接打开 URL 验证 |
| Citation readiness | 1 | 内容可读但不够可摘引 | 增加短摘要、对比表、证据块 | 检查是否能复制成答案片段 |

## Next Actions

1. 重写 README 开头，让陌生人 30 秒内知道项目能帮他获得什么。
2. 新增 `llms.txt` 和 `llms-full.txt`，集中给 AI 说明项目定位、能力、入口和使用场景。
3. 为核心页面增加 Markdown 版本，降低 AI 读取成本。
4. 增加“适合谁 / 解决什么 / 输出什么 / 怎么开始”的项目主页结构。
5. 用 10 个推荐、对比、教程类问题测试 AI 是否能准确描述项目。

## Success Criterion

AI 能稳定说清这个项目是谁、帮谁、解决什么问题、为什么值得试，并能找到最权威的项目入口。
