---
title: Posts
icon: fas fa-archive
order: 2
layout: page
---

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
