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
* Ph.D in ECE, Queen's University at Kingston, ON, Canada, -
* MASc in ECE, Queen's University at Kingston, ON, Canada, 2022
* Meng in ECE, Queen's University at Kingston, ON, Canada, 2019
* Summer School, Imperial College London, UK, 2014
* Bachelor, Nanjing Forestry University, Nanjing, China, 2017

Work experience
======
* Summer 2015: Statistics Analysis Intern
  * L'oreal China Research & Innovation Center, Shanghai, China

* Summer 2017: Mechnic Engineer Intern
  * Jabil, China

* 2019-2020: AR Software Developer
  * Kingston, ON Canada

  
Skills
======
* Machine Learning
* Python
  * Pytorch
* NVCC kernels
* C++

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
  
TAs
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Reviewer of AAAI, ECCV, CVPR, and ICCV
