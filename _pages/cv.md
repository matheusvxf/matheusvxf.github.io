---
layout: archive
title: "My CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
img {
    display: block;
    margin-left: auto;
    margin-right: auto;
}
</style>

<img src="/images/study.png" alt="Education" width="10%" height="10%">
======
* B.Sc. in Computer Engineering, Federal University of Itajubá, 2016
* M.A. in Computer Science, Princeton University, 2018
* Ph.D in Computer Science, Princeton University (In progress)

<img src="/images/business.png" alt="Work Experience" width="10%" height="10%">
======
* Summer 2014: Software Development Engineering Intern
  * Broadcom
  * Duties included: Software Development for Bluetooth Stack
  * Supervisor: David Hughes

* Fall 2011: Research Assistant
  * Federal University of Itajubá

<img src="/images/talk.png" alt="Languages" width="10%" height="10%">
======
* Portuguese is my mother tongue.
* I am fluent in English.

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
