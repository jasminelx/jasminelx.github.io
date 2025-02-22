---
layout: page
title: Lists
permalink: /lists/
---

# 📋 Lists

here are some lists that i made. i like making lists, and here they are. the fruits of my labour. my labour is making lists. :

<ul>
  {% for list in site.lists reversed %}
    <li>
      <a href="{{ list.url | relative_url }}">{{ list.title }}</a> - <small>{{ list.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
