---
layout: default
title: "Horizon Summary: 2026-06-26 (ZH)"
date: 2026-06-26
lang: zh
---

> 从 20 条内容中筛选出 5 条重要资讯。

---

1. [首卷赫库兰尼姆古卷借助 AI 完全解读](#item-1) ⭐️ 9.0/10
2. [德国法院裁定谷歌对 AI 摘要错误承担责任](#item-2) ⭐️ 9.0/10
3. [将代理工作流编译成 LLM 权重](#item-3) ⭐️ 9.0/10
4. [一键在 Hugging Face Jobs 上运行 vLLM 服务器](#item-4) ⭐️ 7.0/10
5. [混合模型 token 预测分析](#item-5) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [首卷赫库兰尼姆古卷借助 AI 完全解读](https://scrollprize.org/firstscroll) ⭐️ 9.0/10

研究人员首次成功完整读出一卷赫库兰尼姆古卷，这一突破得益于维苏威挑战赛中开发的基于 AI 的墨水检测和数字展开技术。 这一成就标志着数字考古学的历史性突破，使得此前被认为无法阅读的古代文字得以重见天日。它有望解锁赫库兰尼姆埋藏的数百卷古卷，可能重新发现失传的古典哲学与文学作品。 研究团队使用机器学习模型，在卷轴微 CT 扫描图像上检测碳基墨水，通过分割虚拟层来读取连续文本。该方法避免了物理展开脆化的碳化莎草纸，从而避免了对卷轴的破坏。

hackernews · verditelabs · 6月25日 15:48 · [社区讨论](https://news.ycombinator.com/item?id=48675179)

**背景**: 赫库兰尼姆纸莎草卷轴在公元 79 年维苏威火山喷发中被碳化，脆弱到无法物理展开。维苏威挑战赛于 2023 年启动，为使用 AI 自动阅读这些卷轴设立奖项。此前尝试利用 X 射线成像和墨水检测仅能恢复零散的单词或短语。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://scrollprize.org/tutorial5">Tutorial: Ink Detection | Vesuvius Challenge</a></li>
<li><a href="https://en.wikipedia.org/wiki/Vesuvius_Challenge">Vesuvius Challenge</a></li>

</ul>
</details>

**社区讨论**: 社区成员对这一成就的规模表示惊叹，指出赫库兰尼姆遗址仅发掘了 20%，因此有希望发现一个完整的图书馆。一位维苏威挑战赛团队成员主动解答关于分割和墨水检测流程的问题。其他人则感叹于漫长的时间尺度——古代作者无法想象现代技术能保存他们的作品。

**标签**: `#AI`, `#archaeology`, `#machine learning`, `#ancient texts`, `#Vesuvius Challenge`

---

<a id="item-2"></a>
## [德国法院裁定谷歌对 AI 摘要错误承担责任](https://simonwillison.net/2026/Jun/25/ai-and-liability/#atom-everything) ⭐️ 9.0/10

一家德国法院裁定，谷歌对其 AI 生成的摘要中的错误负责，视其为谷歌自己的言论。布鲁斯·施奈尔认为，AI 代理应被视为部署它们的组织的代理。 这一里程碑式的裁决确立了 AI 责任先例，意味着公司不能通过将错误归咎于 AI 来逃避责任。它可能改变企业在法律、医疗和客户服务等关键领域部署 AI 的方式。 该裁决特别适用于谷歌由大型语言模型生成的 AI 摘要。援引的法律原则类似于替代责任，即雇主对雇员的行为负责，并将其扩展到 AI 系统。

rss · Simon Willison · 6月25日 22:28

**背景**: 替代责任是一项法律原则，要求雇主对雇员在履职过程中造成的损害负责。德国这项裁决将该原则适用于 AI，意味着部署 AI 的公司对其输出承担法律责任，就如同雇用了人类员工一样。该裁决具有开创性，因为它直接回答了当 AI 产生不准确或有害内容时谁应负责的问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://thelyonfirm.com/blog/agentic-ai-liability-legal-responsibility-autonomous-ai-agents/">Who Is Legally Liable When an AI Agent Makes a Mistake?</a></li>
<li><a href="https://en.wikipedia.org/wiki/Vicarious_liability_in_English_law">Vicarious liability in English law</a></li>

</ul>
</details>

**标签**: `#AI liability`, `#legal`, `#AI ethics`, `#Google`, `#regulation`

---

<a id="item-3"></a>
## [将代理工作流编译成 LLM 权重](https://www.reddit.com/r/MachineLearning/comments/1ufgpnh/r_compiling_agentic_workflows_into_llm_weights/) ⭐️ 9.0/10

一篇新论文提出通过在前沿模型轨迹上进行监督微调，将代理工作流编译成 LLM 权重，以实现近乎前沿的质量，同时成本降低两个数量级。 这一突破可能通过使用在昂贵前沿模型轨迹上微调的小型语言模型，实现高质量 AI 代理的经济高效部署，大幅降低推理成本。 该方法将持久性程序知识编译到模型权重中，同时将瞬态状态保留在提示中，类似于传统编译。它利用了来自 LangGraph 和 CrewAI 等代理编排框架的轨迹进行监督微调。

reddit · r/MachineLearning · /u/ThirdWaveCat · 6月25日 17:31

**背景**: 代理工作流涉及多个相互依赖的 LLM 调用，通常导致高昂的 token 成本和延迟。小型语言模型（SLM）更便宜但能力较弱。这篇论文表明，可以通过在更强模型的执行轨迹上微调 SLM，使其内化工作流逻辑，从而大幅降低成本同时保持性能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2605.22502">[2605.22502] Compiling Agentic Workflows into LLM Weights: Near ...</a></li>
<li><a href="https://arxiv.org/html/2605.22502v1">Compiling Agentic Workflows into LLM Weights: Near-Frontier Quality at Two Orders of Magnitude Less Cost</a></li>

</ul>
</details>

**社区讨论**: Reddit 发帖人询问是否有人在实际中尝试过这种方法，表明了对应用该方法以降低 token 成本的实践兴趣。该论文的高分表明社区参与度很高。

**标签**: `#LLM`, `#agentic workflows`, `#supervised fine-tuning`, `#cost reduction`, `#SLM`

---

<a id="item-4"></a>
## [一键在 Hugging Face Jobs 上运行 vLLM 服务器](https://huggingface.co/blog/vllm-jobs) ⭐️ 7.0/10

Hugging Face 宣布了一种新的一键式方法，可以在其管理的 GPU 基础设施 Hugging Face Jobs 上部署 vLLM 推理服务器，简化了 LLM 服务的设置。 这一集成极大降低了开发者部署高性能 LLM 推理的门槛，无需复杂的手动分布式推理配置即可使用。 该命令利用了 vLLM 对跨多 GPU 的张量并行推理的支持，而 Hugging Face Jobs 提供了完全托管的云 GPU，并采用类似于 Google Colab 的积分系统。

rss · Hugging Face Blog · 6月26日 00:00

**背景**: vLLM 是一个用于快速 LLM 推理和服务的开源库，支持高效的内存管理和分布式执行。Hugging Face Jobs 是一项托管计算服务，允许用户在云 GPU 上运行 AI 工作负载。一键式方法将这两个工具结合，自动化部署过程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://python.langchain.com/v0.1/docs/integrations/llms/vllm/">vLLM is a fast and easy-to-use library for LLM inference and serving...</a></li>
<li><a href="https://unsloth.ai/docs/basics/inference-and-deployment/deploying-with-hugging-face-jobs">Deploying with Hugging Face Jobs | Unsloth Documentation</a></li>

</ul>
</details>

**标签**: `#vLLM`, `#Hugging Face`, `#LLM inference`, `#deployment`

---

<a id="item-5"></a>
## [混合模型 token 预测分析](https://huggingface.co/blog/allenai/hybrid-token-prediction) ⭐️ 7.0/10

AI2 的研究人员发布了一篇博客，分析了混合模型（结合自回归和掩码语言建模）相较于纯自回归或掩码模型更好地预测哪些 token。 这一分析帮助 NLP 研究人员了解混合架构的优势，指导对特定 token 类型（如命名实体或罕见词）关键的任务的模型设计。 该研究可能比较了不同 token 类别（如常见词、罕见词、标点符号）的预测准确率，并提供了混合模型何时优于纯模型的见解。

rss · Hugging Face Blog · 6月25日 16:11

**背景**: 像 MARIA（掩码和自回归填充架构）这样的混合模型集成了自回归（AR）的下一个 token 预测和掩码语言建模（MLM）的填空目标。AR 模型擅长开放式生成，而 MLM 模型更擅长双向理解上下文。这篇博客探讨了哪些 token 最受益于这种组合。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2502.06901v1">Enabling Autoregressive Models to Fill In Masked Tokens</a></li>
<li><a href="https://explore.n1n.ai/blog/which-tokens-do-hybrid-models-predict-better-2026-06-26">Decoding LLM Performance: Which Tokens Do Hybrid Models Predict Best ...</a></li>
<li><a href="https://zglg.work/en/ai/news/2026-06-25-which-tokens-does-a-hybrid-model-predict-better-a86c4b4c5d">Which tokens does a hybrid model predict better? - zglg.work</a></li>

</ul>
</details>

**标签**: `#NLP`, `#hybrid models`, `#token prediction`, `#AI research`

---