---
layout: single
title: ""
permalink: /projects/nozzle-analysis/
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

/* Hide anchor links beside headings */

.header-link {
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
  margin-top: 0.8rem;
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

}

</style>

<div class="project-wrap">

  <div class="project-hero">
    <img src="/assets/images/nozzle-project/Nozzle4.jpg" alt="Nozzle Flow Classification">
  </div>

  <h1 class="project-title">
    Nozzle Flow Classification
  </h1>

  <div class="project-meta">

    <div class="project-date">
      April 2026
    </div>

    <div class="skill-tags">
      <span class="skill">MATLAB</span>
      <span class="skill">Compressible Aerodynamics</span>
      <span class="skill">Flow Classification</span>
      <span class="skill">Numerical Methods</span>
      <span class="skill">Data Visualization</span>
    </div>

  </div>

  <hr class="project-divider">

</div>

## Objective

The goal of this project was to analyze flow in a converging-diverging nozzle under different flow conditions in order to identify key elements of nozzle flow, such as exit velocity, as well as shock location and angle wherever possible.

## Methodology

A MATLAB program was developed to classify flow within a converging-diverging nozzle based on the specified back pressure ratio. The implementation applied compressible flow relations to determine the operating regime and calculate key flow properties, including exit conditions and the location of normal shocks when present. The results were then compared against theoretical nozzle behavior to verify the accuracy of the classification algorithm.

## Results

The developed MATLAB program successfully classified all seven operating conditions for the converging-diverging nozzle by varying the back pressure ratio. Representative outputs for each operating regime are shown below.

<div class="result-gallery">

  <figure>
    <img src="/assets/images/nozzle-project/Nozzle1.jpg" alt="Case 1">
    <figcaption><strong>Case 1.</strong> Not Choked Flow</figcaption>
  </figure>

  <figure>
    <img src="/assets/images/nozzle-project/Nozzle2.jpg" alt="Case 2">
    <figcaption><strong>Case 2.</strong> Choked at the Throat</figcaption>
  </figure>

  <figure>
    <img src="/assets/images/nozzle-project/Nozzle3.jpg" alt="Case 3">
    <figcaption><strong>Case 3.</strong> Normal Shock in the Diverging Section</figcaption>
  </figure>

  <figure>
    <img src="/assets/images/nozzle-project/Nozzle4.jpg" alt="Case 4">
    <figcaption><strong>Case 4.</strong> Normal Shock at the Exit Plane</figcaption>
  </figure>

  <figure>
    <img src="/assets/images/nozzle-project/Nozzle5.jpg" alt="Case 5">
    <figcaption><strong>Case 5.</strong> Overexpanded Flow</figcaption>
  </figure>

  <figure>
    <img src="/assets/images/nozzle-project/Nozzle6.jpg" alt="Case 6">
    <figcaption><strong>Case 6.</strong> Perfectly Expanded Flow</figcaption>
  </figure>

  <figure>
    <img src="/assets/images/nozzle-project/Nozzle7.jpg" alt="Case 7">
    <figcaption><strong>Case 7.</strong> Underexpanded Flow</figcaption>
  </figure>

</div>

## Key Takeaways

- Implemented a MATLAB tool to classify converging-diverging nozzle operating regimes.
- Applied compressible flow theory to compute exit conditions and identify shock locations.
- Verified predicted flow behavior against theoretical expectations for seven representative pressure ratios.
- Strengthened understanding of quasi-one-dimensional compressible flow and numerical implementation techniques.
```
