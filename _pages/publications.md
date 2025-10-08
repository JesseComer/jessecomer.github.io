---
layout: archive
permalink: /publications/
author_profile: true
---

<h3 class="pub-section">Journal Articles</h3>
{% assign journals = site.publications | where: "pubtype", "journal" | sort: "date" | reverse %}
<ol class="pub-list">
{% for post in journals %}
  {% include pub-item.html post=post %}
{% endfor %}
</ol>

<h3 class="pub-section">Conference Papers</h3>
{% assign conf = site.publications | where: "pubtype", "confpaper" | sort: "date" | reverse %}
<ol class="pub-list">
{% for post in conf %}
  {% include pub-item.html post=post %}
{% endfor %}
</ol>

<h3 class="pub-section">Book Chapters</h3>
{% assign bkchap = site.publications | where: "pubtype", "book_chapter" | sort: "date" | reverse %}
<ol class="pub-list">
{% for post in bkchap %}
  {% include pub-item.html post=post %}
{% endfor %}
</ol>

<h3 class="pub-section">Talks</h3>
{% assign talks = site.publications | where: "pubtype", "talk" | sort: "date" | reverse %}
<ol class="pub-list">
{% for post in talks %}
  {% include pub-item.html post=post %}
{% endfor %}
</ol>

<h3 class="pub-section">Master's Thesis</h3>
{% assign theses = site.publications | where: "pubtype", "thesis" | sort: "date" | reverse %}
<ol class="pub-list">
{% for post in theses %}
  {% include pub-item.html post=post %}
{% endfor %}
</ol>

<h3 class="pub-section">Manuscripts</h3>
{% assign mans = site.publications | where: "pubtype", "manuscript" | sort: "date" | reverse %}
<ol class="pub-list">
{% for post in mans %}
  {% include pub-item.html post=post %}
{% endfor %}
</ol>
