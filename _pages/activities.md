---
layout: archive
title: "Activities"
permalink: /activities/
author_profile: true
---

[//]: # (# Activities)

{% for activity in site.activities %}
  <div class="activities">
    <a href="{{activity.permalink}}"><h2>{{ activity.title }}</h2></a>
    <p><strong>Position Held:</strong> {{ activity.position }}</p>
    <p><strong>Types of Programs:</strong> {{ activity.programs | join: ", " }}</p>
    <p><strong>Impact Made:</strong> {{ activity.impact }}</p>
    <hr>
  </div>
{% endfor %}
