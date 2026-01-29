---
layout: default
title: Math Marvels
---

# Math Marvels

{% for post in site.mathmarvels reversed %}
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p><em>{{ post.date | date: "%B %d, %Y" }}</em></p>
{% endfor %}
