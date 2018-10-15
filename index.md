---
page: introduction
title: Introduction
nav: Home
group: navigation
weight: 1
layout: default
subnav:
  - title: Audience
    tag: audience
  - title: Goal
    tag: goal
  - title: Philosophy
    tag: philosophy
  - title: Contributing
    tag: contributing
updated: 15 Oct 2018
---

<div class="toc">
	<header>
		<h2>Table of Contents</h2>
	</header>

  <div class="col">
    <h3><a href="{{ site.baseurl }}#top">Introduction</a></h3>
    <ul>
      <li><a href="{{ site.baseurl }}/#audience">Audience</a></li>
      <li><a href="{{ site.baseurl }}/#goal">Goal</a></li>
      <li><a href="{{ site.baseurl }}/#philosophy">Philosophy</a></li>
      <li><a href="{{ site.baseurl }}/#contributing">Contributing</a></li>
    </ul>
  </div>

  <div class="col">
    <h3><a href="{{ site.baseurl }}/projects/#top">Projects</a></h3>
    <ul>
    <li><a href="{{ site.baseurl }}/projects/#projects-overview">Overview</a></li>
    <li><a href="{{ site.baseurl }}/projects/#active-projects">Active Projects</a></li>
    </ul>
  </div>

  <div class="col">
    <h3><a href="{{ site.baseurl }}/tools/#top">Tools</a></h3>
    <ul>
    <li><a href="{{ site.baseurl }}/projects/#local-development">Local Development</a></li>
    <li><a href="{{ site.baseurl }}/projects/#documentation">Documentation</a></li>
    <li><a href="{{ site.baseurl }}/projects/#plugin-boilerplate">Plugin Boilerplate</a></li>
    <li><a href="{{ site.baseurl }}/projects/#theme-boilerplate">Theme Boilerplate</a></li>
    </ul>
  </div>



  <div class="col">

  </div>

</div>

<div class="docs-section">
		{% capture introduction %}{% include markdown/Introduction.md %}{% endcapture %}
		{{ introduction | markdownify }}
</div>
