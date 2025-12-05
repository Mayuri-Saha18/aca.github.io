---
layout: archive
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

<style>
.highlight-banner {
  background-image: linear-gradient(rgba(0, 0, 0, 0.45), rgba(0, 0, 0, 0.55)), 
              url('/images/cornell-campus.jpg');
  background-size: 100% 100%;
  background-position: center center;
  background-repeat: no-repeat;
  border: 1px solid rgba(255, 255, 255, 0.15);
  border-radius: 12px;
  padding: 2rem 2rem;
  margin-bottom: 2rem;
  position: relative;
  min-height: 250px;
  display: flex;
  align-items: center;
}

.highlight-content {
  display: flex;
  flex-direction: column;
  gap: 0.8rem;
  position: relative;
  z-index: 2;
}

.highlight-row {
  display: flex;
  align-items: baseline;
  gap: 0.75rem;
}

.highlight-label {
  font-size: 0.75rem;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  font-weight: 700;
  color: #7dd3fc;
  min-width: 110px;
  flex-shrink: 0;
  text-shadow: 0 1px 3px rgba(0, 0, 0, 0.5);
}

.highlight-text {
  font-size: 0.9rem;
  color: #ffffff;
  margin: 0;
  line-height: 1.5;
  text-shadow: 0 1px 3px rgba(0, 0, 0, 0.5);
}

.highlight-text strong {
  color: #ffffff;
  font-weight: 700;
}

.highlight-link {
  color: #7dd3fc;
  font-weight: 600;
  text-decoration: none;
  margin-left: 0.5rem;
  font-size: 0.85rem;
  text-shadow: 0 1px 3px rgba(0, 0, 0, 0.5);
}

.highlight-link:hover {
  text-decoration: underline;
  color: #bae6fd;
}

html[data-theme="dark"] .highlight-banner {
  background-image: linear-gradient(rgba(0, 0, 0, 0.55), rgba(0, 0, 0, 0.65)), 
              url('/images/cornell-campus.jpg');
  background-size: cover;
  background-position: center center;
  background-repeat: no-repeat;
  border: 1px solid rgba(255, 255, 255, 0.1);
}

@media (max-width: 768px) {
  .highlight-banner {
    padding: 1.25rem;
    min-height: 150px;
  }
  .highlight-row {
    flex-direction: column;
    gap: 0.2rem;
  }
  .highlight-label {
    min-width: auto;
    margin-bottom: 2px;
  }
}
</style>

<div class="highlight-banner">
  <div class="highlight-content">
    <div class="highlight-row">
      <span class="highlight-label"><i class="fas fa-briefcase" style="margin-right: 6px;"></i>Status</span>
      <p class="highlight-text">
        Seeking <strong>Analog Mixed-Signal Design</strong> roles (Summer 2026).
        <a href="/cv/" class="highlight-link">View CV →</a>
      </p>
    </div>
    <div class="highlight-row">
      <span class="highlight-label"><i class="fas fa-microphone-alt" style="margin-right: 8px;"></i>Latest Talk</span>
      <p class="highlight-text">
        Guest Lecture: <strong>Advanced Circuit Design</strong> (EE301, Fall 2024).
        <a href="https://www.youtube.com/watch?v=7vbgmH7sLNQ" class="highlight-link" target="_blank">Watch →</a>
      </p>
    </div>
    <div class="highlight-row">
      <span class="highlight-label"><i class="fas fa-trophy" style="margin-right: 8px;"></i>Award</span>
      <p class="highlight-text">
        Recipient of the <strong>GFF Scholarship</strong> (TU Dresden, 2017).
      </p>
    </div>
  </div>
</div>

Hello! I'm Bitan Mallik, a seasoned Analog Mixed-Signal Design Engineer currently pursuing a Master of Engineering in Engineering Management at Cornell University (Class of 2026). With over 6 years of professional experience in semiconductor industry, I specialize in designing high-performance analog and mixed-signal circuits for advanced applications.

## Professional Background

My career has been defined by working at leading technology companies on cutting-edge semiconductor projects:

* **Renesas Electronics (2023-2025)**: Led requirements analysis and analog transmitter design for industrial Ethernet PHY IP on 40nm TSMC, achieving first silicon success.
* **Apple (2022-2023)**: Managed a team of 4 engineers developing PMU using FinFET technology for Cellular RF SoC, introducing advanced PnR techniques that reduced critical-net RC by 20%.
* **Fraunhofer IIS (2018-2022)**: Designed CDR circuits and multiple ROICs for automotive, ToF imaging, and IoT applications using advanced process nodes.

## Technical Expertise

I have extensive experience with:
* **EDA Tools**: Cadence Virtuoso (ADE, Spectre, AMS), Innovus, Quantus/QRC, Calibre (DRC/LVS)
* **Circuit Design**: SerDes, CDR, PLLs, Data Converters, PMU, Analog Transmitters
* **Process Technologies**: 22nm GF FDX, 40nm TSMC, 180nm XFAB/TowerJazz, FinFET
* **Workflow**: Polarion, Confluence, JIRA, Git, LaTeX

## Education

* **M.Eng in Engineering Management**, Cornell University, 2025-2026
* **M.Sc in Nanoelectronic Systems**, TU Dresden, Germany, 2015-2018 (GPA: 3.73/4.00)
* **B.Tech in Electronics and Communication Engineering**, West Bengal University of Technology, India, 2009-2013 (GPA: 3.76/4.00)

## Languages

* English (Fluent)
* German (Advanced)
* Hindi (Fluent)
* Bengali (Native)
