---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

<style>
  /* 1. Layout Control: Center the content and limit width */
  .page__content {
    width: 100%;
    display: flex;
    justify-content: center;
  }

  .projects-list {
    display: flex;
    flex-direction: column;
    gap: 24px;
    margin-top: 15px;
    width: 100%;
    max-width: 900px;
  }

  /* 2. Project Card Design */
  .project-card {
    display: flex;
    width: 100%;
    background: #ffffff;
    border: 1px solid #e5e7eb;
    border-radius: 10px;
    overflow: hidden;
    text-decoration: none !important;
    color: inherit !important;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.04);
    transition: all 0.25s ease-in-out;
  }

  .project-card:hover {
    transform: translateY(-2px);
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08);
    border-color: #cbd5e1;
  }

  /* 3. Image & Content Balance (35% Image / 65% Text) */
  .project-img-wrapper {
    width: 35%;
    min-width: 220px;
    background: #f1f5f9;
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
    transform: scale(1.05);
  }

  .project-content {
    padding: 24px;
    width: 65%;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  /* 4. Typography & Elements */
  .project-title {
    margin: 0 0 6px 0 !important;
    font-size: 1.4rem !important;
    font-weight: 700 !important;
    color: #292b2c;
    transition: color 0.2s ease;
    line-height: 1.3;
  }

  .project-card:hover .project-title {
    color: #2563eb;
  }

  .project-timeline {
    font-size: 0.75rem;
    color: #64748b;
    text-transform: uppercase;
    letter-spacing: 0.5px;
    margin-bottom: 10px;
  }

  .project-summary {
    font-size: 0.95rem;
    line-height: 1.5;
    color: #475569;
    margin: 0 0 14px 0;
  }

  .project-link-text {
    font-size: 0.88rem;
    font-weight: 600;
    color: #2563eb;
    display: inline-flex;
    align-items: center;
  }

  .project-link-text svg {
    margin-left: 6px;
    transition: transform 0.2s ease;
  }

  .project-card:hover .project-link-text svg {
    transform: translateX(4px);
  }

  /* 5. Mobile Responsiveness */
  @media (max-width: 768px) {
    .project-card { flex-direction: column; }
    .project-img-wrapper { width: 100%; height: 200px; }
    .project-content { width: 100%; padding: 20px; }
  }
</style>

<div class="projects-list">

  <a href="/projects/nozzle-analysis/" class="project-card">
    <div class="project-img-wrapper">
      <img src="/assets/images/NozzleThumb.jpg" alt="Nozzle Analysis" class="project-img">
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
      <img src="/assets/images/orbit-thumb.jpg" alt="Orbit Determination" class="project-img">
    </div>
    <div class="project-content">
      <div class="project-timeline">Mar 2026 – Apr 2026</div>
      <h2 class="project-title">Orbit Determination (Gauss Method)</h2>
      <p class="project-summary">Developed complex MATLAB scripts utilizing the Gauss Method to extract and process clean orbital elements directly from raw observational tracking data inputs.</p>
      <span class="project-link-text">
        View Project Details 
        <svg width="14" height="14" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M6 12L10 8L6 4" stroke="#2563eb" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
      </span>
    </div>
  </a>

</div>
