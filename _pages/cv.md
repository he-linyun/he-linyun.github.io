---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
## Education  
* Ph.D. in Operations Research, Georgia Institute of Technology, 2024 (Expected)
* M.A. in Statistics, Columbia University, 2019
* B.S. in Mathematics and Applied Mathematics, Fudan University, 2017

## Papers
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## Talks
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
## Skills
* Languages: C++, R, Python
* Software: $\LaTeX$, MATLAB.
