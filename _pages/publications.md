---
layout: page
permalink: /publications/
title: publications
description: My publications and talks
years: [2021, 2022, 2023]
nav: false
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>
