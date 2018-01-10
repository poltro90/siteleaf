---
title: Posts
date: 2018-01-10 17:07:00 Z
layout: post
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>