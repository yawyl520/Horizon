---
layout: default
title: "Horizon Summary: 2026-07-12 (ZH)"
date: 2026-07-12
lang: zh
---

> 从 16 条内容中筛选出 2 条重要资讯。

---

1. [消息称 DeepSeek 正在自研 AI 芯片以减少依赖](#item-1) ⭐️ 9.0/10
2. [Mesh LLM：基于 iroh 的分布式 AI 计算](#item-2) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [消息称 DeepSeek 正在自研 AI 芯片以减少依赖](https://www.reddit.com/r/LocalLLaMA/comments/1uu15mz/chinas_deepseek_developing_its_own_ai_chip/) ⭐️ 9.0/10

据报道，中国 AI 公司 DeepSeek（R1 模型开发者）正在研发自有 AI 芯片，以减少对英伟达等外国供应商的依赖。 此举可能重塑 AI 硬件格局：通过垂直整合，DeepSeek 有望降低成本并规避出口限制，同时挑战英伟达在 AI 芯片领域的主导地位。 据报道，DeepSeek 正在招聘芯片设计人才并探索推理专用架构，与 OpenAI 和 Anthropic 等 AI 公司的做法类似。鉴于 DeepSeek 此前在受限硬件上以低成本训练成功，其芯片可能侧重推理而非训练。

reddit · r/LocalLLaMA · /u/TheRealMasonMac · 7月12日 01:04

**背景**: DeepSeek 是一家由中国对冲基金 High-Flyer 支持、梁文锋于 2023 年创立的 AI 公司。该公司因使用受限出口的较弱芯片、以极低成本训练出与美国竞争对手相当的 LLM 而备受关注。其模型已开源，但面临美国对先进半导体的出口管制。自研芯片符合行业趋势——AI 公司设计专用芯片以优化性能并降低成本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek_(Company)">DeepSeek (Company)</a></li>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek - Wikipedia</a></li>

</ul>
</details>

**标签**: `#AI Hardware`, `#DeepSeek`, `#AI Chips`, `#China`, `#Semiconductor`

---

<a id="item-2"></a>
## [Mesh LLM：基于 iroh 的分布式 AI 计算](https://www.iroh.computer/blog/mesh-llm) ⭐️ 8.0/10

Mesh LLM 通过使用 iroh 点对点协议将模型层拆分到多个节点，实现了大型语言模型的分布式推理。它允许运行超过单个节点内存容量的模型，利用联网的消费级硬件。 这种方法通过减少对昂贵专用硬件的依赖，使个人和小团队能够使用多台消费级机器运行如 Qwen 235B 等大型模型，从而民主化了大型 AI 模型的访问。它还探索了去中心化 AI 计算的新范式。 该项目是实验性的，包含一个名为 'skippy' 的引擎，用于在节点间拆分模型。社区的性能数据显示，Qwen 235B MoE 模型在跨两个节点拆分时约为每秒 16 个 token，但延迟可能高于本地推理。

hackernews · tionis · 7月11日 22:38 · [社区讨论](https://news.ycombinator.com/item?id=48876505)

**背景**: 大型语言模型（LLM）通常需要高内存 GPU 进行推理，这些 GPU 价格昂贵。分布式推理将模型拆分到多个设备，但网络带宽和延迟是瓶颈。iroh 是一个模块化工具包，提供加密的 QUIC 连接和点对点通信协议，Mesh LLM 利用它来协调分布式推理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://meshllm.cloud/">Mesh LLM</a></li>
<li><a href="https://github.com/Mesh-LLM/mesh-llm">GitHub - Mesh - LLM / mesh - llm : Distributed AI/ LLM for the people.</a></li>
<li><a href="https://docs.iroh.computer/concepts/protocols">Protocols - iroh</a></li>

</ul>
</details>

**社区讨论**: 社区评论展现出兴趣和担忧。一名贡献者澄清了技术细节。一位用户询问性能，另一位则提出了将此类网络用于类似僵尸网络的分布式 AI 的可能性。技术问题包括节点间加密以及混合专家模型的处理。

**标签**: `#distributed computing`, `#LLM inference`, `#AI`, `#peer-to-peer`, `#mesh network`

---