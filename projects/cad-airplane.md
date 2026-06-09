---
layout: single
title: ""
permalink: /projects/cad-airplane/
author_profile: false
---

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

/* Side-by-side image pairs */

.drawing-pair {
  display: flex;
  gap: 16px;
  justify-content: center;
  align-items: flex-start;
}

.drawing-pair img {
  width: calc(50% - 8px);
  max-width: none;
  margin: 0;
}

/* Mobile */

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

  .drawing-pair img {
    width: 100%;
  }

}

</style>

<div class="project-wrap">

  <div class="project-hero">
    <img src="/assets/images/cad-airplane/airplanemodified.png" alt="Nozzle Flow Classification">
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

## Objective

The objective of this project was to recreate a physical LEGO aircraft using CATIA by modeling small sections of the set, assembling the complete design, and implementing modifications to improve the original configuration while maintaining compatibility with existing LEGO elements.

## Design Process
Similar LEGO components were grouped to streamline the modeling process and measured using digital calipers. These measurements were translated into individual CATIA parts using features such as pads, pockets, and patterns before being assembled into the complete aircraft. The grouping strategy allowed the model to be constructed from stacked plate assemblies, requiring interference checks and iterative adjustments to resolve overlapping geometry. Design modifications were constrained to existing LEGO components and included the addition of a nose wheel, a redesigned nose cone, and the removal of unnecessary studs to improve both appearance and the conceptual aerodynamic profile. The completed assembly was then documented through engineering drawings and rendered alongside the physical LEGO model for comparison.


## Results

<div class="result-gallery">

  <!-- CAD Models -->

  <figure>

    <div class="drawing-pair">

      <div>
        <figcaption><strong>Original LEGO Aircraft</strong></figcaption>
        <img src="/assets/images/cad-airplane/airplaneog.png"
             alt="Original LEGO Aircraft">
      </div>

      <div>
        <figcaption><strong>Modified CAD Assembly</strong></figcaption>
        <img src="/assets/images/cad-airplane/airplanemodified.png"
             alt="Modified CAD Assembly">
      </div>

    </div>

  </figure>

  <!-- Engineering Drawings -->

  <figure>

    <div class="drawing-pair">

      <div>
        <figcaption><strong>Assembly Drawing</strong></figcaption>
        <img src="/assets/images/cad-airplane/drafting1.png"
             alt="Assembly Drawing">
      </div>

      <div>
        <figcaption><strong>Part Drawing</strong></figcaption>
        <img src="/assets/images/cad-airplane/drafting2.png"
             alt="Part Drawing">
      </div>

    </div>

  </figure>

  <!-- Render -->

  <figure>
    <figcaption><strong>Rendered Model</strong></figcaption>
    <img src="/assets/images/cad-airplane/render.png"
         alt="Rendered Model">
  </figure>

</div>

<p style="text-align:center; margin-top:2rem;">
  <a class="project-button"
     href="/assets/files/cad-airplane-presentation.pdf"
     target="_blank">
    View Full Project Presentation →
  </a>
</p>


## Key Takeaways

- Recreated a complex physical LEGO aircraft by reverse engineering individual components into accurate CATIA part models using precision caliper measurements.

- Developed proficiency with CATIA's part design, assembly, drafting, and rendering workbenches throughout the complete design workflow.

- Applied geometric reasoning and interference analysis to resolve part conflicts and successfully assemble a multi-component model.

- Implemented design modifications while maintaining compatibility with existing LEGO components, balancing functional constraints with aesthetic improvements.

- Produced professional engineering drawings and high-quality rendered visualizations to effectively communicate the completed design.
