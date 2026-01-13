---
layout: default
title: Home
---

<h1>Latest Posts</h1>

{% for post in site.posts %}
<div class="post-card">
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <small>{{ post.date | date: "%Y-%m-%d" }}</small>
</div>
{% endfor %}
