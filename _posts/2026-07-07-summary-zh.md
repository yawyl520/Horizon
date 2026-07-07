---
layout: default
title: "Horizon Summary: 2026-07-07 (ZH)"
date: 2026-07-07
lang: zh
---

> 从 24 条内容中筛选出 4 条重要资讯。

---

1. [Kyutai 发布 Pocket TTS：5 秒语音克隆，CPU 运行，MIT 许可](#item-1) ⭐️ 9.0/10
2. [OpenWrt One – 开源硬件路由器](#item-2) ⭐️ 8.0/10
3. [腾讯发布 Hy3：295B 参数 MoE 开源模型](#item-3) ⭐️ 8.0/10
4. [LeRobot v0.6.0：想象、评估、改进](#item-4) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Kyutai 发布 Pocket TTS：5 秒语音克隆，CPU 运行，MIT 许可](https://www.reddit.com/r/LocalLLaMA/comments/1up07mk/kyutais_pocket_tts_clones_a_voice_from_5_seconds/) ⭐️ 9.0/10

Kyutai 发布了 Pocket TTS，一个开源语音克隆模型，仅需 5 秒音频即可克隆声音，且完全在 CPU 上运行。它采用流式自回归架构和 Mimi 神经编解码器，并与 Kokoro、Supertonic 和 Inflect-Nano 进行了英文 TTS 基准测试。 该模型填补了设备端语音克隆的关键空白，无需 GPU 即可进行零样本克隆，并采用宽松的 MIT 许可。它使低成本硬件上的交互式语音应用成为可能，为开发者和用户提供了语音定制的民主化途径。 Pocket TTS 约有 1 亿参数，实时因子（RTF）为 0.69-0.76，UTMOS MOS 得分为 4.10。它是唯一支持零样本语音克隆的 CPU 友好型模型；其他模型仅提供固定语音集。其架构在不同文本长度下产生平坦的延迟，与竞品模型不同。

reddit · r/LocalLLaMA · /u/gvij · 7月6日 15:14

**背景**: 传统 TTS 系统依赖声学模型后接声码器，语音克隆通常需要 GPU 加速。Kyutai 的 Mimi 神经编解码器将语义和声学信息融合为低比特率音频令牌（12.5 Hz）。Pocket TTS 将 TTS 视为自回归令牌生成，类似于语言模型，从而支持流式处理和 CPU 推理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/kyutai/mimi">kyutai/ mimi · Hugging Face</a></li>
<li><a href="https://voxbar.io/blog/voxbar-kyutai-deep-dive">VoxBar Kyutai Deep Dive — Mimi Neural Codec & Frame-by-Frame...</a></li>

</ul>
</details>

**社区讨论**: 基准测试帖子指出，尽管 Pocket TTS 是测试模型中最慢的，但其独特能力突出。作者邀请社区反馈在不同参考音频（如带口音的英语、非英语和歌唱声音）上的克隆表现，表明社区对其实际鲁棒性的关注。

**标签**: `#TTS`, `#voice cloning`, `#open source ML`, `#audio generation`, `#AI`

---

<a id="item-2"></a>
## [OpenWrt One – 开源硬件路由器](https://openwrt.org/toh/openwrt/one) ⭐️ 8.0/10

OpenWrt 正式发布了其自行设计的开源硬件路由器 OpenWrt One，该设备专为原生运行 OpenWrt 固件而设计，并作为开发者的参考平台。 这对开源网络社区来说是一个重要里程碑，提供了一个保证兼容的硬件平台，避免了供应商锁定，并通过社区驱动的更新延长了路由器的使用寿命。 OpenWrt One 是一款仅有两个以太网口的单板路由器，项目方已在规划支持 WiFi 7 的后续型号 OpenWrt Two。

hackernews · peter_d_sherman · 7月6日 18:23 · [社区讨论](https://news.ycombinator.com/item?id=48808482)

**背景**: OpenWrt 是一款广泛使用的路由器开源固件，以广泛的硬件支持和高度可定制性著称。OpenWrt One 是该项目的首个官方参考硬件设计，确保了原生固件支持并简化了开发过程。它面向那些希望获得可靠、由社区支持且不受专有限制的设备的爱好者。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openwrt.org/toh/openwrt/one">[ OpenWrt Wiki] OpenWrt One</a></li>
<li><a href="https://grokipedia.com/page/OpenWrt_One">OpenWrt One</a></li>

</ul>
</details>

**社区讨论**: 社区成员对 OpenWrt One 表现出热情，有人表示已经购买了该设备。讨论还涉及未来的 WiFi 7 计划以及与 OPNSense 等替代方案的比较，不过一些用户也指出了 OpenWrt 在安装和文档方面存在的挑战。

**标签**: `#OpenWrt`, `#open hardware`, `#router`, `#networking`

---

<a id="item-3"></a>
## [腾讯发布 Hy3：295B 参数 MoE 开源模型](https://simonwillison.net/2026/Jul/6/hy3/#atom-everything) ⭐️ 8.0/10

腾讯发布了 Hy3，一个 295B 参数的混合专家模型，具有 21B 活跃参数，采用宽松的 Apache 2.0 许可证。该模型性能优于同尺寸模型，可与参数多 2-5 倍的大型开源旗舰模型媲美。 此次发布意义重大，因为它来自一家中国大型企业，以宽松许可证提供了有竞争力的开源 MoE 模型，可能加速 AI 研究和应用开发。同时表明高效的 MoE 架构能以相对较低的计算成本实现强大性能。 完整模型在 Hugging Face 上大小为 598GB，FP8 量化版本为 300GB。它支持 256K token 的上下文长度，并在 OpenRouter 上免费提供至 2026 年 7 月 21 日。

rss · Simon Willison · 7月6日 23:57

**背景**: 混合专家（MoE）是一种神经网络架构，将模型划分为多个‘专家’子网络，并通过门控机制对每个输入令牌仅激活部分专家。这使得模型拥有大量总参数，同时保持每个令牌的计算成本较低，因为只使用活跃参数。例如，Hy3 有 295B 总参数，但每个令牌仅 21B 活跃参数，使其比类似大小的密集模型更高效。FP8 量化通过使用 8 位浮点数代替 16 位来减少内存占用，通常精度损失很小。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mixture_of_experts">Mixture of experts - Wikipedia</a></li>
<li><a href="https://huggingface.co/blog/moe">Mixture of Experts Explained</a></li>
<li><a href="https://rcrtech.com/semiconductor-news/llms-quantization-fp8-fp4-int8/">LLMs and quantization: FP8, FP4, and INT8 explained</a></li>

</ul>
</details>

**社区讨论**: 社区评论强调从限制性许可证转变为 Apache 2.0，这被视为对开放性的积极举措。一些讨论也提到该模型强大的性能以及在 OpenRouter 上免费测试的可用性。

**标签**: `#large language model`, `#mixture-of-experts`, `#open source`, `#tencent`, `#apache 2.0`

---

<a id="item-4"></a>
## [LeRobot v0.6.0：想象、评估、改进](https://huggingface.co/blog/lerobot-release-v060) ⭐️ 7.0/10

LeRobot v0.6.0 引入了用于想象、评估和改进机器人学习模型的新工具，扩展了其仿真、基准测试和迭代优化的能力。 这一版本降低了机器人研究人员和从业者更高效地训练和测试模型的门槛，加速了面向实际应用的模仿学习和强化学习的进步。 更新包括用于模拟机器人动作（“想象”）的功能、在标准化基准上评估模型性能（“评估”）以及基于反馈迭代改进模型（“改进”）的功能。用户可以利用 Hugging Face Hub 上的预训练模型和数据集。

rss · Hugging Face Blog · 7月7日 00:00

**背景**: LeRobot 是由 Hugging Face 开发的开源库，旨在让机器人领域的 AI 更加易于使用。它提供端到端的工具，用于数据收集、模型训练和推理，专注于模仿学习和强化学习。该库旨在统一硬件接口和仿真，从而实现更快速的实验。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/huggingface/lerobot">GitHub - huggingface/lerobot: 🤗 LeRobot: Making AI for Robotics more accessible with end-to-end learning</a></li>
<li><a href="https://huggingface.co/learn/robotics-course/unit0/1">Welcome to the 🤗 Robotics Course · Hugging Face</a></li>
<li><a href="https://huggingface.co/lerobot">lerobot (LeRobot)</a></li>

</ul>
</details>

**标签**: `#robotics`, `#reinforcement learning`, `#simulation`, `#open-source`, `#huggingface`

---