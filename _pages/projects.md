---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

<style>

/* Container */

.projects-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(380px, 1fr));
  gap: 28px;
  margin-top: 20px;
}

/* Card */

.project-card {
  display: flex;
  flex-direction: column;

  background: #ffffff;

  border: 1px solid #e5e7eb;
  border-radius: 14px;

  overflow: hidden;

  text-decoration: none !important;
  color: inherit !important;

  box-shadow: 0 2px 8px rgba(0,0,0,0.04);

  transition: all 0.25s ease;
}

.project-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 10px 24px rgba(0,0,0,0.08);
  border-color: #cbd5e1;
}

/* Image */

.project-img-wrapper {
  width: 100%;
  aspect-ratio: 16 / 9;
  overflow: hidden;
  background: #f8fafc;
}

.project-img {
  width: 100%;
  height: 100%;
  object-fit: contain;
  display: block;

  transition: transform 0.3s ease;
}

.project-card:hover .project-img {
  transform: scale(1.03);
}

/* Content */

.project-content {
  padding: 22px;
  display: flex;
  flex-direction: column;
  flex-grow: 1;
}

/* Timeline */

.project-timeline {
  font-size: 0.8rem;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  color: #64748b;
  margin-bottom: 10px;
}

/* Title */

.project-title {
  margin: 0 0 12px 0 !important;

  font-size: 1.5rem !important;
  line-height: 1.25;

  color: #1e293b;
  font-weight: 700 !important;

  transition: color 0.2s ease;
}

.project-card:hover .project-title {
  color: #2563eb;
}

/* Summary */

.project-summary {
  color: #475569;
  line-height: 1.65;
  margin-bottom: 20px;
  flex-grow: 1;
}

/* Link */

.project-link-text {
  display: inline-flex;
  align-items: center;

  color: #2563eb;

  font-weight: 600;
  font-size: 0.95rem;
}

.project-link-text svg {
  margin-left: 6px;
  transition: transform 0.2s ease;
}

.project-card:hover .project-link-text svg {
  transform: translateX(4px);
}

/* Mobile */

@media (max-width: 768px) {

  .projects-list {
    grid-template-columns: 1fr;
  }

  .project-title {
    font-size: 1.3rem !important;
  }

}

</style>

<div class="projects-list">

  <a href="/projects/nozzle-analysis/" class="project-card">

    <div class="project-img-wrapper">
      <img
        src="/assets/images/NozzleThumb.jpg"
        alt="Nozzle Analysis"
        class="project-img">
    </div>

    <div class="project-content">

      <div class="project-timeline">
        Apr 2026
      </div>

      <h2 class="project-title">
        Compressible Flow Nozzle Analysis
      </h2>

      <p class="project-summary">
        Coded a custom computational flow classification program that accurately models converging-diverging nozzle environments, calculating pressure maps and identifying internal shock locations.
      </p>

      <span class="project-link-text">
        View Project Details

        <svg width="14" height="14" viewBox="0 0 16 16" fill="none">
          <path d="M6 12L10 8L6 4"
                stroke="#2563eb"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"/>
        </svg>

      </span>

    </div>

  </a>

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
        Orbit Determination Analysis (Gauss Method)
      </h2>

      <p class="project-summary">
        Developed MATLAB scripts implementing the Gauss Method to determine orbital elements directly from observational tracking measurements.
      </p>

      <span class="project-link-text">
        View Project Details

        <svg width="14" height="14" viewBox="0 0 16 16" fill="none">
          <path d="M6 12L10 8L6 4"
                stroke="#2563eb"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"/>
        </svg>

      </span>

    </div>

  </a>

</div>
