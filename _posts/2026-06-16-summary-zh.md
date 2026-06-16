---
layout: default
title: "Horizon Summary: 2026-06-16 (ZH)"
date: 2026-06-16
lang: zh
---

> 从 27 条内容中筛选出 3 条重要资讯。

---

1. [领英招聘中的后门利用 npm prepare 脚本](#item-1) ⭐️ 9.0/10
2. [Qwable-v1：从 Claude Fable-5 蒸馏的开源模型](#item-2) ⭐️ 9.0/10
3. [Anthropic 内部冲突导致模型下线，出口管制争议升级](#item-3) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [领英招聘中的后门利用 npm prepare 脚本](https://roman.pt/posts/linkedin-backdoor/) ⭐️ 9.0/10

一名求职者在招聘过程中发现招聘人员发送的 GitHub 仓库中隐藏着后门，该后门利用 npm 的 prepare 脚本在运行 npm install 时执行任意代码。 这种攻击结合了社会工程学和供应链漏洞，揭示了一种直接针对开发者的危险攻击途径。它凸显了在招聘流程和 npm 生态系统中加强安全措施的必要性。 招聘人员要求申请人审查一个 GitHub 仓库，用于“破损的概念验证”，后门隐藏在注释掉的测试中。prepare 脚本在 npm install 后自动运行，无需用户干预即可执行负载。

hackernews · lwhsiao · 6月15日 20:00 · [社区讨论](https://news.ycombinator.com/item?id=48546294)

**背景**: npm 的生命周期脚本（如 prepare、preinstall 和 postinstall）在包安装期间自动运行，使其成为供应链攻击的常见载体。GitHub 已宣布 npm v12 将默认禁用安装脚本以降低此类风险。npm 生态系统对这些脚本的依赖一直受到批评，因为它助长了此类攻击。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.blog/changelog/2026-06-09-upcoming-breaking-changes-for-npm-v12/">Upcoming breaking changes for npm v12 - GitHub Changelog</a></li>
<li><a href="https://thehackernews.com/2026/06/github-to-disable-npm-install-scripts.html">GitHub to Disable npm Install Scripts by Default to Stop Supply Chain ...</a></li>
<li><a href="https://shipwithai.io/blog/npm-install-security-30-seconds/">The 30-Second npm Defense Every Vibe Coder Needs — ShipWithAI</a></li>

</ul>
</details>

**社区讨论**: 评论者对于 GitHub 和领英未对报告采取行动表示失望，有人指出此类攻击已存在多年。部分人批评 npm 生态系统本身，质疑为什么开发者仍在使用它。还有人称需要更好的网络犯罪举报机制。

**标签**: `#security`, `#npm`, `#social engineering`, `#supply chain attack`, `#recruitment`

---

<a id="item-2"></a>
## [Qwable-v1：从 Claude Fable-5 蒸馏的开源模型](https://www.reddit.com/r/LocalLLaMA/comments/1u6zj79/claude_fable_5_distilled/) ⭐️ 9.0/10

研究人员发布了 Qwable-v1，这是一个从 Anthropic 短暂的 Fable-5 模型中蒸馏得到的开源权重模型，仅使用了 4,659 条绕过反蒸馏过滤的智能编码轨迹。 这是首个从 Fable-5 蒸馏的开源权重模型，保留了其强大的工具使用能力，可能加速开源 AI 代理开发，使高级智能编码更易获取。 该模型基于 Qwen3.6-35B-A3B，在单个 H200 上训练了 14 小时，并包含 GGUF 量化版本（IQ4_XS、Q4_K_M、Q5_K_M、Q8_0），全部在 Hugging Face 上以 AGPL-3.0 许可公开提供。

reddit · r/LocalLLaMA · /u/Anony6666 · 6月16日 01:21

**背景**: 模型蒸馏是一种训练较小学生模型模仿较大教师模型输出的技术。Claude 的 Fable-5 是一个强大但短暂的模型，内置了反蒸馏分类器以防止复制。Qwable-v1 项目使用了绕过这些分类器的轨迹，并在基于 Qwen 的架构上进行了微调。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://platform.claude.com/docs/en/agents-and-tools/tool-use/text-editor-tool">Text editor tool - Claude API Docs</a></li>
<li><a href="https://www.modemguides.com/blogs/ai-news/claude-code-leak-architecture-analysis">Claude Code Leak: Anti - Distillation , Undercover Mode, and...</a></li>

</ul>
</details>

**标签**: `#open-source LLM`, `#model distillation`, `#Claude Fable-5`, `#AI research`, `#agentic coding`

---

<a id="item-3"></a>
## [Anthropic 内部冲突导致模型下线，出口管制争议升级](https://simonwillison.net/2026/Jun/15/axios-clashes-anthropics/#atom-everything) ⭐️ 7.0/10

Axios 报道称，Anthropic 内部的人格冲突导致其 AI 模型下线，与此同时，该公司与美国政府之间关于出口管制的紧张局势升级。包括前沿红队负责人 Logan Graham 在内的关键人物正在与商务部会面以应对此事。 这凸显了 AI 公司与政府监管机构之间日益加剧的摩擦，尤其是在出口控制和越狱漏洞方面。Anthropic 的先进模型（如 Mythos 和 Fable）的命运取决于技术问题和人际问题的解决。 文章引用了熟悉政府和公司情况的匿名消息源，并指出完美的越狱防御可能是不可能的。Anthropic 的宪法分类器工作与触发政府回应的越狱相关，该越狱被归类为“潜在的狭窄、非通用越狱”。

rss · Simon Willison · 6月15日 14:57

**背景**: Anthropic 是一家领先的 AI 安全公司，开发了先进模型如 Mythos（其最强大但未公开发布）和 Fable（面向公众的 Mythos 级模型）。美国政府最近因出口管制担忧和潜在的越狱漏洞下令暂停某些模型的访问。Anthropic 的前沿红队负责评估并公开模型漏洞。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.bloomberg.com/news/articles/2026-04-20/anthropic-s-mythos-ai-model-questions-answered">Anthropic 's Mythos AI Model , Questions Answered - Bloomberg</a></li>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://fortune.com/2025/09/04/anthropic-red-team-pushes-ai-models-into-the-danger-zone-and-burnishes-companys-reputation-for-safety/">Anthropic’s ‘ Red Team ’ pushes its AI models into the danger... | Fortune</a></li>

</ul>
</details>

**标签**: `#AI`, `#government regulation`, `#Anthropic`, `#export controls`, `#AI safety`

---