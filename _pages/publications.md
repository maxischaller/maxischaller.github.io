---
layout: page
permalink: /research/
title: Research
description: 
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature  {% include bib_search.liquid %}  -->


<div class="publications">
    <h2>Publications</h2>
    {% bibliography -f papers.bib %}
</div>

<div class="publications">
<h2>Working Papers</h2>
{% bibliography -f workingpapers.bib %}
</div>



<div style="height: 10mm;"></div>


<!-- inside div block in md file need to use html code -->
<div class="publications">
  <h2>Work in Progress</h2>

  <p><strong>Social Skills and Wage Growth</strong> (with Richard Blundell and Peter Haan)</p>

  <p><strong>Women's Promotion Prospects and Wage Growth</strong> (with Boryana Ilieva)</p>

  <p class="test-bold">This text should be bold (font-weight: bold).</p>
<p class="test-bolder">This text should be bolder (font-weight: bolder).</p>
<p class="test-700">This text should be bold (font-weight: 700).</p>
</div>