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
===

<p style="margin-left: 40px">
<b>Ph.D in Psychological Sciences</b>
<br>Concentration: Ecological Psychology
<br>University of Connecticut
<br><i>December 2025 (anticipated)</i></p>  

<p style="margin-left: 40px">
<b>B.S. in Cognitive Science</b>
<br>Minor: Spanish  
<br>University of Connecticut  
<br><i>December 2019</i></p>   

Work experience
=====
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
  
Skills
=====
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
=====
  {% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}
  
Talks
=====
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
=====
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
=====
* Currently signed in to 43 different slack teams
