---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Research Interests
=====
Internet Measurement, Differential Privacy Applied to Network Data, Device and Content Mobility, Performance Modeling. 

Education
======
* Ph.D Australian National University and Data61 CSIRO 2013. 
* B.E. Australian National University, 2008

Professional Experience
======
* Current: Associate Professor, Computer Science Department,Swarthmore College, Swarthmore, PA 
* 2020: Sabbatical Collaboration, Akamai Networks, Boston, MA
* 2018: Assistant Professor, Computer Science Department Swarthmore College, Swarthmore, PA
* 2014: Post-doctoral Scholar, University of Massachusetts, Amherst, MA
 
  

Publications
======

{% capture publications %}
{% include_relative publications.md %}
{% endcapture %}
{{ publications | split: "---" | last }}

<!--
Talks
======
<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>
-->

  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Professional Service
======

* SOUPs Workshop Organizer SUPA-2024: Societal & User-Centered Privacy in AI :
https://supa-workshop.github.io/supa.github.io/

* NSF NeTs PI Meeting, 2025.

* Invited Reviewer, AAAI Workshop on Privacy-Preserving Artificial Intelligence, 2024, 2025

* Invited Reviewer, Workshop on Cyber Security Experimentation and Test (CSET): 2022

* NSF Panelist 2022, 2023, 2024

* Invited to Co-Lead NSF NeTS PI Meeting 2023

* SIGCOMM (Special Interest Group on Data Communications), Education Workshop Organizing Committee, 2020

* INFOCOM (International Conference on Computer Communications) Technical Program
Committee (TPC) Member -2019, 2020, 2021

* INFOCOM 2021: Chair for Privacy Track – II.

* IEEE Transactions on Wireless Communications Reviewer, 2013
Outreach

* Science For Kids, Summer Program for Chester Children’s Chorus, 2022

* Grace Hopper Faculty Scholarship Application Reviewer, 2019

* Google explore Undergraduate Computer Science Research Experience for Women in Computer Science, 2019



{% capture opensource %}
{% include_relative opensource.md %}
{% endcapture %}
{{ opensource | split: "---" | last }}
