---
layout: default
title: "Horizon Summary: 2026-06-15 (ZH)"
date: 2026-06-15
lang: zh
---

> 从 19 条内容中筛选出 4 条重要资讯。

---

1. [小米 MiMo V2.5 通过 DFlash 和持久化内核实现 1000-3000 tps](#item-1) ⭐️ 9.0/10
2. [ePub 质量争论：Kobo 和 Adobe 被指为问题根源](#item-2) ⭐️ 8.0/10
3. [AI 为何未能也不会取代软件工程师](#item-3) ⭐️ 8.0/10
4. [OpenAI 推出合作伙伴网络，投资 1.5 亿美元](#item-4) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [小米 MiMo V2.5 通过 DFlash 和持久化内核实现 1000-3000 tps](https://www.reddit.com/r/LocalLLaMA/comments/1u5jtr8/xiaomi_is_now_serving_mimo_v25_at_10003000tps/) ⭐️ 9.0/10

小米宣布其 MiMo V2.5 大语言模型现在能够通过 DFlash 技术和持久化内核实现每秒 1000 到 3000 个 token 的推理速度，模型已发布，开源版本承诺即将推出。 这一突破可大幅降低大语言模型推理延迟，使大型模型更适用于实时应用，而承诺的开源发布可能使更广泛的 AI 社区受益，从而在消费级硬件上实现更快的推理。 DFlash 技术与持久化内核共同将计算和通信融合到单一内核中，实现了高达 3000 tps。开源版本预计将验证所声称的性能并允许社区采用。

reddit · r/LocalLLaMA · /u/Dany0 · 6月14日 12:26

**背景**: 大语言模型推理通常受限于内存带宽和内核启动开销。持久化内核（又称巨内核）将多个操作融合到单个 GPU 内核中，以减少启动延迟并提高吞吐量。DFlash 似乎是小米的专有优化技术，可能与闪存或高效数据处理有关。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://zhihaojia.medium.com/compiling-llms-into-a-megakernel-a-path-to-low-latency-inference-cf7840913c17">Compiling LLMs into a MegaKernel: A Path to Low-Latency Inference</a></li>
<li><a href="https://arxiv.org/abs/2512.22219">[2512.22219] MPK: A Compiler and Runtime for Mega-Kernelizing ...</a></li>

</ul>
</details>

**标签**: `#LLM inference`, `#open-source`, `#performance`, `#Xiaomi`, `#DFlash`

---

<a id="item-2"></a>
## [ePub 质量争论：Kobo 和 Adobe 被指为问题根源](https://andreklein.net/your-epub-is-fine-kobo-disagrees-blame-adobe/) ⭐️ 8.0/10

一篇文章认为 ePub 文件在技术上是合格的，但 Kobo 和 Adobe 软件中的实现缺陷导致了渲染问题，引发了社区讨论。 这很重要，因为数百万读者依赖 Kobo 设备和 Adobe Digital Editions，该讨论凸显了专有电子书软件和开放标准的更广泛问题。 社区成员报告称，Kobo 用于.epub 文件的旧渲染引擎会导致性能缓慢，而使用.kepub.epub 格式则能提升速度并启用阅读统计等功能。

hackernews · sohkamyung · 6月14日 22:54 · [社区讨论](https://news.ycombinator.com/item?id=48533848)

**背景**: ePub 是由 W3C 维护的开放电子书标准，但 Kobo 等设备制造商实现自己的渲染引擎。Adobe 的 RMSDK 是一种专有 SDK，被许多电子阅读器使用，但授权困难且存在质量问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/kobolabs/epub-spec/issues">Issues · kobolabs/epub-spec · GitHub</a></li>
<li><a href="https://community.adobe.com/questions-611/adobe-digital-editions-4-5-10-not-responding-in-windows-10-409070">Adobe Digital Editions 4.5.10 not responding in... | Community</a></li>
<li><a href="https://www.reddit.com/r/kobo/comments/1do7ivh/epub_issue_beginner_with_calibre/">EPUB issue/ Beginner with Calibre : r/kobo - Reddit</a></li>

</ul>
</details>

**社区讨论**: 评论批评 Adobe 历史上糟糕的 QA，指出 Flash 因可靠性问题而衰落。用户还提到获取 RMSDK 的困难，并建议使用 kepubify 等工具将 ePub 转换为 Kobo 原生格式以获得更好的性能。

**标签**: `#ePub`, `#Adobe`, `#e-reader`, `#Kobo`, `#software engineering`

---

<a id="item-3"></a>
## [AI 为何未能也不会取代软件工程师](https://simonwillison.net/2026/Jun/14/why-ai-hasnt-replaced-software-engineers/#atom-everything) ⭐️ 8.0/10

在一篇新文章中，Arvind Narayanan 和 Sayash Kapoor 认为数据不支持 AI 导致软件工程领域大规模裁员，指出纽约州 WARN 法案第一年没有公司报告 AI 相关裁员。他们识别出三个真正抵抗自动化的瓶颈：决定构建什么、验证并对交付物负责、以及对代码库、业务和环境的深度人类理解。 这篇文章直接挑战了 AI 将很快取代软件工程师的主流叙事，提供了基于证据的反驳。这很重要，因为软件工程常被认为是最易受 AI 影响的职业，如果它仍具有韧性，那么其他职业更有可能免受大规模替代。 作者指出纽约州 WARN 法案数据是具体证据：在强制披露 AI 相关裁员的第一整年，没有一家公司勾选该选项。他们还认为 AI 仅加速了编码的输入阶段，而软件工程的核心价值在于深度情境理解、决策和问责——这些领域 AI 尚无法自动化。

rss · Simon Willison · 6月14日 23:54

**背景**: 《工人调整和再培训通知法案》(WARN) 要求美国雇主提前通知大规模裁员。2025 年 3 月，纽约州在这些文件中增加了 AI 专用复选框以追踪 AI 相关的失业。文章解释软件工程远不止编写代码——还包括调试、会议和理解复杂系统——这就是为什么即使像 GitHub Copilot 这样的高级 AI 编程助手也没有消除软件工程岗位。

**标签**: `#AI`, `#software engineering`, `#job market`, `#automation`

---

<a id="item-4"></a>
## [OpenAI 推出合作伙伴网络，投资 1.5 亿美元](https://openai.com/index/introducing-openai-partner-network) ⭐️ 7.0/10

OpenAI 推出了新的合作伙伴计划——OpenAI 合作伙伴网络，并投入 1.5 亿美元，以加速企业级 AI 的采用、部署和转型。 OpenAI 的这一重大投资和战略推动表明其致力于扩大企业级 AI 的采用，有望通过认证合作伙伴重塑企业整合 AI 技术的方式。 该计划包括在联合销售、Codex 等专业化领域、工程支持以及渠道合作伙伴的客户机会方面的投资，首批 Frontier Alliance 合作伙伴包括 BCG、McKinsey、Accenture 和 Capgemini。

rss · OpenAI Blog · 6月14日 17:00

**背景**: 企业级 AI 的采用通常需要大量的专业知识和集成工作。合作伙伴网络是科技行业中常见的模式，像 OpenAI 这样的供应商向咨询公司和系统集成商提供资源、培训和支持，使他们能够有效地将供应商的解决方案部署给最终客户。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/introducing-openai-partner-network/">Introducing the OpenAI Partner Network | OpenAI</a></li>
<li><a href="https://openai.com/index/frontier-alliance-partners/">Introducing Frontier Alliances | OpenAI</a></li>
<li><a href="https://www.crn.com/news/ai/2026/openai-unveils-partner-program-150m-investment-channel-chief-sees-massive-opportunity-ahead">OpenAI Unveils Partner Program, $150M Investment; Channel Chief Sees ‘Massive Opportunity’ Ahead</a></li>

</ul>
</details>

**标签**: `#OpenAI`, `#enterprise AI`, `#partnerships`, `#AI adoption`

---