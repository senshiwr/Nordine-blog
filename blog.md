---
layout: blog
title: Blog
permalink: /blog/
---

# Blog

{% for post in site.posts %}

- **{{ post.date | date: "%b %d, %Y" }}**
- [{{ post.title }}]({{ post.url }})
  {% endfor %}
