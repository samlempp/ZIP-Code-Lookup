---
layout: page
title: Journal
permalink: /journal/
---

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <span class="post-meta">{{ post.date }}</span>
      <h3>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </h3>
    </li>
  {% endfor %}
</ul>
