---
layout: archive
title: "Certificates"
permalink: /code/
author_profile: true
classes: wide
---

{% for post in site.code reversed %}
  {% include archive-single.html %}
{% endfor %}
