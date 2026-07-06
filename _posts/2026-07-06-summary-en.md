---
layout: default
title: "Horizon Summary: 2026-07-06 (EN)"
date: 2026-07-06
lang: en
---

> From 20 items, 3 important content pieces were selected

---

1. [Longcat 2.0 (1.6T, ~48B active) open-sourced under MIT](#item-1) ⭐️ 9.0/10
2. [GPT-5.6 Sol Ultra with Subagents Now in Codex](#item-2) ⭐️ 8.0/10
3. [Hugging Face Revamps Its Kernel Library](#item-3) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [Longcat 2.0 (1.6T, ~48B active) open-sourced under MIT](https://www.reddit.com/r/LocalLLaMA/comments/1unyvnz/longcat_20_16t_48b_active_weights_are_now_open/) ⭐️ 9.0/10

Longcat 2.0, a Mixture-of-Experts (MoE) model with 1.6 trillion total parameters and approximately 48 billion active parameters per token, has been released under the highly permissive MIT license. This release significantly strengthens the open-source AI ecosystem by providing a massive yet efficient model that can be freely used, modified, and deployed for research and commercial applications. Despite its 1.6T total parameters, the MoE architecture activates only about 48B parameters per token, enabling efficient inference. The model weights are available under the MIT license, allowing unrestricted use.

reddit · r/LocalLLaMA · /u/Nunki08 · Jul 5, 10:35

**Background**: Mixture-of-Experts (MoE) is a neural network architecture that divides the model into multiple specialized sub-networks called experts, with a router selecting a subset of experts for each input. This allows scaling total parameters while keeping computational cost manageable by using only a fraction of parameters (active parameters) per forward pass. Longcat 2.0 exemplifies this approach, offering a massive model with efficient inference.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/blog/moe">Mixture of Experts Explained</a></li>
<li><a href="https://www.f22labs.com/blogs/active-vs-total-parameters-whats-the-difference/">Active vs Total Parameters : What’s the Difference?</a></li>

</ul>
</details>

**Tags**: `#Large Language Model`, `#Open Source`, `#Mixture of Experts`, `#AI`, `#Model Release`

---

<a id="item-2"></a>
## [GPT-5.6 Sol Ultra with Subagents Now in Codex](https://twitter.com/thsottiaux/status/2073933490513752151) ⭐️ 8.0/10

OpenAI has previewed GPT-5.6 Sol, featuring a new ultra mode that uses subagents to accelerate complex tasks, and it is now available in Codex. This release signals a shift toward multi-agent architectures within a single model, potentially offering significant performance gains for coding, science, and cybersecurity tasks. Users of Codex gain early access to cutting-edge capabilities that could reshape development workflows. The ultra mode goes beyond single-agent capabilities by leveraging subagents to accelerate complex work, but it may incur higher costs and latency compared to standard modes. Access appears to be rolling out to enterprise accounts first, as noted by some corporate users.

hackernews · mfiguiere · Jul 6, 01:04 · [Discussion](https://news.ycombinator.com/item?id=48799614)

**Background**: GPT-5.6 Sol is a next-generation model from OpenAI with enhanced capabilities in coding, science, and cybersecurity, paired with an advanced safety stack. Codex is OpenAI's coding assistant platform. Subagents are specialized AI assistants that can be used for task-specific workflows, improving context management and efficiency.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/previewing-gpt-5-6-sol/">Previewing GPT‑5.6 Sol: a next-generation model - OpenAI</a></li>
<li><a href="https://oakgen.ai/blog/gpt-56-ultra-mode-explained">GPT-5.6 Ultra Mode Explained | Oakgen.ai Blog</a></li>

</ul>
</details>

**Discussion**: Community comments show a mix of curiosity and practical concerns: some ask how ultra mode compares to the existing Pro tier, while others report corporate cost-saving measures limiting usage of expensive models. Users also express anticipation for new model releases in Codex.

**Tags**: `#GPT-5.6`, `#OpenAI`, `#Codex`, `#AI model`, `#machine learning`

---

<a id="item-3"></a>
## [Hugging Face Revamps Its Kernel Library](https://huggingface.co/blog/revamped-kernels) ⭐️ 8.0/10

Hugging Face has announced major updates to its kernels library, introducing new optimized CUDA kernels and a streamlined workflow for building and sharing compute kernels on the Hub. These updates enable machine learning practitioners to more easily leverage custom GPU kernels for faster model training and inference, potentially reducing costs and improving efficiency across the AI/ML ecosystem. The revamp includes a new Python package called 'kernels' for loading compatible kernels from the Hub and a 'kernel-builder' tool for kernel authors, along with a community-maintained set of kernels in the 'kernels-community' repository.

rss · Hugging Face Blog · Jul 6, 00:00

**Background**: In machine learning, custom CUDA kernels are low-level GPU programs that optimize specific operations, such as attention mechanisms or activation functions, beyond what standard libraries offer. Hugging Face's kernels library simplifies the process of finding, building, and integrating these kernels into PyTorch or TensorFlow workflows. The updates likely improve performance, compatibility, and ease of use for the community.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/docs/kernels/index">Kernels · Hugging Face</a></li>
<li><a href="https://github.com/huggingface/kernels">GitHub - huggingface/ kernels : Build compute kernels and load them...</a></li>
<li><a href="https://dev.co/custom-cuda-kernels">Building Custom CUDA Kernels to Boost Deep Learning Performance | DEV.co</a></li>

</ul>
</details>

**Tags**: `#Hugging Face`, `#kernels`, `#AI/ML`, `#performance optimization`

---