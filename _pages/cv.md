---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[View Resume](/files/Resume_BitanMallik.pdf){: .btn .btn--primary}

Education
======
* **Master of Engineering (M.Eng) in Engineering Management**
  * Cornell University (College of Engineering), Ithaca, New York
  * 2025 – 2026

* **Master of Science (M.Sc) in Nanoelectronic Systems**
  * Dresden University of Technology (TU Dresden), Dresden, Germany
  * 2015 – 2018
  * GPA: 3.73/4.00

* **Bachelor of Technology (B.Tech) in Electronics and Communication Engineering**
  * West Bengal University of Technology, Kolkata, India
  * 2009 – 2013
  * GPA: 3.76/4.00

Work Experience
======
* **November 2023 – August 2025: Senior Engineer - Analog Mixed-Signal Design**
  * Renesas Electronics, Bingen, Germany
  * Led requirements analysis for industrial Ethernet; created product spec in Polarion; achieved CDR, SDR, LDR gates
  * Designed analog transmitter on 40 nm TSMC for Ethernet PHY IP; verified chip top; simulated package and signed-off
  * Ran cross-team design, layout, and verification reviews across 3 groups; passed compliance test; got first silicon success

* **March 2022 – October 2023: ICT3 Engineer - AMS Layout Design**
  * Apple, Munich, Germany
  * Led a team of 4 engineers to develop PMU using FinFET for Cellular RF SoC; delivered megacell ahead of schedule
  * Managed third-party vendors; organized daily stand-ups, distributed tasks, accomplished goals, and provided feedback
  * Introduced Innovus PnR for AMS blocks and used ParagonX to minimize parasitics; reduced critical-net RC by 20%

* **November 2018 – February 2022: Research Engineer - Analog Mixed-Signal Design**
  * Fraunhofer IIS, Erlangen, Germany
  * Designed a CDR circuit operating at 8 GHz using 22nm GF FDX for ASA-compliant automotive infotainment SoC
  * Designed multiple ROICs on 180nm XFAB/TowerJazz for ToF imaging, smoke detection, & smart farming applications
  * Mentored over 3 research assistants for master thesis; formally reviewed journal, presentation, & research papers

Technical Skills
======
* **EDA/IC Tools**
  * Cadence Virtuoso (ADE Assembler, Spectre, AMS)
  * Innovus, Quantus/QRC
  * Calibre (DRC/LVS), PEX

* **Digital & Programming**
  * Verilog (RTL)
  * MATLAB/Simulink
  * C, Java, Shell
  * OS (Linux, Windows)

* **Workflow & Collaboration**
  * Polarion, Confluence, JIRA
  * Git, LaTeX

Academic Projects
======
* **M.Sc. Thesis (2017-2018)**: Fast-start-up SerDes transmitter for Neuromorphic Hardware Systems
  * TU Dresden
  * Developed a fast start-up SerDes transmitter for neuromorphic system; modeled and verified architecture in simulation
  * Extracted key metrics e.g. power, performance, area, & wake-up time; documented & presented results; defended thesis

* **M.Sc. Project (2016-2017)**: Low latency SerDes link for high-speed communication systems
  * TU Dresden
  * Designed 2.5 GHz SerDes link and burst-mode CDR (RTL); verified architecture using mixed-mode (AMS) simulation
  * Achieved optimum power efficiency, low latency, and reduced link initialization delay; documented & presented results

Certifications
======
* Phase Locked Loops - Practical & Advanced Design - Prof. Woogeun Rhee (Certificate of Completion) - 2024
* Practical Design of Data Converters - MEAD Course at EPFL, Switzerland (Certificate of Completion) - 2021
* Verification and Test of Integrated Circuits - Practical training at eecy-ic gmbH (Acquired by BOSCH) - 2020

Languages
======
* English (Fluent)
* German (Advanced)
* Hindi (Fluent)
* Bengali (Native)

Honors and Awards
======
* GFF an der TU Dresden Scholarship for research contribution during Master's Thesis at chair HPSN - 2017
* DAAD Scholarship for ranking in the top 5% and delivering exceptional project work at TU Dresden - 2016

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
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
