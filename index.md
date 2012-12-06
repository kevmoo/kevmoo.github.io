---
layout: page
title: kevmoo
---

# Blog Posts
<ul>
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &ndash; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>