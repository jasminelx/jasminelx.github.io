---
layout: page
title: Lists
permalink: /lists/
---

<div class="lists-container">
  <h1>📋 Lists</h1>
  <p>here are some lists i made. i like to write lists, and here they are. the fruits of my labour. my labour is writing lists.</p>

  <ul>
    {% for list in site.lists reversed %}
      <li>
        <a href="{{ list.url | relative_url }}">{{ list.title }}</a> - <small>{{ list.date | date: "%B %d, %Y" }}</small>
      </li>
    {% endfor %}
  </ul>
</div>
