---
layout: default
title: "Horizon Summary: 2026-07-06 (ZH)"
date: 2026-07-06
lang: zh
---

> 从 20 条内容中筛选出 3 条重要资讯。

---

1. [Longcat 2.0（1.6 万亿参数，约 480 亿活跃参数）以 MIT 许可证开源](#item-1) ⭐️ 9.0/10
2. [GPT-5.6 Sol Ultra 现已在 Codex 中推出，采用子代理模式](#item-2) ⭐️ 8.0/10
3. [Hugging Face 全面升级其内核库](#item-3) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Longcat 2.0（1.6 万亿参数，约 480 亿活跃参数）以 MIT 许可证开源](https://www.reddit.com/r/LocalLLaMA/comments/1unyvnz/longcat_20_16t_48b_active_weights_are_now_open/) ⭐️ 9.0/10

Longcat 2.0，一个拥有 1.6 万亿总参数、每个 token 约 480 亿活跃参数的混合专家（MoE）模型，已以高度宽松的 MIT 许可证发布。 此次发布显著增强了开源 AI 生态系统，提供了一个庞大但高效的模型，可自由用于研究和商业应用，并进行修改和部署。 尽管总参数达 1.6 万亿，但 MoE 架构每个 token 仅激活约 480 亿参数，从而实现高效推理。模型权重以 MIT 许可证提供，允许不受限制地使用。

reddit · r/LocalLLaMA · /u/Nunki08 · 7月5日 10:35

**背景**: 混合专家（MoE）是一种神经网络架构，将模型划分为多个称为专家的专用子网络，路由器为每个输入选择一部分专家。这种方法可以在保持计算成本可控的同时扩大总参数规模，每次前向传播仅使用部分参数（活跃参数）。Longcat 2.0 就是这种方法的典范，提供了一个大规模但推理高效的模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/blog/moe">Mixture of Experts Explained</a></li>
<li><a href="https://www.f22labs.com/blogs/active-vs-total-parameters-whats-the-difference/">Active vs Total Parameters : What’s the Difference?</a></li>

</ul>
</details>

**标签**: `#Large Language Model`, `#Open Source`, `#Mixture of Experts`, `#AI`, `#Model Release`

---

<a id="item-2"></a>
## [GPT-5.6 Sol Ultra 现已在 Codex 中推出，采用子代理模式](https://twitter.com/thsottiaux/status/2073933490513752151) ⭐️ 8.0/10

OpenAI 预览了 GPT-5.6 Sol，该模型引入了全新的 ultra 模式，通过子代理加速复杂任务，现已可在 Codex 中使用。 此次发布标志着单一模型内多智能体架构的转变，可能在编程、科学和网络安全任务中带来显著性能提升。Codex 用户将提前获得这些尖端能力，可能重塑开发工作流。 Ultra 模式通过利用子代理加速复杂工作，超越了单个代理的能力，但相比标准模式可能产生更高的成本和延迟。据一些企业用户反馈，访问权限似乎首先向企业账户开放。

hackernews · mfiguiere · 7月6日 01:04 · [社区讨论](https://news.ycombinator.com/item?id=48799614)

**背景**: GPT-5.6 Sol 是 OpenAI 的下一代模型，在编程、科学和网络安全方面能力更强，并配备了先进的安全体系。Codex 是 OpenAI 的编程助手平台。子代理是用于特定任务工作流的专用 AI 助手，可改善上下文管理和效率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/previewing-gpt-5-6-sol/">Previewing GPT‑5.6 Sol: a next-generation model - OpenAI</a></li>
<li><a href="https://oakgen.ai/blog/gpt-56-ultra-mode-explained">GPT-5.6 Ultra Mode Explained | Oakgen.ai Blog</a></li>

</ul>
</details>

**社区讨论**: 社区评论显示出好奇与实用担忧并存：有人询问 ultra 模式与现有 Pro 层级的比较，也有人报告企业为节省成本而限制使用昂贵模型。用户还表达了对 Codex 中新模型发布的期待。

**标签**: `#GPT-5.6`, `#OpenAI`, `#Codex`, `#AI model`, `#machine learning`

---

<a id="item-3"></a>
## [Hugging Face 全面升级其内核库](https://huggingface.co/blog/revamped-kernels) ⭐️ 8.0/10

Hugging Face 宣布对其内核库进行重大更新，引入了新的优化 CUDA 内核，并简化了在 Hub 上构建和共享计算内核的工作流程。 这些更新使机器学习从业者能够更轻松地利用自定义 GPU 内核加速模型训练和推理，有望降低 AI/ML 生态系统的成本并提高效率。 此次升级包括一个名为 'kernels' 的新 Python 包，用于从 Hub 加载兼容的内核，以及一个面向内核作者的 'kernel-builder' 工具，同时还有社区维护的内核集合 'kernels-community' 仓库。

rss · Hugging Face Blog · 7月6日 00:00

**背景**: 在机器学习中，自定义 CUDA 内核是底层 GPU 程序，用于优化标准库无法达到的特定操作（如注意力机制或激活函数）。Hugging Face 的内核库简化了查找、构建和集成这些内核到 PyTorch 或 TensorFlow 工作流的过程。此次更新可能提升了性能、兼容性和易用性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/docs/kernels/index">Kernels · Hugging Face</a></li>
<li><a href="https://github.com/huggingface/kernels">GitHub - huggingface/ kernels : Build compute kernels and load them...</a></li>
<li><a href="https://dev.co/custom-cuda-kernels">Building Custom CUDA Kernels to Boost Deep Learning Performance | DEV.co</a></li>

</ul>
</details>

**标签**: `#Hugging Face`, `#kernels`, `#AI/ML`, `#performance optimization`

---