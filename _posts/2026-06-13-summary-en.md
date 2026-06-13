---
layout: default
title: "Horizon Summary: 2026-06-13 (EN)"
date: 2026-06-13
lang: en
---

> From 25 items, 4 important content pieces were selected

---

1. [US Government Orders Suspension of Anthropic's Fable 5 and Mythos 5](#item-1) ⭐️ 9.0/10
2. [New CRISPR technique shreds cancer cells, targets undruggable cancers](#item-2) ⭐️ 9.0/10
3. [Satirical Crematorium Analogy Mocks AI Investment Hype](#item-3) ⭐️ 7.0/10
4. [olmo-eval: Open Evaluation Workbench for LLM Development](#item-4) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [US Government Orders Suspension of Anthropic's Fable 5 and Mythos 5](https://www.anthropic.com/news/fable-mythos-access) ⭐️ 9.0/10

The US government has ordered Anthropic to suspend access to its advanced AI models Fable 5 and Mythos 5 for all foreign nationals, as announced on June 12, 2026. This marks the first time the US has directly restricted access to state-of-the-art large language models based on safety concerns. This action sets a significant precedent for government regulation of powerful AI models, potentially limiting public access to cutting-edge technology. It could chill investment in AI capabilities and spark debate on the balance between safety, innovation, and civil liberties. Fable 5 is Anthropic's most capable publicly available model, achieving over 90% on internal analytics benchmarks, while Mythos 5 is the same model with enhanced cybersecurity capabilities. The order specifically targets foreign nationals, but community concerns suggest it could lead to broader restrictions.

hackernews · Dylan1312 · Jun 13, 00:51 · [Discussion](https://news.ycombinator.com/item?id=48511072)

**Background**: Anthropic has long warned about the potential dangers of advanced AI, and this government action appears to take those warnings seriously. Fable 5 and Mythos 5 are part of Anthropic's Claude model family, with Mythos 5 described as the strongest cybersecurity model worldwide. The suspension follows a period of heightened scrutiny of AI companies by US regulators.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/news/claude-fable-5-mythos-5">Claude Fable 5 and Claude Mythos 5 \ Anthropic</a></li>
<li><a href="https://www.nytimes.com/2026/06/12/technology/anthropic-mythos-fable5-blocked.html">Anthropic Blocks Foreigners From Using Mythos and Fable AI</a></li>
<li><a href="https://en.wikipedia.org/wiki/Mythos_(Anthropic)">Mythos (Anthropic)</a></li>

</ul>
</details>

**Discussion**: Community comments are sharply divided: some argue Anthropic's own scaremongering backfired, while others see this as government overreach and a threat to open access. A key concern is that this precedent may stifle future AI development and investment, as reaching higher capabilities becomes politically constrained.

**Tags**: `#AI regulation`, `#government policy`, `#large language models`, `#Anthropic`, `#civil liberties`

---

<a id="item-2"></a>
## [New CRISPR technique shreds cancer cells, targets undruggable cancers](https://innovativegenomics.org/news/crispr-technique-selectively-shreds-cancer-cells/) ⭐️ 9.0/10

Researchers have developed a CRISPR-Cas12a2 system that selectively detects tumor-specific mutations and shreds the cell's chromatin, killing cancer cells, including those previously considered undruggable. The findings were published in Nature and on bioRxiv. This technique offers a new way to treat cancers that are resistant to conventional drugs, particularly those with smooth protein surfaces that are hard to target. It could significantly expand the scope of precision oncology. Unlike Cas9, which cuts DNA, Cas12a2 is activated by detecting target RNA sequences and then nonspecifically degrades chromatin, causing massive cellular damage. The system is programmable and can be directed against specific mutations.

hackernews · gmays · Jun 12, 15:15 · [Discussion](https://news.ycombinator.com/item?id=48505231)

**Background**: CRISPR-Cas systems are gene-editing tools derived from bacteria. Cas12a2 is a variant that targets RNA and triggers collateral degradation of cellular content. 'Undruggable' cancers often involve mutations in proteins like RAS or TP53 that have smooth surfaces, making them difficult to target with small molecules.

<details><summary>References</summary>
<ul>
<li><a href="https://attheu.utah.edu/health-medicine/new-kind-of-crispr-could-treat-viral-infection-and-cancer-by-shredding-sick-cells-dna/">New kind of CRISPR could treat viral infection and cancer by shredding...</a></li>

</ul>
</details>

**Discussion**: Comments show excitement but also skepticism, with one commenter noting that earlier Cas9-based approaches existed and that tumors may evolve resistance. Another commenter argued that CRISPR is overhyped compared to viral vector therapies, which have more FDA approvals.

**Tags**: `#CRISPR`, `#cancer research`, `#gene editing`, `#biotechnology`, `#oncology`

---

<a id="item-3"></a>
## [Satirical Crematorium Analogy Mocks AI Investment Hype](https://simonwillison.net/2026/Jun/12/andrew-singleton/#atom-everything) ⭐️ 7.0/10

Andrew Singleton published a satirical piece on McSweeney's that uses a crematorium scenario to parody the circular logic of AI investment valuations, where inflated revenue and equity are created through burning money. The satire resonates with ongoing debates about the sustainability of AI investments and the potential for a bubble, highlighting how current valuation methods may rely on circular reasoning rather than real economic value. In the story, Jenny receives a $20 billion investment for 5% equity, then burns $10 billion and pays John $10 billion for propane to burn the rest, allowing John to claim $10 billion in revenue and value Jenny's business at $100 billion, with a Forbes reporter eventually entering a polyamorous relationship with them.

rss · Simon Willison · Jun 12, 18:09

**Background**: There has been widespread skepticism about the huge sums of money flowing into AI companies, with some economists and tech critics warning of a hype cycle similar to the dot-com bubble. This piece serves as a humorous yet pointed critique of how AI startups can be valued based on illusion rather than fundamental economics.

**Tags**: `#AI`, `#satire`, `#economics`, `#tech criticism`

---

<a id="item-4"></a>
## [olmo-eval: Open Evaluation Workbench for LLM Development](https://huggingface.co/blog/allenai/olmo-eval) ⭐️ 7.0/10

Allen AI has released olmo-eval, an open evaluation workbench that integrates benchmarking into the daily model development loop for large language models, extending the OLMES framework for reproducibility. This tool enables ML practitioners to continuously evaluate model checkpoints during development, improving efficiency and reproducibility in LLM training, which is crucial for open science and rapid iteration. olmo-eval is built on top of the OLMES evaluation suite and is designed to work with the OLMo model family, allowing users to add custom benchmarks and track performance across checkpoints.

rss · Hugging Face Blog · Jun 12, 15:56

**Background**: The OLMo project by Allen AI is an open-source framework for training large language models. Model development typically involves iterating on training data, architecture, and hyperparameters, requiring frequent evaluation. OLMES provided a standardized evaluation suite for final model scores, but lacked integration into the iterative development loop. olmo-eval fills this gap by enabling evaluation during training.

<details><summary>References</summary>
<ul>
<li><a href="https://allenai.org/blog/olmo-eval">olmo-eval: An evaluation workbench for the model development loop</a></li>
<li><a href="https://allenai.org/olmo">Olmo from Ai2</a></li>

</ul>
</details>

**Tags**: `#evaluation`, `#OLMo`, `#model development`, `#workbench`, `#AI`

---