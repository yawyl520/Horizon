---
layout: default
title: "Horizon Summary: 2026-06-30 (ZH)"
date: 2026-06-30
lang: zh
---

> 从 22 条内容中筛选出 4 条重要资讯。

---

1. [最高法院要求地理围栏搜查令需受第四修正案保护](#item-1) ⭐️ 9.0/10
2. [谷歌 AI 审稿人处理约万篇论文，发现错误多 34%](#item-2) ⭐️ 9.0/10
3. [Ornith-1.0：用于智能体编程的开源自构架大语言模型](#item-3) ⭐️ 8.0/10
4. [DiScoFormer：统一密度与得分估计的 Transformer](#item-4) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [最高法院要求地理围栏搜查令需受第四修正案保护](https://www.theguardian.com/us-news/2026/jun/29/supreme-court-geofence-warrants-case-decision) ⭐️ 9.0/10

美国最高法院裁定，要求谷歌等公司提供特定区域内设备位置数据的地理围栏搜查令，必须符合第四修正案的合理根据要求，即需要基于个别化怀疑的搜查令。 这项里程碑式的裁决为数百万智能手机用户建立了关键的隐私保护，限制了执法机构在没有司法监督的情况下进行大规模数字排查的能力。它为其他形式的反向位置搜查和监控技术树立了先例。 案件源于一起银行抢劫案调查，谷歌的 Sensorvault 提供了 150 米范围内 19 台设备的数据。法院明确指出，地理围栏搜查令属于第四修正案下的搜查行为，必须基于合理理由，驳回了政府关于用户对与第三方共享的位置数据没有合理隐私期待的主张。

hackernews · cdrnsf · 6月29日 15:54 · [社区讨论](https://news.ycombinator.com/item?id=48720924)

**背景**: 地理围栏搜查令是一种搜查令，允许执法机构向科技公司请求在特定时间段内特定地理区域内的所有移动设备记录。谷歌的 Sensorvault 数据库存储了启用位置历史记录的用户的历史地理位置数据。第四修正案保护民众免受不合理搜查和扣押，历史上法院要求对私人财产和物品的搜查必须基于合理理由。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Geofence_warrant">Geofence warrant</a></li>

</ul>
</details>

**社区讨论**: 评论者强调了历史背景，例如 Paula Broadwell 是如何在没有地理围栏搜查令的情况下通过酒店住客名单和 IP 地理定位被识别的，并指出法院意见引用了 Riley 诉 California 案等来源。一位评论者提出裁决是否适用于 Flock 自动车牌识别系统等设备，暗示了对其他监控技术的潜在影响。

**标签**: `#privacy`, `#supreme court`, `#geofence`, `#fourth amendment`, `#digital rights`

---

<a id="item-2"></a>
## [谷歌 AI 审稿人处理约万篇论文，发现错误多 34%](https://www.reddit.com/r/MachineLearning/comments/1uio9rb/googles_agentic_peerreviewer_handled_10k_papers/) ⭐️ 9.0/10

谷歌在顶级计算机科学会议 ICML 和 STOC 部署了代理式 AI 审稿人，处理了约一万篇论文，每篇平均 30 分钟完成评审。正式研究论文显示，相比零样本提示，它多发现了 34%的数学错误。 这为大规模 AI 自动化科学评审开创了先例，有望减轻审稿人负担并提升学术出版的质量控制。它可能重塑会议和期刊处理同行评审的方式，尤其在数学严谨性方面。 该代理式系统在有限监督下自主运行，实时模拟人类决策。它在检测数学错误方面显著优于零样本提示——后者不给 AI 任何示例就直接提问。

reddit · r/MachineLearning · /u/Justgototheeffinmoon · 6月29日 10:05

**背景**: 代理式 AI 指能在有限监督下完成目标的系统，利用模仿人类决策的 AI 智能体。零样本提示是一种不给任何示例、仅依赖模型训练来执行任务的技术。传统的学术同行评审依赖人类专家，可能缓慢且不一致；AI 辅助评审旨在提升效率和客观性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ibm.com/think/topics/agentic-ai">What is Agentic AI? | IBM</a></li>
<li><a href="https://promplify.ai/blog/zero-shot-prompting/">Zero - Shot Prompting : How to Get Great Results... — Promplify Blog</a></li>

</ul>
</details>

**标签**: `#AI`, `#peer review`, `#machine learning`, `#automation`, `#scientific publishing`

---

<a id="item-3"></a>
## [Ornith-1.0：用于智能体编程的开源自构架大语言模型](https://simonwillison.net/2026/Jun/29/ornith/#atom-everything) ⭐️ 8.0/10

DeepReinforce 发布了 Ornith-1.0，这是一个采用 MIT 开源协议的自构架大语言模型系列，专为智能体编程设计，包含 9B Dense、31B Dense、35B MoE 和 397B MoE 等多种变体，基于 Gemma 4 和 Qwen 3.5 构建，在同等规模的开源模型中达到了编码基准测试的顶尖水平。 Ornith-1.0 代表了开源权重大模型在代码生成领域的重大进步，它在提供顶尖性能的同时，其基础模型采用宽松的 Apache 2.0 许可，使得研究和商业用途更加便捷。 该模型采用自构架技术，每次强化学习迭代都会生成一个构架，并支持在多次工具调用中运行智能体框架，早期用户已通过 LM Studio 和 GGUF 版本进行了演示。

rss · Simon Willison · 6月29日 16:17

**背景**: 自构架大语言模型是在大模型核心周围包裹程序化构架的系统，通过串联多个大模型调用来实现自主推理和行动。智能体编程利用 AI 智能体在最少人工干预下规划、编写、测试和修改代码。Ornith-1.0 结合了这两种方法以增强代码生成和调试能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Agentic_coding">Agentic coding</a></li>
<li><a href="https://medium.com/data-science-in-your-pocket/ornith-1-0-self-learning-llm-for-coding-318c9a830bfc">Ornith 1.0 : Self Learning LLM for Coding | by Mehul Gupta | Medium</a></li>
<li><a href="https://www.lesswrong.com/posts/mAwxebLw3nYbDivmt/scaffolded-llms-less-obvious-concerns">Scaffolded LLMs: Less Obvious Concerns — LessWrong</a></li>

</ul>
</details>

**标签**: `#LLM`, `#open-source`, `#coding`, `#agentic`, `#AI model`

---

<a id="item-4"></a>
## [DiScoFormer：统一密度与得分估计的 Transformer](https://huggingface.co/blog/allenai/discoformer) ⭐️ 7.0/10

AI2 的研究人员推出了 DiScoFormer，一个单一的 Transformer 模型，能够跨多个分布联合执行密度估计和得分估计，统一了生成模型中传统上分离的两个任务。 这种方法可以通过利用共享表示来简化和改进生成模型，可能在不同数据分布上实现更高效的训练和更好的样本质量。 该模型设计为跨分布工作，意味着它可以处理多个数据集或领域而无需重新训练，并联合估计密度和得分（对数密度的梯度）。

rss · Hugging Face Blog · 6月29日 18:02

**背景**: 密度估计涉及近似数据的概率分布，而基于得分的模型学习对数密度的梯度以进行生成采样。传统上，这些是独立的任务，需要不同的架构。DiScoFormer 在一个 Transformer 中结合了它们，可能实现联合学习和跨分布泛化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Density_estimation">Density estimation</a></li>
<li><a href="https://arxiv.org/abs/2011.13456">[2011.13456] Score-Based Generative Modeling through Stochastic Differential Equations</a></li>
<li><a href="https://fanpu.io/blog/2023/score-based-diffusion-models/">Score-Based Diffusion Models | Fan Pu Zeng</a></li>

</ul>
</details>

**标签**: `#transformer`, `#density estimation`, `#score-based models`, `#generative AI`

---