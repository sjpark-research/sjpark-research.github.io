---
layout: page
permalink: /publications/
title: publications
description: undeer construction.
nav: true
nav_order: 2
---
<style>
/* Stronger year headings on publications page */
h2 {
  color: var(--global-text-color) !important;
  font-weight: 700 !important;
  opacity: 1 !important;
}

/* Highlight my name in publication author lists */
.bibliography .author em,
.bibliography .authors em,
.bibliography em {
  font-weight: 700 !important;
  font-style: normal !important;
  color: var(--global-text-color) !important;
}
</style>
<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
