---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

<p> <strong> Proceeding Papers </strong> <br>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'confpaper' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

<p> <strong> Manuscripts </strong> <br>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'manuscript' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

<p> <strong> Master's Thesis </strong> <br>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'thesis' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

<p> <strong> Talks </strong> <br>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'talk' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
