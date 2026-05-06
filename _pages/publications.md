---
layout: page
permalink: /publications/
title: research
description: Publications, working papers, and ongoing projects.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<div class="publications">

<h2 class="category">Publications</h2>

{% bibliography -q @*[category=publications] %}

<h2 class="category">Working papers</h2>

{% bibliography -q @*[category=working_papers] %}

<h2 class="category">Work in progress</h2>

{% bibliography -q @*[category=work_in_progress] %}

</div>
