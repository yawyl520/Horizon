---
layout: default
title: "Horizon Summary: 2026-06-13 (EN)"
date: 2026-06-13
lang: en
---

> From 19 items, 3 important content pieces were selected

---

1. [US Suspends Access to Anthropic's Fable 5 and Mythos 5](#item-1) ⭐️ 9.0/10
2. [CRISPR technique selectively shreds cancer cells, including 'undruggable' cancers](#item-2) ⭐️ 9.0/10
3. [Allen AI Releases OLMo-Eval for Streamlined Model Evaluation](#item-3) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [US Suspends Access to Anthropic's Fable 5 and Mythos 5](https://www.anthropic.com/news/fable-mythos-access) ⭐️ 9.0/10

The US government has issued a directive ordering Anthropic to suspend public access to its advanced large language models, Fable 5 and Mythos 5, citing national security concerns. This marks a potential shift in AI regulation, as it is the first time a government has directly restricted access to a state-of-the-art AI model, setting a precedent that could impact future AI development and public availability. Fable 5, released publicly just days ago, and Mythos 5, which was only available to vetted partners, are both affected; the directive initially restricts access for non-US citizens but effectively curbs widespread public use.

hackernews · Dylan1312 · Jun 13, 00:51 · [Discussion](https://news.ycombinator.com/item?id=48511072)

**Background**: Anthropic is a leading AI company known for its Claude series of large language models. Fable 5 and Mythos 5 represent their most capable models, designed to work autonomously on complex tasks like software engineering. The government intervention follows Anthropic's own warnings about the potential dangers of such powerful AI.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/news/claude-fable-5-mythos-5">Claude Fable 5 and Claude Mythos 5 \ Anthropic</a></li>
<li><a href="https://www.bbc.com/news/articles/c932g3v3e13o">Anthropic's Claude Fable 5 and Mythos 5 AI suspended over ...</a></li>

</ul>
</details>

**Discussion**: Commenters are divided: some argue this is a natural consequence of Anthropic's fear-mongering, while others see it as government overreach or a vendetta. A key viewpoint warns that this could be the beginning of governments restricting public access to strong LLMs, which may have far-reaching implications.

**Tags**: `#AI regulation`, `#government intervention`, `#Anthropic`, `#LLMs`, `#AI safety`

---

<a id="item-2"></a>
## [CRISPR technique selectively shreds cancer cells, including 'undruggable' cancers](https://innovativegenomics.org/news/crispr-technique-selectively-shreds-cancer-cells/) ⭐️ 9.0/10

Researchers have developed a novel CRISPR-Cas12a2 technique that selectively destroys cancer cells by shredding their chromatin upon detecting cancer-specific RNA transcripts, as reported in a recent Nature paper. This approach offers a potential therapy for previously undruggable cancer mutations, showing high specificity and a novel mechanism that could be broadly applicable. Unlike Cas9, Cas12a2 possesses trans-nucleolytic activity that shreds chromatin (the DNA-protein complex) once activated by binding to target RNA, triggering DNA damage and cell death.

hackernews · gmays · Jun 12, 15:15 · [Discussion](https://news.ycombinator.com/item?id=48505231)

**Background**: CRISPR-Cas systems are adaptive immune systems in bacteria, repurposed for genome editing. Cas12a2 is a variant that cuts both RNA and DNA, and can be programmed to recognize RNA sequences. Chromatin is the packaged form of DNA in cells; shredding it leads to cell death. 'Undruggable' cancers have mutations that are difficult to target with conventional drugs.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nature.com/articles/s41586-026-10738-7">Targeting Cancer-Specific Mutations with RNA-Triggered Chromatin Shredding | Nature</a></li>
<li><a href="https://www.biorxiv.org/content/10.64898/2026.05.08.723607v1">Selective Elimination of TP53 Mutant Cells by Transcript-Activated Chromatin Shredding | bioRxiv</a></li>
<li><a href="https://medicalxpress.com/news/2026-06-crispr-enzyme-precisely-shreds-dna.html">CRISPR enzyme precisely detects and shreds DNA in cancer...</a></li>

</ul>
</details>

**Discussion**: Comments show a mix of excitement and skepticism; some users applaud the progress while others note current CRISPR therapies lag behind viral vector approaches in FDA approvals. There is technical discussion about potential resistance evolution and comparisons to previous Cas9 methods.

**Tags**: `#CRISPR`, `#cancer therapy`, `#Cas12a2`, `#biotechnology`, `#genomics`

---

<a id="item-3"></a>
## [Allen AI Releases OLMo-Eval for Streamlined Model Evaluation](https://huggingface.co/blog/allenai/olmo-eval) ⭐️ 7.0/10

Allen AI has released olmo-eval, an open evaluation workbench that integrates seamlessly into the model development loop, allowing developers to add, run, and analyze benchmarks across changing LLM checkpoints. This tool addresses a critical bottleneck in LLM development by enabling rapid, reproducible evaluation during iterative training, helping practitioners make informed decisions and accelerate model improvement. Olmo-eval extends the OLMES framework from final-score reproducibility into daily development, and it supports tool-augmented evaluation, enabling comparison of baseline and tool-enhanced performance on the same tasks.

rss · Hugging Face Blog · Jun 12, 15:56

**Background**: Evaluating large language models (LLMs) during development is challenging because benchmarks must be run consistently across many checkpoints, and results need to be easily comparable. OLMES is a standardized evaluation suite for LLMs, but it was designed for final model evaluation rather than iterative development. Olmo-eval fills this gap by providing a workbench that integrates with the training loop, allowing developers to track progress and catch regressions early.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/allenai/OLMo-Eval/">GitHub - allenai/olmo-eval</a></li>
<li><a href="https://allenai.org/blog/olmo-eval">olmo-eval: An evaluation workbench for the model development loop</a></li>

</ul>
</details>

**Tags**: `#evaluation`, `#model development`, `#workbench`, `#AI tools`

---