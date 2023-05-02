---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
classes: wide
---

This page will be updated at the right moment.


<img src="../images/Inrae.png" width="150" hspace="75"> <img src="../images/Inria.png" width="150" hspace="80"> <img src="../images/UCA1.jpg" width="150" hspace="80"><br clear="left">

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
