---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

<style>

/* =========================
   PROJECT GRID
========================= */

.projects-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(400px, 1fr));
  gap: 28px;
  margin-top: 20px;
  max-width: 1050px;
}

/* =========================
   PROJECT CARDS
========================= */

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

  box-shadow: 0 2px 8px rgba(0,0,0,.04);
}

.project-card:hover {
  transform: translateY(-4px);

  border-color: #cbd5e1;

  box-shadow:
    0 10px 24px rgba(0,0,0,.08);
}

/* =========================
   IMAGES
========================= */

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
  transform: scale(1.03);
}

/* =========================
   CONTENT
========================= */

.project-content {
  padding: 22px;
}

.project-timeline {
  font-size: .8rem;
  letter-spacing: .08em;
  text-transform: uppercase;

  color: #64748b;

  margin-bottom: 10px;
}

.project-title {
  margin: 0 0 14px 0 !important;

  font-size: 2rem !important;
  line-height: 1.2;

  color: #1e293b;
}

.project-summary {
  font-size: 1rem;
  line-height: 1.7;

  color: #475569;

  margin-bottom: 16px;
}

.project-link {
  font-size: .95rem;
  font-weight: 600;

  color: #2563eb;
}

/* =========================
   RESPONSIVE
========================= */

@media (max-width: 1100px) {

  .projects-grid {
    grid-template-columns: 1fr;
  }

}

@media (max-width: 700px) {

  .projects-grid {
    grid-template-columns: 1fr;
  }

}

</style>

<div class="projects-grid">

  <!-- PROJECT 1 -->

  <a href="/projects/nozzle-analysis/" class="project-card">

    <div class="project-img-wrapper">
      <img
        src="/assets/images/NozzleThumb.jpg"
        alt="Nozzle Flow Analysis"
        class="project-img">
    </div>

    <div class="project-content">

      <div class="project-timeline">
        Apr 2026
      </div>

      <h2 class="project-title">
        Nozzle Flow Analysis
      </h2>

      <div class="project-summary">
        Developed a computational flow-classification tool for converging-diverging nozzle environments, generating pressure distributions and identifying internal shock locations.
      </div>

      <div class="project-link">
        View Project →
      </div>

    </div>

  </a>

  <!-- PROJECT 2 -->

  <a href="/projects/orbit-determination/" class="project-card">

    <div class="project-img-wrapper">
      <img
        src="/assets/images/orbit-thumb.jpg"
        alt="Orbit Determination"
        class="project-img">
    </div>

    <div class="project-content">

      <div class="project-timeline">
        Mar 2026 – Apr 2026
      </div>

      <h2 class="project-title">
        Orbit Determination
      </h2>

      <div class="project-summary">
        Utilized MATLAB and the Gauss Method to extract orbital elements from observational tracking data and analyze spacecraft trajectories.
      </div>

      <div class="project-link">
        View Project →
      </div>

    </div>

  </a>

  <!-- PROJECT 3 -->

  <a href="/projects/cad-aircraft/" class="project-card">

    <div class="project-img-wrapper">
      <img
        src="/assets/images/cad-thumb.jpg"
        alt="CAD Aircraft Design"
        class="project-img">
    </div>

    <div class="project-content">

      <div class="project-timeline">
        2025
      </div>

      <h2 class="project-title">
        CAD Aircraft Design
      </h2>

      <div class="project-summary">
        Designed and modeled a LEGO-inspired aircraft using CATIA, applying principles of aircraft geometry, assembly design, and technical drafting.
      </div>

      <div class="project-link">
        View Project →
      </div>

    </div>

  </a>

</div>
