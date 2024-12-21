---
layout: archive
title: "Representation and Dynamics Learning for Robotics"
permalink: /dyn_learning/
author_profile: true
---

{% for post in site.publications reversed %}
  {% if post.tag == "dyn" %}
  {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}
