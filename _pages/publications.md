---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

<h5>Conference Papers</h5>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'confpaper' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h5>Manuscripts</h5>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'manuscript' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h5>Master's Thesis</h5>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'thesis' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h5>Talks</h5>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'talk' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
