---
layout: page
permalink: /research/
title: Research
categories: [Posters]
years: [2023, 2024]
description: Projects to which I have contributed (non-exhaustive).
nav: true
nav_order: 2
---

<!-- _pages/talks.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
