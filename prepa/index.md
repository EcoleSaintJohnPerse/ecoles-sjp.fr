---
layout: page
title: Prépas de l'Ecole Saint-John Perse
permalink: "/prepa/index"
---

{% for item in site.menus.prepa %}
  <ul>
    <li><a href="{{ item.url }}" {% if item.url contains 'http' -%}target="_blank"{% endif %} title="{{ item.title }}">{{ item.title }}</a></li>
  </ul>
{% endfor %}
