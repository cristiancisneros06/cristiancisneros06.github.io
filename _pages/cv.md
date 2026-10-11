---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- TODO: Once your CV PDF is ready, upload it to the files/ folder as cristian-cisneros-cv.pdf, then delete the comment markers around the next line. -->
<!-- [Download CV (PDF)](/files/cristian-cisneros-cv.pdf) -->

Education
======
* B.S. in Physics and B.S. in Mathematics, University of Houston, Spring 2027 (expected)

Research experience
======
* Undergraduate Researcher, Nonlinear Dynamics <!-- TODO: add start date, e.g. "2024 – present" -->
  * Department of Physics, University of Houston
  * Advisor: Dr. Gemunu Gunaratne
  * Projects: CNN classification of the Hénon map; multifractal analysis of genomic point-sets; riboswitch folding

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

Awards and funding
======
* University of Houston Department of Physics Undergraduate Research Support ($1,000), 2026

<!-- TODO: Add a Skills section, for example:
Skills
======
* Programming: Python, ...
* Machine learning: PyTorch, ...
-->
