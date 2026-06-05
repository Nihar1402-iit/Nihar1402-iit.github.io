---
layout: archive
title: "Hackathons"
permalink: /hackathons/
author_profile: true
redirect_from:
  - /hackathon/
  - /hackathons
---

{% include base_path %}

<style>
.hackathon-intro {
  max-width: 900px;
  margin-bottom: 1.5rem;
  line-height: 1.7;
  color: #cdeff0;
}

.hackathon-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.5rem;
  margin-top: 1.5rem;
}

.hackathon-card {
  position: relative;
  overflow: hidden;
}

.hackathon-header {
  display: flex;
  align-items: flex-start;
  gap: 1rem;
  margin-bottom: 1rem;
}

.hackathon-thumb {
  flex: 0 0 74px;
  width: 74px;
  height: 74px;
  border-radius: 18px;
  display: grid;
  place-items: center;
  color: #0b0c10;
  font-size: 1.45rem;
  font-weight: 800;
  letter-spacing: 0.04em;
  box-shadow: 0 10px 28px rgba(0, 0, 0, 0.35);
  position: relative;
  overflow: hidden;
}

.hackathon-thumb::after {
  content: "";
  position: absolute;
  inset: 0;
  background: radial-gradient(circle at top left, rgba(255, 255, 255, 0.45), transparent 52%);
}

.hackathon-thumb span {
  position: relative;
  z-index: 1;
}

.hackathon-thumb--hackrush {
  background: linear-gradient(135deg, #66FCF1 0%, #b7fff9 100%);
}

.hackathon-thumb--deepmind {
  background: linear-gradient(135deg, #6ee7ff 0%, #8b5cf6 100%);
}

.hackathon-thumb--growve {
  background: linear-gradient(135deg, #34d399 0%, #f59e0b 100%);
}

.hackathon-thumb--openenv {
  background: linear-gradient(135deg, #a3e635 0%, #14b8a6 100%);
}

.hackathon-thumb--amazon {
  background: linear-gradient(135deg, #fbbf24 0%, #fb7185 100%);
}

.hackathon-heading {
  min-width: 0;
}

.hackathon-card::before {
  content: "";
  position: absolute;
  inset: 0;
  background: linear-gradient(135deg, rgba(102, 252, 241, 0.16), transparent 45%);
  pointer-events: none;
}

.hackathon-card .eyebrow {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  color: #66FCF1;
  font-size: 0.85rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  margin-bottom: 0.6rem;
}

.hackathon-card h3 {
  margin-bottom: 0.25rem;
}

.hackathon-preview {
  width: 100%;
  height: 180px;
  border-radius: 18px;
  overflow: hidden;
  margin-bottom: 1rem;
  background: #0b0c10;
  border: 1px solid rgba(102, 252, 241, 0.15);
  box-shadow: 0 10px 28px rgba(0, 0, 0, 0.25);
}

.hackathon-preview img,
.hackathon-preview video {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

.hackathon-preview--video {
  background: linear-gradient(135deg, #111827, #0f172a);
}

.hackathon-meta {
  color: #45A29E;
  font-size: 0.95rem;
  margin-bottom: 1rem;
}

.hackathon-card ul {
  margin: 0;
  padding-left: 1.2rem;
  color: #d8f4f3;
}

.hackathon-links {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
  margin-top: 1.25rem;
}

.hackathon-link {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  border-radius: 999px;
  padding: 0.55rem 1rem;
  border: 1px solid rgba(102, 252, 241, 0.35);
  color: #66FCF1;
  text-decoration: none;
  transition: all 0.25s ease;
  background: rgba(102, 252, 241, 0.06);
}

.hackathon-link:hover {
  transform: translateY(-2px);
  color: #0b0c10;
  background: #66FCF1;
}

.hackathon-link--primary {
  color: #0b0c10;
  background: #66FCF1;
}

.hackathon-link--primary:hover {
  background: #9ffdf6;
}

.hackathon-link--action {
  background: rgba(11, 12, 16, 0.18);
  color: #cdeff0;
}

.hackathon-link--action:hover {
  color: #0b0c10;
  background: #66FCF1;
}

@media (max-width: 640px) {
  .hackathon-header {
    flex-direction: column;
  }

  .hackathon-thumb {
    width: 62px;
    height: 62px;
    border-radius: 16px;
    font-size: 1.2rem;
  }
}
</style>

<p class="hackathon-intro">
  A curated set of hackathon submissions, challenge builds, and competition repos.
  This section collects the work I shipped under tight deadlines across product, ML,
  and computer vision tracks.
</p>

<div class="domain-badges scroll-reveal" style="margin-bottom: 2rem;">
  <span class="badge"><i class="fas fa-trophy"></i> Winner</span>
  <span class="badge"><i class="fas fa-eye"></i> Computer Vision</span>
  <span class="badge"><i class="fas fa-robot"></i> Generative AI</span>
  <span class="badge"><i class="fas fa-chart-line"></i> Applied ML</span>
</div>

<div class="hackathon-grid">
  <article class="glass-card scroll-reveal hackathon-card">
    <div class="hackathon-preview">
      <img src="{{ base_path }}/images/hackrush-cover.svg" alt="HackRush 2026 cover">
    </div>
    <div class="hackathon-header">
      <div class="hackathon-thumb hackathon-thumb--hackrush"><span>HR</span></div>
      <div class="hackathon-heading">
        <div class="eyebrow"><i class="fas fa-trophy"></i> HackRush 2026</div>
        <h3>CV Problem Statement Solution</h3>
      </div>
    </div>
    <div class="hackathon-meta">IIT Gandhinagar • Winner</div>
    <ul>
      <li>Submission for the IITGN Computer Vision problem statement.</li>
      <li>Primary code is in <code>Hackrush_2026</code>, with the alternate solution in <code>Hackathon_2026_Sol2</code>.</li>
    </ul>
    <div class="hackathon-links">
      <a class="hackathon-link hackathon-link--action" href="https://github.com/Nihar1402-iit/Hackrush_2026" target="_blank" rel="noreferrer">
        <i class="fab fa-github"></i> View Code
      </a>
    </div>
  </article>

  <article class="glass-card scroll-reveal hackathon-card">
    <div class="hackathon-preview">
      <img src="{{ base_path }}/images/sketch2site-cover.svg" alt="Sketch2Site pipeline cover">
    </div>
    <div class="hackathon-header">
      <div class="hackathon-thumb hackathon-thumb--deepmind"><span>DM</span></div>
      <div class="hackathon-heading">
        <div class="eyebrow"><i class="fas fa-magic"></i> Google DeepMind Hackathon</div>
        <h3>Sketch2Site</h3>
      </div>
    </div>
    <div class="hackathon-meta">Pipeline documented in the Kaggle write-up</div>
    <ul>
      <li>Sketch-to-site pipeline spanning image parsing, symbol detection, component detection, prompt creation, and HTML/CSS generation.</li>
      <li>Implemented with Gemini API + Flask, with the flow visualized in the Kaggle write-up.</li>
    </ul>
    <div class="hackathon-links">
      <a class="hackathon-link hackathon-link--action" href="https://youtu.be/2bToevN2Sjo?si=ZmuFlMovNE-49-wW" target="_blank" rel="noreferrer">
        <i class="fas fa-play"></i> Watch Demo
      </a>
    </div>
  </article>

  <article class="glass-card scroll-reveal hackathon-card">
    <div class="hackathon-preview">
      <img src="{{ base_path }}/images/growve-cover.svg" alt="Growve cover">
    </div>
    <div class="hackathon-header">
      <div class="hackathon-thumb hackathon-thumb--growve"><span>GV</span></div>
      <div class="hackathon-heading">
        <div class="eyebrow"><i class="fas fa-building"></i> Microsoft Imagine Cup</div>
        <h3>Growve</h3>
      </div>
    </div>
    <div class="hackathon-meta">Private codebase • FinanceFlow AI / Growve demo</div>
    <ul>
      <li>Private Microsoft Imagine Cup submission built as Growve / FinanceFlow AI.</li>
      <li>Demo covers smart OCR, auto-categorization, duplicate detection, dashboard analytics, balance sheets, tax suggestions, and business consulting.</li>
      <li>Includes a screen-recorded product walkthrough for review and presentation.</li>
    </ul>
    <div class="hackathon-links">
      <a class="hackathon-link hackathon-link--action" href="{{ base_path }}/images/growve-demo.mp4" target="_blank" rel="noreferrer">
        <i class="fas fa-play"></i> Watch Demo
      </a>
    </div>
  </article>

  <article class="glass-card scroll-reveal hackathon-card">
    <div class="hackathon-preview">
      <img src="{{ base_path }}/images/openenv-cover.svg" alt="OpenEnv cover">
    </div>
    <div class="hackathon-header">
      <div class="hackathon-thumb hackathon-thumb--openenv"><span>OE</span></div>
      <div class="hackathon-heading">
        <div class="eyebrow"><i class="fas fa-leaf"></i> Meta OpenEnv Hackathon</div>
        <h3>OpenEnv</h3>
      </div>
    </div>
    <div class="hackathon-meta">Hackathon submission</div>
    <ul>
      <li>Submission repo for the Meta OpenEnv Hackathon.</li>
      <li>Captured here as part of the main hackathon portfolio.</li>
    </ul>
    <div class="hackathon-links">
      <a class="hackathon-link hackathon-link--action" href="https://github.com/Nihar1402-iit/OpenEnv-Hackathon" target="_blank" rel="noreferrer">
        <i class="fab fa-github"></i> View Code
      </a>
    </div>
  </article>

  <article class="glass-card scroll-reveal hackathon-card">
    <div class="hackathon-preview">
      <img src="{{ base_path }}/images/amazon-cover.svg" alt="Amazon ML Challenge cover">
    </div>
    <div class="hackathon-header">
      <div class="hackathon-thumb hackathon-thumb--amazon"><span>AM</span></div>
      <div class="hackathon-heading">
        <div class="eyebrow"><i class="fas fa-clipboard-list"></i> Amazon ML Challenge</div>
        <h3>Shot Prompting</h3>
      </div>
    </div>
    <div class="hackathon-meta">Project page</div>
    <ul>
      <li>Public write-up page for the Amazon ML challenge work.</li>
      <li>Kept as a standalone project page for quick sharing.</li>
    </ul>
    <div class="hackathon-links">
      <a class="hackathon-link hackathon-link--action" href="https://nihar1402-iit.github.io/_pages/Shot_Prompting.html" target="_blank" rel="noreferrer">
        <i class="fas fa-external-link-alt"></i> Open Write-up
      </a>
    </div>
  </article>
</div>
