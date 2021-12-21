---
layout: archive
title: "Curriculum vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
  <ul>{% for post in site.education %}
    {% include archive-single-edu-cv.html %}
  {% endfor %}</ul>

Work experience
======
* February 2019 to 2022: Research Assistant
  * Management Center Innsbruck, Department of Business & Management
  * Supervisor: FH-Prof. PD DR. Thomas Stöckl

* June 2019: Research Assistant
  * University of Innsbruck, Department of Public Finance

* June 2018 to September 2019: Student Assistant
  * University of Innsbruck, Department of Public Finance, Department of Banking and Finance, and Department of Economics

  
Fields of interest
======
* Microeconomics
* Behavioural economics
* Experiemental economics
* Information economics

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Work in progress
======
  <ul>{% for post in site.ongoing %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
 
IT Skills
======
* R
* Stata
* Matlab
* Python
* Mathematica
