---
layout: default
title: "Horizon Summary: 2026-06-16 (EN)"
date: 2026-06-16
lang: en
---

> From 27 items, 3 important content pieces were selected

---

1. [Backdoor in LinkedIn Job Offer Exploits npm Prepare Script](#item-1) ⭐️ 9.0/10
2. [Qwable-v1: Open Weights from Claude Fable-5 Distillation](#item-2) ⭐️ 9.0/10
3. [Personality clashes at Anthropic take models offline amid export control dispute](#item-3) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Backdoor in LinkedIn Job Offer Exploits npm Prepare Script](https://roman.pt/posts/linkedin-backdoor/) ⭐️ 9.0/10

A job applicant discovered a backdoor hidden in a GitHub repository sent by a recruiter during a job application process, which exploited npm's prepare script to execute arbitrary code upon running npm install. This attack combines social engineering with a supply chain vulnerability, highlighting a dangerous vector that targets developers directly. It underscores the need for stronger security measures in recruitment processes and npm ecosystem defenses. The recruiter asked the applicant to review a GitHub repo for a 'broken proof-of-concept', and the backdoor was hidden within commented-out tests. The prepare script automatically runs after npm install, executing the payload without user intervention.

hackernews · lwhsiao · Jun 15, 20:00 · [Discussion](https://news.ycombinator.com/item?id=48546294)

**Background**: npm lifecycle scripts like prepare, preinstall, and postinstall run automatically during package installation, making them a common vector for supply chain attacks. GitHub has announced that npm v12 will disable install scripts by default to mitigate such risks. The npm ecosystem's reliance on these scripts has been criticized for enabling attacks like this one.

<details><summary>References</summary>
<ul>
<li><a href="https://github.blog/changelog/2026-06-09-upcoming-breaking-changes-for-npm-v12/">Upcoming breaking changes for npm v12 - GitHub Changelog</a></li>
<li><a href="https://thehackernews.com/2026/06/github-to-disable-npm-install-scripts.html">GitHub to Disable npm Install Scripts by Default to Stop Supply Chain ...</a></li>
<li><a href="https://shipwithai.io/blog/npm-install-security-30-seconds/">The 30-Second npm Defense Every Vibe Coder Needs — ShipWithAI</a></li>

</ul>
</details>

**Discussion**: Commenters expressed frustration that GitHub and LinkedIn did not act on the report, with one noting that such attacks have been occurring for years. Some criticized the npm ecosystem itself, questioning why developers still use it given these vulnerabilities. Others called for better cybercrime reporting mechanisms.

**Tags**: `#security`, `#npm`, `#social engineering`, `#supply chain attack`, `#recruitment`

---

<a id="item-2"></a>
## [Qwable-v1: Open Weights from Claude Fable-5 Distillation](https://www.reddit.com/r/LocalLLaMA/comments/1u6zj79/claude_fable_5_distilled/) ⭐️ 9.0/10

Researchers released Qwable-v1, an open-weights model distilled from Anthropic's short-lived Fable-5 model using only 4,659 agentic-coding traces that survived anti-distillation filters. This is the first open-weight distillation of Fable-5, capturing its powerful tool-use capabilities, which could accelerate open-source AI agent development and make advanced agentic coding more accessible. The model is based on Qwen3.6-35B-A3B, trained for 14 hours on a single H200, and includes GGUF quantizations (IQ4_XS, Q4_K_M, Q5_K_M, Q8_0), all publicly available on Hugging Face under AGPL-3.0.

reddit · r/LocalLLaMA · /u/Anony6666 · Jun 16, 01:21

**Background**: Model distillation is a technique where a smaller student model is trained to mimic a larger teacher model's outputs. Claude's Fable-5 was a powerful but short-lived model that had anti-distillation classifiers to prevent such copying. The Qwable-v1 project used traces that bypassed these classifiers, and fine-tuned on a Qwen-based architecture.

<details><summary>References</summary>
<ul>
<li><a href="https://platform.claude.com/docs/en/agents-and-tools/tool-use/text-editor-tool">Text editor tool - Claude API Docs</a></li>
<li><a href="https://www.modemguides.com/blogs/ai-news/claude-code-leak-architecture-analysis">Claude Code Leak: Anti - Distillation , Undercover Mode, and...</a></li>

</ul>
</details>

**Tags**: `#open-source LLM`, `#model distillation`, `#Claude Fable-5`, `#AI research`, `#agentic coding`

---

<a id="item-3"></a>
## [Personality clashes at Anthropic take models offline amid export control dispute](https://simonwillison.net/2026/Jun/15/axios-clashes-anthropics/#atom-everything) ⭐️ 7.0/10

Axios reports that internal personality clashes at Anthropic led to its AI models going offline, as tensions with the U.S. government over export controls escalate. Key figures including Frontier Red Team lead Logan Graham are meeting with the Commerce Department to address the situation. This highlights the growing friction between AI companies and government regulators, particularly around export controls and jailbreak vulnerabilities. The fate of Anthropic's advanced models like Mythos and Fable hinges on resolving both technical and interpersonal issues. The article cites anonymous sources familiar with the administration and Anthropic, and notes that perfect jailbreak resistance may be impossible. Anthropic's Constitutional Classifiers work is relevant to the jailbreak that triggered the government response, which was classified as a 'potential narrow, non-universal jailbreak'.

rss · Simon Willison · Jun 15, 14:57

**Background**: Anthropic, a leading AI safety company, has developed advanced models like Mythos (its most capable but not publicly released) and Fable (a public Mythos-class model). The U.S. government recently ordered suspension of access to certain models due to export control concerns and potential jailbreak exploits. The Frontier Red Team at Anthropic is responsible for evaluating and publicizing model vulnerabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://www.bloomberg.com/news/articles/2026-04-20/anthropic-s-mythos-ai-model-questions-answered">Anthropic 's Mythos AI Model , Questions Answered - Bloomberg</a></li>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://fortune.com/2025/09/04/anthropic-red-team-pushes-ai-models-into-the-danger-zone-and-burnishes-companys-reputation-for-safety/">Anthropic’s ‘ Red Team ’ pushes its AI models into the danger... | Fortune</a></li>

</ul>
</details>

**Tags**: `#AI`, `#government regulation`, `#Anthropic`, `#export controls`, `#AI safety`

---