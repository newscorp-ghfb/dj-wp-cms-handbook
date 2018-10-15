---
page: markup
title: Markup
nav: Markup
group: navigation
weight: 4
layout: default
---

<div class="docs-section">
		{% capture markup %}{% include markdown/Markup.md %}{% endcapture %}
		{{ markup | markdownify }}
</div>