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
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }} - {{ post.description }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
