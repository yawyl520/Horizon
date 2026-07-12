---
layout: default
title: "Horizon Summary: 2026-07-12 (EN)"
date: 2026-07-12
lang: en
---

> From 16 items, 2 important content pieces were selected

---

1. [DeepSeek reportedly designing its own AI chip to reduce reliance](#item-1) ⭐️ 9.0/10
2. [Mesh LLM: Distributed AI Computing on iroh](#item-2) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [DeepSeek reportedly designing its own AI chip to reduce reliance](https://www.reddit.com/r/LocalLLaMA/comments/1uu15mz/chinas_deepseek_developing_its_own_ai_chip/) ⭐️ 9.0/10

According to sources, DeepSeek, the Chinese AI company behind the R1 model, is developing its own custom AI chip to reduce dependence on foreign suppliers like Nvidia. This move could reshape the AI hardware landscape by giving DeepSeek vertical integration, potentially lowering costs and bypassing export restrictions, while challenging Nvidia's dominance in AI chips. DeepSeek is reportedly hiring chip design talent and exploring inference-specific architectures, similar to other AI companies like OpenAI and Anthropic. The chip would likely focus on inference rather than training, given DeepSeek's past success with lower-cost training on constrained hardware.

reddit · r/LocalLLaMA · /u/TheRealMasonMac · Jul 12, 01:04

**Background**: DeepSeek is a Chinese AI company founded in 2023 by Liang Wenfeng, backed by hedge fund High-Flyer. It gained attention for training competitive LLMs at a fraction of the cost of US rivals, using weaker export-restricted chips. The company has open-sourced its models, yet faces ongoing US export controls on advanced semiconductors. Developing custom chips would align with a broader industry trend where AI companies design specialized silicon to optimize performance and reduce costs.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek_(Company)">DeepSeek (Company)</a></li>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#AI Hardware`, `#DeepSeek`, `#AI Chips`, `#China`, `#Semiconductor`

---

<a id="item-2"></a>
## [Mesh LLM: Distributed AI Computing on iroh](https://www.iroh.computer/blog/mesh-llm) ⭐️ 8.0/10

Mesh LLM enables distributed inference of large language models by splitting model layers across multiple nodes using the iroh peer-to-peer protocol. It allows running models larger than a single node's memory by leveraging networked consumer hardware. This approach democratizes access to large AI models by reducing reliance on expensive specialized hardware, enabling individuals and small teams to run models like Qwen 235B using multiple consumer machines. It also explores new paradigms for decentralized AI computing. The project is experimental and includes an engine called 'skippy' for splitting models across nodes. Performance data from the community shows approximately 16 tokens per second for a Qwen 235B MoE model split across two nodes, but latency may be high compared to local inference.

hackernews · tionis · Jul 11, 22:38 · [Discussion](https://news.ycombinator.com/item?id=48876505)

**Background**: Large language models (LLMs) typically require high-memory GPUs for inference, which are expensive. Distributed inference splits the model across multiple devices, but network bandwidth and latency are bottlenecks. iroh is a modular toolkit providing encrypted QUIC connections and protocols for peer-to-peer communication, which Mesh LLM uses to coordinate distributed inference.

<details><summary>References</summary>
<ul>
<li><a href="https://meshllm.cloud/">Mesh LLM</a></li>
<li><a href="https://github.com/Mesh-LLM/mesh-llm">GitHub - Mesh - LLM / mesh - llm : Distributed AI/ LLM for the people.</a></li>
<li><a href="https://docs.iroh.computer/concepts/protocols">Protocols - iroh</a></li>

</ul>
</details>

**Discussion**: Community comments show interest and concerns. A contributor clarifies technical details. One user asks about performance, while another raises the possibility of using such networks for botnet-like distributed AI. Technical questions include encryption between nodes and handling of mixture-of-experts models.

**Tags**: `#distributed computing`, `#LLM inference`, `#AI`, `#peer-to-peer`, `#mesh network`

---