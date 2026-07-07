---
layout: default
title: "Horizon Summary: 2026-07-07 (EN)"
date: 2026-07-07
lang: en
---

> From 24 items, 4 important content pieces were selected

---

1. [Kyutai's Pocket TTS: 5-second voice cloning on CPU under MIT license](#item-1) ⭐️ 9.0/10
2. [OpenWrt One – Open Hardware Router](#item-2) ⭐️ 8.0/10
3. [Tencent Releases Hy3: 295B MoE Model Open Source](#item-3) ⭐️ 8.0/10
4. [LeRobot v0.6.0: Imagine, Evaluate, Improve](#item-4) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Kyutai's Pocket TTS: 5-second voice cloning on CPU under MIT license](https://www.reddit.com/r/LocalLLaMA/comments/1up07mk/kyutais_pocket_tts_clones_a_voice_from_5_seconds/) ⭐️ 9.0/10

Kyutai released Pocket TTS, an open-source voice cloning model that can clone a voice from just 5 seconds of audio, running entirely on CPU. It uses a streaming autoregressive architecture with Mimi neural codec and is benchmarked against Kokoro, Supertonic, and Inflect-Nano for English TTS. This model fills a critical gap in on-device voice cloning by offering zero-shot cloning without GPU requirements, under a permissive MIT license. It enables interactive voice applications on low-cost hardware, democratizing voice customization for developers and users. Pocket TTS has ~100M parameters, achieves a real-time factor (RTF) of 0.69-0.76, and scores 4.10 on UTMOS MOS. It is the only CPU-friendly model that supports zero-shot voice cloning; others only offer fixed voice sets. The architecture produces flat latency across text lengths, unlike competing models.

reddit · r/LocalLLaMA · /u/gvij · Jul 6, 15:14

**Background**: Traditional TTS systems rely on acoustic models followed by vocoders, often requiring GPU acceleration for voice cloning. Kyutai's Mimi neural codec combines semantic and acoustic information into low-bitrate audio tokens at 12.5 Hz. Pocket TTS treats TTS as autoregressive token generation, similar to language models, enabling streaming and CPU inference.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/kyutai/mimi">kyutai/ mimi · Hugging Face</a></li>
<li><a href="https://voxbar.io/blog/voxbar-kyutai-deep-dive">VoxBar Kyutai Deep Dive — Mimi Neural Codec & Frame-by-Frame...</a></li>

</ul>
</details>

**Discussion**: The benchmarking post highlights Pocket TTS's unique capabilities despite being the slowest among tested models. The author invites feedback on voice cloning performance with diverse reference clips, particularly accented English, non-English, and singing voices, indicating community interest in real-world robustness.

**Tags**: `#TTS`, `#voice cloning`, `#open source ML`, `#audio generation`, `#AI`

---

<a id="item-2"></a>
## [OpenWrt One – Open Hardware Router](https://openwrt.org/toh/openwrt/one) ⭐️ 8.0/10

OpenWrt has officially announced its own open hardware router, the OpenWrt One, designed to natively run OpenWrt firmware and serve as a reference platform for developers. This is a major milestone for the open-source networking community, providing a guaranteed compatible hardware platform that avoids vendor lock-in and extends router lifespan with community-driven updates. The OpenWrt One is a single-board router with only two Ethernet ports, and the project is already planning a successor model, OpenWrt Two, which will support WiFi 7.

hackernews · peter_d_sherman · Jul 6, 18:23 · [Discussion](https://news.ycombinator.com/item?id=48808482)

**Background**: OpenWrt is a widely used open-source firmware for routers, known for its extensive hardware support and customization. The OpenWrt One is the first official reference hardware design from the project, ensuring native firmware support and simplifying development. It is aimed at enthusiasts who want a reliable, community-supported device without proprietary limitations.

<details><summary>References</summary>
<ul>
<li><a href="https://openwrt.org/toh/openwrt/one">[ OpenWrt Wiki] OpenWrt One</a></li>
<li><a href="https://grokipedia.com/page/OpenWrt_One">OpenWrt One</a></li>

</ul>
</details>

**Discussion**: Community members expressed enthusiasm for the OpenWrt One, with some noting they already purchased it. Discussions also covered future WiFi 7 plans and comparisons to alternatives like OPNSense, though some users pointed out challenges with OpenWrt installation and documentation.

**Tags**: `#OpenWrt`, `#open hardware`, `#router`, `#networking`

---

<a id="item-3"></a>
## [Tencent Releases Hy3: 295B MoE Model Open Source](https://simonwillison.net/2026/Jul/6/hy3/#atom-everything) ⭐️ 8.0/10

Tencent has released Hy3, a 295B-parameter Mixture-of-Experts model with 21B active parameters, under the permissive Apache 2.0 license. The model outperforms similar-size models and rivals larger flagship open-source models with 2-5x parameters. This release is significant because it provides a competitive open-source MoE model from a major Chinese company under a permissive license, potentially accelerating AI research and application development. It also demonstrates that efficient MoE architectures can achieve strong performance with relatively low computational cost. The full model is 598GB on Hugging Face, and an FP8 quantized version is 300GB. It supports a context length of 256K tokens and is available for free on OpenRouter until July 21st, 2026.

rss · Simon Willison · Jul 6, 23:57

**Background**: Mixture-of-Experts (MoE) is a neural network architecture that divides the model into multiple 'expert' sub-networks, with a gating mechanism that activates only a subset of experts per input token. This allows the model to have a large total parameter count while keeping the computational cost per token low, as only the active parameters are used. For example, Hy3 has 295B total parameters but only 21B active per token, making it more efficient than a dense model of similar size. FP8 quantization reduces memory footprint by using 8-bit floating point numbers instead of 16-bit, often with minimal loss in accuracy.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mixture_of_experts">Mixture of experts - Wikipedia</a></li>
<li><a href="https://huggingface.co/blog/moe">Mixture of Experts Explained</a></li>
<li><a href="https://rcrtech.com/semiconductor-news/llms-quantization-fp8-fp4-int8/">LLMs and quantization: FP8, FP4, and INT8 explained</a></li>

</ul>
</details>

**Discussion**: Community comments highlight the shift from a restrictive license to Apache 2.0, which is seen as a positive move for openness. Some discussion also notes the model's strong performance and its availability on OpenRouter for free testing.

**Tags**: `#large language model`, `#mixture-of-experts`, `#open source`, `#tencent`, `#apache 2.0`

---

<a id="item-4"></a>
## [LeRobot v0.6.0: Imagine, Evaluate, Improve](https://huggingface.co/blog/lerobot-release-v060) ⭐️ 7.0/10

LeRobot v0.6.0 introduces new tools for imagining, evaluating, and improving robot learning models, expanding its capabilities for simulation, benchmarking, and iterative refinement. This release lowers the barrier for robotics researchers and practitioners to train and test models more efficiently, accelerating progress in imitation learning and reinforcement learning for real-world applications. The update includes features for simulating robot actions ('Imagine'), evaluating model performance on standardized benchmarks ('Evaluate'), and iteratively improving models based on feedback ('Improve'). Users can leverage pre-trained models and datasets from the Hugging Face Hub.

rss · Hugging Face Blog · Jul 7, 00:00

**Background**: LeRobot is an open-source library developed by Hugging Face that makes AI for robotics more accessible. It provides end-to-end tools for data collection, model training, and inference, focusing on imitation learning and reinforcement learning. The library aims to unify hardware interfacing and simulation, enabling faster experimentation.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/huggingface/lerobot">GitHub - huggingface/lerobot: 🤗 LeRobot: Making AI for Robotics more accessible with end-to-end learning</a></li>
<li><a href="https://huggingface.co/learn/robotics-course/unit0/1">Welcome to the 🤗 Robotics Course · Hugging Face</a></li>
<li><a href="https://huggingface.co/lerobot">lerobot (LeRobot)</a></li>

</ul>
</details>

**Tags**: `#robotics`, `#reinforcement learning`, `#simulation`, `#open-source`, `#huggingface`

---