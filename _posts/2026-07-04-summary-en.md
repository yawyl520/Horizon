---
layout: default
title: "Horizon Summary: 2026-07-04 (EN)"
date: 2026-07-04
lang: en
---

> From 15 items, 5 important content pieces were selected

---

1. [EU Parliament Spyware Investigator Hacked with Pegasus](#item-1) ⭐️ 9.0/10
2. [SearXNG: Free, self-hostable metasearch engine](#item-2) ⭐️ 8.0/10
3. [Open Source AI Gap Map Launched by Current AI](#item-3) ⭐️ 8.0/10
4. [Josh Comeau Reports 67% Drop in Course Sales Due to AI](#item-4) ⭐️ 7.0/10
5. [Let AI Models Use Their Own Judgment for Efficiency](#item-5) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [EU Parliament Spyware Investigator Hacked with Pegasus](https://citizenlab.ca/research/member-of-committee-investigating-spyware-hacked-with-pegasus/) ⭐️ 9.0/10

Citizen Lab confirmed with high confidence that a member of the European Parliament's committee investigating spyware was infected with Pegasus spyware on multiple occasions in 2022 and 2023. This incident underscores the threat of state-sponsored espionage targeting European democratic institutions, potentially compromising sensitive investigations and undermining parliamentary sovereignty. The first infection in October 2022 overlapped with a Pegasus campaign targeting exiled journalists from Russia and Belarus, suggesting a single Pegasus customer with cross-border authorization. The target's personal phone also contained confidential medical and government documents, indicating a lack of device separation.

hackernews · ledoge · Jul 3, 20:38 · [Discussion](https://news.ycombinator.com/item?id=48779683)

**Background**: Pegasus is a powerful spyware developed by Israel's NSO Group, enabling remote surveillance of mobile devices. It is sold to governments under the guise of fighting crime and terrorism but has been widely abused to target journalists, activists, and politicians. Citizen Lab is a University of Toronto research group that exposes digital threats to human rights.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Pegasus_(spyware)">Pegasus (spyware)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Pegasus_Project_(investigation)">Pegasus Project (investigation) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Citizen_Lab">Citizen Lab</a></li>

</ul>
</details>

**Discussion**: Commenters noted that similar Pegasus attacks have occurred in Greece and Poland, with speculation that the attack may be linked to domestic political espionage rather than external actors. Some criticized the EU Parliament for lacking policies to separate work and personal devices, potentially compromising sensitive data.

**Tags**: `#cybersecurity`, `#espionage`, `#Pegasus`, `#European Parliament`, `#spyware`

---

<a id="item-2"></a>
## [SearXNG: Free, self-hostable metasearch engine](https://github.com/searxng/searxng) ⭐️ 8.0/10

SearXNG is a free, open-source internet metasearch engine that aggregates search results from multiple search services and databases without tracking or profiling users. This tool is significant for privacy-conscious users and developers building local AI agents, as it enables privacy-respecting search that can be integrated into tool-calling and RAG pipelines without relying on centralized search APIs. SearXNG supports JSON formatted results, making it ideal for programmatic use in agent workflows, and can be self-hosted on a local network or personal device. However, users may occasionally encounter captcha blocks from upstream search engines like DuckDuckGo or Brave.

hackernews · theanonymousone · Jul 3, 20:15 · [Discussion](https://news.ycombinator.com/item?id=48779454)

**Background**: A metasearch engine is an online tool that sends user queries to multiple search engines simultaneously and aggregates their results into a single list. Unlike traditional search engines, metasearch engines do not maintain their own index of web pages, which enhances user privacy because the query is distributed across different services. SearXNG is a fork of the original Searx project, which was created by asciimoo and has since been maintained by a community of developers.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/searxng/searxng">GitHub - searxng/searxng: SearXNG is a free internet metasearch engine which aggregates results from various search services and databases. Users are neither tracked nor profiled. · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/SearXNG">SearXNG - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Metasearch_engine">Metasearch engine - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Original creator asciimoo noted he is no longer involved due to limitations of the metasearch concept, and pointed to his new project Hister. Other users praised SearXNG for enabling local model tool calling and RAG, with some reporting daily use over five years. Common concerns include slower search speed and occasional captcha challenges.

**Tags**: `#search engine`, `#privacy`, `#self-hosted`, `#metasearch`, `#open source`

---

<a id="item-3"></a>
## [Open Source AI Gap Map Launched by Current AI](https://simonwillison.net/2026/Jul/3/open-source-ai-gap-map/#atom-everything) ⭐️ 8.0/10

Current AI, a non-profit backed by $400 million, launched the Open Source AI Gap Map (v0.1) indexing 421 products from 228 organizations across models, tools, datasets, and hardware. This systematic mapping provides a comprehensive view of the open source AI ecosystem, helping researchers and practitioners identify gaps and opportunities, and fostering collaboration. The map categorizes 421 products into 14 categories across three stack layers, with an additional 24,400 uncategorized artifacts; the underlying data is released under an MIT license on GitHub.

rss · Simon Willison · Jul 3, 22:04

**Background**: Current AI is a global non-profit founded at the AI Action Summit in Paris in February 2025, aiming to build a public option for AI. The Gap Map builds on work from experts at Columbia Convening, MOF, Hugging Face, and others, evaluating over 24,626 projects for openness, capability, and adoption.

<details><summary>References</summary>
<ul>
<li><a href="https://map.currentai.org/">Current AI – Open Source AI Gap Map</a></li>

</ul>
</details>

**Tags**: `#open source`, `#AI`, `#ecosystem mapping`, `#non-profit`, `#gap analysis`

---

<a id="item-4"></a>
## [Josh Comeau Reports 67% Drop in Course Sales Due to AI](https://simonwillison.net/2026/Jul/3/josh-w-comeau/#atom-everything) ⭐️ 7.0/10

Josh W. Comeau, a well-known educator, reported that his latest course launch sold roughly one-third as many copies as previous launches, attributing the decline to AI-driven job uncertainty and LLMs replacing paid learning resources. This trend indicates a significant disruption in the developer education market, as AI not only reduces demand for learning due to job fears but also provides free alternatives to paid courses, threatening the business model of independent creators. Comeau noted that his two existing courses have also seen sales down significantly year-over-year, and other course creators reported revenue drops of 50% or more, with users switching to LLMs that consume their content without compensation.

rss · Simon Willison · Jul 3, 21:25

**Background**: Josh W. Comeau is a respected front-end developer educator known for interactive courses on CSS and React. The rise of large language models (LLMs) like GPT-4 has enabled personalized tutoring without human instructors, while AI-driven automation has sparked fears of job displacement in tech, reducing willingness to invest in skill development.

**Tags**: `#AI Impact`, `#Education`, `#Developer Trends`, `#Online Courses`

---

<a id="item-5"></a>
## [Let AI Models Use Their Own Judgment for Efficiency](https://simonwillison.net/2026/Jul/3/judgement/#atom-everything) ⭐️ 7.0/10

The Claude Code team recommended letting AI models like Fable use their own judgment for tasks such as testing and model selection, rather than dictating specific instructions, to save tokens and improve efficiency. Simon Willison successfully implemented this by prompting Claude Code to delegate coding tasks to subagents with appropriate lower-power models. This practical tip can help developers significantly reduce token usage and costs when using advanced AI coding assistants like Claude Code, especially as pricing changes loom. It also demonstrates a shift towards more autonomous AI workflows where models manage their own resource allocation. The prompt used was "For all coding tasks use your judgement to decide an appropriate lower power model and run that in a subagent". Claude Code stored this as a memory file, delegating to Sonnet for substantive implementation and Haiku for trivial edits, while keeping judgment-heavy tasks in the main model.

rss · Simon Willison · Jul 3, 18:51

**Background**: Claude Fable 5 is Anthropic's most capable model for ambitious coding projects, but it is expensive and token-intensive. Claude Code is an AI agent that can read codebases, edit files, and run commands. The tip leverages subagents with lower-power models like Sonnet and Haiku to handle routine coding tasks, preserving Fable tokens for high-level judgment and review.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://docs.anthropic.com/en/docs/claude-code/overview">Claude Code overview - Anthropic</a></li>

</ul>
</details>

**Tags**: `#AI`, `#prompt engineering`, `#Claude Code`, `#software engineering`

---