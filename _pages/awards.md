---
layout: default
title: "Awards"
permalink: /awards/
---

# Awards

{% for award in site.awards %}
  <div class="award">
    <h2><a href="{{ award.url }}">{{ award.title }}</a></h2>
    <p>{{ award.short_description }}</p>
    <a href="{{ award.url }}">Read more</a>
    <hr>
  </div>
{% endfor %}
