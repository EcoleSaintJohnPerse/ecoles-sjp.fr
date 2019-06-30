---
layout: page
title: Filières de l'Ecole Saint-John Perse
permalink: "/filieres/index/"
---

{% for item in site.menus.filiere %}
  <ul>
    <li><a href="{{ item.url }}" {% if item.url contains 'http' -%}target="_blank"{% endif %} title="{{ item.title }}">{{ item.title }}</a></li>
  </ul>
{% endfor %}
