---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
classes: wide
---

<p style="text-decoration:underline;"><a href="/talkmap.html">Check out this cool map of everywhere I have given a talk!</a></p>

{% for post in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}
