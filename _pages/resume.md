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
  
  /* 2. Reset the grid layout and remove the forced right float */
  .page {
    width: 100% !important;
    float: none !important;
    padding-right: 0 !important;
  }
  
  /* 3. Constrain the container width to match a PDF's 8.5x11 aspect ratio */
  #main {
    width: 100% !important;
    max-width: 690px !important; /* The magic number that snaps the side gray bars away */
    margin-left: auto !important;
    margin-right: auto !important;
    padding: 0 20px !important;
  }

  /* 4. Sleek, professional interface styling for the download button */
  .resume-download-btn {
    display: inline-flex;
    align-items: center;
    background: transparent;
    color: #495057;
    border: 1px solid #ced4da;
    padding: 8px 14px;
    border-radius: 6px;
    text-decoration: none;
    font-weight: 500;
    font-size: 0.9em;
    transition: all 0.2s ease-in-out;
  }

  /* Interactive hover effect to make it feel like a premium native UI element */
  .resume-download-btn:hover {
    background: #f8f9fa !important;
    border-color: #495057 !important;
    color: #212529 !important;
    text-decoration: none !important;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
  }
</style>

<div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px; margin-top: 10px;">
  <h1 style="margin: 0; font-size: 2.2rem; font-weight: 700; color: #292b2c;">Resume</h1>
  
  <a href="/assets/files/GraysenBrinkmanResume.pdf" 
     download="Graysen_Brinkman_Resume.pdf"
     class="resume-download-btn">
     <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" style="margin-right: 8px; margin-top: -2px;" viewBox="0 0 16 16">
       <path d="M.5 9.9a.5.5 0 0 1 .5.5v2.5a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1v2.5a.5.5 0 0 1 1 0v2.5a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2v2.5a.5.5 0 0 1 .5-.5z"/>
       <path d="M7.646 11.854a.5.5 0 0 0 .708 0l3-3a.5.5 0 0 0-.708-.708L8.5 10.293V1.5a.5.5 0 0 0-1 0v8.793L5.354 8.146a.5.5 0 1 0-.708.708l3 3z"/>
     </svg>
     Download PDF
  </a>
</div>

<iframe
    src="/assets/files/GraysenBrinkmanResume.pdf#toolbar=0&navpanes=0"
    width="100%"
    height="850px"
    style="border: 1px solid #e5e7eb; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.06);">
</iframe>
