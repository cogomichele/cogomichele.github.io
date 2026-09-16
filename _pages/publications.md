---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->

<h2 class="bibliography-section">Peer-reviewed journal articles</h2>
<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} -q @article %}

</div>

<h2 class="bibliography-section">Conference proceedings</h2>
<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} -q @inproceedings %}

</div>

<h2 class="bibliography-section">PhD thesis</h2>
<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} -q @phdthesis %}

</div>
