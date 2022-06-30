<!-- blog.md -->
---
layout: page
title: null
permalink: /blog
---

# Blog

TEST

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
