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
* B.S. in Physics, Heidelberg University, 2018
* M.S. in Physics, Heidelberg University, 2020
* Ph.D in Astrophysics, Kopenhagen University & KULeuven, 2023 (expected)

Previous work
======
* Spring 2018: Bachelor thesis
  * Heidelberg University
  * Looking at surface waves in protoplanetary disks due to stellar luminosity outbursts
  * Supervisor: Prof. Dr. Cornelis Dullemond

* Fall 2019 - Fall 2020: Master thesis
  * Max Planck Institute of Astronomy
  * Looking at the heavy element content of hot gas giants due to the accretion of pebbles, planetesimals and gas
  * Supervisor: Dr. Bertram Bitsch

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
