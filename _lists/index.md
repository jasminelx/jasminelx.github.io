---
layout: page
title: Lists
permalink: /lists/
---

<div class="lists-container">
  <h1>📋 Lists</h1>
  <p>Here are some lists I made. I like to write lists, and here they are. The fruits of my labour. My labour is writing lists.</p>

  <!-- Blog posts will be listed here -->
  <div class="lists-posts">
    {% for post in site.categories.lists reversed %}
      <p class="list-item">
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      </p>
    {% endfor %}
  </div>
</div>
