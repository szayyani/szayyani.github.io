---
layout : page
title : "Physics Bytes !"
icon: fas fa-podcast
category : blog
order: 5
---
Welcome to Physics Bytes ! the english language podcast of the students of Notre-Dame de Sion here in Paris!

<ul>
  {% for post in site.categories.blog %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span>{{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
