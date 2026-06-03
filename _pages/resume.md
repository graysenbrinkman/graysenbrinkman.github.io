---
layout: single
title: ""
permalink: /resume/
author_profile: false
classes: wide
---

<style>
  /* Hide the sidebar */
  .sidebar { 
    display: none !important; 
  }
  
  /* Reset the grid layout */
  .page {
    width: 100% !important;
    float: none !important;
    padding-right: 0 !important;
  }
  
  /* Increased max-width to make the resume display significantly larger */
  #main {
    width: 100% !important;
    max-width: 850px !important; 
    margin-left: auto !important;
    margin-right: auto !important;
    padding: 0 20px !important;
  }

  /* Sleek, interactive download button */
  .resume-download-btn {
    display: inline-flex;
    align-items: center;
    background: #ffffff;
    color: #292b2c;
    border: 1px solid #dcdde1;
    padding: 8px 16px;
    border-radius: 20px;
    text-decoration: none !important;
    font-weight: 600;
    font-size: 0.85em;
    letter-spacing: 0.2px;
    transition: all 0.2s ease-in-out;
    box-shadow: 0 1px 3px rgba(0,0,0,0.05);
  }

  .resume-download-btn:hover {
    background: #2563eb !important; 
    border-color: #2563eb !important;
    color: #ffffff !important;
    transform: translateY(-1px);
    box-shadow: 0 4px 10px rgba(37, 99, 235, 0.2);
  }
</style>

<!-- Header row with title and button -->
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

<!-- The PDF Viewer (Height increased to 1100px to match the wider scale) -->
<iframe
    src="/assets/files/GraysenBrinkmanResume.pdf#toolbar=0&navpanes=0&view=FitH"
    width="100%"
    height="1100px"
    style="border: 1px solid #d1d5db; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.08); display: block;">
</iframe>
