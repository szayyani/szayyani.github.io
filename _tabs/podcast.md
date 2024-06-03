---
layout : dafault
title : "Physics Bytes !"
icon: fas fa-podcast
category : blog
order: 5
---
# {{ page.title }}

#### Welcome to Physics Bytes ! the english language podcast of the students of Notre-Dame de Sion here in Paris!

  <div class="post-list">
    {% assign tech_posts = site.posts | where: "categories", "blog" %}
    {% for post in tech_posts %}
      <article class="post-preview">
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <p>{{ post.excerpt | strip_html | truncate: 160 }}</p>
        <p><a href="{{ post.url }}">Read More</a></p>
      </article>
    {% endfor %}
  </div>
