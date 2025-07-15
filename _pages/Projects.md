---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

[//]: # (# Projects)

{% assign sorted_projects = site.projects | sort: 'weight' %}
{% for project in sorted_projects %}
  <div class="project-entry">
    <h2><a class="project-title" href="{{ project.url }}">{{ project.title }}</a></h2>
    <p><strong>Skills:</strong> {{ project.skills | join: ", " }}</p>
    <p>{{ project.excerpt }}</p>
    <p><a class="read-more-link" href="{{ project.url }}">→ Read more</a></p>
    <hr>
  </div>
{% endfor %}
