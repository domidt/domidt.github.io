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
  <ul>{% for post in site.education reversed %}
    {% include archive-single-edu-cv.html %}
  {% endfor %}</ul>

Work experience
======
* March 2023 to September 2025: Research Associate
  * Université Paris 1 Pantéon-Sorbonne, Centre d'Èconomie de la Sorbonne

* February 2019 to February 2022: Research Assistant
  * Management Center Innsbruck, Department of Business & Management
  * Supervisor: FH-Prof. PD Dr. Thomas Stöckl

* June 2019: Research Assistant
  * University of Innsbruck, Department of Public Finance

* June 2018 to September 2019: Student Assistant
  * University of Innsbruck, Department of Public Finance, Department of Banking and Finance, and Department of Economics

* February 2016 to April 2016: Internship
  * Deutsche Börse Group, Group Risk Monitoring, Eschborn, Germany  

  
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
  <ul>{% for post in site.progress %}
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
 
Grants and Awards
======
  <ul>{% for post in site.awards reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
 
IT Skills
======
* R
* Stata
* Matlab
* Python
* Mathematica

<p class="page__meta"><i class="fa fa-download" aria-hidden="true"></i> <a href="http://domidt.github.io/files/CV.pdf"> Download CV here </a> </p> 
