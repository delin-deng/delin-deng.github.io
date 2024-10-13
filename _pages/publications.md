---
layout: page
permalink: /publications/
title: publications
#description: A full list of publications can be found at my google scholar page.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->


<div class="publications">

<h4>Book</h4>

{% bibliography -f papers --group_by year --group_order descending -q @*[section=Book]* %}

</div>

<div class="publications">

<h4>Book Chapter</h4>

{% bibliography -f papers --group_by year --group_order descending -q @*[section=Book Chapter]* %}

</div>

<div class="publications">

<h4>Journal Articles</h4>

{% bibliography -f papers --group_by year --group_order descending -q @*[section=Journal Articles]* %}

</div>

<div class="publications">

<h4>Conference Proceedings</h4>

{% bibliography -f papers --group_by year --group_order descending -q @*[section=Conference Proceedings]* %}

</div>


