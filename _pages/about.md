---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* Global Theme Colors */
  :root {
    --kyoto-blue: #004471;
    --text-main: #24292e;
    --text-sub: #586069;
    --bg-light: #f6f8fa;
  }

  /* Hero Image Styling */
  .hero-container {
    position: relative;
    margin-bottom: 30px;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
  }
  .hero-image {
    width: 100%;
    display: block;
    transition: transform 0.6s cubic-bezier(0.165, 0.84, 0.44, 1);
  }
  .hero-container:hover .hero-image {
    transform: scale(1.03);
  }

  /* Academic Profile Card */
  .profile-header {
    display: flex;
    align-items: center;
    background: linear-gradient(135deg, #ffffff, var(--bg-light));
    padding: 24px;
    border-radius: 12px;
    border-left: 6px solid var(--kyoto-blue);
    margin-bottom: 30px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
  }
  .uni-logo {
    width: 80px;
    height: auto;
    margin-right: 25px;
    filter: drop-shadow(0 2px 4px rgba(0,0,0,0.1));
  }
  .profile-info h1 {
    margin: 0;
    font-size: 1.6em;
    color: var(--kyoto-blue);
  }
  .profile-info p {
    margin: 5px 0 0;
    color: var(--text-main);
    font-weight: 500;
  }
  .supervisor-link {
    font-size: 0.9em;
    color: var(--text-sub);
    margin-top: 4px;
  }

  /* Skill Badges */
  .badge-container {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin: 20px 0;
  }
  .skill-badge {
    padding: 6px 14px;
    background: #fff;
    color: var(--kyoto-blue);
    border: 1px solid #d1d5da;
    border-radius: 20px;
    font-size: 0.85em;
    font-weight: 600;
    transition: all 0.3s ease;
  }
  .skill-badge:hover {
    background: var(--kyoto-blue);
    color: #fff;
    border-color: var(--kyoto-blue);
    transform: translateY(-3px);
    box-shadow: 0 4px 10px rgba(0,68,113,0.2);
  }

  /* Professional Timeline */
  .timeline {
    border-left: 2px solid #e1e4e8;
    padding-left: 20px;
    margin: 20px 0 20px 10px;
  }
  .timeline-item {
    margin-bottom: 20px;
    position: relative;
  }
  .timeline-item::before {
    content: '';
    position: absolute;
    width: 12px;
    height: 12px;
    background: var(--kyoto-blue);
    border-radius: 50%;
    left: -27px;
    top: 5px;
    border: 2px solid #fff;
  }
  .time-label {
    font-family: "SFMono-Regular", Consolas, monospace;
    font-weight: 700;
    color: var(--kyoto-blue);
    display: block;
    font-size: 0.9em;
  }
</style>

<div class="hero-container">
  <img src="/images/Uji Campus.jpg" alt="Kyoto University Uji Campus" class="hero-image">
</div>

<div class="profile-header">
  <img src="/images/KyotoU Logo.png" alt="Kyoto University Logo" class="uni-logo">
  <div class="profile-info">
    <h1>W. Z.</h1>
    <p>Ph.D. Candidate in Informatics</p>
    <div class="supervisor-link">
      Kyoto University | Supervisor: Prof. Takeyuki Tamura
    </div>
  </div>
</div>

## 🧬 Biography

I am a Ph.D. student at the **Graduate School of Informatics, Kyoto University**. My research stands at the convergence of **Machine Learning, Cheminformatics, and Bioinformatics**.

I am committed to developing advanced deep learning frameworks to decode complex biochemical systems. My current research focus includes:
* **Interkcat Framework**: Developing Attention-based deep learning models for high-precision prediction of enzyme kinetic constants (k<sub>cat</sub>).
* **Protein Engineering**: Utilizing Attention Site Mapping to identify lethal mutation sites and "hit zones" in enzymes.
* **AI for Science**: Implementing ML frameworks for solvent identification and precursor coordination in **Perovskite Solar Cells** to optimize film fabrication.

## 🛠 Technical Stack

<div class="badge-container">
  <span class="skill-badge">PyTorch</span>
  <span class="skill-badge">Graph Neural Networks (GNNs)</span>
  <span class="skill-badge">Transformer & Attention</span>
  <span class="skill-badge">RDKit</span>
  <span class="skill-badge">Scikit-Learn</span>
  <span class="skill-badge">Metabolic Modeling (GEMs)</span>
  <span class="skill-badge">Linux / CUDA</span>
</div>

## 📢 News & Updates

<div class="timeline">
  <div class="timeline-item">
    <span class="time-label">Apr 2026</span>
    Research article accepted for publication in <strong>Energy & Environmental Science (EES)</strong>.
  </div>
  <div class="timeline-item">
    <span class="time-label">Mar 2026</span>
    Successfully completed point-by-point reviewer responses for the solvent identification framework in perovskite research.
  </div>
  <div class="timeline-item">
    <span class="time-label">Oct 2025</span>
    Commenced Ph.D. journey at the Laboratory of Mathematical Bioinformatics, Kyoto University.
  </div>
</div>

## 🎓 Education
* **Ph.D. in Informatics** | Kyoto University, Japan | Oct 2025 – Present
* **M.Eng. Chemical Engineering** | Dalian Univ. of Technology, China | Sep 2022 – Jun 2025
* **B.S. Applied Chemistry** | Qingdao Univ. of Sci. & Tech., China | Sep 2018 – Jun 2025