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
* B.S. in Economics, Rikkyo University, 2011
* M.S. in Economics, Norwegian School of Economics, 2013

Work experience
======
* 2013 - 2016: Economic Research Scientist
  * Cyberagent, Inc. AILab
* 2013 - 2016: Data Scientist
  * Cyberagent, Inc. AdTech Unit
* 2011 - 2013: Data Analyst
  * Cyberagent, Inc. ADs Agency Unit
  
Skills
======
* R
* Python
* SQL

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  