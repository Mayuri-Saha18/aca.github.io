---
layout: archive
title: "Project Activities"
permalink: /projects_activity/
author_profile: true
---

<style>
  .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    gap: 1.5rem;
    margin-top: 1.5rem;
  }

  .project-card {
    background-color: #f9f9f9;
    border: 1px solid var(--global-border-color);
    border-radius: 18px;
    padding: 1.75rem;
    box-shadow: 0 20px 40px rgba(15, 23, 42, 0.08);
    display: flex;
    flex-direction: column;
    min-height: 100%;
  }

  html[data-theme="dark"] .project-card {
    background: rgba(67, 68, 72, 0.65);
    border: 1px solid rgba(148, 163, 184, 0.35);
    box-shadow: 0 10px 24px rgba(2, 6, 23, 0.65);
  }

  .project-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-bottom: 1rem;
    gap: 0.5rem;
  }

  .project-title {
    font-size: 1.3rem;
    font-weight: 700;
    margin: 0;
    color: var(--global-text-color);
  }

  .project-date {
    font-size: 0.9rem;
    color: var(--global-text-color-light);
    font-weight: 600;
  }

  .project-subtitle {
    font-size: 1rem;
    font-weight: 600;
    color: var(--global-link-color);
    margin: 0 0 0.75rem 0;
  }

  .project-description {
    font-size: 0.95rem;
    color: var(--global-text-color);
    line-height: 1.6;
    flex: 1;
  }

  .video-wrapper {
    position: relative;
    width: 100%;
    margin-top: 1.25rem;
    aspect-ratio: 16 / 9;
    overflow: hidden;
    border-radius: 12px;
    box-shadow: 0 10px 30px rgba(15,23,42,0.15);
    background: #000;
  }

  .video-wrapper iframe,
  .video-wrapper video {
    width: 100%;
    height: 100%;
    border: none;
    display: block;
  }
</style>

{% include base_path %}

<p>
  Here you will find updates on my ongoing engineering tasks, simulation demos, and project milestones.
</p>

<div class="projects-grid">
  <!-- PROJECT ENTRY 1 (YouTube/Vimeo Embed Example) -->
  <div class="project-card">
    <div class="project-header">
      <h2 class="project-title">High-Speed SerDes Transmitter</h2>
      <span class="project-date">October 2025</span>
    </div>

    <div class="project-subtitle">Initial Eye Diagram Simulation</div>

    <div class="project-description">
      This project focuses on the architecture of a 56Gbps PAM4 transmitter. In this phase, I am verifying the equalization logic using Cadence Virtuoso. The video below demonstrates the adaptive equalizer convergence and the resulting eye opening after channel loss.
    </div>

    <div class="video-wrapper">
      <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" allowfullscreen></iframe>
    </div>
  </div>


  <!-- PROJECT ENTRY 2 (Local Video File Example) -->
  <div class="project-card">
    <div class="project-header">
      <h2 class="project-title">Mixed-Signal Layout Automation</h2>
      <span class="project-date">August 2025</span>
    </div>

    <div class="project-subtitle">Scripting in SKILL & Python</div>

    <div class="project-description">
      An ongoing effort to automate the layout generation for differential pairs to minimize parasitic mismatch. This tool takes a netlist as input and automatically places devices with common-centroid matching. The demo shows the script execution and DRC check.
    </div>

    <div class="video-wrapper">
      <video controls>
        <source src="../files/313145_tiny.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
  </div>
</div>