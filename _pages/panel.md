---
layout: page
title: Career Panel
permalink: "/panelists/"
---

{% for speaker in site.panelists %}
  <div class="panelist">
    <p><a href="{{ site.baseurl }}/{{ speaker.day }}">{{ speaker.label }} &nbsp; {{ speaker.time }}</a> &nbsp; <a href="{{ speaker.website }}">{{ speaker.name }}</a> &nbsp; <a href="/acs{{ speaker.url }}">{{ speaker.title }}</a></p>
  </div>
{% endfor %}
