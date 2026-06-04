---
layout: single
title: "Resume"
permalink: /resume/
author_profile: false
classes: wide
---

<style>
/* Remove sidebar and let the page use the full width */
.sidebar,
.page__related {
  display: none !important;
}

.page {
  width: 100% !important;
  float: none !important;
  padding-right: 0 !important;
}

#main,
.page__inner-wrap,
.page__content {
  width: 100% !important;
  max-width: 1100px !important;
  margin-left: auto !important;
  margin-right: auto !important;
  padding-left: 20px !important;
  padding-right: 20px !important;
}

.page__content {
  border: none !important;
  box-shadow: none !important;
  background: transparent !important;
}

/* Header */
.resume-header {
  text-align: center;
  margin: 0 0 1.5rem 0;
}

.resume-header h1 {
  margin: 0;
  font-size: 2.5rem;
  line-height: 1.1;
  font-weight: 700;
  color: #111827;
}

/* Buttons */
.resume-actions {
  display: flex;
  justify-content: center;
  gap: 0.75rem;
  flex-wrap: wrap;
  margin-bottom: 1.5rem;
}

.resume-download-btn,
.resume-view-btn {
  display: inline-flex !important;
  align-items: center !important;
  gap: 8px !important;
  padding: 12px 20px !important;
  border-radius: 10px !important;
  text-decoration: none !important;
  font-weight: 600 !important;
  transition: all 0.2s ease !important;
  border: 1px solid transparent !important;
}

.resume-download-btn {
  background: #2563eb !important;
  color: #ffffff !important;
}

.resume-download-btn:hover {
  background: #1d4ed8 !important;
  color: #ffffff !important;
  transform: translateY(-1px) !important;
}

.resume-view-btn {
  background: #ffffff !important;
  color: #111827 !important;
  border-color: #d1d5db !important;
}

.resume-view-btn:hover {
  background: #f9fafb !important;
  color: #111827 !important;
  transform: translateY(-1px) !important;
}

/* PDF area — intentionally minimal */
.pdf-shell {
  width: 100%;
  height: calc(100vh - 220px);
  min-height: 850px;
  background: transparent !important;
  border: none !important;
  box-shadow: none !important;
  overflow: hidden;
}

.pdf-shell object,
.pdf-shell iframe {
  width: 100%;
  height: 100%;
  display: block;
  border: 0 !important;
  outline: none !important;
  box-shadow: none !important;
  background: #ffffff;
}

/* Fallback text */
.pdf-fallback {
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

  .resume-header h1 {
    font-size: 2rem;
  }

  .pdf-shell {
    min-height: 70vh;
    height: 70vh;
  }
}
</style>

<div class="resume-header">
  <h1>Resume</h1>
</div>

<div class="resume-actions">
  <a
    href="/assets/files/GraysenBrinkmanResume.pdf"
    download="Graysen_Brinkman_Resume.pdf"
    class="resume-download-btn"
  >
    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" viewBox="0 0 16 16" aria-hidden="true">
      <path d="M.5 9.9a.5.5 0 0 1 .5.5v2.5a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1v2.5a.5.5 0 0 1 1 0v2.5a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2v-2.5a.5.5 0 0 1 .5-.5z"/>
      <path d="M7.646 11.854a.5.5 0 0 0 .708 0l3-3a.5.5 0 0 0-.708-.708L8.5 10.293V1.5a.5.5 0 0 0-1 0v8.793L5.354 8.146a.5.5 0 1 0-.708.708l3 3z"/>
    </svg>
    Download PDF
  </a>

  <a
    href="/assets/files/GraysenBrinkmanResume.pdf"
    target="_blank"
    rel="noopener"
    class="resume-view-btn"
  >
    Open in New Tab
  </a>
</div>

<div class="pdf-shell">
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

<p class="pdf-fallback">
  If the preview does not load correctly, use the Download PDF button above.
</p>
