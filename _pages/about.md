---
permalink: /
title: "Philipp Becker (Site still under construction)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p>
I am persuing my PhD in Machine Learning at the Karlsruhe Institute of Technology under the supervision of Prof. Gerhanrd Neumann. 

</p>

<h2> Reserach </h2>
<p>
Probablisitc SSMs for World Models for RL + Sometimes Robots?
</p>

<p>
Other stuff 
</p>

<h2> Updates </h2>

{% include base_path %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
  {% endif %}
  {% include archive-single.html %}
{% endfor %}
