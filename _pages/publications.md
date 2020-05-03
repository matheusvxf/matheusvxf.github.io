---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<script src="https://bibbase.org/show?bib=https%3A%2F%2Fmatheusvxf.github.io%2Ffiles%2Fmypubs.bib&jsonp=1"></script>

Manuscripts
======
{% for post in site.manuscripts reversed %}
  {% include archive-manuscript.html %}
{% endfor %}
