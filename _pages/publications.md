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
  font-weight: 500;
}
</style>

<style>
@media (min-width: 576px) {
  .publications .abbr {
    flex: 0 0 25% !important;
    max-width: 25% !important;
  }

  .publications .abbr + .col-sm-8 {
    flex: 0 0 75% !important;
    max-width: 75% !important;
  }

  .publications .abbr img.preview {
    width: 100% !important;
    max-width: 100% !important;
    height: auto !important;
  }
}
</style>

<!-- <style>
.publications .preview {
  width: 180px !important;
  max-width: 180px !important;
}

.publications .preview img {
  width: 180px !important;
  height: auto !important;
}
</style> -->

<!-- _pages/publications.md -->

<p>
  <strong>*</strong> Equal contribution
</p>

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
