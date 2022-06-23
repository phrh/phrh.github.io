---
layout: page
permalink: /publications/
title: publications
description: Recent publications.
years: [2022,2021,2020,2015,2014,2011,2010,2009]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
