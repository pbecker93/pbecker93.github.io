---
layout: archive
title: "Versatile Imitation Learning"
permalink: /versatile_il/
author_profile: true
---

{% for post in site.publications reversed %}
  {% if post.tag == "vil" %}
  {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}
