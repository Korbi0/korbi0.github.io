---
layout: page
title: Meeting Notes
permalink: /meeting_notes/
---

# ELK

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.date | date: "%B %d, %Y" }}</p>
  <p>{{ post.excerpt }}</p>
{% endfor %}