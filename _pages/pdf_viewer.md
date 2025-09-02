---
layout: page
title: PDF Viewer
permalink: /pdf-viewer/
nav: false
---

<div class="pdf-container" style="width: 100%; height: 90vh;">
  <iframe 
    id="pdf-iframe" 
    style="width: 100%; height: 100%; border: none;"
    src=""
    title="PDF Viewer">
  </iframe>
</div>

<script>
// Get PDF path from URL parameter
const urlParams = new URLSearchParams(window.location.search);
const pdfPath = urlParams.get('pdf');
const projectTitle = urlParams.get('title');

if (pdfPath) {
  // Set the PDF source
  document.getElementById('pdf-iframe').src = pdfPath;
  
  // Update page title if provided
  if (projectTitle) {
    document.title = projectTitle + ' - PDF Viewer';
  }
} else {
  // Handle case when no PDF is specified
  document.getElementById('pdf-iframe').src = '/assets/pdf/default.pdf';
}
</script>
