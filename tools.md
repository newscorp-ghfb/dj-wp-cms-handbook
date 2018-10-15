---
page: tools
title: Tools
nav: Tools
group: navigation
weight: 2
layout: default
subnav:
  - title: Local Development
    tag: local-development
  - title: Documentation
    tag: documentation
  - title: Plugin Boilerplate
    tag: plugin-boilerplate
  - title: Theme Boilerplate
    tag: theme-boilerplate
updated: 15 Oct 2018
---

<div class="docs-section">
		{% capture tools %}{% include markdown/Tools.md %}{% endcapture %}
		{{ tools | markdownify }}
</div>