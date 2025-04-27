---
layout: default
title: "Projects"
---

# My Data Science Projects

Here are my data science projects:

{% for project in site.projects %}
## [{{ project.title }}]({{ project.url }})
{{ project.description }}

{% endfor %}

