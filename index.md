---
layout: single
title: ""
author_profile: true
permalink: /
---

<style>
.hero-banner {
  position: relative;
  margin-bottom: 2rem;
  border-radius: 12px;
  width: 100%;
  overflow: hidden;
}

/* Dark gradient for text readability */
.hero-banner::after {
  content: "";
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 60%;
  background: linear-gradient(
    to top,
    rgba(0,0,0,0.85) 0%,
    rgba(0,0,0,0) 100%
  );
  pointer-events: none;
}

.hero-banner img {
  width: 100%;
  height: 400px;
  object-fit: cover;
  display: block;
}

.hero-text {
  position: absolute;
  bottom: 40px;
  left: 35px;
  color: white;
  z-index: 1;
}

.hero-text h1 {
  margin: 0;
  font-size: 3.5rem;
  font-weight: 700;
  line-height: 1.1;
  text-shadow: 1px 1px 4px rgba(0,0,0,0.4);
}

/* About Section */

.about-section {
  background: #f8f9fb;
  padding: 2rem;
  border-radius: 12px;
  margin-bottom: 2rem;
}

.about-section h2 {
  margin-top: 0;
}

/* Stats */

.stats-row {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  margin-bottom: 2rem;
}

.stat-card {
  flex: 1;
  min-width: 200px;
  background: #f8f9fb;
  border-radius: 10px;
  padding: 1.25rem;
  text-align: center;
  border: 1px solid #e5e7eb;
}

.stat-card h3 {
  margin: 0;
  font-size: 1.1rem;
  color: #1e293b;
}

.stat-card p {
  margin: 0.5rem 0 0;
  color: #64748b;
}

/* Information Cards */

.card-container {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  margin-bottom: 2rem;
}

.info-card {
  flex: 1;
  min-width: 280px;
  background: #f8f9fb;
  border-radius: 10px;
  padding: 1.5rem;
  border: 1px solid #e5e7eb;
}

.info-card h3 {
  margin-top: 0;
  color: #1e293b;
  border-bottom: 2px solid #e2e8f0;
  padding-bottom: 0.5rem;
}

/* Projects Button */

.project-button {
  display: inline-block;
  padding: 12px 24px;
  border-radius: 8px;
  background: #2563eb;
  color: white !important;
  text-decoration: none;
  font-weight: 600;
  transition: background 0.2s ease;
}

.project-button:hover {
  background: #1d4ed8;
  text-decoration: none;
}

/* Mobile */

@media (max-width: 768px) {
  .hero-banner img {
    height: 300px;
  }

  .hero-text h1 {
    font-size: 2.4rem;
  }

  .stats-row,
  .card-container {
    flex-direction: column;
  }
}
</style>

<div class="hero-banner">
  <img src="/assets/images/airplanebanner.jpg" alt="Aircraft Banner">

  <div class="hero-text">
    <h1>Engineering Portfolio</h1>
  </div>
</div>

<div class="about-section">
  <h2>About Me</h2>

  <p>
    I am a second-year Aerospace Engineering student at Embry-Riddle
    Aeronautical University pursuing a Bachelor of Science in Aerospace
    Engineering with a concentration in Aeronautics and a minor in Applied
    Mathematics.
  </p>

  <p>
    This portfolio showcases my academic projects, research experiences,
    technical skills, and professional development as I work toward a career
    in the aerospace industry.
  </p>
</div>

<div class="stats-row">

  <div class="stat-card">
    <h3>Aerospace Engineering</h3>
    <p>B.S. Candidate</p>
  </div>

  <div class="stat-card">
    <h3>Applied Mathematics</h3>
    <p>Minor</p>
  </div>

  <div class="stat-card">
    <h3>Expected Graduation</h3>
    <p>Winter 2027</p>
  </div>

</div>

<div class="card-container">

  <div class="info-card">
    <h3>Areas of Interest</h3>

    <ul>
      <li>Flight Mechanics & Aircraft Design</li>
      <li>Autonomous Systems & UAV Offboard Control</li>
      <li>Wind Tunnel Testing</li>
      <li>Aerodynamics & Compressible Flow</li>
    </ul>
  </div>

  <div class="info-card">
    <h3>Technical Skills</h3>

    <p><strong>Programming:</strong> MATLAB, ROS 2, Python, PX4</p>

    <p><strong>Engineering Software:</strong> CATIA</p>

    <p><strong>Documentation & Fabrication:</strong> LaTeX, 3D Printing</p>
  </div>

</div>

## Featured Work

Explore engineering projects involving compressible flow nozzle analysis, orbit determination utilizing the Gauss Method, and the AIRHOUND UAV integration project.

<br>

<a class="project-button" href="/projects/">
  View Projects →
</a>
