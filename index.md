---
title: Index
layout: default
---

{% for post in site.posts %}
<a href="/ghpages-test{{ post.url }}">{{ post.title }}</a>
{% endfor %}