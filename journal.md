---
layout: page
title: Journal
permalink: /journal/
---
<h3>Schedule</h3>
Team Meetings: <br>
Client Meetings: Wednesdays 3:00 - 4:00 pm <br>
Mentor Meetings: <br>
<br>

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
