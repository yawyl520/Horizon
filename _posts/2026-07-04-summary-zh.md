---
layout: default
title: "Horizon Summary: 2026-07-04 (ZH)"
date: 2026-07-04
lang: zh
---

> 从 15 条内容中筛选出 5 条重要资讯。

---

1. [欧盟议会间谍软件调查员遭 Pegasus 入侵](#item-1) ⭐️ 9.0/10
2. [SearXNG：免费、可自托管的元搜索引擎](#item-2) ⭐️ 8.0/10
3. [Current AI 发布开源 AI 差距地图](#item-3) ⭐️ 8.0/10
4. [Josh Comeau 报告课程销量因 AI 下降 67%](#item-4) ⭐️ 7.0/10
5. [让 AI 模型自行判断以提高效率](#item-5) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [欧盟议会间谍软件调查员遭 Pegasus 入侵](https://citizenlab.ca/research/member-of-committee-investigating-spyware-hacked-with-pegasus/) ⭐️ 9.0/10

公民实验室高度确信，欧盟议会调查间谍软件委员会的一名成员在 2022 年和 2023 年多次感染了 Pegasus 间谍软件。 这一事件凸显了由国家支持的间谍活动对欧洲民主机构的威胁，可能危及敏感调查并破坏议会主权。 2022 年 10 月的首次感染与一项针对俄罗斯和白俄罗斯流亡记者的 Pegasus 活动重叠，暗示同一个拥有跨国授权的 Pegasus 客户。目标的个人手机还包含机密医疗和政府文件，表明缺乏设备隔离。

hackernews · ledoge · 7月3日 20:38 · [社区讨论](https://news.ycombinator.com/item?id=48779683)

**背景**: Pegasus 是由以色列 NSO 集团开发的一款强大的间谍软件，能够远程监视移动设备。它以打击犯罪和恐怖主义的名义出售给政府，但被广泛滥用于针对记者、活动家和政治家。公民实验室是多伦多大学的一个研究小组，揭露对人权的数字威胁。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Pegasus_(spyware)">Pegasus (spyware)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Pegasus_Project_(investigation)">Pegasus Project (investigation) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Citizen_Lab">Citizen Lab</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，希腊和波兰也发生过类似的 Pegasus 攻击，猜测此次攻击可能与国内政治间谍活动有关而非外部势力。有人批评欧盟议会缺乏工作与个人设备分离的政策，可能危及敏感数据。

**标签**: `#cybersecurity`, `#espionage`, `#Pegasus`, `#European Parliament`, `#spyware`

---

<a id="item-2"></a>
## [SearXNG：免费、可自托管的元搜索引擎](https://github.com/searxng/searxng) ⭐️ 8.0/10

SearXNG 是一个免费、开源的互联网元搜索引擎，它从多个搜索服务和数据库中聚合搜索结果，且不会跟踪或分析用户。 该工具对注重隐私的用户和构建本地 AI 助手的开发者意义重大，它提供了尊重隐私的搜索能力，可集成到工具调用和 RAG 流程中，无需依赖中心化搜索 API。 SearXNG 支持 JSON 格式的结果输出，非常适合在代理工作流中程序化使用，并且可以在本地网络或个人设备上自托管。不过，用户偶尔可能会遇到来自上游搜索引擎（如 DuckDuckGo 或 Brave）的验证码拦截。

hackernews · theanonymousone · 7月3日 20:15 · [社区讨论](https://news.ycombinator.com/item?id=48779454)

**背景**: 元搜索引擎是一种在线工具，它将用户的查询同时发送到多个搜索引擎，并将结果聚合到一个列表中。与传统搜索引擎不同，元搜索引擎不维护自己的网页索引，这增强了用户隐私，因为查询被分散到不同的服务中。SearXNG 是原始 Searx 项目的一个分支，由 asciimoo 创建，并由一个开发者社区维护。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/searxng/searxng">GitHub - searxng/searxng: SearXNG is a free internet metasearch engine which aggregates results from various search services and databases. Users are neither tracked nor profiled. · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/SearXNG">SearXNG - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Metasearch_engine">Metasearch engine - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 原始创建者 asciimoo 表示因元搜索概念的限制已不再参与开发，并指向了他的新项目 Hister。其他用户称赞 SearXNG 支持本地模型工具调用和 RAG，有人已将其作为日常搜索工具使用超过五年。常见的顾虑包括搜索速度较慢以及偶尔遇到的验证码挑战。

**标签**: `#search engine`, `#privacy`, `#self-hosted`, `#metasearch`, `#open source`

---

<a id="item-3"></a>
## [Current AI 发布开源 AI 差距地图](https://simonwillison.net/2026/Jul/3/open-source-ai-gap-map/#atom-everything) ⭐️ 8.0/10

非营利组织 Current AI 获得 4 亿美元资助，发布了开源 AI 差距地图 v0.1，收录了来自 228 个组织的 421 款产品，涵盖模型、工具、数据集和硬件。 该系统性地图提供了开源 AI 生态的全面视图，有助于研究人员和实践者识别差距与机遇，并促进合作。 该地图将 421 款产品分为 3 个堆栈层的 14 个类别，另有 24,400 个未分类制品；底层数据以 MIT 许可证发布在 GitHub 上。

rss · Simon Willison · 7月3日 22:04

**背景**: Current AI 是一家全球性非营利组织，于 2025 年 2 月在巴黎人工智能行动峰会上成立，旨在构建人工智能的公共选项。该差距地图基于哥伦比亚大学会议、MOF、Hugging Face 等专家的工作，评估了超过 24,626 个项目在开放性、能力和采用方面的表现。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://map.currentai.org/">Current AI – Open Source AI Gap Map</a></li>

</ul>
</details>

**标签**: `#open source`, `#AI`, `#ecosystem mapping`, `#non-profit`, `#gap analysis`

---

<a id="item-4"></a>
## [Josh Comeau 报告课程销量因 AI 下降 67%](https://simonwillison.net/2026/Jul/3/josh-w-comeau/#atom-everything) ⭐️ 7.0/10

知名教育者 Josh W. Comeau 报告称，其最新课程发布销量仅为以往的三分之一左右，并将下滑归因于 AI 带来的就业不确定性以及 LLM 取代付费学习资源。 这一趋势表明开发者教育市场正遭受重大冲击：AI 不仅因就业担忧减少学习需求，还提供了付费课程的免费替代方案，威胁独立创作者的商业模式。 Comeau 指出，他现有的两门课程销量同比也大幅下滑，其他课程创作者报告收入下降超过 50%，用户转向 LLM，而 LLM 未经同意或补偿便吞噬了他们的创作内容。

rss · Simon Willison · 7月3日 21:25

**背景**: Josh W. Comeau 是备受尊敬的前端开发教育者，以 CSS 和 React 的交互式课程闻名。大型语言模型（如 GPT-4）的兴起使得无需人类讲师即可提供个性化辅导，同时 AI 驱动的自动化引发了技术岗位被取代的担忧，降低了人们投资技能发展的意愿。

**标签**: `#AI Impact`, `#Education`, `#Developer Trends`, `#Online Courses`

---

<a id="item-5"></a>
## [让 AI 模型自行判断以提高效率](https://simonwillison.net/2026/Jul/3/judgement/#atom-everything) ⭐️ 7.0/10

Claude Code 团队建议让 Fable 等 AI 模型自行判断测试和模型选择等任务，而不是给出具体指令，以节省令牌并提高效率。Simon Willison 通过提示 Claude Code 将编码任务委托给使用适当低功率模型的子代理，成功实现了这一点。 这一实用技巧可以帮助开发者在使用 Claude Code 等高级 AI 编码助手时显著减少令牌使用和成本，尤其是在价格即将变化之际。它也展示了向更自主的 AI 工作流程的转变，模型自行管理资源分配。 使用的提示是“对于所有编码任务，请自行判断并使用合适的低功率模型，在子代理中运行”。Claude Code 将此存储为记忆文件，将实质性实现委托给 Sonnet，琐碎编辑委托给 Haiku，而将判断密集型任务保留在主模型中。

rss · Simon Willison · 7月3日 18:51

**背景**: Claude Fable 5 是 Anthropic 最具能力的模型，适用于大型编码项目，但使用成本高且消耗大量令牌。Claude Code 是一个 AI 代理，可以读取代码库、编辑文件和运行命令。该技巧利用 Sonnet 和 Haiku 等低功率模型的子代理来处理常规编码任务，为高级判断和审查保留 Fable 令牌。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://docs.anthropic.com/en/docs/claude-code/overview">Claude Code overview - Anthropic</a></li>

</ul>
</details>

**标签**: `#AI`, `#prompt engineering`, `#Claude Code`, `#software engineering`

---