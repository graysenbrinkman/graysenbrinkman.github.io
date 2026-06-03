---
layout: single
title: "Projects"
permalink: /projects/
author_profile: false
classes: wide
---

<style>
  /* Page layout normalization */
  .sidebar { display: none !important; }
  .page { width: 100% !important; float: none !important; padding-right: 0 !important; }
  
  #main {
    width: 100% !important;
    max-width: 900px !important;
    margin: 0 auto !important;
    padding: 0 20px !important;
  }

  /* Scrollable Card Container List */
  .projects-list {
    display: flex;
    flex-direction: column;
    gap: 24px;
    margin-top: 30px;
  }

  /* Rectangular Project Card */
  .project-card {
    display: flex;
    background: #ffffff;
    border: 1px solid #e5e7eb;
    border-radius: 10px;
    overflow: hidden;
    text-decoration: none !important;
    color: inherit !important;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.04);
    transition: all 0.25s ease-in-out;
  }

  /* Elegant Card Hover Effect */
  .project-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08);
    border-color: #cbd5e1;
  }

  /* Preview Image Container */
  .project-img-wrapper {
    width: 35%;
    min-width: 220px;
    background: #f8fafc;
    position: relative;
    overflow: hidden;
  }

  .project-img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
    transition: transform 0.3s ease;
  }

  .project-card:hover .project-img {
    transform: scale(1.03);
  }

  /* Text Content Container */
  .project-content {
    padding: 24px;
    width: 65%;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .project-title {
    margin: 0 0 8px 0 !important;
    font-size: 1.4rem !important;
    font-weight: 700 !important;
    color: #292b2c;
    transition: color 0.2s ease;
  }

  .project-card:hover .project-title {
    color: #2563eb; /* Title turns crisp blue on card hover */
  }

  .project-timeline {
    font-size: 0.8rem;
    color: #64748b;
    text-transform: uppercase;
    letter-spacing: 0.5px;
    margin-bottom: 12px;
  }

  .project-summary {
    font-size: 0.95rem;
    line-height: 1.5;
    color: #475569;
    margin: 0 0 16px 0;
  }

  /* Clean "View Full Project" Text Link */
  .project-link-text {
    font-size: 0.88rem;
    font-weight: 600;
    color: #2563eb;
    display: inline-flex;
    align-items: center;
  }

  .project-link-text svg {
    margin-left: 4px;
    transition: transform 0.2s ease;
  }

  .project-card:hover .project-link-text svg {
    transform: translateX(3px);
  }

  /* Responsive adjustment for small/mobile screens */
  @media (max-width: 640px) {
    .project-card { flex-direction: column; }
    .project-img-wrapper { width: 100%; height: 180px; }
    .project-content { width: 100%; padding: 20px; }
  }
</style>

<div class="projects-list">

  <a href="/projects/airhound/" class="project-card">
    <div class="project-img-wrapper">
      <img src="/assets/images/airhound-thumb.jpg" alt="AIRHOUND Project" class="project-img" onerror="this.src='https://placehold.co/600x400/f1f5f9/64748b?text=UAV+Control'">
    </div>
    <div class="project-content">
      <div class="project-timeline">Aug 2025 – Apr 2026</div>
      <h2 class="project-title">AIRHOUND Project: Offboard Control & PX4 Integration</h2>
      <p class="project-summary">Integrated advanced PX4 middleware to establish reliable onboard and offboard UAV flight control communication architectures for autonomous flight systems.</p>
      <span class="project-link-text">
        View Project Details 
        <svg width="14" height="14" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M6 12L10 8L6 4" stroke="#2563eb" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
      </span>
    </div>
  </a>

  <a href="/projects/nozzle-analysis/" class="project-card">
    <div class="project-img-wrapper">
      <img src="/assets/images/nozzle-thumb.jpg" alt="Nozzle Analysis Project" class="project-img" onerror="this.src='https://placehold.co/600x400/f1f5f9/64748b?text=Nozzle+Analysis'">
    </div>
    <div class="project-content">
      <div class="project-timeline">Apr 2026</div>
      <h2 class="project-title">Compressible Flow Nozzle Analysis</h2>
      <p class="project-summary">Coded a custom computational flow classification program that accurately models converging-diverging nozzle environments, calculating pressure maps and mapping internal shock locations.</p>
      <span class="project-link-text">
        View Project Details 
        <svg width="14" height="14" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M6 12L10 8L6 4" stroke="#2563eb" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
      </span>
    </div>
  </a>

  <a href="/projects/orbit-determination/" class="project-card">
    <div class="project-img-wrapper">
      <img src="/assets/images/orbit-thumb.jpg" alt="Orbit Determination Project" class="project-img" onerror="this.src='https://placehold.co/600x400/f1f5f9/64748b?text=Orbit+Determination'">
    </div>
    <div class="project-content">
      <div class="project-timeline">Mar 2026 – Apr 2026</div>
      <h2 class="project-title">Orbit Determination Analysis (Gauss Method)</h2>
      <p class="project-summary">Developed complex MATLAB scripts utilizing the Gauss Method to extract and process clean orbital elements directly from raw observational tracking data inputs.</p>
      <span class="project-link-text">
        View Project Details 
        <svg width="14" height="14" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M6 12L10 8L6 4" stroke="#2563eb" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
      </span>
    </div>
  </a>

</div>
