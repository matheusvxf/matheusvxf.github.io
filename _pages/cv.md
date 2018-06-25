---
layout: archive
title: "My CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({tex2jax: {inlineMath: [['$','$'], ['\\(','\\)']]}});
</script>
<script type="text/javascript"
  src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>

<style>
img {
    display: block;
    margin-left: auto;
    margin-right: auto;
}
</style>

<img src="/images/study.png" alt="Education" width="10%" height="10%">
======
* Ph.D in Computer Science, Princeton University (In progress)
* M.A. in Computer Science, Princeton University, 2018
* B.Sc. in Computer Engineering, Federal University of Itajubá, 2016
  * Visiting Undergraduate, University of California, San Diego, 2014

<img src="/images/business.png" alt="Work Experience" width="10%" height="10%">
======
* Summer 2014: Software Development Engineering Intern
  * Broadcom, San Diego
  * Duties included: Software Development for Broadcom's Bluetooth Stack
  * Supervisor: David Hughes

<img src="/images/talk.jpg" alt="Talks" width="15%" height="15%">
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

<img src="/images/teaching.png" alt="Teaching" width="10%" height="10%">
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<img src="/images/honor.jpg" alt="Honors and Awards" width="10%" height="10%">
======
* Dean's Grant, [Princeton University](https://www.princeton.edu/) 2016-2021
* First Year Fellowship, [Princeton University](https://www.princeton.edu/) 2016
* Academic Accolade for best student, [Federal University of Itajubá](https://unifei.edu.br/) 2016
* [Congratulations from Higher Counsel](https://unifei.edu.br/conselhos/conselhos-universitario-consuni/), [Federal University of Itajubá](https://unifei.edu.br/) 2016
* [Motion of Applause](http://www.itabira.cam.mg.gov.br/abrir_arquivo.aspx/Ata_da_17_Reuniao_Ordinaria_da_4_Sessao_2016?cdLocal=2&arquivo={CE6B2E83-56DC-B64E-2BEC-ADB15ECB6572}.pdf#search=matheus), [Municipal Chamber of Itabira](http://www.itabira.cam.mg.gov.br/) 2016
* [CNS Espresso Prize for Excellence in Networking](https://cns.ucsd.edu/cns-students-portal/cns-espresso-prize-for-excellence-in-networking/) 2014
* [Brazil Scientific Mobility Program](https://www.iie.org/en/Programs/Brazil-Scientific-Mobility/About), fully-funded fellowship recipient 2014
* [Fapemig Research Fellowship](http://www.fapemig.br/), [LOTMine](http://www.dcc.ufmg.br/dcc/?q=en/node/305) 2013
* [$1^{st}$ place Line Follower Robot Competition](/honors/line-follower), [Federal University of Itajubá](https://unifei.edu.br/) 2013
* [Fapemig Research Fellowship](href="http://www.fapemig.br/) 2012

<img src="/images/language.png" alt="Languages" width="10%" height="10%">
======
* Portuguese is my mother tongue.
* I am fluent in English.

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
