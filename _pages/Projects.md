---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

[//]: # (# Projects)

{% for project in site.projects %}
  <div class="project">
    <h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
    <p><strong>Date:</strong> {{ project.date | date: "%B %d, %Y" }}</p>
    <p><strong>Skills:</strong> {{ project.skills | join: ", " }}</p>
    <p>{{ project.excerpt }}</p>
    <a href="{{ project.url }}">Read more</a>
    <hr>
  </div>
{% endfor %}
