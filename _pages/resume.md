---
layout: single
title: ""
permalink: /resume/
author_profile: false
classes: wide
---

<style>
  /* 1. Hide the sidebar completely */
  .sidebar { 
    display: none !important; 
  }
  
  /* 2. Reset the grid layout and padding */
  .page {
    width: 100% !important;
    float: none !important;
    padding-right: 0 !important;
  }
  
  /* 3. Center the layout and set max scale */
  #main {
    width: 100% !important;
    max-width: 850px !important; 
    margin-left: auto !important;
    margin-right: auto !important;
    padding: 0 20px !important;
  }

  /* 4. Force the sleek pill-button styling over the site's default blue */
  .resume-download-btn {
    display: inline-flex !important;
    align-items: center !important;
    background: #ffffff !important;
    color: #292b2c !important;
    border: 1px solid #dcdde1 !important;
    padding: 8px 16px !important;
    border-radius: 20px !important;
    text-decoration: none !important;
    font-weight: 600 !important;
    font-size: 0.85em !important;
    letter-spacing: 0.2px !important;
    transition: all 0.2s ease-in-out !important;
    box-shadow: 0 1px 3px rgba(0,0,0,0.05) !important;
  }

  .resume-download-btn:hover {
    background: #2563eb !important; 
    border-color: #2563eb !important;
    color: #ffffff !important;
    transform: translateY(-1px) !important;
    box-shadow: 0 4px 10px rgba(37, 99, 235, 0.2) !important;
  }

  /* 5. The Magic Fix: Lock the container to an 8.5x11 paper ratio */
  .pdf-wrapper {
    width: 100%;
    aspect-ratio: 8.5 / 11;
    border: 1px solid #d1d5db; 
    border-radius: 8px; 
    box-shadow: 0 4px 12px rgba(0,0,0,0.08); 
    overflow: hidden; /* Hides any bleeding edges */
    background: #ffffff;
  }

  .pdf-wrapper iframe {
    width: 100%;
    height: 100%;
    border: none;
    display: block;
  }
</style>

<div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 25px; margin-top: 10px;">
  <h1 style="margin: 0; font-size: 2.2rem; font-weight: 700; color: #292b2c;">Resume</h1>
  
  <a href="/assets/files/GraysenBrinkmanResume.pdf" 
     download="Graysen_Brinkman_Resume.pdf"
     class="resume-download-btn">
     <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" fill="currentColor" style="margin-right: 8px;" viewBox="0 0 16 16">
       <path d="M.5 9.9a.5.5 0 0 1 .5.5v2.5a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1v2.5a.5.5 0 0 1 1 0v2.5a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2v2.5a.5.5 0 0 1 .5-.5z"/>
       <path d="M7.646 11.854a.5.5 0 0 0 .708 0l3-3a.5.5 0 0 0-.708-.708L8.5 10.293V1.5a.5.5 0 0 0-1 0v8.793L5.354 8.146a.5.5 0 1 0-.708.708l3 3z"/>
     </svg>
     Download PDF
  </a>
</div>

<div class="pdf-wrapper">
    <iframe src="/assets/files/GraysenBrinkmanResume.pdf#toolbar=0&navpanes=0&view=FitH" title="Graysen Brinkman Resume"></iframe>
</div>
