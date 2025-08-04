---
title: Posts
icon: fas fa-archive
order: 1
layout: page
permalink: /posts/
---

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
