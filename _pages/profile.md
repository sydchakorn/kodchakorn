---
layout: archive
title: "Profile"
permalink: /profile/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Bioengineering, University of Illinois at Urbana-Champaign, 2024
* B.S. in Chemical Engineering (Second-class honor), Khon Kaen University, 2021

Work experience
======
* Graduate Research Assistant (June 2024 - present)
  * Biomedical Engineering Lab at Khon Kaen University
  * PI: Prof. Oranat Chuchuen
  * Collaborated with 2 graduate students on the project for glucose and alcohol detection using paper-based fuel cell biosensors

* Graduate Research Assistant (August 2022 – May 2024)
  * Nanosensors group at the University of Illinois at Urbana-Champaign 
  * PI: Prof. Brian. T. Cunningham
  * A portable, digital resolution, and smartphone-linked Photonic Resonator Absorption Microscope (PRAM Mini) for point-of-care diagnostics

* Undergraduate Research Assistant (August 2020 – August 2022)
  * Biomedical Engineering Lab at Khon Kaen University 
  * PI: Prof. Oranat Chuchuen
  * Project 1: A Wristband for Real-Time Sweat Alcohol Monitoring and Drunk Driving Prevention
  * Project 2: A Disposable Paper-Based Biosensor Integrated with Smartphone for Real-Time Sweat Alcohol Sensing
  
Skills
======
* Analytical Techniques
  * Scanning Electron Microscope (SEM)
  * Spectrometer
  * Dynamic Light Scattering
* Prototyping
  * Arduino boards
  * Epilog (Laser cutting)
  * 3D printing (SLA)
* Modeling
  * SolidWorks
  * AutoCAD

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
  
Awards
======
  <ul>{% for post in site.awards reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Volunteer
======
  <ul>{% for post in site.volunteer reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
