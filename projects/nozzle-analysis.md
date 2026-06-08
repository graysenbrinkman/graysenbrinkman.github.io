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

/* Hide heading anchor links */

.header-link,
.anchorjs-link {
  display: none !important;
}

/* Main wrapper */

.project-wrap {
  max-width: 980px;
  margin: 0 auto;
  padding: 0 1rem;
}

/* Hero image */

.project-hero {
  width: 100%;
  margin-bottom: 1rem;
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
  margin: 0.25rem 0 0.4rem;
  font-size: 2.15rem;
  font-weight: 700;
  line-height: 1.1;
  color: #0f172a;
}

/* Meta information */

.project-meta {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 0.75rem 1rem;
  margin-bottom: 1.35rem;
  color: #64748b;
  font-size: 0.98rem;
}

.project-date {
  font-weight: 500;
}

/* Skill pills */

.skill-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
}

.skill {
  background: #eef2ff;
  color: #3730a3;
  padding: 0.35rem 0.8rem;
  border-radius: 999px;
  font-size: 0.8rem;
  font-weight: 600;
}

/* Divider */

.project-divider {
  border: none;
  border-top: 1px solid #e5e7eb;
  margin: 1.5rem 0;
}

/* Mobile */

@media (max-width: 768px) {

  .project-wrap {
    padding: 0 0.75rem;
  }

  .project-title {
    font-size: 1.8rem;
  }

}

</style>

<div class="project-wrap">

  <div class="project-hero">
    <img src="/assets/images/nozzle-project/Nozzle1.jpg"
         alt="Nozzle Flow Classification">
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

<p>
The developed MATLAB program successfully classified all seven operating
conditions for the converging-diverging nozzle by varying the back pressure
ratio. Representative outputs for each regime are shown below.
</p>

<style>
.results-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 1.5rem;
  margin-top: 1.5rem;
}

.result-card img {
  width: 100%;
  display: block;
  border-radius: 10px;
  box-shadow: 0 3px 10px rgba(0,0,0,0.08);
}

.result-caption {
  margin-top: 0.5rem;
  text-align: center;
  font-size: 0.9rem;
  color: #64748b;
}

@media (max-width: 768px) {
  .results-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="results-grid">

  <div class="result-card">
    <img src="/assets/images/nozzle-project/Nozzle1.jpg" alt="Case 1">
    <div class="result-caption">Case 1 — Not Choked</div>
  </div>

  <div class="result-card">
    <img src="/assets/images/nozzle-project/Nozzle2.jpg" alt="Case 2">
    <div class="result-caption">Case 2 — Choked at Throat</div>
  </div>

  <div class="result-card">
    <img src="/assets/images/nozzle-project/Nozzle3.jpg" alt="Case 3">
    <div class="result-caption">Case 3 — Normal Shock in Diverging Section</div>
  </div>

  <div class="result-card">
    <img src="/assets/images/nozzle-project/Nozzle4.jpg" alt="Case 4">
    <div class="result-caption">Case 4 — Shock at Exit</div>
  </div>

  <div class="result-card">
    <img src="/assets/images/nozzle-project/Nozzle5.jpg" alt="Case 5">
    <div class="result-caption">Case 5 — Overexpanded Flow</div>
  </div>

  <div class="result-card">
    <img src="/assets/images/nozzle-project/Nozzle6.jpg" alt="Case 6">
    <div class="result-caption">Case 6 — Ideally Expanded Flow</div>
  </div>

  <div class="result-card">
    <img src="/assets/images/nozzle-project/Nozzle7.jpg" alt="Case 7">
    <div class="result-caption">Case 7 — Underexpanded Flow</div>
  </div>

</div>

## Key Takeaways
