---
layout: archive
title: "All Posts"
permalink: /posts/
---

Archive of all posts

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p><small>{{ post.date | date: "%B %d, %Y" }}</small></p>
  <p>{{ post.excerpt }}</p>
  <hr>
{% endfor %}
