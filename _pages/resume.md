---
layout: single
title: ""
permalink: /resume/
author_profile: false
classes: wide
---

<style>

/* Hide sidebar and extra theme elements */
.sidebar,
.page__related,
.page__meta,
.page__share {
  display: none !important;
}

/* Hide default page title */
.page__title {
  display: none !important;
}

/* Center page */
.page {
  width: 100% !important;
  float: none !important;
  padding-right: 0 !important;
}

#main,
.page__inner-wrap,
.page__content {
  width: 100% !important;
  max-width: 1000px !important;
  margin-left: auto !important;
  margin-right: auto !important;
  padding-left: 20px !important;
  padding-right: 20px !important;
}

/* Header */

.resume-hero {
  text-align: center;
  margin: 1rem 0 2rem 0;
}

.resume-hero h1 {
  margin: 0;
  font-size: 2.75rem;
  font-weight: 700;
  color: #111827;
}

.resume-hero p {
  margin-top: 0.75rem;
  color: #6b7280;
  font-size: 1rem;
}

/* Buttons */

.resume-actions {
  display: flex;
  justify-content: center;
  gap: 12px;
  flex-wrap: wrap;
  margin-bottom: 2rem;
}

.resume-btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;

  padding: 12px 22px;

  border-radius: 8px;

  font-size: 0.95rem;
  font-weight: 600;

  text-decoration: none !important;

  transition: all 0.2s ease;
}

/* Download button */

.resume-btn.primary {
  background: #111827;
  color: #ffffff !important;
  border: 1px solid #111827;
}

.resume-btn.primary:hover {
  background: #1f2937;
  border-color: #1f2937;
  color: #ffffff !important;
  transform: translateY(-1px);
}

/* Secondary button */

.resume-btn.secondary {
  background: #ffffff;
  color: #111827 !important;
  border: 1px solid #d1d5db;
}

.resume-btn.secondary:hover {
  background: #f9fafb;
  color: #111827 !important;
  transform: translateY(-1px);
}

/* Resume Card */

.resume-card {
  background: #ffffff;
  border-radius: 16px;
  box-shadow: 0 8px 24px rgba(0,0,0,0.06);
  overflow: hidden;
}

.resume-card-header {
  padding: 1rem 1.5rem;
  border-bottom: 1px solid #f1f5f9;

  display: flex;
  justify-content: space-between;
  align-items: center;
}

.resume-card-header .label {
  font-size: 0.85rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  color: #6b7280;
}

.resume-card-header .subtext {
  color: #6b7280;
  font-size: 0.9rem;
}

/* PDF Preview */

.resume-preview {
  width: 100%;
  height: 82vh;
  min-height: 850px;
  background: white;
}

.resume-preview iframe {
  width: 100%;
  height: 100%;
  border: none;
  display: block;
}

/* Footer note */

.resume-note {
  text-align: center;
  margin-top: 1rem;
  color: #6b7280;
  font-size: 0.95rem;
}

/* Mobile */

@media (max-width: 768px) {

  #main,
  .page__inner-wrap,
  .page__content {
    padding-left: 12px !important;
    padding-right: 12px !important;
  }

  .resume-hero h1 {
    font-size: 2.2rem;
  }

  .resume-preview {
    height: 70vh;
    min-height: 600px;
  }

  .resume-card-header {
    flex-direction: column;
    gap: 0.5rem;
    align-items: flex-start;
  }
}

</style>

<div class="resume-hero">
  <h1>Resume</h1>

  <p>
    Download my current resume or view the PDF below.
  </p>
</div>

<div class="resume-actions">

  <a
    href="/assets/files/GraysenBrinkmanResume.pdf"
    download="Graysen_Brinkman_Resume.pdf"
    class="resume-btn primary">

    Download PDF

  </a>

  <a
    href="/assets/files/GraysenBrinkmanResume.pdf"
    target="_blank"
    rel="noopener"
    class="resume-btn secondary">

    Open in New Tab

  </a>

</div>

<div class="resume-card">

  <div class="resume-card-header">
    <div class="label">Current Resume</div>
    <div class="subtext">PDF Preview</div>
  </div>

  <div class="resume-preview">
    <iframe
      src="/assets/files/GraysenBrinkmanResume.pdf"
      title="Graysen Brinkman Resume">
    </iframe>
  </div>

</div>

<p class="resume-note">
  If the preview does not display properly in your browser,
  use the download button above.
</p>
