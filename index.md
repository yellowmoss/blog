---
layout: default
title: Home
---

# Welcome to My Blog

Here are my posts:

{% for post in site.posts %}
<link rel="canonical" href="{{ post.url | absolute.url }}">
<a href="{{ post.url | relative.url }}">{{ post.title }}</a>
{% endfor %}
