---
layout: default
title: "Horizon Summary: 2026-06-21 (EN)"
date: 2026-06-21
lang: en
---

> From 13 items, 2 important content pieces were selected

---

1. [SMPTE Opens Its Standards Library to All](#item-1) ⭐️ 9.0/10
2. [Loupe iOS App Exposes Data Accessible to Native Apps Without Permissions](#item-2) ⭐️ 8.0/10

---

<a id="item-1"></a>
## [SMPTE Opens Its Standards Library to All](https://www.smpte.org/blog/smpte-makes-its-standards-freely-accessible-openingstandards-library-to-the-global-media-technology-community) ⭐️ 9.0/10

SMPTE has announced that all its technical standards are now freely accessible to anyone, removing the previous paywall on its standards library. This move lowers barriers to innovation in media technology, enabling wider adoption and faster development of interoperable systems across broadcast, cinema, and streaming industries. The transition includes adopting GitHub-based workflows, HTML-based authoring, and an integrated publishing pipeline to streamline standards development and maintenance.

hackernews · zdw · Jun 20, 17:01 · [Discussion](https://news.ycombinator.com/item?id=48610827)

**Background**: SMPTE (Society of Motion Picture and Television Engineers) is a global standards body founded in 1916, responsible for over 800 standards including SMPTE timecode and digital cinema specifications. Previously, accessing these standards required purchasing individual documents or membership subscriptions.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/SMPTE">SMPTE</a></li>
<li><a href="https://en.wikipedia.org/wiki/Society_of_Motion_Picture_and_Television_Engineers">Society of Motion Picture and Television Engineers - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The community overwhelmingly supports the move, with commenters noting it aligns with the success of open IETF standards. Some recall paying hundreds of dollars for standards in the past, while others question why this wasn't the default.

**Tags**: `#standards`, `#open-access`, `#SMPTE`, `#media-technology`, `#video-codecs`

---

<a id="item-2"></a>
## [Loupe iOS App Exposes Data Accessible to Native Apps Without Permissions](https://github.com/mysk-research/loupe) ⭐️ 8.0/10

Loupe is a new iOS and iPadOS app from security research team Mysk that shows users what device data native apps can access without requiring any permissions, including setup date, volume creation time, and installed apps list. This app raises critical privacy awareness by demonstrating how apps can perform device fingerprinting using data that is freely available through public iOS APIs, revealing a significant privacy gap that affects all iOS users. Loupe reads real values from public iOS APIs, the same ones any third-party app can call, and displays them in categories: passive, permission, and advanced. It is available on GitHub and the App Store.

hackernews · Cider9986 · Jun 20, 12:08 · [Discussion](https://news.ycombinator.com/item?id=48608645)

**Background**: Device fingerprinting is a technique where apps collect small, ordinary details about a device to create a unique identifier, often used for tracking users across apps without consent. On iOS, third-party apps can access certain data like device name, system uptime, and installed apps list without requiring explicit user permission, because these are not considered sensitive by the operating system.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/mysk-research/loupe">GitHub - mysk-research/loupe: A privacy-focused iOS app that raises awareness about what native apps can see · GitHub</a></li>
<li><a href="https://apps.apple.com/us/app/loupe-what-apps-can-see/id6766152470">Loupe: What Apps Can See App - App Store</a></li>

</ul>
</details>

**Discussion**: Commenters expressed shock at specific data points like the exact setup time and volume creation date, calling them 'nasty' and 'egregious'. Some noted that Loupe's categorization helps make privacy risks understandable, while others compared iOS unfavorably to Android in certain areas.

**Tags**: `#privacy`, `#iOS`, `#security`, `#app development`, `#data access`

---