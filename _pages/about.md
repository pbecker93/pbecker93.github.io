---
permalink: /
title: "Philipp's Academic Page - Under Construction"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p>
Introduction
</p>

<h2> Reserach </h2>
<p>
Something about my research
</p>

<h2> Updates </h2>

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}
