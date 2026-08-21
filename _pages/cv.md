---
layout: cv
permalink: /cv/
title: CV
nav: true
nav_order: 4
cv_pdf: /assets/pdf/cv.pdf # you can also use external links here
cv_format:  # options: rendercv, jsonresume
description: This is a description of the page. You can modify it in '_pages/cv.md'. You can also change or remove the top pdf download button.
toc:
  sidebar: left
---
<div class="cv-container">
  <embed src="{{ '/assets/pdf/cv.pdf' | relative_url }}" type="application/pdf" width="100%" height="1000px" style="border: 1px solid rgba(0,0,0,0.1); border-radius: 4px;" />

  <p style="text-align: center; margin-top: 1rem;">
    <a href="{{ '/assets/pdf/cv.pdf' | relative_url }}" class="cv-download-link" download>
      📄 Download CV (PDF)
    </a>
  </p>
</div>