---
layout: page
permalink: /teaching/
title: Teaching
description:
years: [Spring 2024, Fall 2023]
nav: false
nav_order: 3
---
Below are the courses for which I have served as an undergraduate TA

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f classes -q @*[year={{y}}]* %}
{% endfor %}

</div>
