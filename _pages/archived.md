---
layout: page
title: Archived Posts
permalink: /archived/
---

# 归档博客文章

<ul>
  {% for post in site.posts %}
    {% if post.categories contains "jyyos 2025" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: '%B %d, %Y' }}</li>
    {% endif %}
  {% endfor %}
</ul>
