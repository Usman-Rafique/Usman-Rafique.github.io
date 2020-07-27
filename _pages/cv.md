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
* B.E. in Mechatronics Engineering, National University of Sciences and Technology, Pakistan, 2003 - 2007
* M.S. in Mechatronics Engineering, National University of Sciences and Technology, Pakistan, 2008 - 2010
* Ph.D in Electrical Engineering, University of Kentucky, 2016 - 2021 (expected)
  
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
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
 
