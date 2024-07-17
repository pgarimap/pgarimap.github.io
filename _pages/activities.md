---
layout: default
title: "Activities"
permalink: /activities/
---

# Activities

{% for activity in site.activities %}
  <div class="activities">
    <h2>{{ activity.title }}</h2>
    <p><strong>Position Held:</strong> {{ activity.position }}</p>
    <p><strong>Types of Programs:</strong> {{ activity.programs | join: ", " }}</p>
    <p><strong>Impact Made:</strong> {{ activity.impact }}</p>
    <hr>
  </div>
{% endfor %}
