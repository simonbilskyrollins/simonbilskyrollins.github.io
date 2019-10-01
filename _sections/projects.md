---
title: Projects
identifier: projects
order: 2
---
{% assign projects = site.projects | sort: 'end_date' | reverse %}

{% for project in projects %}
{% include project.html %}
{% endfor %}