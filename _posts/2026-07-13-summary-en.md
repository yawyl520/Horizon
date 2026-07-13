---
layout: default
title: "Horizon Summary: 2026-07-13 (EN)"
date: 2026-07-13
lang: en
---

> From 14 items, 3 important content pieces were selected

---

1. [Math.tanh in Chromium 148 Enables OS Fingerprinting](#item-1) ⭐️ 8.0/10
2. [Proposal to Flag AI-Generated Articles on HN](#item-2) ⭐️ 8.0/10
3. [Why AI Agents Cannot Be Directly Responsible Individuals](#item-3) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Math.tanh in Chromium 148 Enables OS Fingerprinting](https://scrapfly.dev/posts/browser-math-os-fingerprint/) ⭐️ 8.0/10

Chromium 148 changed V8's Math.tanh implementation to use the operating system's native math library, causing slight differences in results across Linux, macOS, and Windows. This allows websites to fingerprint the underlying OS via a single JavaScript call. This adds a novel, persistent fingerprinting vector that is harder to block than traditional methods like canvas or WebGL. It undermines privacy protections and can expose mismatches between the claimed User-Agent and the actual OS. The difference lies in the last bits of the floating-point result for certain inputs, due to variations in the OS math library's tanh implementation. Browser version ranges can also be inferred, making it a more fine-grained tracking signal.

hackernews · joahnn_s · Jul 12, 21:12 · [Discussion](https://news.ycombinator.com/item?id=48884853)

**Background**: Browser fingerprinting collects device and browser characteristics to identify users without cookies. Prior techniques include canvas fingerprinting, WebGL, and font enumeration. Math.tanh fingerprinting is new because it relies on OS-level math library differences, which are harder to spoof.

<details><summary>References</summary>
<ul>
<li><a href="https://geekhaus.club/feed/2026/07/12/chrome-s-switch-to-os-native-math-tanh-exposes-a">Chrome's switch to OS-native Math.tanh exposes a subtle JavaScript ...</a></li>
<li><a href="https://asibiont.com/en/blog/since-chromium-148-math-tanh-teper-mozhno-ispolzovat-dlya-privyazki-k-os-chto-eto-znachit-dlya-veb-razrabotchikov">Chromium 148: How Math .tanh Became a Fingerprinting Tool That...</a></li>
<li><a href="https://hacknjill.com/cybersecurity/since-chronium-148-math-tanh-is-now-fingerprintable-to-link-underlying-os/">Since Chronium 148, Math .tanh Is Now Fingerprintable To... - Hack'n Jill</a></li>

</ul>
</details>

**Discussion**: Commenters note that this technique can also detect browser version ranges and that correctly rounded transcendental functions would eliminate such discrepancies. Some criticize the article's motives, suggesting scraping companies profit from fingerprinting vulnerabilities, while others see it as a call for better privacy measures.

**Tags**: `#browser fingerprinting`, `#privacy`, `#chromium`, `#math functions`, `#security`

---

<a id="item-2"></a>
## [Proposal to Flag AI-Generated Articles on HN](https://news.ycombinator.com/item?id=48886741) ⭐️ 8.0/10

A user proposed adding a flag for AI-generated articles on Hacker News, sparking community debate about enforcement and false positives. This proposal highlights the challenge platforms face in moderating AI-generated content and balancing transparency with potential harm from false accusations. Moderator dang noted that HN already bans AI-generated text in comments but has no rule for articles; he observed the community discounts such content sharply.

hackernews · levkk · Jul 13, 01:24

**Background**: Hacker News is a social news website focusing on computer science and entrepreneurship. Users submit links and comment. The community has norms against low-quality content, and AI-generated text often raises concerns about authenticity and quality.

**Discussion**: Comments were mixed: some supported the idea to avoid AI content, while others worried about false positives and bad-faith accusations. A moderator confirmed existing rules against AI-generated text on HN itself but noted difficulty in enforcement for external articles.

**Tags**: `#AI`, `#Hacker News`, `#content moderation`, `#community discussion`, `#platform governance`

---

<a id="item-3"></a>
## [Why AI Agents Cannot Be Directly Responsible Individuals](https://simonwillison.net/2026/Jul/12/directly-responsible-individuals/#atom-everything) ⭐️ 7.0/10

Simon Willison argues that AI agents should never be considered Directly Responsible Individuals (DRI) because they cannot take accountability, citing the GitLab handbook definition and IBM's 1979 training slide that states a computer must never make a management decision. This argument is significant for organizations integrating AI agents, as it clarifies that accountability and management responsibility must remain with humans, preventing misuse of AI in decision-making roles. The term DRI originated at Apple and is defined in the GitLab handbook as the person ultimately accountable for a project's success or failure. Willison emphasizes that machines cannot be held accountable, echoing IBM's 1979 principle.

rss · Simon Willison · Jul 12, 23:57

**Background**: Directly Responsible Individuals (DRI) is a concept popularized at companies like Apple and GitLab, where one person is designated as ultimately responsible for a project or decision. This ensures clear accountability. The author references IBM's 1979 training slide, which states 'A computer can never be held accountable, therefore a computer must never make a management decision,' highlighting a long-standing principle in computing ethics.

<details><summary>References</summary>
<ul>
<li><a href="https://handbook.gitlab.com/handbook/people-group/directly-responsible-individuals/">Directly Responsible Individuals ( DRI ) | The GitLab Handbook</a></li>
<li><a href="https://tettra.com/article/directly-responsible-individuals-guide/">Directly Responsible Individuals : The What, How and Why of DRIs</a></li>

</ul>
</details>

**Tags**: `#DRI`, `#accountability`, `#AI agents`, `#human-machine interaction`, `#GitLab handbook`

---