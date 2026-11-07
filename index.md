---
layout: page
title: "ClearType"
permalink: /
---

<style>
  html {
    scroll-behavior: smooth;
  }

  /* Hide Jekyll default headers & titles */
  .page-header,
  .page-title,
  .post-title,
  .entry-title,
  .page-description,
  .post-description,
  .site-description,
  .page-content > header,
  .page-content > hr:first-of-type,
  article > header,
  article > hr:first-of-type {
    display: none !important;
  }

  /* Widen main content area */
  .site-content,
  .page-content,
  .wrapper,
  .inner,
  main,
  article,
  .post-content {
    max-width: 1050px !important;
    width: 92% !important;
    margin-left: auto !important;
    margin-right: auto !important;
  }

  /* Global body text legibility enhancements */
  .post-content p, 
  .post-content li {
    font-size: 1.1rem !important;
    line-height: 1.75 !important;
    color: #334155;
  }
</style>

<!-- Top Hero Header with Integrated Navigation -->
<div style="text-align: center; padding: 2.5rem 1.5rem; background: #f8fafc; border: 1px solid #e2e8f0; border-radius: 12px; margin-bottom: 2.5rem;">
  <img src="{{ site.baseurl }}/assets/images/cleartype-logo.svg" alt="ClearType Logo" style="width: 260px; max-width: 100%; height: auto; display: block; margin: 0 auto 1rem auto;">
  <p style="font-size: 1.2rem; font-weight: 500; color: #475569; max-width: 750px; margin: 0 auto 1.5rem auto; line-height: 1.6;">
    Empowering readers with dyslexia through real-time, customizable visual typography overlays.
  </p>
  
  <!-- Navigation Buttons -->
  <div style="display: flex; justify-content: center; gap: 0.6rem; flex-wrap: wrap;">
    <a href="#about-the-project" style="background: #0f172a; color: #ffffff; padding: 8px 18px; border-radius: 20px; text-decoration: none; font-weight: 600; font-size: 0.9rem;">About</a>
    <a href="#meet-the-development-team" style="background: #0f172a; color: #ffffff; padding: 8px 18px; border-radius: 20px; text-decoration: none; font-weight: 600; font-size: 0.9rem;">Team</a>
    <a href="#phase-reports" style="background: #0f172a; color: #ffffff; padding: 8px 18px; border-radius: 20px; text-decoration: none; font-weight: 600; font-size: 0.9rem;">Reports</a>
    <a href="#presentations" style="background: #0f172a; color: #ffffff; padding: 8px 18px; border-radius: 20px; text-decoration: none; font-weight: 600; font-size: 0.9rem;">Presentations</a>
    <a href="#prototypes" style="background: #0f172a; color: #ffffff; padding: 8px 18px; border-radius: 20px; text-decoration: none; font-weight: 600; font-size: 0.9rem;">Prototypes</a>
  </div>
</div>

## Introduction

<h3 id="about-the-project" style="font-size: 1.5rem; margin-bottom: 1rem;">About the Project</h3>
<p style="font-size: 1.2rem; line-height: 1.85; color: #334155; margin-bottom: 2rem;">
  Standard digital learning materials and web pages use dense layouts, harsh contrast, and rigid typography that cause rapid visual fatigue for dyslexic readers. <strong>ClearType</strong> is an interactive web platform that lets students and teachers preview, test, and toggle dyslexia-friendly formatting in real time through instant visual overlays and live controls.
</p>

<h3 id="meet-the-development-team" style="text-align: center; margin-top: 2.5rem; margin-bottom: 1.5rem; font-size: 1.5rem;">Meet the development team</h3>

<!-- Team Members Grid -->
<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 1.5rem; margin-bottom: 3rem;">

  <!-- Javier C. -->
  <div style="background: #262626; border: 1px solid #3f3f46; border-radius: 8px; padding: 1.5rem 1rem; width: 220px; text-align: center; color: #ffffff; box-shadow: 0 4px 6px rgba(0,0,0,0.2);">
    <div style="width: 95px; height: 95px; border-radius: 50%; overflow: hidden; margin: 0 auto 1rem auto; background: #3f3f46;">
      <img src="{{ site.baseurl }}/assets/images/javier-picture.png" alt="Javier C." style="width: 100%; height: 100%; object-fit: cover;">
    </div>
    <div style="font-size: 1.15rem; font-weight: bold; margin-bottom: 0.3rem;">Javier C.</div>
    <div style="font-size: 0.9rem; color: #a1a1aa;">Project Website Programmer</div>
  </div>

  <!-- Ervin L. -->
  <div style="background: #262626; border: 1px solid #3f3f46; border-radius: 8px; padding: 1.5rem 1rem; width: 220px; text-align: center; color: #ffffff; box-shadow: 0 4px 6px rgba(0,0,0,0.2);">
    <div style="width: 95px; height: 95px; border-radius: 50%; overflow: hidden; margin: 0 auto 1rem auto; background: #3f3f46;">
      <img src="{{ site.baseurl }}/assets/images/ervin-picture.png" alt="Ervin L." style="width: 100%; height: 100%; object-fit: cover;">
    </div>
    <div style="font-size: 1.15rem; font-weight: bold; margin-bottom: 0.3rem;">Ervin L.</div>
    <div style="font-size: 0.9rem; color: #a1a1aa;">UI/UX Designer & Prototyper</div>
  </div>

  <!-- Alfred A. -->
  <div style="background: #262626; border: 1px solid #3f3f46; border-radius: 8px; padding: 1.5rem 1rem; width: 220px; text-align: center; color: #ffffff; box-shadow: 0 4px 6px rgba(0,0,0,0.2);">
    <div style="width: 95px; height: 95px; border-radius: 50%; overflow: hidden; margin: 0 auto 1rem auto; background: #3f3f46;">
      <img src="{{ site.baseurl }}/assets/images/alfred-picture.png" alt="Alfred A." style="width: 100%; height: 100%; object-fit: cover;">
    </div>
    <div style="font-size: 1.15rem; font-weight: bold; margin-bottom: 0.3rem;">Alfred A.</div>
    <div style="font-size: 0.9rem; color: #a1a1aa;">UI/UX Designer</div>
  </div>

</div>

---

## Documentation

<h3 id="phase-reports" style="font-size: 1.4rem;">Phase Reports</h3>

<!-- Report Card: SPP2 -->
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 2rem; margin-bottom: 2rem; background: #ffffff; padding: 1.5rem; border: 1px solid #e2e8f0; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
  <div style="flex: 1; min-width: 280px;">
    <img src="{{ site.baseurl }}/assets/images/SPP2-Report.png" alt="SPP2 Report Preview" style="width: 100%; border-radius: 6px; border: 1px solid #cbd5e1;">
  </div>
  <div style="flex: 1.5; min-width: 280px;">
    <h3 style="margin-top: 0; color: #0f172a; font-size: 1.25rem;">SPP2 — Point of View & Experience Prototypes</h3>
    <p style="color: #475569; line-height: 1.7; margin-bottom: 1rem; font-size: 1.05rem;">Comprehensive study on dyslexic reading hurdles, user interviews, and experience prototype insights.</p>
    <div>
      <a href="{{ site.baseurl }}/assets/reports/spp2-needfinding-report.pdf" target="_blank" style="background-color: #007bff; color: #ffffff; padding: 8px 18px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 0.9rem; display: inline-block;">PDF Report</a>
    </div>
  </div>
</div>

<!-- Report Card: SPP5 -->
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 2rem; margin-bottom: 2rem; background: #ffffff; padding: 1.5rem; border: 1px solid #e2e8f0; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.05); flex-direction: row-reverse;">
  <div style="flex: 1; min-width: 280px;">
    <img src="{{ site.baseurl }}/assets/images/SPP5-Report.png" alt="SPP5 Report Preview" style="width: 100%; border-radius: 6px; border: 1px solid #cbd5e1;">
  </div>
  <div style="flex: 1.5; min-width: 280px;">
    <h3 style="margin-top: 0; color: #0f172a; font-size: 1.25rem;">SPP5 — Low-Fi Prototyping Report</h3>
    <p style="color: #475569; line-height: 1.7; margin-bottom: 1rem; font-size: 1.05rem;">Paper prototype testing observations, task success rates, and user feedback evaluations.</p>
    <div>
      <a href="{{ site.baseurl }}/assets/reports/spp5-low-fi-prototyping-report.pdf" target="_blank" style="background-color: #007bff; color: #ffffff; padding: 8px 18px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 0.9rem; display: inline-block;">PDF Report</a>
    </div>
  </div>
</div>

---

<h3 id="presentations" style="font-size: 1.4rem;">Presentations</h3>

<!-- Presentation Card 1: SPP1 -->
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 2rem; margin-bottom: 2rem; background: #ffffff; padding: 1.5rem; border: 1px solid #e2e8f0; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
  <div style="flex: 1; min-width: 280px;">
    <img src="{{ site.baseurl }}/assets/images/SPP1-Presentation.png" alt="SPP1 Presentation Preview" style="width: 100%; border-radius: 6px; border: 1px solid #cbd5e1;">
  </div>
  <div style="flex: 1.5; min-width: 280px;">
    <h3 style="margin-top: 0; color: #0f172a; font-size: 1.25rem;">SPP1 — Needfinding Presentation</h3>
    <p style="color: #475569; line-height: 1.7; margin-bottom: 1rem; font-size: 1.05rem;">Initial presentation establishing problem domain, target group needs, and initial project goals for dyslexic readers.</p>
    <div style="display: flex; gap: 0.75rem; flex-wrap: wrap;">
      <a href="{{ site.baseurl }}/assets/presentations/spp1-presentation.pdf" target="_blank" style="background-color: #007bff; color: #ffffff; padding: 8px 18px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 0.9rem;">PDF Slides</a>
      <a href="{{ site.baseurl }}/assets/presentations/spp1-presentation.pptx" download style="background-color: #6c757d; color: #ffffff; padding: 8px 18px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 0.9rem;">PowerPoint (.pptx)</a>
    </div>
  </div>
</div>

<!-- Presentation Card 2: SPP2 -->
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 2rem; margin-bottom: 2rem; background: #ffffff; padding: 1.5rem; border: 1px solid #e2e8f0; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.05); flex-direction: row-reverse;">
  <div style="flex: 1; min-width: 280px;">
    <img src="{{ site.baseurl }}/assets/images/SPP2-Presentation.png" alt="SPP2 Presentation Preview" style="width: 100%; border-radius: 6px; border: 1px solid #cbd5e1;">
  </div>
  <div style="flex: 1.5; min-width: 280px;">
    <h3 style="margin-top: 0; color: #0f172a; font-size: 1.25rem;">SPP2 — Point of View & Experience Prototypes</h3>
    <p style="color: #475569; line-height: 1.7; margin-bottom: 1rem; font-size: 1.05rem;">Presentation on empathy mapping, POV statements, and early experience testing with readers.</p>
    <div style="display: flex; gap: 0.75rem; flex-wrap: wrap;">
      <a href="{{ site.baseurl }}/assets/presentations/spp2-presentation.pdf" target="_blank" style="background-color: #007bff; color: #ffffff; padding: 8px 18px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 0.9rem;">PDF Slides</a>
      <a href="{{ site.baseurl }}/assets/presentations/spp2-presentation.pptx" download style="background-color: #6c757d; color: #ffffff; padding: 8px 18px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 0.9rem;">PowerPoint (.pptx)</a>
    </div>
  </div>
</div>

<!-- Presentation Card 3: SPP4 -->
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 2rem; margin-bottom: 2rem; background: #ffffff; padding: 1.5rem; border: 1px solid #e2e8f0; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
  <div style="flex: 1; min-width: 280px;">
    <img src="{{ site.baseurl }}/assets/images/SPP4-Presentation.png" alt="SPP4 Presentation Preview" style="width: 100%; border-radius: 6px; border: 1px solid #cbd5e1;">
  </div>
  <div style="flex: 1.5; min-width: 280px;">
    <h3 style="margin-top: 0; color: #0f172a; font-size: 1.25rem;">SPP4 — Concept Video Presentation</h3>
    <p style="color: #475569; line-height: 1.7; margin-bottom: 1rem; font-size: 1.05rem;">Visual narrative presentation showcasing real-world dyslexia reading hurdles and the ClearType workflow solution.</p>
    <div style="display: flex; gap: 0.75rem; flex-wrap: wrap;">
      <a href="{{ site.baseurl }}/assets/presentations/spp4-presentation.pdf" target="_blank" style="background-color: #007bff; color: #ffffff; padding: 8px 18px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 0.9rem;">PDF Slides</a>
      <a href="{{ site.baseurl }}/assets/presentations/spp4-presentation.pptx" download style="background-color: #6c757d; color: #ffffff; padding: 8px 18px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 0.9rem;">PowerPoint (.pptx)</a>
    </div>
  </div>
</div>

<!-- Presentation Card 4: SPP5 -->
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 2rem; margin-bottom: 2rem; background: #ffffff; padding: 1.5rem; border: 1px solid #e2e8f0; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.05); flex-direction: row-reverse;">
  <div style="flex: 1; min-width: 280px;">
    <img src="{{ site.baseurl }}/assets/images/SPP5-Presentation.png" alt="SPP5 Presentation Preview" style="width: 100%; border-radius: 6px; border: 1px solid #cbd5e1;">
  </div>
  <div style="flex: 1.5; min-width: 280px;">
    <h3 style="margin-top: 0; color: #0f172a; font-size: 1.25rem;">SPP5 — Low-Fi Prototyping & Pilot Usability Testing</h3>
    <p style="color: #475569; line-height: 1.7; margin-bottom: 1rem; font-size: 1.05rem;">Overview of low-fidelity paper prototype trials, task execution metrics, and usability findings.</p>
    <div style="display: flex; gap: 0.75rem; flex-wrap: wrap;">
      <a href="{{ site.baseurl }}/assets/presentations/spp5-presentation.pdf" target="_blank" style="background-color: #007bff; color: #ffffff; padding: 8px 18px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 0.9rem;">PDF Slides</a>
      <a href="{{ site.baseurl }}/assets/presentations/spp5-presentation.pptx" download style="background-color: #6c757d; color: #ffffff; padding: 8px 18px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 0.9rem;">PowerPoint (.pptx)</a>
    </div>
  </div>
</div>

<!-- Presentation Card 5: SPP8 -->
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 2rem; margin-bottom: 2rem; background: #ffffff; padding: 1.5rem; border: 1px solid #e2e8f0; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
  <div style="flex: 1; min-width: 280px;">
    <div style="width: 100%; height: 160px; background: #f1f5f9; border: 2px dashed #cbd5e1; border-radius: 6px; display: flex; align-items: center; justify-content: center; color: #64748b; font-weight: 600; text-align: center; padding: 1rem;">
      SPP8 Poster & Pitch Thumbnail Placeholder
    </div>
  </div>
  <div style="flex: 1.5; min-width: 280px;">
    <h3 style="margin-top: 0; color: #0f172a; font-size: 1.25rem;">SPP8 — Poster & Pitch Slide</h3>
    <p style="color: #475569; line-height: 1.7; margin-bottom: 1rem; font-size: 1.05rem;">Final showcase presentation featuring our elevator pitch slide deck and capstone project poster summarizing the ClearType design process.</p>
    <div style="display: flex; gap: 0.75rem; flex-wrap: wrap;">
      <a href="#" style="background-color: #007bff; color: #ffffff; padding: 8px 18px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 0.9rem; opacity: 0.85;">Pitch Slides (PDF)</a>
      <a href="#" style="background-color: #6c757d; color: #ffffff; padding: 8px 18px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 0.9rem; opacity: 0.85;">Pitch Source (.pptx)</a>
      <a href="#" style="background-color: #28a745; color: #ffffff; padding: 8px 18px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 0.9rem; opacity: 0.85;">Poster (PDF)</a>
      <a href="#" style="background-color: #6c757d; color: #ffffff; padding: 8px 18px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 0.9rem; opacity: 0.85;">Poster Source (.pptx / .svg)</a>
    </div>
  </div>
</div>

---

<h2 id="prototypes" style="font-size: 1.6rem; margin-bottom: 1.5rem;">Prototypes</h2>

<!-- Low-Fidelity Prototype Card -->
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 2rem; margin-bottom: 2.5rem; background: #ffffff; padding: 1.5rem; border: 1px solid #e2e8f0; border-radius: 8px; box-shadow: 0 2px 4px rgba(0,0,0,0.05);">
  <div style="flex: 1; min-width: 280px;">
    <img src="{{ site.baseurl }}/assets/images/low-fi-prototype.png" alt="Low-Fidelity Paper Prototype" style="width: 100%; border-radius: 6px; border: 1px solid #cbd5e1;">
  </div>
  <div style="flex: 1.5; min-width: 280px;">
    <h3 style="margin-top: 0; color: #0f172a; font-size: 1.3rem;">Low-Fidelity Prototype</h3>
    <p style="color: #475569; line-height: 1.7; margin-bottom: 1rem; font-size: 1.05rem;">Paper interface sketches demonstrating initial navigation, contrast toggle switches, and font preview overlays evaluated during pilot usability testing.</p>
    <div>
      <a href="{{ site.baseurl }}/assets/reports/spp5-low-fi-prototyping-report.pdf" target="_blank" style="background-color: #007bff; color: #ffffff; padding: 8px 18px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 0.9rem; display: inline-block;">View Testing Report</a>
    </div>
  </div>
</div>

### Medium-Fidelity Prototype
- **Link:** [Launch Wireframe Prototype (Figma)](https://figma.com/your-med-fi-link)
- **Instructions:**
  1. Click the prototype link above to open the interactive Figma canvas.
  2. Click **Present (Play button)** in the top right corner.
  3. Test task 1: Toggle the font selector and select an OpenDyslexic font visual overlay.

### High-Fidelity Prototype
- **Link:** [Launch Interactive Web Prototype](https://your-demo-app.com) | [View Code Repo](https://github.com/Javier-Coyoc/prototype-app)
- **Instructions:**
  1. Log in using guest credentials: User: `test@example.com` / Pass: `demo123`.
  2. Navigate to the **Reader Preview Canvas**.
  3. Adjust the line-spacing slider to test real-time visual formatting adjustment.
