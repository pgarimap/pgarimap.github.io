---
layout: archive
title: "Awards"
permalink: /awards/
author_profile: true
---

[//]: # (# Awards)

{% for award in site.awards %}
  <div class="awards">
    <h2><a href="{{ award.url }}">{{ award.title }}</a></h2>
    <p>{{ award.short_description }}</p>
    <a href="{{ award.url }}">Read more</a>
    <hr>
  </div>
{% endfor %}
