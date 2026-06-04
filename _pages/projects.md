---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

<style>
/* Main Container */
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  gap: 24px;
  margin-top: 20px;
}

/* Project Cards */
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
  box-shadow: 0 2px 8px rgba(0,0,0,0.04);
}

.project-card:hover {
  transform: translateY(-4px);
  border-color: #cbd5e1;
  box-shadow: 0 12px 24px rgba(0,0,0,0.08);
}

.project-image {
  width: 100%;
  height: 220px;
  overflow: hidden;
  background: #e2e8f0;
}

.project-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
  transition: transform 0.3s ease;
}

.project-card:hover .project-image img {
  transform: scale(1.04);
}

/* Content */
.project-content {
  padding: 22px;
  display: flex;
  flex-direction: column;
  flex-grow: 1;
}

.project-date {
  font-size: 0.8rem;
  text-transform: uppercase;
  letter-spacing: 1px;
  color: #64748b;
  margin-bottom: 10px;
}

.project-title {
  font-size: 1.45rem;
  font-weight: 700;
  line-height: 1.25;
  color: #1e293b;
  margin-bottom: 12px;
}

.project-summary {
  font-size: 0.95rem;
  line-height: 1.65;
  color: #475569;
  flex-grow: 1;
  margin-bottom: 18px;
}

.project-link {
  font-weight: 600;
  color: #2563eb;
  text-decoration: none;
}

.project-link:hover {
  color: #1d4ed8;
}

/* Mobile */
@media (max-width: 768px) {
  .projects-grid {
    grid-template-columns: 1fr;
  }

  .project-image {
    height: 200px;
  }
}
</style>

<div class="projects-grid">

  <!-- Project 1 -->
  <a href="/projects/nozzle-analysis/" class="project-card">
    <div class="project-image">
      <img src="/assets/images/NozzleThumb.jpg" alt="Compressible Flow Nozzle Analysis">
    </div>

    <div class="project-content">
      <div class="project-date">Apr 2026</div>

      <div class="project-title">
        Compressible Flow Nozzle Analysis
      </div>

      <div class="project-summary">
        Developed a MATLAB computational flow-classification tool for converging-diverging nozzles, generating pressure distributions and identifying internal shock locations across multiple operating regimes.
      </div>

      <div class="project-link">
        View Project →
      </div>
    </div>
  </a>

  <!-- Project 2 -->
  <a href="/projects/orbit-determination/" class="project-card">
    <div class="project-image">
      <img src="/assets/images/orbit-thumb.jpg" alt="Orbit Determination">
    </div>

    <div class="project-content">
      <div class="project-date">Mar 2026 – Apr 2026</div>

      <div class="project-title">
        Orbit Determination Using the Gauss Method
      </div>

      <div class="project-summary">
        Created MATLAB scripts implementing the Gauss Method to determine orbital elements from observational tracking data and analyze spacecraft trajectories.
      </div>

      <div class="project-link">
        View Project →
      </div>
    </div>
  </a>

  <!-- Project 3 -->
  <a href="#" class="project-card">
    <div class="project-image">
      <img src="/assets/images/cad-aircraft-thumb.jpg" alt="CAD Aircraft Design">
    </div>

    <div class="project-content">
      <div class="project-date">2025</div>

      <div class="project-title">
        CAD Aircraft Design Project
      </div>

      <div class="project-summary">
        Designed and modeled a LEGO-inspired aircraft using computer-aided design principles, developing proficiency in 3D modeling, assemblies, engineering drawings, and design iteration.
      </div>

      <div class="project-link">
        View Project →
      </div>
    </div>
  </a>

</div>
