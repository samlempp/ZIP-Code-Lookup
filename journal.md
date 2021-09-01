---
layout: default
title: Journal
permalink: /journal/
---
<h2>Schedule</h2>
<b>Team Meetings:</b> <br>
<b>Client Meetings:</b> Wednesdays 3:00 - 4:00 pm <br>
<b>Mentor Meetings:</b> <br>
<br>

<h2>Journal</h2>
<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <span class="post-meta">{{ post.date | date: "%B %d, %Y"}}</span>
      <h3>
        <a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
      </h3>
    </li>
  {% endfor %}
</ul>
