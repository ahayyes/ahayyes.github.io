---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Medical Studies, University of Exeter, 2023
* M.S. in Advanced Biological Sciences (Microbiology) University of Liverpool, 2019
* B.S. in Biomedicine, Lancaster University, 2017

Work experience
======
* Postdoctoral Researcher, University of Exeter
  
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Co-founder of the University of Exeter Penryn Microbiology Early Career Researcher Network
