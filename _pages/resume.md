---
layout: single
title: "Resume"
permalink: /resume/
author_profile: false
classes: wide
---

<style>
/* Remove theme sidebar and extra clutter */
.sidebar,
.page__related,
.page__meta,
.page__share {
  display: none !important;
}

/* Make the content area centered and clean */
.page {
  width: 100% !important;
  float: none !important;
  padding-right: 0 !important;
}

#main,
.page__inner-wrap,
.page__content {
  width: 100% !important;
  max-width: 980px !important;
  margin-left: auto !important;
  margin-right: auto !important;
  padding-left: 20px !important;
  padding-right: 20px !important;
}

/* Hide the theme's default page title so it doesn't duplicate ours */
.page__title {
  display: none !important;
}

/* Top section */
.resume-hero {
  text-align: center;
  margin: 1rem 0 2rem 0;
}

.resume-hero h1 {
  margin: 0;
  font-size: 2.8rem;
  font-weight: 700;
  line-height: 1.1;
  color: #111827;
}

.resume-hero p {
  margin: 0.75rem auto 0;
  max-width: 700px;
  font-size: 1.05rem;
  color: #6b7280;
  line-height: 1.6;
}

/* Action buttons */
.resume-actions {
  display: flex;
  justify-content: center;
  gap: 0.9rem;
  flex-wrap: wrap;
  margin-bottom: 2rem;
}

.resume-btn {
  display: inline-flex !important;
  align-items: center !important;
  gap: 8px !important;
  padding: 12px 20px !important;
  border-radius: 999px !important;
  text-decoration: none !important;
  font-weight: 600 !important;
  transition: all 0.2s ease !important;
  border: 1px solid transparent !important;
}

.resume-btn.primary {
  background: #2563eb !important;
  color: #ffffff !important;
  box-shadow: 0 6px 18px rgba(37, 99, 235, 0.18);
}

.resume-btn.primary:hover {
  background: #1d4ed8 !important;
  color: #ffffff !important;
  transform: translateY(-1px) !important;
  text-decoration: none !important;
}

.resume-btn.secondary {
  background: #ffffff !important;
  color: #111827 !important;
  border-color: #d1d5db !important;
}

.resume-btn.secondary:hover {
  background: #f9fafb !important;
  color: #111827 !important;
  transform: translateY(-1px) !important;
  text-decoration: none !important;
}

/* Clean document card */
.resume-card {
  background: #ffffff;
  border: 1px solid #e5e7eb;
  border-radius: 20px;
  box-shadow: 0 10px 30px rgba(15, 23, 42, 0.06);
  padding: 1.5rem;
}

.resume-card-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 1rem;
  margin-bottom: 1rem;
  padding-bottom: 1rem;
  border-bottom: 1px solid #eef2f7;
}

.resume-card-header .label {
  font-size: 0.9rem;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: #6b7280;
  font-weight: 700;
}

.resume-card-header .subtext {
  font-size: 0.95rem;
  color: #6b7280;
}

/* Optional simple embedded preview area */
.resume-preview {
  width: 100%;
  height: 78vh;
  min-height: 760px;
  border: none;
  border-radius: 14px;
  overflow: hidden;
  background: #f8fafc;
}

/* Use object/iframe only as fallback and keep them borderless */
.resume-preview object,
.resume-preview iframe {
  width: 100%;
  height: 100%;
  border: none !important;
  outline: none !important;
  display: block;
  background: #ffffff;
}

/* Small note */
.resume-note {
  margin-top: 1rem;
  text-align: center;
  font-size: 0.95rem;
  color: #6b7280;
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

  .resume-card {
    padding: 1rem;
    border-radius: 16px;
  }

  .resume-preview {
    height: 70vh;
    min-height: 620px;
  }

  .resume-card-header {
    flex-direction: column;
    align-items: flex-start;
  }
}
</style>

<div class="resume-hero">
  <h1>Resume</h1>
  <p>
    Download my current resume or open the PDF in a new tab.
    This page is designed to keep the document clean and easy to access.
  </p>
</div>

<div class="resume-actions">
  <a
    href="/assets/files/GraysenBrinkmanResume.pdf"
    download="Graysen_Brinkman_Resume.pdf"
    class="resume-btn primary"
  >
    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" viewBox="0 0 16 16" aria-hidden="true">
      <path d="M.5 9.9a.5.5 0 0 1 .5.5v2.5a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1v-2.5a.5.5 0 0 1 1 0v2.5a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2v-2.5a.5.5 0 0 1 .5-.5z"/>
      <path d="M7.646 11.854a.5.5 0 0 0 .708 0l3-3a.5.5 0 0 0-.708-.708L8.5 10.293V1.5a.5.5 0 0 0-1 0v8.793L5.354 8.146a.5.5 0 1 0-.708.708l3 3z"/>
    </svg>
    Download PDF
  </a>

  <a
    href="/assets/files/GraysenBrinkmanResume.pdf"
    target="_blank"
    rel="noopener"
    class="resume-btn secondary"
  >
    Open in New Tab
  </a>
</div>

<div class="resume-card">
  <div class="resume-card-header">
    <div class="label">Current Resume</div>
    <div class="subtext">PDF preview</div>
  </div>

  <div class="resume-preview">
    <object
      data="/assets/files/GraysenBrinkmanResume.pdf#toolbar=0&navpanes=0&view=FitH"
      type="application/pdf"
    >
      <iframe
        src="/assets/files/GraysenBrinkmanResume.pdf#toolbar=0&navpanes=0&view=FitH"
        title="Graysen Brinkman Resume"
      ></iframe>
    </object>
  </div>
</div>

<p class="resume-note">
  If the preview does not display in your browser, use the download or open-in-new-tab button above.
</p>
