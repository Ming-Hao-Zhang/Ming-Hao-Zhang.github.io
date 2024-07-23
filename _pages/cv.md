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
* Ph.D in Beijing Normal University, 2025 (expected)
* B.S. in Beijing Normal University, 2019

  
Skills
======
* Theoretical Nuclear Physics
    * Di-nuclear system (DNS) model
    * Boltzmann-Langevin (BLE) model
    * Isospin dependent Quantum Molecular Dynamics (IQMD) model
* Programing
  * Data processing and visualization using Python.
  * Fortran programing.
  * Experienced in parallel computing.

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
