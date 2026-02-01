---
layout: default
title: Recursive Reflections
---

<div class="blog-layout">

  <aside class="blog-sidebar">
    <h3>Explore</h3>
    <input type="text" placeholder="Search thoughts...">

    <h4>Topics</h4>
    <div class="tag-cloud">
      <a href="#">Patterns</a>
      <a href="#">Nature</a>
      <a href="#">Books</a>
      <a href="#">Geometry</a>
    </div>
  </aside>

  <main class="blog-content">
    <h1>Recursive Reflections</h1>

    {% for post in site.recursive-reflections %}
  <div class="post-card">
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <small>{{ post.date | date: "%B %d, %Y" }}</small>

    <p>
      {{ post.content | strip_html | truncate: 220 }}
    </p>

    <a class="read-more" href="{{ post.url }}">Read more →</a>
  </div>
{% endfor %}


  </main>

</div>
