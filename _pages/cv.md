---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p style="margin-bottom: 2rem;">
  Here is a comprehensive overview of my professional experience, education, and technical skills. You can also view or download my resume.
</p>

<style>
  /* PROFESSIONAL CV STYLES */
  
  /* 1. General Typography */
  h2.cv-section-title {
    font-size: 1.4rem;
    font-weight: 700;
    color: var(--global-text-color);
    border-bottom: 2px solid var(--global-border-color);
    padding-bottom: 0.5rem;
    margin-top: 2.5rem;
    margin-bottom: 1.5rem;
    text-transform: uppercase;
    letter-spacing: 0.5px;
  }

  h2.cv-section-title i {
    color: var(--global-link-color);
    margin-right: 10px;
    font-size: 1.2rem;
  }

  /* 2. Timeline Layout (Date Left, Content Right) */
  .cv-entry {
    display: flex;
    margin-bottom: 1.5rem;
    gap: 20px;
  }

  .cv-date {
    flex: 0 0 130px; /* Fixed width for dates */
    font-weight: 600;
    color: var(--global-text-color-light);
    font-size: 0.95rem;
    text-align: right;
    padding-top: 2px;
  }

  .cv-content {
    flex: 1;
  }

  .cv-job-title {
    font-size: 1.1rem;
    font-weight: 700;
    color: var(--global-text-color);
    margin-bottom: 0.2rem;
  }

  .cv-company {
    font-size: 0.95rem;
    font-weight: 500;
    color: var(--global-text-color-light);
    font-style: italic;
    margin-bottom: 0.5rem;
    display: block;
  }

  .cv-location {
    font-size: 0.85rem;
    color: var(--global-text-color-light);
    margin-left: 5px;
    font-style: normal;
    opacity: 0.85;
  }

  .cv-content ul {
    margin: 0.5rem 0 0 1rem;
    padding: 0;
    font-size: 0.95rem;
    color: var(--global-text-color);
    line-height: 1.6;
  }

  /* 3. Skill Tags */
  .skills-container {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-bottom: 1rem;
  }

  .skill-category {
    font-weight: 600;
    color: var(--global-text-color);
    margin-bottom: 0.5rem;
    display: block;
  }

  .skill-tag {
    background-color: color-mix(in srgb, var(--global-border-color) 50%, var(--global-bg-color));
    border: 1px solid var(--global-border-color);
    color: var(--global-text-color);
    padding: 4px 10px;
    border-radius: 6px;
    font-size: 0.85rem;
    font-weight: 500;
  }

  html:not([data-theme="dark"]) .skill-tag {
    background-color: #f3f4f6;
    border-color: #d1d5db;
    color: #1f2933;
    box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.6);
  }

  /* 4. Button Styling */
  .btn-resume {
    display: inline-block;
    background-color: var(--global-text-color);
    color: var(--global-bg-color) !important;
    padding: 10px 20px;
    border-radius: 5px;
    text-decoration: none;
    font-weight: 600;
    transition: background-color 0.3s, color 0.3s;
    margin-bottom: 1rem;
  }

  .btn-resume:hover {
    background-color:rgb(151, 152, 152);;
    color: var(--global-bg-color) !important;
    text-decoration: none;
  }

  /* Mobile Responsive */
  @media (max-width: 768px) {
    .cv-entry {
      flex-direction: column;
      gap: 5px;
    }
    .cv-date {
      text-align: left;
      flex: none;
      color: var(--global-link-color);
      font-size: 0.9rem;
    }
  }
</style>

<!-- DOWNLOAD BUTTON -->
<div style="text-align: left;">
  <a href="/files/Resume_BitanMallik.pdf" target="_blank" class="btn-resume">
    <i class="fas fa-file-download"></i> View Resume
  </a>
</div>

<!-- WORK EXPERIENCE -->
<h2 class="cv-section-title"><i class="fas fa-briefcase"></i> Work Experience</h2>

<div class="cv-entry">
  <div class="cv-date">2023 – 2025</div>
  <div class="cv-content">
    <div class="cv-job-title">Senior Engineer - Analog Mixed-Signal Design</div>
    <span class="cv-company">Renesas Electronics <span class="cv-location">• Bingen, Germany</span></span>
    <ul>
      <li>Led requirements analysis for industrial Ethernet; created product spec in Polarion; achieved CDR, SDR, LDR gates.</li>
      <li>Designed analog transmitter on 40 nm TSMC for Ethernet PHY IP; verified chip top; simulated package and signed-off.</li>
      <li>Ran cross-team design, layout, and verification reviews across 3 groups; passed compliance test; got first silicon success.</li>
    </ul>
  </div>
</div>

<div class="cv-entry">
  <div class="cv-date">2022 – 2023</div>
  <div class="cv-content">
    <div class="cv-job-title">ICT3 Engineer - AMS Layout Design</div>
    <span class="cv-company">Apple <span class="cv-location">• Munich, Germany</span></span>
    <ul>
      <li>Led a team of 4 engineers to develop PMU using FinFET for Cellular RF SoC; delivered megacell ahead of schedule.</li>
      <li>Managed third-party vendors; organized daily stand-ups, distributed tasks, accomplished goals, and provided feedback.</li>
      <li>Introduced Innovus PnR for AMS blocks and used ParagonX to minimize parasitics; reduced critical-net RC by 20%.</li>
    </ul>
  </div>
</div>

<div class="cv-entry">
  <div class="cv-date">2018 – 2022</div>
  <div class="cv-content">
    <div class="cv-job-title">Research Engineer - Analog Mixed-Signal Design</div>
    <span class="cv-company">Fraunhofer IIS <span class="cv-location">• Erlangen, Germany</span></span>
    <ul>
      <li>Designed a CDR circuit operating at 8 GHz using 22nm GF FDX for ASA-compliant automotive infotainment SoC.</li>
      <li>Designed multiple ROICs on 180nm XFAB/TowerJazz for ToF imaging, smoke detection, & smart farming applications.</li>
      <li>Mentored over 3 research assistants for master thesis; formally reviewed journal, presentation, & research papers.</li>
    </ul>
  </div>
</div>


<!-- EDUCATION -->
<h2 class="cv-section-title"><i class="fas fa-graduation-cap"></i> Education</h2>

<div class="cv-entry">
  <div class="cv-date">2025 – 2026</div>
  <div class="cv-content">
    <div class="cv-job-title">Master of Engineering (M.Eng) in Engineering Management</div>
    <span class="cv-company">Cornell University <span class="cv-location">• Ithaca, New York</span></span>
  </div>
</div>

<div class="cv-entry">
  <div class="cv-date">2015 – 2018</div>
  <div class="cv-content">
    <div class="cv-job-title">Master of Science (M.Sc) in Nanoelectronic Systems</div>
    <span class="cv-company">TU Dresden <span class="cv-location">• Dresden, Germany</span></span>
    <ul>
      <li><strong>GPA:</strong> 3.73/4.00</li>
    </ul>
  </div>
</div>

<div class="cv-entry">
  <div class="cv-date">2009 – 2013</div>
  <div class="cv-content">
    <div class="cv-job-title">Bachelor of Technology (B.Tech) in ECE</div>
    <span class="cv-company">West Bengal University of Technology <span class="cv-location">• Kolkata, India</span></span>
    <ul>
      <li><strong>GPA:</strong> 3.76/4.00</li>
    </ul>
  </div>
</div>


<!-- TECHNICAL SKILLS -->
<h2 class="cv-section-title"><i class="fas fa-tools"></i> Technical Skills</h2>

<div class="cv-entry">
  <div class="cv-date">EDA/IC Tools</div>
  <div class="cv-content skills-container">
    <span class="skill-tag">Cadence Virtuoso</span>
    <span class="skill-tag">ADE Assembler/Spectre/AMS</span>
    <span class="skill-tag">Innovus</span>
    <span class="skill-tag">Quantus/QRC</span>
    <span class="skill-tag">Calibre (DRC/LVS/PEX)</span>
  </div>
</div>

<div class="cv-entry">
  <div class="cv-date">Digital & Coding</div>
  <div class="cv-content skills-container">
    <span class="skill-tag">Verilog (RTL)</span>
    <span class="skill-tag">MATLAB/Simulink</span>
    <span class="skill-tag">C</span>
    <span class="skill-tag">Java</span>
    <span class="skill-tag">Shell Scripting</span>
    <span class="skill-tag">Linux/Windows</span>
  </div>
</div>

<div class="cv-entry">
  <div class="cv-date">Workflow</div>
  <div class="cv-content skills-container">
    <span class="skill-tag">Polarion</span>
    <span class="skill-tag">Confluence</span>
    <span class="skill-tag">JIRA</span>
    <span class="skill-tag">Git</span>
    <span class="skill-tag">LaTeX</span>
  </div>
</div>


<!-- ACADEMIC PROJECTS -->
<h2 class="cv-section-title"><i class="fas fa-project-diagram"></i> Academic Projects</h2>

<div class="cv-entry">
  <div class="cv-date">2017 – 2018</div>
  <div class="cv-content">
    <div class="cv-job-title">M.Sc. Thesis: Fast-start-up SerDes Transmitter</div>
    <span class="cv-company">TU Dresden</span>
    <ul>
      <li>Developed a fast start-up SerDes transmitter for neuromorphic systems; verified architecture in simulation.</li>
      <li>Extracted key metrics (power, area, wake-up time); documented results and defended thesis.</li>
    </ul>
  </div>
</div>

<div class="cv-entry">
  <div class="cv-date">2016 – 2017</div>
  <div class="cv-content">
    <div class="cv-job-title">M.Sc. Project: Low Latency SerDes Link</div>
    <span class="cv-company">TU Dresden</span>
    <ul>
      <li>Designed 2.5 GHz SerDes link and burst-mode CDR (RTL); verified using mixed-mode (AMS) simulation.</li>
      <li>Achieved optimum power efficiency and reduced link initialization delay.</li>
    </ul>
  </div>
</div>


<!-- CERTIFICATIONS & AWARDS GRID -->
<div style="display: flex; flex-wrap: wrap; gap: 2rem; margin-top: 2rem;">
  
  <!-- Certifications -->
  <div style="flex: 1; min-width: 300px;">
    <h2 class="cv-section-title" style="margin-top: 0;"><i class="fas fa-certificate"></i> Certifications</h2>
    <ul style="color: var(--global-text-color); line-height: 1.6;">
      <li><strong>Phase Locked Loops</strong> - Prof. Woogeun Rhee (2024)</li>
      <li><strong>Practical Design of Data Converters</strong> - EPFL (2021)</li>
      <li><strong>Verification & Test of ICs</strong> - eecy-ic gmbH (2020)</li>
    </ul>
  </div>

  <!-- Awards -->
  <div style="flex: 1; min-width: 300px;">
    <h2 class="cv-section-title" style="margin-top: 0;"><i class="fas fa-trophy"></i> Awards</h2>
    <ul style="color: var(--global-text-color); line-height: 1.6;">
      <li><strong>GFF Scholarship</strong> - TU Dresden (2017)</li>
      <li><strong>DAAD Scholarship</strong> - TU Dresden (2016)</li>
    </ul>
  </div>

</div>


<!-- LANGUAGES -->
<h2 class="cv-section-title"><i class="fas fa-language"></i> Languages</h2>
<div class="skills-container">
  <span class="skill-tag">English (Fluent)</span>
  <span class="skill-tag">German (Advanced)</span>
  <span class="skill-tag">Hindi (Fluent)</span>
  <span class="skill-tag">Bengali (Native)</span>
</div>