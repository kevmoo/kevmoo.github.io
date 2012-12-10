---
layout: page
title: kevmoo
---

> Because I don't have enough web pages. ...and I figured I'd try this whole Github and Jekyll thing.
>
> You can find my main webpage [here](http://j832.com).

# Blog Posts
<ul>
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &ndash; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>