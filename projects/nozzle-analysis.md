/* =========================
   PROJECT HERO
========================= */

.project-hero {
  max-width: 1000px;          /* slightly wider */
  margin: 2rem auto 2rem auto;
  text-align: center;
}

.project-hero img {
  width: 90%;
  max-width: 950px;
  border-radius: 14px;
  display: block;
  margin: 0 auto;

  box-shadow:
    0 6px 18px rgba(0,0,0,.08);
}

.project-title {
  margin-top: 2rem;           /* reduced from ~3rem */
  margin-bottom: 0.5rem;

  font-size: 3.1rem;          /* was visually around 4rem */
  line-height: 1.1;
  font-weight: 700;

  color: #0f172a;
}

.project-date {
  font-size: 1.1rem;
  color: #64748b;

  margin-bottom: 1.25rem;     /* tightened */
}

.skills {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;

  gap: 0.75rem;

  margin-bottom: 2rem;        /* tightened */
}

.skill {
  background: #eef2ff;
  color: #3730a3;

  padding: 0.55rem 1.25rem;

  border-radius: 999px;

  font-size: 1rem;
  font-weight: 500;
}

.project-divider {
  border: none;
  border-top: 1px solid #e5e7eb;

  margin: 0 auto 2.5rem auto;
  max-width: 950px;
}

<div class="project-hero">

  <img
    src="/assets/images/NozzleThumb.jpg"
    alt="Nozzle Flow Classification">

  <h1 class="project-title">
    Nozzle Flow Classification
  </h1>

  <div class="project-date">
    April 2026
  </div>

  <div class="skills">
    <span class="skill">MATLAB</span>
    <span class="skill">Compressible Aerodynamics</span>
    <span class="skill">Flow Classification</span>
    <span class="skill">Numerical Methods</span>
    <span class="skill">Data Visualization</span>
  </div>

  <hr class="project-divider">

</div>
