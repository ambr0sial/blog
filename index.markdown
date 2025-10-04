---
layout: default
title: "blog"
---

# welcome to my blog

posts:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%b %-d, %Y" }}
{% endfor %}