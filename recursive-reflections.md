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
      <div style="margin-bottom: 25px;">
        <a href="{{ post.url }}"><strong>{{ post.title }}</strong></a><br>
        <small>{{ post.date | date: "%B %d, %Y" }}</small>
      </div>
    {% endfor %}

  </main>

</div>
