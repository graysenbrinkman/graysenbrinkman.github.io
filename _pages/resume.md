---
layout: single
title: ""
permalink: /resume/
author_profile: false
classes: wide
---

<style>

/* Hide sidebar completely */
.sidebar {
  display: none !important;
}

/* Reset page layout */
.page {
  width: 100% !important;
  float: none !important;
  padding-right: 0 !important;
}

/* Center content */
#main {
  width: 100% !important;
  max-width: 950px !important;
  margin-left: auto !important;
  margin-right: auto !important;
  padding: 0 20px !important;
}

/* Page header */
.resume-header {
  text-align: center;
  margin-bottom: 2rem;
}

.resume-header h1 {
  margin-bottom: 1rem;
  font-size: 2.5rem;
  font-weight: 700;
}

/* Download button */
.resume-download-btn {
  display: inline-flex;
  align-items: center;
  gap: 8px;

  background: #2563eb;
  color: white !important;

  padding: 12px 24px;
  border-radius: 8px;

  text-decoration: none !important;
  font-weight: 600;

  transition: all 0.2s ease;
}

.resume-download-btn:hover {
  background: #1d4ed8;
  color: white !important;
  transform: translateY(-1px);
  text-decoration: none !important;
}

/* PDF viewer */
.pdf-wrapper {
  width: 100%;
  aspect-ratio: 8.5 / 11;

  overflow: hidden;
  background: white;

  box-shadow: 0 3px 12px rgba(0,0,0,0.08);
}

.pdf-wrapper iframe {
  width: 100%;
  height: 100%;
  border: none;
  display: block;
}

/* Mobile */
@media (max-width: 768px) {
  .resume-header h1 {
    font-size: 2rem;
  }

  .pdf-wrapper {
    aspect-ratio: 8.5 / 12;
  }
}

</style>

<div class="resume-header">

# Resume

<a href="/assets/files/GraysenBrinkmanResume.pdf"
   download="Graysen_Brinkman_Resume.pdf"
   class="resume-download-btn">

<svg xmlns="http://www.w3.org/2000/svg"
     width="16"
     height="16"
     fill="currentColor"
     viewBox="0 0 16 16">
  <path d="M.5 9.9a.5.5 0 0 1 .5.5v2.5a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1v-2.5a.5.5 0 0 1 1 0v2.5a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2v-2.5a.5.5 0 0 1 .5-.5z"/>
  <path d="M7.646 11.854a.5.5 0 0 0 .708 0l3-3a.5.5 0 0 0-.708-.708L8.5 10.293V1.5a.5.5 0 0 0-1 0v8.793L5.354 8.146a.5.5 0 1 0-.708.708l3 3z"/>
</svg>

Download PDF

</a>

</div>

<div class="pdf-wrapper">
  <iframe
    src="/assets/files/GraysenBrinkmanResume.pdf#toolbar=0&navpanes=0&view=FitH"
    title="Graysen Brinkman Resume">
  </iframe>
</div>
