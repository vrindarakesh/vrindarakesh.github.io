---
layout: default
title: Booksorbed
---

# Booksorbed

{% for post in site.booksorbed reversed %}
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p><em>{{ post.date | date: "%B %d, %Y" }}</em></p>
{% endfor %}
