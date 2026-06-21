---
layout: single
title: ""
author_profile: true
layout: single
classes: wide
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

/* Hero Text */

.hero-text {
  position: absolute;
  bottom: 40px;
  left: 35px;
  color: white;
  z-index: 1;
}

.hero-text h1 {
  margin: 0;
  font-size: 2.8rem;
  font-weight: 700;
  line-height: 1.1;
  text-shadow: 1px 1px 4px rgba(0,0,0,0.4);
}

.hero-text p {
  margin: 0.35rem 0 0 0;
  font-size: 1rem;
  font-weight: 400;
  letter-spacing: 0.5px;
  color: rgba(255,255,255,0.9);
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
    font-size: 2rem;
  }

  .hero-text p {
    font-size: 0.85rem;
  }

  .stats-row,
  .card-container {
    flex-direction: column;
  }
}
</style>

<div class="hero-banner">
  <img src="/assets/images/index/airplanebanner.jpg" alt="Aircraft Banner">

  <div class="hero-text">
    <h1>Graysen Brinkman</h1>

    <p>
      Aerospace Engineering Student<br>
      Embry-Riddle Aeronautical University<br>
      4.0 GPA • Applied Mathematics Minor
    </p>

    <div class="hero-links">
      <a href="/resume/">Resume</a>
      <a href="https://linkedin.com/in/YOUR-LINKEDIN">LinkedIn</a>
      <a href="https://github.com/brinkgra">GitHub</a>
      <a href="mailto:graybrinkman06@gmail.com">Contact</a>
    </div>
  </div>
</div>



<div class="about-section">
  <h2>About Me</h2>

  <p>
    I am an Aerospace Engineering student at Embry-Riddle Aeronautical University
    pursuing a concentration in Aeronautics and a minor in Applied Mathematics.
    My interests include aircraft design, autonomous systems, flight mechanics,
    and experimental aerodynamics. This portfolio highlights projects, research
    experiences, and technical work that reflect those interests.
  </p>
</div>

<div class="stats-row">

  <div class="stat-card">
    <h3>GPA</h3>
    <p>4.0 / 4.0</p>
  </div>

  <div class="stat-card">
    <h3>Expected Graduation</h3>
    <p>Winter 2027</p>
  </div>

  <div class="stat-card">
    <h3>Minor</h3>
    <p>Applied Mathematics</p>
  </div>

</div>

<div class="card-container">

  <div class="info-card">
    <h3>Current Highlights</h3>

    <ul>
      <li>Undergraduate Aerospace Engineering Student</li>
      <li>Autonomous UAV Systems Development</li>
      <li>Wind Tunnel Testing Experience</li>
      <li>Academic Research & Engineering Projects</li>
    </ul>
  </div>

  <div class="info-card">
    <h3>Technical Skills</h3>

    <p><strong>Programming:</strong><br>
    MATLAB • Python • ROS 2 • PX4</p>

    <p><strong>Engineering Tools:</strong><br>
    CATIA • CFD</p>

    <p><strong>Documentation & Fabrication:</strong><br>
    LaTeX • 3D Printing</p>
  </div>

</div>

## Featured Projects

<div class="card-container">

  <div class="info-card">
    <h3>Compressible Flow Nozzle Analysis</h3>

    <p>
      Numerical analysis of converging-diverging nozzle performance,
      shock formation, and compressible flow behavior.
    </p>
  </div>

  <div class="info-card">
    <h3>UAV Systems Integration</h3>

    <p>
      Development and testing of autonomous UAV control systems utilizing
      ROS 2, PX4, and offboard control architectures.
    </p>
  </div>

</div>

<br>

<a class="project-button" href="/projects/">
  View All Projects →
</a>
