---
layout: default
title: blog
---

{% for post in site.posts %}
<h3 class="postTitle"><a href="{{ post.url }}">{{ post.title }}</a> on {{ post.date | date: "%B %d, %Y" }}</h3>
{% endfor %}
