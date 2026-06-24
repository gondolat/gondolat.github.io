---
layout: default
title: Szuttafordítások
---
<ul class="sutta-list">
{% for sutta in site.suttas %}
  <li><a href="{{ sutta.url }}">{{ sutta.title }}</a> — {{ sutta.sutta_number }}</li>
{% endfor %}
</ul>