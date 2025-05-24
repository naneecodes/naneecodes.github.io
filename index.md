---
layout: default
title: Home
---

Welcome to **Small Mood Blog** — a soft space for quiet thoughts and slow becoming.

## Latest Posts 

<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> — {{ post.date | date: "%B %d, %Y" }}</li>
  {% endfor %}
</ul>