---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

<div style="margin-bottom: 0.5em;">

  <h3> Conference Papers </h3>
  {% for post in site.publications reversed %}
    {% if post.pubtype == 'confpaper' %}
        {% include archive-single.html %}
    {% endif %}
  {% endfor %}

  <h3> Manuscripts </h3>
  {% for post in site.publications reversed %}
    {% if post.pubtype == 'manuscript' %}
        {% include archive-single.html %}
    {% endif %}
  {% endfor %}

  <h3> Master's Thesis </h3>
  {% for post in site.publications reversed %}
    {% if post.pubtype == 'thesis' %}
        {% include archive-single.html %}
    {% endif %}
  {% endfor %}

  <h3> Talks </h3>
  {% for post in site.publications reversed %}
    {% if post.pubtype == 'talk' %}
        {% include archive-single.html %}
    {% endif %}
  {% endfor %}

</div>
