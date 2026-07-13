---
layout: default
title: "Horizon Summary: 2026-07-13 (ZH)"
date: 2026-07-13
lang: zh
---

> 从 14 条内容中筛选出 3 条重要资讯。

---

1. [Chromium 148 中 Math.tanh 可用于 OS 指纹识别](#item-1) ⭐️ 8.0/10
2. [提议在 HN 上标记 AI 生成的文章](#item-2) ⭐️ 8.0/10
3. [为何 AI 代理不能作为直接负责人](#item-3) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Chromium 148 中 Math.tanh 可用于 OS 指纹识别](https://scrapfly.dev/posts/browser-math-os-fingerprint/) ⭐️ 8.0/10

Chromium 148 将 V8 的 Math.tanh 实现改为使用操作系统的原生数学库，导致在不同操作系统（Linux、macOS、Windows）上计算结果出现微小差异。网站可以通过一次 JavaScript 调用推断底层操作系统。 这增加了一种新颖且持久的指纹识别手段，比传统的 canvas 或 WebGL 方法更难阻止。它破坏了隐私保护机制，并能揭示声明的 User-Agent 与实际操作系统之间的不匹配。 差异源于某些输入下浮点结果的最后几位，原因是不同操作系统的数学库在 tanh 实现上有所不同。还可以推断浏览器版本范围，使其成为更细粒度的追踪信号。

hackernews · joahnn_s · 7月12日 21:12 · [社区讨论](https://news.ycombinator.com/item?id=48884853)

**背景**: 浏览器指纹识别收集设备和浏览器特征来识别用户，无需使用 Cookie。此前的方法包括 canvas 指纹识别、WebGL 和字体枚举。Math.tanh 指纹识别是新的，因为它依赖于操作系统级别的数学库差异，更难以伪造。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://geekhaus.club/feed/2026/07/12/chrome-s-switch-to-os-native-math-tanh-exposes-a">Chrome's switch to OS-native Math.tanh exposes a subtle JavaScript ...</a></li>
<li><a href="https://asibiont.com/en/blog/since-chromium-148-math-tanh-teper-mozhno-ispolzovat-dlya-privyazki-k-os-chto-eto-znachit-dlya-veb-razrabotchikov">Chromium 148: How Math .tanh Became a Fingerprinting Tool That...</a></li>
<li><a href="https://hacknjill.com/cybersecurity/since-chronium-148-math-tanh-is-now-fingerprintable-to-link-underlying-os/">Since Chronium 148, Math .tanh Is Now Fingerprintable To... - Hack'n Jill</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，这种技术还能检测浏览器版本范围，而正确舍入的超越函数可以消除此类差异。有人批评该文章的动机，认为爬虫公司从指纹识别漏洞中获利，而另一些人则视其为呼吁更好的隐私保护措施。

**标签**: `#browser fingerprinting`, `#privacy`, `#chromium`, `#math functions`, `#security`

---

<a id="item-2"></a>
## [提议在 HN 上标记 AI 生成的文章](https://news.ycombinator.com/item?id=48886741) ⭐️ 8.0/10

一位用户提议在 Hacker News 上增加对 AI 生成文章的标记功能，引发了关于执行和误报的社区讨论。 该提案突显了平台在审核 AI 生成内容时面临的挑战，以及需要在透明度与误报可能造成的伤害之间取得平衡。 版主 dang 指出 HN 已在评论中禁止 AI 生成文本，但对文章尚无规定；他观察到社区对此类内容严重打折。

hackernews · levkk · 7月13日 01:24

**背景**: Hacker News 是一个专注于计算机科学和创业的社交新闻网站。用户提交链接并评论。社区有反对低质量内容的规范，AI 生成的文本常常引发对真实性和质量的担忧。

**社区讨论**: 评论观点不一：一些人支持该想法以避免 AI 内容，而另一些人则担心误报和恶意指控。版主确认了 HN 自身已有禁止 AI 生成文本的规定，但指出对外部文章执行困难。

**标签**: `#AI`, `#Hacker News`, `#content moderation`, `#community discussion`, `#platform governance`

---

<a id="item-3"></a>
## [为何 AI 代理不能作为直接负责人](https://simonwillison.net/2026/Jul/12/directly-responsible-individuals/#atom-everything) ⭐️ 7.0/10

Simon Willison 认为 AI 代理绝不应被视为直接负责人（DRI），因为它们无法承担责任，他引用了 GitLab 手册的定义以及 IBM 1979 年培训幻灯片中的观点：计算机绝不能做出管理决策。 这一论点对于正在整合 AI 代理的组织具有重要意义，它明确了问责制和管理责任必须由人类承担，防止 AI 在决策角色中被滥用。 DRI 一词源于苹果公司，在 GitLab 手册中定义为对项目成败最终负责的个人。Willison 强调机器无法被问责，呼应了 IBM 1979 年的原则。

rss · Simon Willison · 7月12日 23:57

**背景**: 直接负责人（DRI）是一个在苹果和 GitLab 等公司流行的概念，指定一个人对项目或决策最终负责，以确保清晰的问责。作者引用了 IBM 1979 年的培训幻灯片，其中写道‘计算机永远不能被问责，因此计算机绝不能做出管理决策’，这凸显了计算机伦理中的一个长期原则。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://handbook.gitlab.com/handbook/people-group/directly-responsible-individuals/">Directly Responsible Individuals ( DRI ) | The GitLab Handbook</a></li>
<li><a href="https://tettra.com/article/directly-responsible-individuals-guide/">Directly Responsible Individuals : The What, How and Why of DRIs</a></li>

</ul>
</details>

**标签**: `#DRI`, `#accountability`, `#AI agents`, `#human-machine interaction`, `#GitLab handbook`

---