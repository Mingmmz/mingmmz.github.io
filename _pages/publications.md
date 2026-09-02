---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 2
---
<style>
@media (min-width: 576px) {
  .publications .abbr {
    flex: 0 0 270px !important;
    width: 270px !important;
    max-width: 270px !important;
  }

  .publications .abbr + .col-sm-8 {
    flex: 1 1 0 !important;
    width: auto !important;
    max-width: none !important;
  }

  .publications .abbr img.preview {
    width: 100% !important;
    max-width: 100% !important;
    height: auto !important;
    object-fit: contain;
  }
}

.publications .author em,
.publications .author em a {
  font-weight: 600 !important;
  font-style: normal !important;
}
</style>

<!-- <style>
.publications .author em {
  font-weight: 400;
}
</style> -->

<!-- <style>
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
