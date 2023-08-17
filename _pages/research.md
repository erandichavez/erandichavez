---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}


Black Holes
===

Currently in progress.

Neptune
===

My undergraduate work focused on how Neptune's atmosphere and its clouds were changing over time. Neptune has one of the most active atmospheres in the Solar System, and studying Neptune's clouds gan give insight into the planet's deeper atmospheric processes. 

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
