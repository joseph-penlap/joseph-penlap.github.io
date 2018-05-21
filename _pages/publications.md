---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Clicking on any of the links below will redirect you to the abstract and details of my contributions.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
