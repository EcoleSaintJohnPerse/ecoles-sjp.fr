---
layout: page
title: Scolarité à l'Ecole Saint-John Perse
permalink: "/scolarite/index/"
---

{% for item in site.menus.scolarite %}
  <ul>
    <li><a href="{{ item.url }}" {% if item.url contains 'http' -%}target="_blank"{% endif %} title="{{ item.title }}">{{ item.title }}</a></li>
  </ul>
{% endfor %}
