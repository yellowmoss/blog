---
layout: default
title: "Home"
---

# Welcome to My Blog

Here are my posts:

{% for post in site.posts %}
<a href="{{ post.url | relative_url }}">{{ post.title }}</a>
{% endfor %}


<p>Baseurl: {{ site.baseurl }} </p>
<p>Rawpost.url: {{ site.post[0].url }} </p>
<p>Relative.url: {{ site.post[0].url | relative_url }} </p>
