---
layout: default
title: "Horizon Summary: 2026-06-30 (EN)"
date: 2026-06-30
lang: en
---

> From 22 items, 4 important content pieces were selected

---

1. [Supreme Court mandates Fourth Amendment protections for geofence warrants](#item-1) ⭐️ 9.0/10
2. [Google's AI peer-reviewer processes ~10K papers, finds 34% more errors](#item-2) ⭐️ 9.0/10
3. [Ornith-1.0: Open-Weight Self-Scaffolding LLM for Agentic Coding](#item-3) ⭐️ 8.0/10
4. [DiScoFormer: Unified Transformer for Density and Score Estimation](#item-4) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Supreme Court mandates Fourth Amendment protections for geofence warrants](https://www.theguardian.com/us-news/2026/jun/29/supreme-court-geofence-warrants-case-decision) ⭐️ 9.0/10

The US Supreme Court ruled that geofence warrants, which compel companies like Google to provide location data of devices within a specific area, must comply with the Fourth Amendment's probable cause requirement, effectively requiring a warrant based on individualized suspicion. This landmark decision establishes crucial privacy protections for millions of smartphone users, limiting law enforcement's ability to conduct broad digital dragnets without judicial oversight. It sets a precedent that could impact other forms of reverse location searches and surveillance technologies. The case arose from a bank robbery investigation where Google's Sensorvault provided data on 19 devices within a 150-meter radius. The Court specified that geofence warrants are searches under the Fourth Amendment and must be supported by probable cause, rejecting the government's argument that users lack a reasonable expectation of privacy in their location data shared with third parties.

hackernews · cdrnsf · Jun 29, 15:54 · [Discussion](https://news.ycombinator.com/item?id=48720924)

**Background**: A geofence warrant is a type of search warrant that allows law enforcement to request records from tech companies identifying all mobile devices within a defined geographic area during a specific time period. Google's Sensorvault database stores historical geolocation data from users who have opted into Location History. The Fourth Amendment protects against unreasonable searches and seizures, and courts have historically required warrants based on probable cause for searches of private property and effects.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Geofence_warrant">Geofence warrant</a></li>

</ul>
</details>

**Discussion**: Commenters highlighted historical context, such as how Paula Broadwell was identified through hotel guest lists and IP geolocation without a geofence warrant, and noted that the Court's opinion cited sources like Riley v. California. One commenter raised a question about whether the ruling applies to devices like Flock automated license plate readers, suggesting potential implications for other surveillance technologies.

**Tags**: `#privacy`, `#supreme court`, `#geofence`, `#fourth amendment`, `#digital rights`

---

<a id="item-2"></a>
## [Google's AI peer-reviewer processes ~10K papers, finds 34% more errors](https://www.reddit.com/r/MachineLearning/comments/1uio9rb/googles_agentic_peerreviewer_handled_10k_papers/) ⭐️ 9.0/10

Google deployed an agentic AI peer-reviewer at top computer science conferences ICML and STOC, handling about 10,000 papers with a 30-minute turnaround. The formal research paper shows it catches 34% more mathematical errors than zero-shot prompting. This sets a precedent for AI-automated scientific review at scale, potentially reducing reviewer burden and improving quality control in academic publishing. It could reshape how conferences and journals handle peer review, especially for mathematical rigor. The agentic system operates autonomously with limited supervision, mimicking human decision-making in real time. It outperformed zero-shot prompting, where the AI is given no examples, by a significant margin in detecting mathematical errors.

reddit · r/MachineLearning · /u/Justgototheeffinmoon · Jun 29, 10:05

**Background**: Agentic AI refers to systems that can accomplish goals with limited supervision, using AI agents that mimic human decision-making. Zero-shot prompting is a technique where a language model is given a task with no examples, relying solely on its training. Academic peer review traditionally relies on human experts, which can be slow and inconsistent; AI-assisted review aims to improve efficiency and objectivity.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ibm.com/think/topics/agentic-ai">What is Agentic AI? | IBM</a></li>
<li><a href="https://promplify.ai/blog/zero-shot-prompting/">Zero - Shot Prompting : How to Get Great Results... — Promplify Blog</a></li>

</ul>
</details>

**Tags**: `#AI`, `#peer review`, `#machine learning`, `#automation`, `#scientific publishing`

---

<a id="item-3"></a>
## [Ornith-1.0: Open-Weight Self-Scaffolding LLM for Agentic Coding](https://simonwillison.net/2026/Jun/29/ornith/#atom-everything) ⭐️ 8.0/10

DeepReinforce released Ornith-1.0, an open-weight (MIT license) family of self-scaffolding LLMs for agentic coding, with variants including 9B Dense, 31B Dense, 35B MoE, and 397B MoE, built on Gemma 4 and Qwen 3.5, achieving state-of-the-art coding benchmark performance among open-source models of comparable size. Ornith-1.0 represents significant progress in open-weight LLMs for code generation, offering state-of-the-art performance while being built on permissively licensed base models (Apache 2.0), making it accessible for research and commercial use. The model uses a self-scaffolding technique where each reinforcement learning iteration generates a scaffold, and it supports running an agent harness over many tool calls, as demonstrated by early users with LM Studio and the GGUF version.

rss · Simon Willison · Jun 29, 16:17

**Background**: Self-scaffolding LLMs are systems that wrap a programmatic scaffold around an LLM core, chaining together multiple LLM calls to autonomously reason and act. Agentic coding uses AI agents to plan, write, test, and modify code with minimal human intervention. Ornith-1.0 combines these approaches to enhance code generation and debugging.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Agentic_coding">Agentic coding</a></li>
<li><a href="https://medium.com/data-science-in-your-pocket/ornith-1-0-self-learning-llm-for-coding-318c9a830bfc">Ornith 1.0 : Self Learning LLM for Coding | by Mehul Gupta | Medium</a></li>
<li><a href="https://www.lesswrong.com/posts/mAwxebLw3nYbDivmt/scaffolded-llms-less-obvious-concerns">Scaffolded LLMs: Less Obvious Concerns — LessWrong</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#open-source`, `#coding`, `#agentic`, `#AI model`

---

<a id="item-4"></a>
## [DiScoFormer: Unified Transformer for Density and Score Estimation](https://huggingface.co/blog/allenai/discoformer) ⭐️ 7.0/10

Researchers from AI2 introduce DiScoFormer, a single transformer model that jointly performs density estimation and score estimation across multiple distributions, unifying two traditionally separate tasks in generative modeling. This approach could simplify and improve generative models by leveraging shared representations, potentially leading to more efficient training and better sample quality across diverse data distributions. The model is designed to work across distributions, meaning it can handle multiple datasets or domains without retraining, and jointly estimates both the density and the score (gradient of log-density).

rss · Hugging Face Blog · Jun 29, 18:02

**Background**: Density estimation involves approximating the probability distribution of data, while score-based models learn the gradient of the log-density for generative sampling. Traditionally, these are separate tasks requiring different architectures. DiScoFormer combines them in a single transformer, potentially enabling joint learning and cross-distribution generalization.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Density_estimation">Density estimation</a></li>
<li><a href="https://arxiv.org/abs/2011.13456">[2011.13456] Score-Based Generative Modeling through Stochastic Differential Equations</a></li>
<li><a href="https://fanpu.io/blog/2023/score-based-diffusion-models/">Score-Based Diffusion Models | Fan Pu Zeng</a></li>

</ul>
</details>

**Tags**: `#transformer`, `#density estimation`, `#score-based models`, `#generative AI`

---