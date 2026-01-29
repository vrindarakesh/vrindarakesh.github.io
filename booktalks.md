---
layout: default
title: Book Talks
---

# Book Talks

{% for post in site.booktalks reversed %}
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p><em>{{ post.date | date: "%B %d, %Y" }}</em></p>
{% endfor %}
