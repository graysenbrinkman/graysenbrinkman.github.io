---
layout: single
title: ""
permalink: /projects/cad-airplane/
author_profile: false
---

<style>
/* Remove default theme spacing */
.page,
.page__inner-wrap,
.page__content,
.initial-content {
  padding-top: 0 !important;
  margin-top: 0 !important;
}

/* Remove heading anchor icons */
.header-link,
.anchorjs-link {
  display: none !important;
}

/* Main layout */
.project-wrap {
  max-width: 980px;
  margin: 0 auto;
  padding: 0 1rem;
}

/* Hero image */
.project-hero {
  width: 100%;
  margin-bottom: 1.25rem;
}

.project-hero img {
  width: 100%;
  height: auto;
  display: block;
  border-radius: 14px;
  box-shadow: 0 4px 14px rgba(0,0,0,0.08);
}

/* Title */
.project-title {
  margin: 0;
  font-size: 2.35rem;
  line-height: 1.15;
  font-weight: 700;
  color: #0f172a;
}

/* Metadata */
.project-meta {
  margin-top: 0.6rem;
  margin-bottom: 1.4rem;
}

.project-date {
  color: #64748b;
  font-size: 1rem;
  margin-bottom: 0.8rem;
}

.skill-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.55rem;
}

.skill {
  background: #eef2ff;
  color: #3730a3;
  padding: 0.35rem 0.8rem;
  border-radius: 999px;
  font-size: 0.8rem;
  font-weight: 600;
}

.project-divider {
  border: none;
  border-top: 1px solid #e5e7eb;
  margin: 1.6rem 0 2rem;
}

/* Results gallery */
.result-gallery {
  margin-top: 2rem;
}

.result-gallery figure {
  margin: 0 0 2.75rem 0;
}

.result-gallery img {
  width: 100%;
  max-width: 900px;
  display: block;
  margin: 0 auto;
  border-radius: 10px;
  box-shadow: 0 3px 10px rgba(0,0,0,0.08);
}

.result-gallery figcaption {
  margin-bottom: 0.8rem;
  text-align: center;
  color: #64748b;
  font-size: 1rem;
}

/* Side-by-side image pairs */
.drawing-pair {
  display: flex;
  gap: 20px;
  margin-bottom: 2.75rem;
}

.drawing-pair figure {
  flex: 1;
  margin: 0;
}

.drawing-pair img {
  width: 100%;
  display: block;
  border-radius: 10px;
  box-shadow: 0 3px 10px rgba(0,0,0,0.08);
}

.drawing-pair figcaption {
  margin-bottom: 0.8rem;
  text-align: center;
  color: #64748b;
  font-size: 1rem;
}

@media (max-width: 768px) {
  .project-wrap {
    padding: 0 0.75rem;
  }

  .project-title {
    font-size: 1.9rem;
  }

  .drawing-pair {
    flex-direction: column;
  }
}
</style>

<div class="project-wrap">

  <div class="project-hero">
    <img src="/assets/images/cad-airplane/airplanemodified.png" alt="CAD LEGO Airplane Model">
  </div>

  <h1 class="project-title">
    CAD LEGO Airplane Model
  </h1>

  <div class="project-meta">
    <div class="project-date">
      January - April 2026
    </div>

    <div class="skill-tags">
      <span class="skill">CATIA 3D modeling</span>
      <span class="skill">CATIA Assembly</span>
      <span class="skill">CATIA Drafting</span>
      <span class="skill">CATIA Rendering</span>
      <span class="skill">Spatial visualization</span>
    </div>
  </div>

  <hr class="project-divider">

</div>

<h2>Objective</h2>

<p>
The objective of this project was to recreate a physical LEGO aircraft using CATIA by modeling small sections of the set, assembling the complete design, and implementing modifications to improve the original configuration while maintaining compatibility with existing LEGO elements.
</p>

<h2>Design Process</h2>

<p>
Similar LEGO components were grouped to streamline the modeling process and measured using digital calipers. These measurements were translated into individual CATIA parts using features such as pads, pockets, and patterns before being assembled into the complete aircraft. The grouping strategy allowed the model to be constructed from stacked plate assemblies, requiring interference checks and iterative adjustments to resolve overlapping geometry. Design modifications were constrained to existing LEGO components and included the addition of a nose wheel, a redesigned nose cone, and the removal of unnecessary studs to improve both appearance and the conceptual aerodynamic profile. The completed assembly was then documented through engineering drawings and rendered alongside the physical LEGO model for comparison.
</p>

<h2>Results</h2>

<div class="result-gallery">

  <div class="drawing-pair">
    <figure>
      <figcaption><strong>Original LEGO Aircraft</strong></figcaption>
      <img src="/assets/images/cad-airplane/airplaneog.png" alt="Original LEGO Aircraft">
    </figure>

    <figure>
      <figcaption><strong>Modified CAD Assembly</strong></figcaption>
      <img src="/assets/images/cad-airplane/airplanemodified.png" alt="Modified CAD Assembly">
    </figure>
  </div>

  <div class="drawing-pair">
    <figure>
      <figcaption><strong>Assembly Drawing</strong></figcaption>
      <img src="/assets/images/cad-airplane/drafting1.png" alt="Assembly Drawing">
    </figure>

    <figure>
      <figcaption><strong>Component Drawing</strong></figcaption>
      <img src="/assets/images/cad-airplane/drafting2.png" alt="Component Drawing">
    </figure>
  </div>

  <figure>
    <figcaption><strong>Rendered Model</strong></figcaption>
    <img src="/assets/images/cad-airplane/render.png" alt="Rendered Model">
  </figure>

</div>

<p style="text-align:center; margin-top:2rem;">
  <a class="project-button" href="/assets/files/cad-airplane-presentation.pdf" target="_blank">
    View Full Project Presentation →
  </a>
</p>

<h2>Key Takeaways</h2>

<ul>
  <li>Recreated a complex physical LEGO aircraft by reverse engineering individual components into accurate CATIA part models using precision caliper measurements.</li>
  <li>Developed proficiency with CATIA's part design, assembly, drafting, and rendering workbenches throughout the complete design workflow.</li>
  <li>Applied geometric reasoning and interference analysis to resolve part conflicts and successfully assemble a multi-component model.</li>
  <li>Implemented design modifications while maintaining compatibility with existing LEGO components, balancing functional constraints with aesthetic improvements.</li>
  <li>Produced professional engineering drawings and high-quality rendered visualizations to effectively communicate the completed design.</li>
</ul>
