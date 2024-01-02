---
title: gSKIE - Главная
page-title: Welcome to My Home Page
layout: default
---

{% include projects.html %}

<ul>
  {% for post in site.posts %}
    <li>
      <h2>{{ post.title }}</h2>
      <p>{{ post.annotatio }}</p>
      {{ post.date | timeago }}
      <a href="{{ post.url }}">Читать ...</a>
      
    </li>
  {% endfor %}
</ul>