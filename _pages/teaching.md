---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
classes: wide
---


<img src="../images/Inrae.png" width="150" hspace="75"> <img src="../images/Inria.png" width="150" hspace="80"> <img src="../images/UCA1.jpg" width="150" hspace="80"><br clear="left">

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
