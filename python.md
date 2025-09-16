---
layout: page
title: Python
permalink: /python/
---

<ul>
{% for post in site.categories.python %}
  <li><a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%Y-%m-%d" }}</li>
{% endfor %}
</ul>
