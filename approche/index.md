---
layout: page
title: Approche de l'école Saint-John Perse
permalink: "/approche/index"
---

{% for item in site.menus.ecole %}
  <ul>
    <li><a href="{{ item.url }}" {% if item.url contains 'http' -%}target="_blank"{% endif %} title="{{ item.title }}">{{ item.title }}</a></li>
  </ul>
{% endfor %}
