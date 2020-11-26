---
layout: home
title: Домашняя страница
landing-title: 'Привет. Это я.'
description: null
image: null
author: null
show_tile: false
---

<ul>
  {% for pages in site.pages %}
    <li>
      <a href="{{ page.url }}">{{ page.title }} - {{ page.description }}</a>
    </li>
  {% endfor %}
</ul>
