---
layout: archive
title: "Bayesian Deep Learning"
permalink: /bdl/
author_profile: true
---

{% for post in site.publications reversed %}
  {% if post.tag == "bdl" %}
  {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}
