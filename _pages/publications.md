---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 2
_styles: >
  .post-title { text-transform: capitalize; }
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography --group_by none %}

</div>
