---
layout: default
title: "Horizon Summary: 2026-06-21 (ZH)"
date: 2026-06-21
lang: zh
---

> 从 13 条内容中筛选出 2 条重要资讯。

---

1. [SMPTE 向全球开放其标准库](#item-1) ⭐️ 9.0/10
2. [Loupe iOS 应用揭示原生应用无需权限即可访问的数据](#item-2) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [SMPTE 向全球开放其标准库](https://www.smpte.org/blog/smpte-makes-its-standards-freely-accessible-openingstandards-library-to-the-global-media-technology-community) ⭐️ 9.0/10

SMPTE 宣布其所有技术标准现已向所有人免费开放，取消了此前标准库的付费墙。 此举降低了媒体技术创新的门槛，促进了广播、电影和流媒体行业互操作系统的广泛采用和更快发展。 这一转变包括采用基于 GitHub 的工作流、基于 HTML 的编写以及集成发布管道，以简化标准的开发和维护。

hackernews · zdw · 6月20日 17:01 · [社区讨论](https://news.ycombinator.com/item?id=48610827)

**背景**: SMPTE（电影电视工程师协会）是一个全球性标准组织，成立于 1916 年，负责制定超过 800 项标准，包括 SMPTE 时间码和数字影院规范。此前，获取这些标准需要购买单个文档或订阅会员。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/SMPTE">SMPTE</a></li>
<li><a href="https://en.wikipedia.org/wiki/Society_of_Motion_Picture_and_Television_Engineers">Society of Motion Picture and Television Engineers - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区压倒性地支持这一举措，评论者指出这与开放 IETF 标准的成功相一致。有人回忆起过去曾为标准支付数百美元，也有人质疑为什么这并非默认做法。

**标签**: `#standards`, `#open-access`, `#SMPTE`, `#media-technology`, `#video-codecs`

---

<a id="item-2"></a>
## [Loupe iOS 应用揭示原生应用无需权限即可访问的数据](https://github.com/mysk-research/loupe) ⭐️ 8.0/10

Loupe 是安全研究团队 Mysk 推出的一款全新 iOS 和 iPadOS 应用，它向用户展示原生应用无需任何权限即可访问的设备数据，包括设置日期、卷创建时间和已安装应用列表。 该应用通过演示应用如何利用通过公共 iOS API 免费获得的数据进行设备指纹识别，提高了关键的隐私意识，揭示了影响所有 iOS 用户的重大隐私漏洞。 Loupe 从公共 iOS API 读取真实值（任何第三方应用都可以调用这些 API），并按“被动”、“权限”和“高级”分类显示。该应用可在 GitHub 和 App Store 上获取。

hackernews · Cider9986 · 6月20日 12:08 · [社区讨论](https://news.ycombinator.com/item?id=48608645)

**背景**: 设备指纹识别是一种技术，应用通过收集设备的小细节来创建唯一标识符，常用于未经用户同意跨应用跟踪用户。在 iOS 上，第三方应用可以访问设备名称、系统运行时间和已安装应用列表等数据，而无需明确用户许可，因为这些数据不被操作系统视为敏感信息。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/mysk-research/loupe">GitHub - mysk-research/loupe: A privacy-focused iOS app that raises awareness about what native apps can see · GitHub</a></li>
<li><a href="https://apps.apple.com/us/app/loupe-what-apps-can-see/id6766152470">Loupe: What Apps Can See App - App Store</a></li>

</ul>
</details>

**社区讨论**: 评论者对具体数据点（如精确的设置时间和卷创建日期）表示震惊，称其“恶劣”和“过分”。一些人指出 Loupe 的分类有助于理解隐私风险，另一些人则在某些方面将 iOS 与 Android 进行了不利比较。

**标签**: `#privacy`, `#iOS`, `#security`, `#app development`, `#data access`

---