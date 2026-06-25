---
layout: default
title: "Horizon Summary: 2026-06-25 (EN)"
date: 2026-06-25
lang: en
---

> From 22 items, 4 important content pieces were selected

---

1. [OpenAI unveils first custom chip 'Jalapeno' with Broadcom](#item-1) ⭐️ 9.0/10
2. [Qualcomm Acquires AI Compiler Startup Modular](#item-2) ⭐️ 8.0/10
3. [SQLite Database of Browser Compat Data from Mozilla](#item-3) ⭐️ 7.0/10
4. [Tom MacWright Criticizes LLM-Generated Job Applications](#item-4) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [OpenAI unveils first custom chip 'Jalapeno' with Broadcom](https://techcrunch.com/2026/06/24/openai-unveils-its-first-custom-chip-built-by-broadcom/) ⭐️ 9.0/10

OpenAI and Broadcom unveiled Jalapeño, the company's first custom-built inference chip, designed from scratch and manufactured by TSMC. The chip was developed from design to production in nine months, with OpenAI's models accelerating parts of the design process. This marks a major milestone for OpenAI, signaling a strategic shift toward vertical integration in AI hardware to reduce dependence on NVIDIA GPUs and lower inference costs. The move could reshape the AI chip landscape, inspiring other AI companies to follow suit. Jalapeño is specifically designed for inference workloads, optimized for large language models (LLMs) and focused on low operating cost. While OpenAI announced the chip, technical specifications such as performance per watt and transistor count were not disclosed in the initial release.

hackernews · jamdesk · Jun 24, 17:47 · [Discussion](https://news.ycombinator.com/item?id=48663324)

**Background**: Inference chips are specialized processors that run pre-trained AI models to generate responses, as opposed to training chips used to build models. OpenAI previously relied on NVIDIA GPUs and cloud providers for inference; developing its own chip allows OpenAI to optimize hardware-software co-design, potentially achieving better performance and cost efficiency for ChatGPT and other services.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/06/24/openai-unveils-its-first-custom-chip-built-by-broadcom/">OpenAI unveils its first custom chip, built by Broadcom</a></li>
<li><a href="https://openai.com/index/openai-broadcom-jalapeno-inference-chip/">OpenAI and Broadcom unveil LLM-optimized inference chip</a></li>
<li><a href="https://www.cnbc.com/2026/06/24/openai-and-broadcom-reveal-jalapeno-first-ai-chip-in-partnership.html">OpenAI and Broadcom reveal Jalapeno, first AI chip in ... - CNBC OpenAI and Broadcom Unveil LLM-Optimized Intelligence ... Jalapeño Is The First AI Chip From OpenAI And Broadcom Broadcom and OpenAI debut Jalapeño Intelligence Processor ... OpenAI unveils Jalapeño chip for large-scale inference workloads</a></li>

</ul>
</details>

**Discussion**: Comments ranged from skepticism to excitement: some questioned whether OpenAI's use of its own models to accelerate chip design was genuine or marketing fluff, while others confirmed the TSMC fabrication and debated alternative approaches like burning weights into silicon (e.g., Taalas). Overall, the community recognized the move as significant, comparing it to Google's TPU strategy.

**Tags**: `#AI`, `#hardware`, `#OpenAI`, `#chip`, `#inference`

---

<a id="item-2"></a>
## [Qualcomm Acquires AI Compiler Startup Modular](https://www.reuters.com/business/qualcomm-buy-ai-startup-modular-2026-06-24/) ⭐️ 8.0/10

On June 24, 2026, Qualcomm announced the acquisition of Modular, an AI compiler startup known for the Mojo programming language and the MAX platform, aiming to strengthen its AI chip software stack. This acquisition positions Qualcomm to challenge NVIDIA's CUDA dominance in AI inference, especially for ARM-based devices, by providing a portable, high-performance compiler stack. The deal is reportedly valued at $4 billion, and includes Modular's technology such as Mojo—a Python-like language for AI—and the MAX inference platform.

hackernews · timmyd · Jun 24, 13:49 · [Discussion](https://news.ycombinator.com/item?id=48659798)

**Background**: Modular, founded by LLVM creator Chris Lattner, aims to unify AI development across CPUs, GPUs, and other hardware through its compiler and runtime. The company's Mojo language combines Python-like syntax with C-level performance for AI workloads. Qualcomm, a leading designer of ARM-based chips, seeks to expand beyond mobile into AI inference at scale.

<details><summary>References</summary>
<ul>
<li><a href="https://www.modular.com/">Modular: Inference from Kernel to Cloud</a></li>
<li><a href="https://github.com/modular/modular">GitHub - modular/modular: The Modular Platform (includes MAX & Mojo)</a></li>
<li><a href="https://www.modular.com/company/about">Modular: About Us</a></li>

</ul>
</details>

**Discussion**: Community reactions are mixed: some celebrate the potential for Qualcomm ARMv9 chips with Mojo/MAX to provide low-cost AI inference, while others express disappointment that Mojo may not reach its full potential as an independent project. Skeptics question whether the acquisition signals a failure of Modular's original vision.

**Tags**: `#acquisition`, `#AI`, `#compiler`, `#Qualcomm`, `#Modular`

---

<a id="item-3"></a>
## [SQLite Database of Browser Compat Data from Mozilla](https://simonwillison.net/2026/Jun/24/browser-compat-db/#atom-everything) ⭐️ 7.0/10

Simon Willison released a new GitHub repository that converts Mozilla's browser compatibility data into a SQLite database, made accessible via GitHub CDN with open CORS headers. A script using sqlite-utils and a GitHub Actions workflow automate the build and deployment. This tool enables developers to query browser compatibility data locally or via web using SQL, making it easier to integrate into CI/CD pipelines and web applications. It reduces reliance on MDN's online API and works offline. The resulting database is approximately 66MB and is stored on an orphan branch named 'db' in the same repository. It can be explored directly using Datasette Lite, a web-based SQLite explorer.

rss · Simon Willison · Jun 24, 23:59

**Background**: Mozilla's MDN Web Docs maintain a comprehensive dataset of browser compatibility information for web platform features. Simon Willison's project uses sqlite-utils, a Python library for manipulating SQLite databases, and leverages GitHub Actions to automatically rebuild and host the database via GitHub's CDN with permissive CORS headers.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.mozilla.org/en-US/blog/introducing-mdn-mcp-server/">Introducing the MDN MCP server | MDN Blog - MDN Web Docs</a></li>
<li><a href="https://github.com/simonw/sqlite-utils">GitHub - simonw/sqlite-utils: Python CLI utility and library for manipulating SQLite databases · GitHub</a></li>
<li><a href="https://developer.mozilla.org/en-US/mcp">MDN MCP server</a></li>

</ul>
</details>

**Tags**: `#browser compatibility`, `#SQLite`, `#developer tools`, `#open data`

---

<a id="item-4"></a>
## [Tom MacWright Criticizes LLM-Generated Job Applications](https://simonwillison.net/2026/Jun/24/tom-macwright/#atom-everything) ⭐️ 7.0/10

Tom MacWright observed a rise in job applications that are clearly co-written by LLMs, making candidates indistinguishable and impersonal. This trend undermines authenticity in hiring, making it harder for employers to assess genuine candidate skills and fit. It raises ethical questions about AI use in careers. MacWright notes that such applications include LLM-generated portfolios, GitHub projects, and commit messages, providing no real insight into the candidate.

rss · Simon Willison · Jun 24, 18:13

**Background**: Large Language Models (LLMs) like GPT-4 can generate text for resumes and portfolios. Over-reliance on LLMs removes personal voice and authenticity, a concern growing as AI tools become more prevalent in professional contexts.

**Tags**: `#ai`, `#careers`, `#ethics`, `#hiring`, `#authenticity`

---