---
layout: default
title: Blog
---

# Blog

<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date }}</li>
  {% endfor %}
</ul>
