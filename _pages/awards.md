---
layout: archive
title: "Awards"
permalink: /awards/
author_profile: true
---

[//]: # (# Awards)
{% assign sorted_awards = site.awards | sort: "weight" %}
{% for award in sorted_awards %}
  <div class="award">
    <h2><a class="award-title" href="{{ award.url }}">{{ award.title }}</a></h2>
    <p>{{ award.short_description }}</p>
    <a class="read-more-link" href="{{ award.url }}">→ Read more</a>
    <hr>
  </div>
{% endfor %}
