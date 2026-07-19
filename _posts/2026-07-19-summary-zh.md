---
layout: default
title: "Horizon Summary: 2026-07-19 (ZH)"
date: 2026-07-19
lang: zh
---

> 从 20 条内容中筛选出 3 条重要资讯。

---

1. [LG 显示器通过 Windows Update 未经同意安装软件](#item-1) ⭐️ 9.0/10
2. [Basalt Labs 被曝伪造 HLE 基准测试分数](#item-2) ⭐️ 8.0/10
3. [Anthropic 永久保留 Claude Fable 5 于订阅计划中](#item-3) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [LG 显示器通过 Windows Update 未经同意安装软件](https://videocardz.com/newz/lg-monitors-silently-install-software-through-windows-update-without-user-consent) ⭐️ 9.0/10

LG 显示器在未经用户同意的情况下，通过 Windows Update 静默安装软件，只要通过 HDMI 插入 LG 显示器就会触发。 这构成了重大的安全和隐私风险，因为该软件具有完全的系统访问权限，开机自启，且无需用户交互即可安装，可能影响所有 LG 显示器用户。 当连接新的 LG 显示器或已有旧 LG 显示器时，该软件会自动安装，具有互联网访问权限且无沙盒隔离，每次系统启动时运行。

hackernews · baranul · 7月18日 10:21 · [社区讨论](https://news.ycombinator.com/item?id=48956688)

**背景**: Windows Update 可以推送驱动和厂商软件更新，但通常需要用户同意。这种情况下，LG 使用了一种机制在未经明确批准的情况下推送软件，用户可以通过在设备安装设置中阻止自动下载制造商应用程序来禁用此功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.lg.com/html/support/software-drivers.html">LG Software & Drivers | LG U.S.A</a></li>
<li><a href="https://www.fingerlakes1.com/2026/07/18/lg-monitor-software-now-installs-through-windows-update-and-many-users-did-not-expect-it/">LG Monitor Software Now Installs Through Windows Update and ...</a></li>

</ul>
</details>

**社区讨论**: 评论表达了愤怒，称该软件为恶意软件，因其静默安装和完全系统访问权限。用户分享了通过组策略或系统设置禁用自动下载制造商应用程序的解决方法，并指责 LG 和微软存在安全漏洞。

**标签**: `#privacy`, `#security`, `#Windows`, `#LG`, `#driver installation`

---

<a id="item-2"></a>
## [Basalt Labs 被曝伪造 HLE 基准测试分数](https://www.reddit.com/r/LocalLLaMA/comments/1uztylz/basalt_labs_pulling_a_generationally_dumb_scam/) ⭐️ 8.0/10

一位 Reddit 用户揭露 Basalt Labs 在人类最后考试（HLE）基准测试中虚假声称达到 99.44% 的分数。该公司发布的模型基于 Qwen2.5-7B-Instruct，而其网站上提供的模型实际上是 DeepSeek。 这损害了人们对 AI 研究和基准测试报告的信任，因为这是为了显得优越而故意欺诈。它凸显了模型评估中透明度和验证的必要性。 声称的 HLE 99.44% 分数异常高，其欺骗手段是在推理中使用不同的、可能更强的模型（DeepSeek）。发布的开源模型是 Qwen2.5-7B-Instruct，它明显更小且能力较弱。

reddit · r/LocalLLaMA · /u/WithoutReason1729 · 7月18日 11:58

**背景**: 人类最后考试（HLE）是一个多模态基准测试，旨在极具挑战性，常用于评估前沿 AI 模型。Qwen2.5-7B-Instruct 是阿里巴巴千问系列的一个 70 亿参数模型，而 DeepSeek 是一个更先进、性能强大的模型。基准测试欺诈损害了 AI 进展的可信度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.modelscope.cn/models/qwen/Qwen2.5-7B-Instruct">Qwen2.5-7B-Instruct · Models</a></li>
<li><a href="https://github.com/deepseek-ai/deepseek-v3">GitHub - deepseek-ai/DeepSeek-V3 · GitHub</a></li>

</ul>
</details>

**社区讨论**: Reddit 社区的反应是愤怒和嘲讽，称这个骗局“世代级的愚蠢”并称赞揭露行为。许多评论者讨论了这一欺诈行为的无耻以及验证基准测试声明的重要性。

**标签**: `#AI ethics`, `#benchmark fraud`, `#scam alert`, `#open-source models`

---

<a id="item-3"></a>
## [Anthropic 永久保留 Claude Fable 5 于订阅计划中](https://simonwillison.net/2026/Jul/18/claude-make-fable-5-permanent/#atom-everything) ⭐️ 7.0/10

Anthropic 撤销了原先从订阅计划中移除 Claude Fable 5 的计划，宣布自 7 月 20 日起，Fable 5 将包含在 Max 和 Team Premium 计划中（额度减半），其他用户将获得一次性 100 美元积分。 这一决定反映了 AI 模型市场的激烈竞争——对手 GPT-5.6 Sol 和 Kimi 3 迫使 Anthropic 在订阅中保留其最佳模型。这表明模型可用性已成为订阅定价的关键差异化因素。 Fable 5 将以 50%的用量限制包含在 Max（每月 100 美元）和 Team Premium 计划中，而 Pro 和 Team Standard 用户将获得一次性 100 美元积分。每月 20 美元的计划仍无法访问 Fable 5。

rss · Simon Willison · 7月18日 06:00

**背景**: Claude Fable 5 是 Anthropic 于 2026 年 6 月 9 日发布的强大大型语言模型，是 Mythos 系列模型的安全版本。Anthropic 最初因计算资源限制计划将 Fable 5 从订阅中移除，仅通过 API 提供。然而，来自 OpenAI 的 GPT-5.6 Sol（旗舰编码模型）和 Moonshot AI 的 Kimi 3 的竞争压力迫使他们改变决定。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Fable_5">Claude Fable 5</a></li>
<li><a href="https://www.anthropic.com/news/claude-fable-5-mythos-5">Claude Fable 5 and Claude Mythos 5 \ Anthropic</a></li>
<li><a href="https://openai.com/index/gpt-5-6/">GPT‑5.6: Frontier intelligence that scales with your ambition</a></li>

</ul>
</details>

**标签**: `#AI`, `#Anthropic`, `#Claude`, `#Fable 5`, `#competition`

---