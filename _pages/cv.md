---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

<div class="cv-container" style="max-width: 1000px; margin: 0 auto; padding: 20px; background: #fff; border-radius: 10px; box-shadow: 0 4px 20px rgba(0,0,0,0.1);">
  <div class="pdf-viewer" style="position: relative; width: 100%; height: 900px; border: none; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 15px rgba(0,0,0,0.15);">
    <iframe 
      src="{{ base_path }}/files/BingranLIU_CV%20202509.pdf#toolbar=1&navpanes=1&scrollbar=1&view=FitH" 
      width="100%" 
      height="100%" 
      style="border: none; border-radius: 8px;"
      title="Bingran Liu CV">
      <div style="text-align: center; padding: 50px; background: #f8f9fa; border-radius: 8px; color: #6c757d;">
        <i class="fas fa-file-pdf" style="font-size: 48px; margin-bottom: 20px; color: #dc3545;"></i>
        <p style="font-size: 18px; margin: 0;">Your browser does not support PDF viewing.</p>
        <p style="font-size: 14px; margin: 10px 0 0 0;">Please use a modern browser to view this document.</p>
      </div>
    </iframe>
  </div>
</div>

<style>
.cv-container {
  animation: fadeIn 0.6s ease-in-out;
}

@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}

.pdf-viewer iframe {
  transition: all 0.3s ease;
}

.pdf-viewer:hover {
  box-shadow: 0 4px 25px rgba(0,0,0,0.2);
  transform: translateY(-2px);
}
</style>
