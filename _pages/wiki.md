---
layout: page
title: Wiki
permalink: /wiki
---

# List of All Notes

<ul>
  {% for notes in site.notes %}
    <li>
      <a href="{{ notes.url }}">{{ notes.title }}</a>
    </li>
  {% endfor %}
</ul>