---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
<div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}
<br>
<br>


# Published
{% for post in site.publications reversed %}
  {% if post.status == 'published' %}
    {% include archive-single-custom.html %}
  {% endif %}
{% endfor %}


# Under-review
{% for post in site.publications reversed %}
  {% if post.status == 'under-review' %}
    {% include archive-single-custom.html %}
  {% endif %}
{% endfor %}


# Under-preparation
{% for post in site.publications reversed %}
  {% if post.status == 'under-preparation' %}
    {% include archive-single-custom.html %}
  {% endif %}
{% endfor %}
