---
layout: page
title: Schedule
permalink: /schedule/
---

<ul>
  {% for post in site.posts %}
    <h3>
      <a href="/dc2021{{ post.url }}">{{ post.title }}</a>
    </h3>
  {% endfor %}
</ul>
