---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<h2>Conference Publications</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'confpaper' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Talks</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'talk' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
