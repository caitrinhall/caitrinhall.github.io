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

## Peer-Reviewed Journal Publications
You can also find my articles on <u><a href="https://scholar.google.com/citations?view_op=list_works&hl=en&hl=en&user=YliGD2YAAAAJ" style="color:#0C16A7">my Google Scholar profile</a>.</u>
<br/>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  
## Conference Talks and Posters

{% for post in site.talks reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  
## Teaching

{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}
  
## Service and leadership

* Currently signed in to 43 different slack teams

## Work experience

* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
  
## Skills

* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3
