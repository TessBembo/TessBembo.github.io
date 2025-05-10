---
layout: page
title: My Projects
permalink: /blog/
---

<ul>
  {% for post in site.posts %}
    {% if post.tags contains 'project' %}
      <li style="margin-bottom: 25px;">
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <p>{{ post.excerpt }}</p>
      </li>
    {% endif %}
  {% endfor %}
</ul>
