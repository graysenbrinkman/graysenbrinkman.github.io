---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

<style>

.page__content {
  width: 100%;
}

.projects-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 24px;
  margin-top: 20px;
  max-width: 1150px;
}

/* Card */

.project-card {
  display: flex;
  flex-direction: column;
  background: #f8fafc;
  border: 1px solid #e2e8f0;
  border-radius: 12px;
  overflow: hidden;
  text-decoration: none !important;
  color: inherit !important;
  transition: all 0.25s ease;
  box-shadow: 0 2px 6px rgba(0,0,0,.04);
}

.project-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 10px 24px rgba(0,0,0,.08);
  border-color: #cbd5e1;
}

/* Image */

.project-img-wrapper {
  width: 100%;
  aspect-ratio: 16 / 9;
  overflow: hidden;
  background: #e5e7eb;
}

.project-img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
  transition: transform .3s ease;
}

.project-card:hover .project-img {
  transform: scale(1.04);
}

/* Content */

.project-content {
  padding: 18px;
}

.project-timeline {
  font-size: .75rem;
  text-transform: uppercase;
  letter-spacing: .08em;
  color: #64748b;
  margin-bottom: 10px;
}

.project-title {
  font-size: 1.35rem;
  line-height: 1.25;
  margin: 0 0 12px 0 !important;
  color: #1e293b;
}

.project-summary {
  font-size: .95rem;
  line-height: 1.6;
  color: #475569;
  margin-bottom: 16px;
}

.project-link {
  font-size: .9rem;
  font-weight: 600;
  color: #2563eb;
}

/* Tablet */

@media (max-width: 1100px) {
  .projects-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

/* Mobile */

@media (max-width: 700px) {
  .projects-grid {
    grid-template-columns: 1fr;
  }
}

</style>

<div class="projects-grid">

  <a href="/projects/nozzle-analysis/" class="project-card">

    <div class="project-img-wrapper">
      <img src="/assets/images/NozzleThumb.jpg"
           alt="Compressible Flow Nozzle Analysis"
           class="project-img">
    </div>

    <div class="project-content">

      <div class="project-timeline">
        Apr 2026
      </div>

      <h2 class="project-title">
        Compressible Flow Nozzle Analysis
      </h2>

      <div class="project-summary">
        Developed a computational flow-classification tool for converging-diverging nozzle environments, generating pressure distributions and identifying internal shock locations.
      </div>

      <div class="project-link">
        View Project →
      </div>

    </div>

  </a>

  <a href="/projects/orbit-determination/" class="project-card">

    <div class="project-img-wrapper">
      <img src="/assets/images/orbit-thumb.jpg"
           alt="Orbit Determination"
           class="project-img">
    </div>

    <div class="project-content">

      <div class="project-timeline">
        Mar 2026 – Apr 2026
      </div>

      <h2 class="project-title">
        Orbit Determination Analysis
      </h2>

      <div class="project-summary">
        Utilized MATLAB and the Gauss Method to extract orbital elements from observational tracking data and analyze spacecraft trajectories.
      </div>

      <div class="project-link">
        View Project →
      </div>

    </div>

  </a>

  <a href="/projects/cad-airplane/" class="project-card">

    <div class="project-img-wrapper">
      <img src="/assets/images/cad-thumb.jpg"
           alt="CAD Aircraft Project"
           class="project-img">
    </div>

    <div class="project-content">

      <div class="project-timeline">
        2025
      </div>

      <h2 class="project-title">
        CAD Aircraft Design Project
      </h2>

      <div class="project-summary">
        Designed and modeled a LEGO-inspired aircraft using CATIA, applying fundamental principles of aircraft geometry, assembly design, and technical drafting.
      </div>

      <div class="project-link">
        View Project →
      </div>

    </div>

  </a>

</div>
