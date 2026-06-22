---
layout: default
title: "Horizon Summary: 2026-06-22 (EN)"
date: 2026-06-22
lang: en
---

> From 12 items, 5 important content pieces were selected

---

1. [Reflecting on fraud-built tech roles](#item-1) ⭐️ 8.0/10
2. [Apertus: Open Foundation Model for AI Sovereignty](#item-2) ⭐️ 8.0/10
3. [Samsung deploys ChatGPT Enterprise and Codex to employees](#item-3) ⭐️ 8.0/10
4. [sqlite-utils 4.0rc1 released with migrations and nested transactions](#item-4) ⭐️ 8.0/10
5. [Cloudflare Introduces Temporary Workers Deployments](#item-5) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Reflecting on fraud-built tech roles](https://david.newgas.net/did-my-old-job-only-exist-because-of-fraud/) ⭐️ 8.0/10

David Newgas's reflective article questions whether certain tech jobs exist solely due to fraud, supported by community anecdotes of billing scams and wasteful projects. This matters because it exposes systemic ethical issues in tech and corporate culture, impacting software engineers' sense of meaningful work and prompting conversation about fraud in job creation. The discussion includes patterns of contractors being rehired through outsourcing at higher costs, fraudulent billing on government projects, and companies operating at a loss for tax benefits.

hackernews · advisedwang · Jun 21, 21:40 · [Discussion](https://news.ycombinator.com/item?id=48622867)

**Background**: The article is a personal blog post that uses the provocative question to examine how some tech positions may exist due to unethical practices rather than genuine business need. Community comments provide real-world examples, such as billing padding and empire-building by management.

**Discussion**: Community comments show high engagement with diverse anecdotes. Key viewpoints include observations of contractor rehiring at inflated costs via outsourcing, fraudulent billing in government projects, and suspicion that some companies are run at a loss for tax purposes. Sentiments range from shock to resignation.

**Tags**: `#corporate fraud`, `#tech ethics`, `#software engineering`, `#organizational culture`, `#professional ethics`

---

<a id="item-2"></a>
## [Apertus: Open Foundation Model for AI Sovereignty](https://apertvs.ai/) ⭐️ 8.0/10

Apertus, a fully open, transparent, and multilingual foundation model developed by ETH Zurich, has been released to promote AI sovereignty. It is among the few fully open LLMs at this scale. Apertus addresses the growing demand for AI sovereignty, enabling nations and organizations to control their AI infrastructure without relying on dominant US tech companies. Its openness could foster innovation, competition, and trust in AI systems globally. The model includes full training pipelines and datasets, emphasizing multilingualism and compliance with data protection. Its license requires careful handling of personal data, designating users as independent controllers.

hackernews · T-A · Jun 21, 21:29 · [Discussion](https://news.ycombinator.com/item?id=48622778)

**Background**: Foundation models are large AI models trained on vast datasets that can be adapted for a wide range of tasks. AI sovereignty refers to a nation's or organization's ability to control its AI technology stack, including data, models, and infrastructure. Apertus is an initiative to provide a fully open alternative to proprietary models, aiming to empower regions outside the US to achieve AI self-sufficiency.

<details><summary>References</summary>
<ul>
<li><a href="https://ethz.ch/en/news-and-events/eth-news/news/2025/09/press-release-apertus-a-fully-open-transparent-multilingual-language-model.html">Apertus: a fully open, transparent, multilingual language model | ETH Zurich</a></li>
<li><a href="https://www.ibm.com/think/topics/ai-sovereignty">What is AI Sovereignty? | IBM</a></li>
<li><a href="https://news.ycombinator.com/item?id=48622778">Apertus – Open Foundation Model for Sovereign AI | Hacker News</a></li>

</ul>
</details>

**Discussion**: Community comments express cautious optimism but doubt about Apertus's competitiveness and pace, comparing it to other fully open LLMs like OLMo, K2, and Nemotron. Some see the initiative as a necessary step for sovereignty, while others note that Chinese open models may be more promising.

**Tags**: `#open source`, `#AI sovereignty`, `#foundation models`, `#LLMs`

---

<a id="item-3"></a>
## [Samsung deploys ChatGPT Enterprise and Codex to employees](https://openai.com/index/samsung-electronics-chatgpt-codex-deployment) ⭐️ 8.0/10

Samsung Electronics is deploying OpenAI's ChatGPT Enterprise and Codex to employees worldwide, marking one of the largest enterprise AI rollouts by OpenAI. This signals a major shift toward widespread adoption of generative AI in corporate environments, potentially boosting developer productivity and enterprise efficiency across Samsung's global workforce. ChatGPT Enterprise offers enterprise-grade security, unlimited GPT-4 access, and advanced data analysis, while Codex automates software engineering tasks from pull requests to complex refactors.

rss · OpenAI Blog · Jun 21, 23:00

**Background**: ChatGPT Enterprise is OpenAI's business-tier version of ChatGPT designed for organizations, with enhanced privacy and data integration. Codex is an AI coding agent that translates natural language into code and automates development workflows. This deployment reflects growing enterprise interest in AI tools to improve productivity.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/introducing-chatgpt-enterprise/">Introducing ChatGPT Enterprise | OpenAI</a></li>
<li><a href="https://openai.com/codex/">Codex | AI Coding Partner from OpenAI</a></li>
<li><a href="https://openai.com/index/openai-codex/">OpenAI Codex</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Enterprise`, `#ChatGPT`, `#Codex`, `#Samsung`

---

<a id="item-4"></a>
## [sqlite-utils 4.0rc1 released with migrations and nested transactions](https://simonwillison.net/2026/Jun/21/sqlite-utils/#atom-everything) ⭐️ 8.0/10

The first release candidate for sqlite-utils 4.0 introduces built-in support for database migrations and nested transactions, porting the sqlite-migrate package into the core library. This marks a significant evolution for a widely-used Python SQLite tool, providing users with a native migration system and nested transaction capabilities that simplify schema management and complex database workflows. The migration system does not support reverse migrations, so errors must be corrected with new forward migrations. Nested transactions are also a new feature in this release candidate.

rss · Simon Willison · Jun 21, 23:30

**Background**: sqlite-utils is a Python library and CLI tool that provides higher-level operations on top of the standard sqlite3 module, such as table transformations and automatic schema creation from JSON. Database migrations allow incremental, version-controlled changes to a database schema, ensuring consistency and traceability. Nested transactions enable a transaction to be started within an existing transaction, useful for modular application components.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Nested_transaction">Nested transaction</a></li>
<li><a href="https://en.wikipedia.org/wiki/Database_migration">Database migration</a></li>

</ul>
</details>

**Tags**: `#sqlite-utils`, `#SQLite`, `#Python`, `#migrations`, `#transactions`

---

<a id="item-5"></a>
## [Cloudflare Introduces Temporary Workers Deployments](https://simonwillison.net/2026/Jun/21/temporary-cloudflare-accounts/#atom-everything) ⭐️ 7.0/10

Cloudflare now allows developers to deploy Workers projects for 60 minutes without creating an account, using the `npx wrangler deploy --temporary` command. This feature lowers the barrier for testing and prototyping serverless applications, particularly for AI agents that need ephemeral deployments, but is useful for all developers. The temporary deployment provides a unique URL and a claim page allowing the project to be converted to a permanent account within 60 minutes; the claimed project retains all resources.

rss · Simon Willison · Jun 21, 22:01

**Background**: Cloudflare Workers is a serverless computing platform that runs code at the edge in over 330 cities. Wrangler is the official CLI for building and deploying Workers projects. Previously, deploying required a Cloudflare account; the new --temporary flag removes that requirement for quick experiments.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cloudflare.com/products/workers/">Cloudflare Workers - Global Serverless Functions Platform</a></li>
<li><a href="https://developers.cloudflare.com/workers/wrangler/">Wrangler · Cloudflare Workers docs</a></li>

</ul>
</details>

**Tags**: `#Cloudflare`, `#serverless`, `#developer tools`, `#AI`, `#ephemeral`

---