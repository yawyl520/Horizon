---
layout: default
title: "Horizon Summary: 2026-07-03 (EN)"
date: 2026-07-03
lang: en
---

> From 25 items, 5 important content pieces were selected

---

1. [US Bans Differential Privacy in Census Data](#item-1) ⭐️ 9.0/10
2. [Virginia Bans Sale of Geolocation Data](#item-2) ⭐️ 8.0/10
3. [Using DSPy to improve Datasette Agent's SQL prompts](#item-3) ⭐️ 7.0/10
4. [Understand to Participate: A New Framing for AI Coding Agents](#item-4) ⭐️ 7.0/10
5. [Smart Model Routing: An Emerging Trend in AI](#item-5) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [US Bans Differential Privacy in Census Data](https://scottaaronson.blog/?p=9902) ⭐️ 9.0/10

On June 4, 2026, the U.S. Secretary of Commerce issued directive DAO 216-26, banning the use of noise infusion and differential privacy in all statistical products published by the Census Bureau and the Bureau of Economic Analysis. This order severely weakens privacy protections for census respondents and degrades data quality, jeopardizing critical research and policy decisions that rely on accurate demographic statistics. The directive restricts disclosure avoidance to 'coarsening' only—such as aggregating or suppressing data—and explicitly forbids adding random noise, which was the foundation of differential privacy used in the 2020 Census.

hackernews · flowercalled · Jul 3, 00:01 · [Discussion](https://news.ycombinator.com/item?id=48768992)

**Background**: Differential privacy is a mathematical framework that adds carefully calibrated noise to data to protect individual records while preserving statistical accuracy. The Census Bureau adopted it for the 2020 Census after researchers showed that older methods like swapping leaked personal information. The new ban eliminates this modern protection, leaving only coarsening as an allowable disclosure avoidance technique.

<details><summary>References</summary>
<ul>
<li><a href="https://stateofsurveillance.org/news/census-bureau-noise-infusion-ban-differential-privacy-rollback-2026/">The Census Bureau Just Banned the Math That Kept Your Data ...</a></li>
<li><a href="https://www.npr.org/2026/06/12/nx-s1-5855734/census-bureau-data-differential-privacy">Trump privacy restrictions may reduce Census Bureau data : NPR</a></li>
<li><a href="https://www.404media.co/census-data-privacy-trump-policy-change-noise-infusion/">The Trump Administration’s New Census Data Rules Are a Policy ...</a></li>

</ul>
</details>

**Discussion**: Commenters express alarm, with Scott Aaronson calling it a 'privacy emergency.' Some question the political motive, while others urge contacting legislators and provide links to find representatives.

**Tags**: `#privacy`, `#differential privacy`, `#census`, `#data policy`, `#disclosure avoidance`

---

<a id="item-2"></a>
## [Virginia Bans Sale of Geolocation Data](https://www.hunton.com/privacy-and-cybersecurity-law-blog/virginia-bans-sale-of-geolocation-data) ⭐️ 8.0/10

Virginia has enacted legislation banning the sale of precise geolocation data, prohibiting the transfer of location information that can identify an individual within 1,750 feet. This law marks a significant step in state-level privacy regulation, addressing growing concerns over the misuse of location data, such as tracking visits to abortion clinics. It sets a precedent that could influence other states and pressure tech companies to adopt stricter data practices. The ban applies only to precise geolocation data within 1,750 feet, meaning companies can still sell fuzzy or aggregated location data. Enforcement against out-of-state entities and data stored on cloud servers in Virginia remains ambiguous.

hackernews · toomuchtodo · Jul 2, 21:03 · [Discussion](https://news.ycombinator.com/item?id=48767347)

**Background**: Geolocation data is collected from mobile devices and apps, often sold to advertisers and data brokers. This data can reveal sensitive information such as medical visits, religious practices, and political affiliations. The U.S. lacks a comprehensive federal privacy law, leading states to enact their own protections. Virginia's Consumer Data Protection Act previously included some data rights, but this new ban specifically targets the sale of location data.

**Discussion**: Community comments are generally supportive of the ban, but raise concerns about enforcement loopholes, particularly regarding out-of-state companies and the sale of fuzzy location data. Some emphasize the real-world harms of precise data tracking, such as anti-abortion ad campaigns targeting Planned Parenthood visitors.

**Tags**: `#privacy`, `#geolocation`, `#legislation`, `#data rights`, `#US law`

---

<a id="item-3"></a>
## [Using DSPy to improve Datasette Agent's SQL prompts](https://simonwillison.net/2026/Jul/2/dspy-datasette-agent-prompts/#atom-everything) ⭐️ 7.0/10

Simon Willison used the DSPy framework to evaluate and improve the system prompts of Datasette Agent, an AI assistant for Datasette, specifically for generating SQL queries to answer user questions. This demonstrates a practical, programmatic approach to prompt optimization for AI agents, potentially reducing reliance on manual prompt engineering and improving reliability of SQL generation in data exploration tools. The research, conducted as an asynchronous task using Claude Code and Claude Fable 5, tested with GPT-4.1 mini and nano models, and identified improvements such as including column names in schema listings to avoid error-retry loops.

rss · Simon Willison · Jul 2, 18:25

**Background**: DSPy (Declarative Self-improving Python) is a framework for algorithmically optimizing language model prompts and weights, enabling developers to programmatically improve AI pipeline performance. Datasette Agent is an AI assistant that uses large language models to generate and execute SQL queries for exploring data in Datasette, an open-source tool for publishing and analyzing data.

<details><summary>References</summary>
<ul>
<li><a href="https://dspy.ai/">DSPy</a></li>
<li><a href="https://agent.datasette.io/">Datasette Agent : an AI assistant for Datasette to help explore and...</a></li>
<li><a href="https://github.com/stanfordnlp/dspy">GitHub - stanfordnlp/dspy: DSPy: The framework for ... What Is DSPy? How It Works, Use Cases, and Resources GitHub - isaka/DSPy: DSPy: The framework for programming—not ... Tutorials Overview - DSPy DSPy Framework — Programmatic Prompt Optimization (2026) Programming, Not Prompting: A Hands-On Guide to DSPy</a></li>

</ul>
</details>

**Tags**: `#DSPy`, `#prompt engineering`, `#SQL`, `#AI agents`, `#Datasette`

---

<a id="item-4"></a>
## [Understand to Participate: A New Framing for AI Coding Agents](https://simonwillison.net/2026/Jul/2/understand-to-participate/#atom-everything) ⭐️ 7.0/10

Geoffrey Litt, speaking at the AI Engineer World's Fair in 2026, introduced the concept of 'understand to participate,' arguing that developers must deeply understand AI-generated code to avoid accumulating cognitive debt. This framing provides a crucial mindset for software engineers using AI coding agents, highlighting that passive acceptance of AI outputs can lead to loss of project understanding and increased cognitive debt. Cognitive debt, distinct from technical debt, refers to the erosion of shared understanding across a team over time. Litt emphasizes the need to actively learn from AI agents to maintain creative participation.

rss · Simon Willison · Jul 2, 17:07

**Background**: Cognitive debt is a concept in software engineering describing the loss of understanding of a codebase as it evolves, often accelerated by AI-generated code. The 'understand to participate' approach counters this by urging developers to study AI changes thoroughly. This contrasts with simply reviewing diffs, aiming for deeper comprehension that enables further collaboration.

<details><summary>References</summary>
<ul>
<li><a href="https://www.geoffreylitt.com/2026/07/02/understanding-is-the-new-bottleneck.html">Understanding is the new bottleneck - Geoffrey Litt</a></li>
<li><a href="https://digg.com/tech/glvyx0iw">Geoffrey Litt argues that human comprehension of AI-generated ...</a></li>

</ul>
</details>

**Tags**: `#AI agents`, `#cognitive debt`, `#software engineering`, `#code collaboration`

---

<a id="item-5"></a>
## [Smart Model Routing: An Emerging Trend in AI](https://blog.pragmaticengineer.com/the-pulse-a-new-trend-smart-model-routing/) ⭐️ 7.0/10

The article by Gergely Orosz investigates intelligent router solutions that automatically select the most appropriate AI model for each task, highlighting a shift from monolithic model usage. Smart model routing can significantly reduce inference costs and improve efficiency by matching tasks to the right-sized model, which is critical as AI adoption scales across industries. Platforms like Not Diamond, Martian, LiteLLM, MindStudio, and OpenRouter's Auto Router (powered by NotDiamond) offer intelligent routing capabilities, with some using semantic routing based on embeddings.

rss · The Pragmatic Engineer · Jul 2, 18:46

**Background**: Traditionally, companies rely on a single powerful model like GPT-4 for all tasks, leading to overspending. Model routing addresses this by classifying each request and selecting a model (e.g., a smaller one for simple queries) to optimize cost and latency.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cnbc.com/2026/06/05/model-routing-on-ai-is-a-problem-for-openai-and-anthropic.html">Model routing is a fix for AI overspending. That's a problem for OpenAI and Anthropic</a></li>
<li><a href="https://openrouter.ai/docs/guides/routing/routers/auto-router">Auto Router | Smart AI Model Selection | OpenRouter | Documentation</a></li>
<li><a href="https://github.com/vllm-project/semantic-router">GitHub - vllm-project/semantic-router: System Level ...</a></li>
<li><a href="https://medium.com/google-cloud/a-developers-guide-to-model-routing-1f21ecc34d60">A Developer’s Guide to Model Routing | by Karl Weinmeister | Google Cloud - Community | Medium</a></li>

</ul>
</details>

**Tags**: `#AI/ML`, `#model routing`, `#engineering`, `#pragmatic engineer`

---