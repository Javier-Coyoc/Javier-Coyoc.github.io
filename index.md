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

  /* Hero Section */
  .hero-card {
    text-align: center;
    padding: 2.5rem 1.5rem;
    background: #f8fafc;
    border: 1px solid #e2e8f0;
    border-radius: 12px;
    margin-bottom: 2.5rem;
  }
  .hero-tagline {
    font-size: 1.5rem;
    font-weight: 600;
    color: #475569;
    max-width: 750px;
    margin: 0 auto 1.5rem auto;
    line-height: 1.5;
  }

  /* Quick Nav Pills */
  .nav-pills {
    display: flex;
    justify-content: center;
    gap: 0.6rem;
    flex-wrap: wrap;
  }
  .nav-pill {
    background: #0f172a;
    color: #ffffff !important;
    padding: 8px 18px;
    border-radius: 20px;
    text-decoration: none !important;
    font-weight: 600;
    font-size: 0.9rem;
    transition: background 0.2s ease;
  }
  .nav-pill:hover {
    background: #1e293b;
  }

  /* Team Member Cards */
  .team-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1.5rem;
    margin-bottom: 3rem;
  }
  .team-card {
    background: #262626;
    border: 1px solid #3f3f46;
    border-radius: 8px;
    padding: 1.5rem 1rem;
    width: 220px;
    text-align: center;
    color: #ffffff;
    box-shadow: 0 4px 6px rgba(0,0,0,0.2);
  }
  .team-avatar {
    width: 95px;
    height: 95px;
    border-radius: 50%;
    overflow: hidden;
    margin: 0 auto 1rem auto;
    background: #3f3f46;
  }
  .team-avatar img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  /* Deliverable Cards (Reports & Presentations) */
  .doc-card {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 2rem;
    margin-bottom: 2rem;
    background: #ffffff;
    padding: 1.5rem;
    border: 1px solid #e2e8f0;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.05);
  }
  .doc-card.reverse {
    flex-direction: row-reverse;
  }
  .doc-media {
    flex: 1;
    min-width: 260px;
  }
  .doc-media img {
    width: 100%;
    height: auto;
    border-radius: 6px;
    border: 1px solid #cbd5e1;
    display: block;
  }
  .doc-info {
    flex: 1.5;
    min-width: 260px;
  }
  .doc-info h3 {
    margin-top: 0;
    color: #0f172a;
    font-size: 1.25rem;
  }
  .doc-info p {
    color: #475569;
    line-height: 1.7;
    margin-bottom: 1rem;
    font-size: 1.05rem !important;
  }

  /* Action Buttons */
  .btn-group {
    display: flex;
    gap: 0.75rem;
    flex-wrap: wrap;
  }
  .btn-primary {
    background-color: #007bff;
    color: #ffffff !important;
    padding: 8px 18px;
    border-radius: 6px;
    text-decoration: none !important;
    font-weight: 600;
    font-size: 0.9rem;
    display: inline-block;
  }
  .btn-secondary {
    background-color: #6c757d;
    color: #ffffff !important;
    padding: 8px 18px;
    border-radius: 6px;
    text-decoration: none !important;
    font-weight: 600;
    font-size: 0.9rem;
    display: inline-block;
  }
  .btn-success {
    background-color: #28a745;
    color: #ffffff !important;
    padding: 8px 18px;
    border-radius: 6px;
    text-decoration: none !important;
    font-weight: 600;
    font-size: 0.9rem;
    display: inline-block;
  }

  /* Placeholder Styling */
  .doc-placeholder {
    width: 100%;
    min-height: 160px;
    background: #f1f5f9;
    border: 2px dashed #cbd5e1;
    border-radius: 6px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #64748b;
    font-weight: 600;
    text-align: center;
    padding: 1rem;
  }

  /* Mobile Media Query Adjustments */
  @media (max-width: 768px) {
    .hero-card {
      padding: 1.75rem 1rem;
      margin-bottom: 1.75rem;
    }
    .hero-tagline {
      font-size: 1.2rem;
    }
    .nav-pill {
      font-size: 0.8rem;
      padding: 6px 14px;
    }
    .doc-card,
    .doc-card.reverse {
      flex-direction: column !important; /* Image always stays on top on mobile */
      gap: 1.25rem;
      padding: 1.25rem;
    }
    .doc-media,
    .doc-info {
      width: 100%;
      min-width: 100%;
    }
    .team-card {
      width: 100%;
      max-width: 280px;
    }
    .btn-group a {
      flex: 1 1 auto;
      text-align: center;
    }
  }
</style>

<!-- Top Hero Header with Integrated Navigation -->
<div class="hero-card">
  <img src="{{ site.baseurl }}/assets/images/cleartype-logo.svg" alt="ClearType Logo" style="width: 260px; max-width: 100%; height: auto; display: block; margin: 0 auto 1rem auto;">
  <p class="hero-tagline">
    Making web content readable for every mind
  </p>
  
  <!-- Navigation Buttons -->
  <div class="nav-pills">
    <a href="#about-the-project" class="nav-pill">About</a>
    <a href="#meet-the-development-team" class="nav-pill">Team</a>
    <a href="#phase-reports" class="nav-pill">Reports</a>
    <a href="#presentations" class="nav-pill">Presentations</a>
    <a href="#prototypes" class="nav-pill">Prototypes</a>
  </div>
</div>

## Introduction

<h3 id="about-the-project" style="font-size: 1.5rem; margin-bottom: 1rem;">About the Project</h3>
<p style="font-size: 1.2rem; line-height: 1.85; color: #334155; margin-bottom: 2rem;">
  Standard digital learning materials and web pages use dense layouts, harsh contrast, and rigid typography that cause rapid visual fatigue for dyslexic readers. <strong>ClearType</strong> is an interactive web platform that lets students and teachers preview, test, and toggle dyslexia-friendly formatting in real time through instant visual overlays and live controls.
</p>

<h3 id="meet-the-development-team" style="text-align: center; margin-top: 2.5rem; margin-bottom: 1.5rem; font-size: 1.5rem;">Meet the development team</h3>

<!-- Team Members Grid -->
<div class="team-grid">

  <!-- Javier C. -->
  <div class="team-card">
    <div class="team-avatar">
      <img src="{{ site.baseurl }}/assets/images/javier-picture.png" alt="Javier C.">
    </div>
    <div style="font-size: 1.15rem; font-weight: bold; margin-bottom: 0.3rem;">Javier C.</div>
    <div style="font-size: 0.9rem; color: #a1a1aa;">Project Website Programmer</div>
  </div>

  <!-- Ervin L. -->
  <div class="team-card">
    <div class="team-avatar">
      <img src="{{ site.baseurl }}/assets/images/ervin-picture.png" alt="Ervin L.">
    </div>
    <div style="font-size: 1.15rem; font-weight: bold; margin-bottom: 0.3rem;">Ervin L.</div>
    <div style="font-size: 0.9rem; color: #a1a1aa;">UI/UX Designer & Prototyper</div>
  </div>

  <!-- Alfred A. -->
  <div class="team-card">
    <div class="team-avatar">
      <img src="{{ site.baseurl }}/assets/images/alfred-picture.png" alt="Alfred A.">
    </div>
    <div style="font-size: 1.15rem; font-weight: bold; margin-bottom: 0.3rem;">Alfred A.</div>
    <div style="font-size: 0.9rem; color: #a1a1aa;">UI/UX Designer</div>
  </div>

</div>

---

## Documentation

<h3 id="phase-reports" style="font-size: 1.4rem;">Phase Reports</h3>

<!-- Report Card: SPP2 -->
<div class="doc-card">
  <div class="doc-media">
    <img src="{{ site.baseurl }}/assets/images/SPP2-Report.png" alt="SPP2 Report Preview">
  </div>
  <div class="doc-info">
    <h3>SPP2 — Point of View & Experience Prototypes</h3>
    <p>Comprehensive study on dyslexic reading hurdles, user interviews, and experience prototype insights.</p>
    <div class="btn-group">
      <a href="{{ site.baseurl }}/assets/reports/spp2-needfinding-report.pdf" target="_blank" class="btn-primary">PDF Report</a>
    </div>
  </div>
</div>

<!-- Report Card: SPP5 -->
<div class="doc-card reverse">
  <div class="doc-media">
    <img src="{{ site.baseurl }}/assets/images/SPP5-Report.png" alt="SPP5 Report Preview">
  </div>
  <div class="doc-info">
    <h3>SPP5 — Low-Fi Prototyping Report</h3>
    <p>Paper prototype testing observations, task success rates, and user feedback evaluations.</p>
    <div class="btn-group">
      <a href="{{ site.baseurl }}/assets/reports/spp5-low-fi-prototyping-report.pdf" target="_blank" class="btn-primary">PDF Report</a>
    </div>
  </div>
</div>

---

<h3 id="presentations" style="font-size: 1.4rem;">Presentations</h3>

<!-- Presentation Card 1: SPP1 -->
<div class="doc-card">
  <div class="doc-media">
    <img src="{{ site.baseurl }}/assets/images/SPP1-Presentation.png" alt="SPP1 Presentation Preview">
  </div>
  <div class="doc-info">
    <h3>SPP1 — Needfinding Presentation</h3>
    <p>Initial presentation establishing problem domain, target group needs, and initial project goals for dyslexic readers.</p>
    <div class="btn-group">
      <a href="{{ site.baseurl }}/assets/presentations/spp1-presentation.pdf" target="_blank" class="btn-primary">PDF Slides</a>
      <a href="{{ site.baseurl }}/assets/presentations/spp1-presentation.pptx" download class="btn-secondary">PowerPoint (.pptx)</a>
    </div>
  </div>
</div>

<!-- Presentation Card 2: SPP2 -->
<div class="doc-card reverse">
  <div class="doc-media">
    <img src="{{ site.baseurl }}/assets/images/SPP2-Presentation.png" alt="SPP2 Presentation Preview">
  </div>
  <div class="doc-info">
    <h3>SPP2 — Point of View & Experience Prototypes</h3>
    <p>Presentation on empathy mapping, POV statements, and early experience testing with readers.</p>
    <div class="btn-group">
      <a href="{{ site.baseurl }}/assets/presentations/spp2-presentation.pdf" target="_blank" class="btn-primary">PDF Slides</a>
      <a href="{{ site.baseurl }}/assets/presentations/spp2-presentation.pptx" download class="btn-secondary">PowerPoint (.pptx)</a>
    </div>
  </div>
</div>

<!-- Presentation Card 3: SPP4 -->
<div class="doc-card">
  <div class="doc-media">
    <img src="{{ site.baseurl }}/assets/images/SPP4-Presentation.png" alt="SPP4 Presentation Preview">
  </div>
  <div class="doc-info">
    <h3>SPP4 — Concept Video Presentation</h3>
    <p>Visual narrative presentation showcasing real-world dyslexia reading hurdles and the ClearType workflow solution.</p>
    <div class="btn-group">
      <a href="{{ site.baseurl }}/assets/presentations/spp4-presentation.pdf" target="_blank" class="btn-primary">PDF Slides</a>
      <a href="{{ site.baseurl }}/assets/presentations/spp4-presentation.pptx" download class="btn-secondary">PowerPoint (.pptx)</a>
    </div>
  </div>
</div>

<!-- Presentation Card 4: SPP5 -->
<div class="doc-card reverse">
  <div class="doc-media">
    <img src="{{ site.baseurl }}/assets/images/SPP5-Presentation.png" alt="SPP5 Presentation Preview">
  </div>
  <div class="doc-info">
    <h3>SPP5 — Low-Fi Prototyping & Pilot Usability Testing</h3>
    <p>Overview of low-fidelity paper prototype trials, task execution metrics, and usability findings.</p>
    <div class="btn-group">
      <a href="{{ site.baseurl }}/assets/presentations/spp5-presentation.pdf" target="_blank" class="btn-primary">PDF Slides</a>
      <a href="{{ site.baseurl }}/assets/presentations/spp5-presentation.pptx" download class="btn-secondary">PowerPoint (.pptx)</a>
    </div>
  </div>
</div>

<!-- Presentation Card 5: SPP7 -->
<div class="doc-card">
  <div class="doc-media">
    <div class="doc-placeholder">
      SPP7 Poster & Pitch Thumbnail Placeholder
    </div>
  </div>
  <div class="doc-info">
    <h3>SPP7 — Poster & Pitch Slide</h3>
    <p>Final showcase presentation featuring our elevator pitch slide deck and capstone project poster summarizing the ClearType design process.</p>
    <div class="btn-group">
      <a href="#" class="btn-primary" style="opacity: 0.85;">Pitch Slides (PDF)</a>
      <a href="https://docs.google.com/presentation/d/1u9fn0gHisWA_eYJ8MssCFnWB4gj3TuDNXC7pdkyeBcs/edit?usp=sharing" target="_blank" class="btn-secondary">Pitch Source (.pptx)</a>
      <a href="{{ site.baseurl }}/assets/images/poster.pdf" target="_blank" class="btn-success">Poster (PDF)</a>
    </div>
  </div>
</div>

---

<h2 id="prototypes" style="font-size: 1.6rem; margin-bottom: 1.5rem;">Prototypes</h2>

<!-- Low-Fidelity Prototype Image -->
<img src="{{ site.baseurl }}/assets/images/low-fi-prototype.png" alt="Low-Fidelity Prototype" style="width: 100%; max-width: 100%; height: auto; border-radius: 8px; border: 1px solid #cbd5e1; margin-bottom: 2.5rem; display: block;">

### Medium-Fidelity Prototype
- **Link:** [Launch Wireframe Prototype (Figma)](https://figma.com/proto/gOqo0Y2JVES3FP581AK846/ClearType-SPP6?node-id=1-8&p=f&t=KIXGTaMVbrXJYDWN-0&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=1%3A8)
- **Instructions:**
  1. Click the prototype link above to open the interactive Figma canvas.
  2. Click **Present (Play button)** in the top right corner.
  3. Test task 1: Go to Reading View[DEMO]. Toggle the font selector, then select the OpenDyslexic font visual overlay.
  4. Test task 2: Go to Clean My Notes and select some text. After using one of the buttons to clean the notes, then try to undo it and reset it.
  5. Test task 3: Go to Teacher Preview and create some text, then make the text more dyslexia-friendly by interacting with the suggestions
