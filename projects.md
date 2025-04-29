---
title: "Projects"
layout: collection
permalink: /projects/
collection: projects
entries_layout: grid
classes: wide
author_profile: true
---


{% for project in site.projects %}
  {% include archive-single.html %}
{% endfor %}

