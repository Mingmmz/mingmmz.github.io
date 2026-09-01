---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 2
---

<style>
.publications .author em {
  font-weight: 700;
}
</style>

<style>
.publications .preview {
  width: 180px !important;
  max-width: 180px !important;
}

.publications .preview img {
  width: 180px !important;
  height: auto !important;
}
</style>

<!-- _pages/publications.md -->

<p>
  <strong>*</strong> Equal contribution
</p>

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
