---
layout: default
title: "Horizon Summary: 2026-06-15 (EN)"
date: 2026-06-15
lang: en
---

> From 19 items, 4 important content pieces were selected

---

1. [Xiaomi MiMo V2.5 Achieves 1000-3000 tps with DFlash & Persistent Kernel](#item-1) ⭐️ 9.0/10
2. [ePub Quality Debate: Kobo and Adobe Blamed](#item-2) ⭐️ 8.0/10
3. [Why AI hasn’t and won’t replace software engineers](#item-3) ⭐️ 8.0/10
4. [OpenAI Launches Partner Network with $150M Investment](#item-4) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Xiaomi MiMo V2.5 Achieves 1000-3000 tps with DFlash & Persistent Kernel](https://www.reddit.com/r/LocalLLaMA/comments/1u5jtr8/xiaomi_is_now_serving_mimo_v25_at_10003000tps/) ⭐️ 9.0/10

Xiaomi announced that their MiMo V2.5 large language model can now serve inference at 1000 to 3000 tokens per second using DFlash technology and a persistent kernel, with the model already released and an open-source version promised soon. This breakthrough could significantly reduce LLM inference latency, making large models more practical for real-time applications, and the promised open-source release may benefit the broader AI community by enabling faster inference on consumer hardware. The DFlash technology and persistent kernel jointly enable fusing computation and communication into a single kernel, achieving up to 3000 tps. The open-source release is expected to verify the claimed performance and allow community adoption.

reddit · r/LocalLLaMA · /u/Dany0 · Jun 14, 12:26

**Background**: Large language model inference is often bottlenecked by memory bandwidth and kernel launch overhead. Persistent kernels (also known as megakernels) fuse multiple operations into a single GPU kernel to reduce launch latency and improve throughput. DFlash appears to be Xiaomi's proprietary optimization, possibly related to flash memory or efficient data handling.

<details><summary>References</summary>
<ul>
<li><a href="https://zhihaojia.medium.com/compiling-llms-into-a-megakernel-a-path-to-low-latency-inference-cf7840913c17">Compiling LLMs into a MegaKernel: A Path to Low-Latency Inference</a></li>
<li><a href="https://arxiv.org/abs/2512.22219">[2512.22219] MPK: A Compiler and Runtime for Mega-Kernelizing ...</a></li>

</ul>
</details>

**Tags**: `#LLM inference`, `#open-source`, `#performance`, `#Xiaomi`, `#DFlash`

---

<a id="item-2"></a>
## [ePub Quality Debate: Kobo and Adobe Blamed](https://andreklein.net/your-epub-is-fine-kobo-disagrees-blame-adobe/) ⭐️ 8.0/10

An article argues that ePub files are technically sound, but implementation flaws in Kobo and Adobe software cause rendering issues, sparking community debate. This matters because millions of readers rely on Kobo devices and Adobe Digital Editions, and the debate highlights broader issues with proprietary e-book software and open standards. Community members report that Kobo's older rendering engine for .epub files causes slow performance, while using .kepub.epub format improves speed and features like reading statistics.

hackernews · sohkamyung · Jun 14, 22:54 · [Discussion](https://news.ycombinator.com/item?id=48533848)

**Background**: ePub is an open standard for e-books maintained by the W3C, but device makers like Kobo implement their own rendering engines. Adobe's RMSDK is a proprietary SDK used by many e-readers, but it is difficult to license and has quality issues.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/kobolabs/epub-spec/issues">Issues · kobolabs/epub-spec · GitHub</a></li>
<li><a href="https://community.adobe.com/questions-611/adobe-digital-editions-4-5-10-not-responding-in-windows-10-409070">Adobe Digital Editions 4.5.10 not responding in... | Community</a></li>
<li><a href="https://www.reddit.com/r/kobo/comments/1do7ivh/epub_issue_beginner_with_calibre/">EPUB issue/ Beginner with Calibre : r/kobo - Reddit</a></li>

</ul>
</details>

**Discussion**: Comments criticize Adobe's history of poor QA, noting Flash's decline due to reliability issues. Users also point out the difficulty of accessing RMSDK and suggest tools like kepubify to convert ePub to Kobo's native format for better performance.

**Tags**: `#ePub`, `#Adobe`, `#e-reader`, `#Kobo`, `#software engineering`

---

<a id="item-3"></a>
## [Why AI hasn’t and won’t replace software engineers](https://simonwillison.net/2026/Jun/14/why-ai-hasnt-replaced-software-engineers/#atom-everything) ⭐️ 8.0/10

In a new essay, Arvind Narayanan and Sayash Kapoor argue that data does not support AI causing mass layoffs in software engineering, citing that no company reported AI-related layoffs under New York's WARN Act in its first year. They identify three real bottlenecks that resist automation: deciding what to build, verifying and being accountable for the delivered work, and deep human understanding of the codebase, business, and environment. This essay directly challenges the popular narrative that AI will soon replace software engineers, providing evidence-based counterarguments. It matters because software engineering is often considered the most vulnerable profession to AI, and if it remains resilient, other professions are even more likely to be cushioned from mass displacement. The authors point to New York's WARN Act data as concrete evidence: in the first full year of mandatory AI disclosure, not a single company checked the AI-related layoffs box. They also argue that AI only speeds up the typing phase of coding, while the core value of software engineering lies in deep contextual understanding, decision-making, and accountability—areas AI cannot yet automate.

rss · Simon Willison · Jun 14, 23:54

**Background**: The Worker Adjustment and Retraining Notification (WARN) Act requires U.S. employers to provide advance notice of mass layoffs. In March 2025, New York added an AI-specific checkbox to these filings to track AI-related job losses. The essay explains that software engineering involves far more than writing code—it includes debugging, meetings, and understanding complex systems—which is why even advanced AI coding assistants like GitHub Copilot have not eliminated software engineering jobs.

**Tags**: `#AI`, `#software engineering`, `#job market`, `#automation`

---

<a id="item-4"></a>
## [OpenAI Launches Partner Network with $150M Investment](https://openai.com/index/introducing-openai-partner-network) ⭐️ 7.0/10

OpenAI has launched the OpenAI Partner Network, a new partner program backed by a $150 million investment to accelerate enterprise AI adoption, deployment, and transformation. This significant investment and strategic push by OpenAI signals a major commitment to expanding enterprise AI adoption, potentially reshaping how businesses integrate AI technologies with the help of certified partners. The program includes investments in co-sales, specializations such as Codex, engineering support, and customer opportunities for channel partners, with initial Frontier Alliance partners including BCG, McKinsey, Accenture, and Capgemini.

rss · OpenAI Blog · Jun 14, 17:00

**Background**: Enterprise AI adoption often requires significant expertise and integration efforts. Partner networks are a common model in the tech industry where a vendor like OpenAI provides resources, training, and support to consulting firms and system integrators, enabling them to effectively deploy the vendor's solutions to end customers.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/introducing-openai-partner-network/">Introducing the OpenAI Partner Network | OpenAI</a></li>
<li><a href="https://openai.com/index/frontier-alliance-partners/">Introducing Frontier Alliances | OpenAI</a></li>
<li><a href="https://www.crn.com/news/ai/2026/openai-unveils-partner-program-150m-investment-channel-chief-sees-massive-opportunity-ahead">OpenAI Unveils Partner Program, $150M Investment; Channel Chief Sees ‘Massive Opportunity’ Ahead</a></li>

</ul>
</details>

**Tags**: `#OpenAI`, `#enterprise AI`, `#partnerships`, `#AI adoption`

---