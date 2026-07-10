---
layout: archive
title: "Key Coursework"
permalink: /coursework/
author_profile: true
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@400;600;700;800&family=Inter:wght@400;500;600&display=swap');

body, p, li, span, div {
  font-family: 'Nunito', 'Inter', sans-serif;
}

.cw-header-desc {
  font-size: 0.95rem;
  color: var(--global-text-color-light);
  line-height: 1.6;
  margin-bottom: 2rem;
}

.degree-section {
  margin-bottom: 3rem;
}

.degree-banner {
  background: var(--global-bg-color);
  border: 1px solid var(--global-border-color);
  border-radius: 12px;
  padding: 20px 24px;
  margin-bottom: 1.5rem;
  box-shadow: 0 2px 8px rgba(0,0,0,0.03);
}

.degree-title {
  font-size: 1.25rem;
  font-weight: 800;
  color: var(--global-text-color);
  margin-bottom: 4px;
}

.degree-subtitle {
  font-size: 0.9rem;
  color: #3084de;
  font-weight: 600;
  margin-bottom: 12px;
}

.degree-meta {
  display: flex;
  gap: 15px;
  font-size: 0.8rem;
  color: var(--global-text-color-light);
  flex-wrap: wrap;
}

.degree-meta span {
  background: var(--global-border-color);
  padding: 3px 10px;
  border-radius: 6px;
  font-weight: 600;
}

/* ===== Thesis Box ===== */
.thesis-card {
  background: var(--global-bg-color);
  border: 1px solid var(--global-border-color);
  border-left: 4px solid #3084de;
  border-radius: 8px;
  padding: 18px 22px;
  margin-bottom: 1.5rem;
  display: flex;
  flex-direction: column;
  gap: 8px;
}

.thesis-label {
  font-size: 0.75rem;
  font-weight: 800;
  color: #3084de;
  text-transform: uppercase;
  letter-spacing: 0.05em;
}

.thesis-title {
  font-size: 1.05rem;
  font-weight: 700;
  color: var(--global-text-color);
  line-height: 1.4;
}

.thesis-venue {
  font-size: 0.85rem;
  color: var(--global-text-color-light);
}

.thesis-actions {
  display: flex;
  gap: 10px;
  margin-top: 5px;
}

.thesis-btn {
  font-size: 0.8rem;
  font-weight: 700;
  padding: 5px 12px;
  border-radius: 6px;
  text-decoration: none;
  transition: all 0.2s ease;
  display: inline-flex;
  align-items: center;
  gap: 6px;
}

.thesis-btn.primary {
  background: #3084de;
  color: #fff;
}

.thesis-btn.primary:hover {
  background: #2066b8;
  text-decoration: none;
}

.thesis-btn.outline {
  border: 1px solid var(--global-border-color);
  color: var(--global-text-color);
}

.thesis-btn.outline:hover {
  background: var(--global-border-color);
  text-decoration: none;
}

/* ===== Course Grid ===== */
.course-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 20px;
}

.course-card {
  background: var(--global-bg-color);
  border: 1px solid var(--global-border-color);
  border-radius: 10px;
  padding: 20px;
  box-shadow: 0 1px 4px rgba(0,0,0,0.02);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.course-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 16px rgba(0,0,0,0.06);
}

.course-card-title {
  font-size: 0.95rem;
  font-weight: 800;
  color: var(--global-text-color);
  margin-bottom: 12px;
  border-bottom: 1px solid var(--global-border-color);
  padding-bottom: 8px;
  display: flex;
  align-items: center;
  gap: 8px;
}

.course-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.course-list li {
  font-size: 0.88rem;
  line-height: 1.5;
  padding: 6px 0 6px 15px;
  position: relative;
  color: var(--global-text-color);
}

.course-list li::before {
  content: '•';
  position: absolute;
  left: 0;
  color: #3084de;
  font-weight: bold;
}

@media (max-width: 768px) {
  .course-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="cw-header-desc">
  An overview of my academic coursework and thesis research during my graduate (M.Tech) and undergraduate (B.Tech) studies.
</div>

<!-- ================= M.TECH ================= -->
<div class="degree-section">
  <div class="degree-banner">
    <div class="degree-title">M.Tech in Data Science & Artificial Intelligence</div>
    <div class="degree-subtitle">Indian Institute of Information Technology, Ranchi</div>
    <div class="degree-meta">
      <span>2024 – 2026</span>
      <span>CGPA: 8.79 / 10</span>
      <span>Institute of National Importance</span>
    </div>
  </div>

  <div class="thesis-card">
    <span class="thesis-label">Master's Thesis</span>
    <span class="thesis-title">Cross-Domain Text Summarization Using Transformer Models</span>
    <span class="thesis-venue">Department of Computer Science & Engineering, IIIT Ranchi</span>
  </div>

  <div class="course-grid">
    <div class="course-card">
      <div class="course-card-title">🧠 Artificial Intelligence & Machine Learning</div>
      <ul class="course-list">
        <li>Advanced Artificial Intelligence</li>
        <li>Advanced Machine Learning</li>
        <li>Pattern Recognition</li>
        <li>Advanced Soft Computing</li>
        <li>Evolutionary & Randomized Algorithms</li>
      </ul>
    </div>

    <div class="course-card">
      <div class="course-card-title">📊 Data Science & Mining</div>
      <ul class="course-list">
        <li>Fundamentals of Data Science</li>
        <li>Data Mining & Data Warehousing</li>
        <li>Software Defect & Quality Prediction</li>
      </ul>
    </div>
  </div>
</div>

<hr style="border: 0; border-top: 1px solid var(--global-border-color); margin: 2rem 0;" />

<!-- ================= B.TECH ================= -->
<div class="degree-section">
  <div class="degree-banner">
    <div class="degree-title">B.Tech in Information Technology</div>
    <div class="degree-subtitle">North-Eastern Hill University (NEHU), Shillong</div>
    <div class="degree-meta">
      <span>2018 – 2022</span>
      <span>CGPA: 7.85 / 10</span>
      <span>Central University</span>
    </div>
  </div>

  <div class="thesis-card">
    <span class="thesis-label">Bachelor's Thesis</span>
    <span class="thesis-title">IoT-HITS: An IoT-Based Human Intrusion Detection System for Border Region Using Deep Learning</span>
    <span class="thesis-venue">Published in the <strong>IETE Journal of Research</strong> (Taylor & Francis) · Scopus & SCI Indexed</span>
    <div class="thesis-actions">
      <a href="https://www.tandfonline.com/doi/full/10.1080/03772063.2025.2521688" target="_blank" class="thesis-btn primary">
        <i class="fas fa-external-link-alt fa-xs"></i> View Publication
      </a>
      <a href="https://doi.org/10.1080/03772063.2025.2521688" target="_blank" class="thesis-btn outline">
        <i class="fas fa-link fa-xs"></i> DOI
      </a>
    </div>
  </div>

  <div class="course-grid">
    <div class="course-card">
      <div class="course-card-title">🧠 AI & Intelligent Systems</div>
      <ul class="course-list">
        <li>Artificial Intelligence</li>
        <li>Soft Computing</li>
      </ul>
    </div>

    <div class="course-card">
      <div class="course-card-title">🔐 Security & Cryptography</div>
      <ul class="course-list">
        <li>Cryptography & Network Security</li>
        <li>Advanced Cryptography</li>
      </ul>
    </div>

    <div class="course-card">
      <div class="course-card-title">💻 Algorithms, Programming & Software</div>
      <ul class="course-list">
        <li>Data Structures & Algorithms</li>
        <li>Algorithm Analysis & Design</li>
        <li>Object-Oriented Programming & Methodology</li>
        <li>Compiler Design</li>
        <li>Software Engineering</li>
        <li>Web Technology</li>
      </ul>
    </div>

    <div class="course-card">
      <div class="course-card-title">🖥️ Systems & Networks</div>
      <ul class="course-list">
        <li>Operating Systems</li>
        <li>Computer Networks</li>
        <li>Computer Organization & Architecture</li>
        <li>Wireless Networks</li>
        <li>Data Communication</li>
      </ul>
    </div>

    <div class="course-card">
      <div class="course-card-title">📐 Mathematics & Theory</div>
      <ul class="course-list">
        <li>Discrete Mathematics</li>
        <li>Statistics & Random Processes</li>
        <li>Formal Language & Automata Theory</li>
      </ul>
    </div>

    <div class="course-card">
      <div class="course-card-title">🗄️ Data Management</div>
      <ul class="course-list">
        <li>Relational Database Management Systems</li>
        <li>Management Information Systems</li>
      </ul>
    </div>
  </div>
</div>
