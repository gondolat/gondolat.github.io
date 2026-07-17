---
layout: default
title: Szuttafordítások
---
<ul class="sutta-list">
{% assign sorted_suttas = site.suttas | sort: "sutta_key" %}
{% for sutta in sorted_suttas %}
  <li><a href="{{ sutta.url }}">{{ sutta.title }}</a> — {{ sutta.sutta_number }}</li>
{% endfor %}
</ul>