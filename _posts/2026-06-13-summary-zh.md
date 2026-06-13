---
layout: default
title: "Horizon Summary: 2026-06-13 (ZH)"
date: 2026-06-13
lang: zh
---

> 从 19 条内容中筛选出 3 条重要资讯。

---

1. [美国政府暂停访问 Anthropic 的 Fable 5 和 Mythos 5 模型](#item-1) ⭐️ 9.0/10
2. [CRISPR 技术选择性摧毁癌细胞，包括“不可成药”癌症](#item-2) ⭐️ 9.0/10
3. [Allen AI 发布 OLMo-Eval 简化模型评估](#item-3) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [美国政府暂停访问 Anthropic 的 Fable 5 和 Mythos 5 模型](https://www.anthropic.com/news/fable-mythos-access) ⭐️ 9.0/10

美国政府发布指令，要求 Anthropic 暂停其先进大语言模型 Fable 5 和 Mythos 5 的公开访问，理由是国家安全隐患。 这标志着 AI 监管可能的转变，这是政府首次直接限制对最先进 AI 模型的访问，为未来 AI 开发和公开可用性树立了先例。 几天前刚公开发布的 Fable 5 以及仅对经过审核的合作伙伴开放的 Mythos 5 均受影响；该指令最初限制非美国公民访问，但实质上抑制了广泛的公众使用。

hackernews · Dylan1312 · 6月13日 00:51 · [社区讨论](https://news.ycombinator.com/item?id=48511072)

**背景**: Anthropic 是一家领先的 AI 公司，以其 Claude 系列大语言模型而闻名。Fable 5 和 Mythos 5 代表了它们最强大的模型，旨在自主处理如软件工程等复杂任务。政府干预是在 Anthropic 自身对如此强大 AI 潜在危险发出警告之后发生的。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/news/claude-fable-5-mythos-5">Claude Fable 5 and Claude Mythos 5 \ Anthropic</a></li>
<li><a href="https://www.bbc.com/news/articles/c932g3v3e13o">Anthropic's Claude Fable 5 and Mythos 5 AI suspended over ...</a></li>

</ul>
</details>

**社区讨论**: 评论者意见分歧：一些人认为这是 Anthropic 散布恐慌的自然结果，而另一些人则视之为政府过度干预或打击报复。一个关键观点警告称，这可能是政府开始限制公众访问强大 LLMs 的开端，可能产生深远影响。

**标签**: `#AI regulation`, `#government intervention`, `#Anthropic`, `#LLMs`, `#AI safety`

---

<a id="item-2"></a>
## [CRISPR 技术选择性摧毁癌细胞，包括“不可成药”癌症](https://innovativegenomics.org/news/crispr-technique-selectively-shreds-cancer-cells/) ⭐️ 9.0/10

研究人员开发了一种新的 CRISPR-Cas12a2 技术，该技术通过检测癌细胞特异性 RNA 转录本，选择性地摧毁癌细胞，相关成果发表于近期《自然》杂志。 该方法为先前不可成药的癌症突变提供了潜在疗法，具有高特异性，其新机制可能具有广泛适用性。 与 Cas9 不同，Cas12a2 具有反式核酸酶活性，一旦结合靶 RNA 即被激活，从而摧毁染色质（DNA-蛋白质复合体），引发 DNA 损伤和细胞死亡。

hackernews · gmays · 6月12日 15:15 · [社区讨论](https://news.ycombinator.com/item?id=48505231)

**背景**: CRISPR-Cas 系统是细菌的适应性免疫系统，已被重新用于基因编辑。Cas12a2 是一种可切割 RNA 和 DNA 的变体，能被编程识别 RNA 序列。染色质是细胞中 DNA 的包装形式，摧毁它会引发细胞死亡。“不可成药”癌症是指突变难以被常规药物靶向的癌症。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nature.com/articles/s41586-026-10738-7">Targeting Cancer-Specific Mutations with RNA-Triggered Chromatin Shredding | Nature</a></li>
<li><a href="https://www.biorxiv.org/content/10.64898/2026.05.08.723607v1">Selective Elimination of TP53 Mutant Cells by Transcript-Activated Chromatin Shredding | bioRxiv</a></li>
<li><a href="https://medicalxpress.com/news/2026-06-crispr-enzyme-precisely-shreds-dna.html">CRISPR enzyme precisely detects and shreds DNA in cancer...</a></li>

</ul>
</details>

**社区讨论**: 评论中既有兴奋也有怀疑；一些用户赞赏这一进展，而另一些则指出目前 CRISPR 疗法在 FDA 批准数量上落后于病毒载体方法。还有关于潜在耐药性进化的技术讨论以及与先前 Cas9 方法的比较。

**标签**: `#CRISPR`, `#cancer therapy`, `#Cas12a2`, `#biotechnology`, `#genomics`

---

<a id="item-3"></a>
## [Allen AI 发布 OLMo-Eval 简化模型评估](https://huggingface.co/blog/allenai/olmo-eval) ⭐️ 7.0/10

Allen AI 发布了 olmo-eval，这是一个开放评估工作台，可无缝集成到模型开发流程中，允许开发者在不断变化的大语言模型检查点上添加、运行和分析基准测试。 该工具解决了大语言模型开发中的一个关键瓶颈，通过在迭代训练期间实现快速、可复现的评估，帮助从业者做出明智决策并加速模型改进。 Olmo-eval 将 OLMES 框架从最终分数可复现性扩展到日常开发，并支持工具增强评估，从而能在相同任务上比较基线性能和工具增强性能。

rss · Hugging Face Blog · 6月12日 15:56

**背景**: 在开发过程中评估大语言模型（LLM）颇具挑战，因为基准测试必须在众多检查点上一致运行，且结果需要易于比较。OLMES 是一个标准化的 LLM 评估套件，但它专为最终模型评估而非迭代开发设计。Olmo-eval 通过提供一个与训练循环集成的工作台来填补这一空白，使开发者能够跟踪进度并及早发现性能倒退。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/allenai/OLMo-Eval/">GitHub - allenai/olmo-eval</a></li>
<li><a href="https://allenai.org/blog/olmo-eval">olmo-eval: An evaluation workbench for the model development loop</a></li>

</ul>
</details>

**标签**: `#evaluation`, `#model development`, `#workbench`, `#AI tools`

---