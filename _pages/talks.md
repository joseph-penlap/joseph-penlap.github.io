---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
classes: wide
---


<img src="../images/Inrae.png" width="150" hspace="75"> <img src="../images/Inria.png" width="150" hspace="80"> <img src="../images/UCA1.jpg" width="150" hspace="80"><br clear="left">

{% for post in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}
