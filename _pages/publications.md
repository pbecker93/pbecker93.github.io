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

<h3> Test </h3>

{% for post in site.publications reversed %}
  {% if post.featured %}
  {% include archive-single-publication.html %}
  {% endif %}
{% endfor %}

<h3> Test2 </h3>

{% for post in site.publications reversed %}
  {% include archive-single-publication.html %}
{% endfor %}