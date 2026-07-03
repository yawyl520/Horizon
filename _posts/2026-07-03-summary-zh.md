---
layout: default
title: "Horizon Summary: 2026-07-03 (ZH)"
date: 2026-07-03
lang: zh
---

> 从 25 条内容中筛选出 5 条重要资讯。

---

1. [美国禁止人口普查数据中的差分隐私](#item-1) ⭐️ 9.0/10
2. [弗吉尼亚州禁止出售地理位置数据](#item-2) ⭐️ 8.0/10
3. [使用 DSPy 改进 Datasette Agent 的 SQL 提示](#item-3) ⭐️ 7.0/10
4. [理解以参与：AI 编程代理的新框架](#item-4) ⭐️ 7.0/10
5. [智能模型路由：AI 新趋势](#item-5) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [美国禁止人口普查数据中的差分隐私](https://scottaaronson.blog/?p=9902) ⭐️ 9.0/10

2026 年 6 月 4 日，美国商务部长发布了第 216-26 号指令，禁止在人口普查局和经济分析局发布的所有统计产品中使用噪声注入和差分隐私技术。 该指令严重削弱了人口普查受访者的隐私保护，并降低了数据质量，危及依赖准确人口统计数据进行的关键研究和政策决策。 该指令将披露避免方法限制为仅限“粗化”处理（如数据聚合或抑制），并明确禁止添加随机噪声，而这正是 2020 年人口普查所采用的差分隐私技术的基础。

hackernews · flowercalled · 7月3日 00:01 · [社区讨论](https://news.ycombinator.com/item?id=48768992)

**背景**: 差分隐私是一种数学框架，通过向数据中添加经过校准的噪声来保护个人记录，同时保持统计准确性。在研究人员表明早期方法（如数据交换）可能泄露个人信息后，人口普查局在 2020 年人口普查中采用了该方法。新禁令取消了这一现代保护措施，仅允许粗化处理作为披露避免手段。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://stateofsurveillance.org/news/census-bureau-noise-infusion-ban-differential-privacy-rollback-2026/">The Census Bureau Just Banned the Math That Kept Your Data ...</a></li>
<li><a href="https://www.npr.org/2026/06/12/nx-s1-5855734/census-bureau-data-differential-privacy">Trump privacy restrictions may reduce Census Bureau data : NPR</a></li>
<li><a href="https://www.404media.co/census-data-privacy-trump-policy-change-noise-infusion/">The Trump Administration’s New Census Data Rules Are a Policy ...</a></li>

</ul>
</details>

**社区讨论**: 评论者表示震惊，Scott Aaronson 称其为“隐私紧急事件”。有人质疑政治动机，也有人呼吁联系立法者并提供了查找代表的链接。

**标签**: `#privacy`, `#differential privacy`, `#census`, `#data policy`, `#disclosure avoidance`

---

<a id="item-2"></a>
## [弗吉尼亚州禁止出售地理位置数据](https://www.hunton.com/privacy-and-cybersecurity-law-blog/virginia-bans-sale-of-geolocation-data) ⭐️ 8.0/10

弗吉尼亚州颁布立法，禁止出售精确地理位置数据，即禁止传输能够识别个人位置至 1750 英尺范围内的位置信息。 这项法律标志着州级隐私监管的重要一步，解决了位置数据被滥用的日益担忧，例如追踪前往堕胎诊所的行为。它树立了一个先例，可能影响其他州并迫使科技公司采取更严格的数据实践。 该禁令仅适用于 1750 英尺范围内的精确地理位置数据，因此公司仍可以出售模糊或聚合的位置数据。对于州外实体以及存储在弗吉尼亚州云服务器上的数据，执法情况仍不明确。

hackernews · toomuchtodo · 7月2日 21:03 · [社区讨论](https://news.ycombinator.com/item?id=48767347)

**背景**: 地理位置数据从移动设备和应用程序中收集，通常出售给广告商和数据经纪人。这些数据可以揭示敏感信息，如医疗就诊、宗教活动和政治归属。美国缺乏全面的联邦隐私法，导致各州自行制定保护措施。弗吉尼亚州的《消费者数据保护法》此前包含一些数据权利，但这项新禁令专门针对位置数据的出售。

**社区讨论**: 社区评论普遍支持这项禁令，但提出对执法漏洞的担忧，特别是针对州外公司以及模糊位置数据的出售。一些人强调精确数据追踪的现实危害，例如针对计划生育访客的反堕胎广告活动。

**标签**: `#privacy`, `#geolocation`, `#legislation`, `#data rights`, `#US law`

---

<a id="item-3"></a>
## [使用 DSPy 改进 Datasette Agent 的 SQL 提示](https://simonwillison.net/2026/Jul/2/dspy-datasette-agent-prompts/#atom-everything) ⭐️ 7.0/10

Simon Willison 使用 DSPy 框架评估并改进了 Datasette Agent 的系统提示，该助手用于生成 SQL 查询以回答用户问题。 这展示了一种对 AI 代理提示进行程序化优化的实用方法，可能减少对手动提示工程的依赖，并提高数据探索工具中 SQL 生成的可靠性。 该研究通过 Claude Code 和 Claude Fable 5 以异步任务形式进行，使用 GPT-4.1 mini 和 nano 模型测试，发现了诸如在 schema 列表中包含列名以避免错误重试循环等改进方向。

rss · Simon Willison · 7月2日 18:25

**背景**: DSPy（Declarative Self-improving Python）是一个用于算法化优化语言模型提示和权重的框架，使开发者能够程序化地改进 AI 管道性能。Datasette Agent 是一个 AI 助手，利用大型语言模型生成并执行 SQL 查询，以探索 Datasette 中的数据，Datasette 是一个用于发布和分析数据的开源工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://dspy.ai/">DSPy</a></li>
<li><a href="https://agent.datasette.io/">Datasette Agent : an AI assistant for Datasette to help explore and...</a></li>
<li><a href="https://github.com/stanfordnlp/dspy">GitHub - stanfordnlp/dspy: DSPy: The framework for ... What Is DSPy? How It Works, Use Cases, and Resources GitHub - isaka/DSPy: DSPy: The framework for programming—not ... Tutorials Overview - DSPy DSPy Framework — Programmatic Prompt Optimization (2026) Programming, Not Prompting: A Hands-On Guide to DSPy</a></li>

</ul>
</details>

**标签**: `#DSPy`, `#prompt engineering`, `#SQL`, `#AI agents`, `#Datasette`

---

<a id="item-4"></a>
## [理解以参与：AI 编程代理的新框架](https://simonwillison.net/2026/Jul/2/understand-to-participate/#atom-everything) ⭐️ 7.0/10

Geoffrey Litt 在 2026 年 AI 工程师世界博览会上提出了‘理解以参与’的概念，认为开发者必须深入理解 AI 生成的代码，以避免积累认知债务。 这一框架为使用 AI 编程代理的软件工程师提供了关键思维模式，强调被动接受 AI 输出会导致对项目理解丧失和认知债务增加。 认知债务与技术债务不同，指的是团队间共享理解随时间推移的侵蚀。Litt 强调需要主动向 AI 代理学习，以保持创造性参与。

rss · Simon Willison · 7月2日 17:07

**背景**: 认知债务是软件工程中的一个概念，描述了代码库演化过程中理解力的丧失，AI 生成的代码往往会加速这一过程。‘理解以参与’方法通过敦促开发者彻底研究 AI 变更来应对此问题。这与简单审查差异形成对比，旨在实现更深层次的理解以促进进一步协作。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.geoffreylitt.com/2026/07/02/understanding-is-the-new-bottleneck.html">Understanding is the new bottleneck - Geoffrey Litt</a></li>
<li><a href="https://digg.com/tech/glvyx0iw">Geoffrey Litt argues that human comprehension of AI-generated ...</a></li>

</ul>
</details>

**标签**: `#AI agents`, `#cognitive debt`, `#software engineering`, `#code collaboration`

---

<a id="item-5"></a>
## [智能模型路由：AI 新趋势](https://blog.pragmaticengineer.com/the-pulse-a-new-trend-smart-model-routing/) ⭐️ 7.0/10

作者 Gergely Orosz 探讨了能够自动为每个任务选择最合适 AI 模型的智能路由方案，指出了从单一模型使用方式转变的趋势。 智能模型路由通过将任务匹配到合适规模的模型，可显著降低推理成本并提高效率，这对 AI 在各行业大规模应用至关重要。 Not Diamond、Martian、LiteLLM、MindStudio 以及由 Not Diamond 驱动的 OpenRouter Auto Router 等平台提供了智能路由功能，其中一些采用基于嵌入向量的语义路由。

rss · The Pragmatic Engineer · 7月2日 18:46

**背景**: 传统上，公司对所有任务依赖单一强大模型（如 GPT-4），导致开销过高。模型路由通过分类每个请求并选择模型（例如对简单查询使用较小模型）来优化成本和延迟。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cnbc.com/2026/06/05/model-routing-on-ai-is-a-problem-for-openai-and-anthropic.html">Model routing is a fix for AI overspending. That's a problem for OpenAI and Anthropic</a></li>
<li><a href="https://openrouter.ai/docs/guides/routing/routers/auto-router">Auto Router | Smart AI Model Selection | OpenRouter | Documentation</a></li>
<li><a href="https://github.com/vllm-project/semantic-router">GitHub - vllm-project/semantic-router: System Level ...</a></li>
<li><a href="https://medium.com/google-cloud/a-developers-guide-to-model-routing-1f21ecc34d60">A Developer’s Guide to Model Routing | by Karl Weinmeister | Google Cloud - Community | Medium</a></li>

</ul>
</details>

**标签**: `#AI/ML`, `#model routing`, `#engineering`, `#pragmatic engineer`

---