---
layout: page
title: Career Panel
permalink: "/panel/"
---

{% for speaker in site.panelists %}
  <div class="panelist">
    <p><a href="{{ site.baseurl }}">link</a> &nbsp; <a href="{{ speaker.website }}">{{ speaker.name }}</a> &nbsp; <a href="/dc2021{{ speaker.url }}">{{ speaker.title }}</a></p>
  </div>
{% endfor %}
