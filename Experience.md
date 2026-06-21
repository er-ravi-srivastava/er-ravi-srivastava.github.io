---
layout: archive
title: "Experience"
permalink: /experience/
author_profile: true
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@400;600;700;800&family=Inter:wght@400;500;600&display=swap');

/* ===== Section Heading ===== */
.exp-section-title {
  font-size: 1.2rem;
  font-weight: 800;
  font-family: 'Nunito', sans-serif;
  color: var(--global-text-color);
  margin: 2.5rem 0 1.2rem 0;
  padding-bottom: 8px;
  border-bottom: 2px solid #3084de;
  display: inline-block;
}

/* ===== Timeline ===== */
.timeline {
  position: relative;
  padding: 0;
  margin: 1.5rem 0 0 0;
  list-style: none;
}

.timeline::before {
  content: '';
  position: absolute;
  left: 16px;
  top: 0;
  bottom: 0;
  width: 2px;
  background: linear-gradient(180deg, #3084de 0%, var(--global-border-color) 100%);
  border-radius: 2px;
}

.timeline-item {
  position: relative;
  padding-left: 52px;
  margin-bottom: 28px;
}

.timeline-item::before {
  content: '';
  position: absolute;
  left: 8px;
  top: 8px;
  width: 18px;
  height: 18px;
  border-radius: 50%;
  background: #3084de;
  border: 3px solid var(--global-bg-color);
  box-shadow: 0 0 0 2px #3084de;
  z-index: 1;
}

/* ===== Timeline Card ===== */
.timeline-card {
  background: var(--global-bg-color);
  border: 1px solid var(--global-border-color);
  border-radius: 10px;
  padding: 20px 22px;
  box-shadow: 0 1px 6px rgba(0,0,0,0.05);
  transition: box-shadow 0.25s ease, transform 0.25s ease;
}

.timeline-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 24px rgba(48, 132, 222, 0.12);
}

/* ===== Card Header ===== */
.tl-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  flex-wrap: wrap;
  gap: 8px;
  margin-bottom: 3px;
}

.tl-role {
  font-weight: 800;
  font-size: 1.05rem;
  color: var(--global-text-color);
  font-family: 'Nunito', sans-serif;
  line-height: 1.3;
}

.tl-date {
  font-size: 0.8rem;
  font-weight: 700;
  color: #3084de;
  background: rgba(48, 132, 222, 0.1);
  padding: 3px 12px;
  border-radius: 20px;
  white-space: nowrap;
  border: 1px solid rgba(48, 132, 222, 0.25);
}

.tl-company {
  font-weight: 600;
  color: #3084de;
  font-size: 0.88rem;
  margin-bottom: 14px;
  display: block;
  font-family: 'Nunito', sans-serif;
}

/* ===== Bullet List ===== */
.tl-desc ul {
  margin: 0;
  padding-left: 0;
  list-style: none;
}

.tl-desc ul li {
  font-size: 0.93rem;
  line-height: 1.65;
  margin-bottom: 9px;
  color: var(--global-text-color);
  padding-left: 1.1em;
  position: relative;
  font-family: 'Nunito', sans-serif;
}

.tl-desc ul li::before {
  content: '▸';
  position: absolute;
  left: 0;
  color: #3084de;
  font-size: 0.75rem;
  top: 3px;
}

.tl-desc ul li:last-child {
  margin-bottom: 0;
}

.tl-desc ul li strong {
  color: var(--global-text-color);
  font-weight: 700;
}

/* ===== Tags on a card ===== */
.tl-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
  margin-top: 14px;
  padding-top: 12px;
  border-top: 1px solid var(--global-border-color);
}

.tl-tag {
  font-size: 0.76rem;
  font-weight: 600;
  background: var(--global-border-color);
  color: var(--global-text-color);
  padding: 3px 10px;
  border-radius: 12px;
  font-family: 'Nunito', sans-serif;
}

/* ===== Education Cards ===== */
.edu-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 14px;
  margin-top: 1rem;
}

.edu-card {
  background: var(--global-bg-color);
  border: 1px solid var(--global-border-color);
  border-left: 4px solid #3084de;
  border-radius: 8px;
  padding: 16px 18px;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.edu-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 18px rgba(48, 132, 222, 0.12);
}

.edu-degree {
  font-weight: 800;
  font-size: 0.95rem;
  color: var(--global-text-color);
  margin-bottom: 4px;
  font-family: 'Nunito', sans-serif;
}

.edu-field {
  font-size: 0.86rem;
  color: var(--global-text-color);
  margin-bottom: 4px;
  font-family: 'Nunito', sans-serif;
}

.edu-school {
  font-size: 0.85rem;
  color: #3084de;
  font-weight: 700;
  margin-bottom: 4px;
  font-family: 'Nunito', sans-serif;
}

.edu-meta {
  font-size: 0.8rem;
  color: var(--global-text-color-light);
  font-style: italic;
  font-family: 'Nunito', sans-serif;
}

/* ===== Skills Section ===== */
.skills-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 16px;
  margin-top: 1rem;
}

.skill-category {
  background: var(--global-bg-color);
  border: 1px solid var(--global-border-color);
  border-radius: 10px;
  padding: 18px 20px;
  box-shadow: 0 1px 6px rgba(0,0,0,0.04);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.skill-category:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 22px rgba(48, 132, 222, 0.1);
}

.skill-cat-title {
  font-weight: 800;
  font-size: 0.82rem;
  color: #3084de;
  margin-bottom: 12px;
  font-family: 'Nunito', sans-serif;
  text-transform: uppercase;
  letter-spacing: 0.06em;
}

.skill-pills {
  display: flex;
  flex-wrap: wrap;
  gap: 7px;
}

.skill-pill {
  background: rgba(48, 132, 222, 0.08);
  color: var(--global-text-color);
  padding: 5px 12px;
  border-radius: 16px;
  font-size: 0.82rem;
  font-weight: 600;
  font-family: 'Nunito', sans-serif;
  border: 1px solid rgba(48, 132, 222, 0.2);
  transition: background 0.2s ease, color 0.2s ease;
}

.skill-pill:hover {
  background: #3084de;
  color: #fff;
  border-color: #3084de;
}

/* ===== Responsive ===== */
@media (max-width: 768px) {
  .tl-header { flex-direction: column; }
  .edu-grid { grid-template-columns: 1fr; }
  .skills-grid { grid-template-columns: 1fr; }
  .timeline-item { padding-left: 40px; }
}
</style>

<!-- ===== Experience Timeline ===== -->
<div class="exp-section-title">Work Experience</div>
<div class="timeline">

  <!-- Software Engineer -->
  <div class="timeline-item">
    <div class="timeline-card">
      <div class="tl-header">
        <span class="tl-role">Software Engineer</span>
        <span class="tl-date">Mar 2026 – Present</span>
      </div>
      <span class="tl-company"><i class="fas fa-building fa-sm"></i>&nbsp; SS Software Solutions LLC &mdash; Hyderabad, India</span>
      <div class="tl-desc">
        <ul>
          <li><strong>ML Pipeline Governance.</strong> Standardised model versioning (MLflow / DVC), structured JSON logging with distributed trace IDs, and drift-detection alerting — reduced incident diagnosis time by ~40% across 3 production models.</li>
          <li><strong>AI Threat Modeling.</strong> Applied STRIDE to ML systems; identified 8 design-level risks (data poisoning, model inversion) — cut mean time-to-debug by ~35% and eliminated untracked deployments.</li>
          <li><strong>DevSecOps Automation.</strong> Integrated SAST tools (Bandit, Semgrep) and dependency-vulnerability scanning into GitHub Actions CI/CD — reduced manual security-review effort by ~60%.</li>
        </ul>
      </div>
      <div class="tl-tags">
        <span class="tl-tag">MLflow</span>
        <span class="tl-tag">DVC</span>
        <span class="tl-tag">STRIDE</span>
        <span class="tl-tag">Semgrep</span>
        <span class="tl-tag">Bandit</span>
        <span class="tl-tag">GitHub Actions</span>
        <span class="tl-tag">AI Security</span>
      </div>
    </div>
  </div>

  <!-- ML Intern C-DAC -->
  <div class="timeline-item">
    <div class="timeline-card">
      <div class="tl-header">
        <span class="tl-role">Machine Learning Research Intern</span>
        <span class="tl-date">Aug 2022 – Feb 2023</span>
      </div>
      <span class="tl-company"><i class="fas fa-landmark fa-sm"></i>&nbsp; C-DAC — Centre for Development of Advanced Computing, Govt. of India &mdash; Hyderabad</span>
      <div class="tl-desc">
        <ul>
          <li><strong>Feature Engineering.</strong> Preprocessed 10,000+ student activity log records (attendance, assignments, quiz scores) and engineered predictive features for academic-performance modeling.</li>
          <li><strong>Model Benchmarking.</strong> Implemented and compared Decision Tree, Random Forest, and SVM classifiers; documented results in internal technical reports.</li>
        </ul>
      </div>
      <div class="tl-tags">
        <span class="tl-tag">Python</span>
        <span class="tl-tag">Scikit-learn</span>
        <span class="tl-tag">Feature Engineering</span>
        <span class="tl-tag">Predictive Modeling</span>
      </div>
    </div>
  </div>

</div>

<!-- ===== Education ===== -->
<div class="exp-section-title">Education</div>
<div class="edu-grid">

  <div class="edu-card">
    <div class="edu-degree">M.Tech</div>
    <div class="edu-field">Data Science &amp; Artificial Intelligence</div>
    <div class="edu-school"><i class="fas fa-university fa-sm"></i>&nbsp; IIIT Ranchi, India</div>
    <div class="edu-meta">Aug 2024 – May 2026 &nbsp;·&nbsp; CGPA: 8.79 / 10 &nbsp;·&nbsp; Institute of National Importance</div>
  </div>

  <div class="edu-card">
    <div class="edu-degree">B.Tech</div>
    <div class="edu-field">Information Technology</div>
    <div class="edu-school"><i class="fas fa-university fa-sm"></i>&nbsp; NEHU, Shillong, India</div>
    <div class="edu-meta">Aug 2018 – Jun 2022 &nbsp;·&nbsp; CGPA: 7.85 / 10 &nbsp;·&nbsp; Central University</div>
  </div>

</div>

<!-- ===== Skills ===== -->
<div class="exp-section-title">Technical Skills</div>
<div class="skills-grid">

  <div class="skill-category">
    <div class="skill-cat-title"><i class="fas fa-shield-alt"></i>&nbsp; AI Security</div>
    <div class="skill-pills">
      <span class="skill-pill">Adversarial ML</span>
      <span class="skill-pill">LLM Prompt Injection</span>
      <span class="skill-pill">Deepfake Detection</span>
      <span class="skill-pill">Threat Modeling (STRIDE)</span>
      <span class="skill-pill">OWASP Top 10</span>
      <span class="skill-pill">IDS / IPS</span>
      <span class="skill-pill">Pentest</span>
    </div>
  </div>

  <div class="skill-category">
    <div class="skill-cat-title"><i class="fas fa-project-diagram"></i>&nbsp; MLOps &amp; DevSecOps</div>
    <div class="skill-pills">
      <span class="skill-pill">MLflow</span>
      <span class="skill-pill">DVC</span>
      <span class="skill-pill">Docker</span>
      <span class="skill-pill">GitHub Actions</span>
      <span class="skill-pill">Semgrep</span>
      <span class="skill-pill">Bandit</span>
      <span class="skill-pill">CI/CD</span>
    </div>
  </div>

  <div class="skill-category">
    <div class="skill-cat-title"><i class="fas fa-brain"></i>&nbsp; ML &amp; Deep Learning</div>
    <div class="skill-pills">
      <span class="skill-pill">PyTorch</span>
      <span class="skill-pill">Hugging Face</span>
      <span class="skill-pill">Transformers</span>
      <span class="skill-pill">Scikit-learn</span>
      <span class="skill-pill">Few-Shot Learning</span>
      <span class="skill-pill">Feature Engineering</span>
    </div>
  </div>

  <div class="skill-category">
    <div class="skill-cat-title"><i class="fas fa-code"></i>&nbsp; Programming &amp; Tools</div>
    <div class="skill-pills">
      <span class="skill-pill">Python</span>
      <span class="skill-pill">C++</span>
      <span class="skill-pill">Bash</span>
      <span class="skill-pill">SQL</span>
      <span class="skill-pill">Linux</span>
      <span class="skill-pill">Git</span>
      <span class="skill-pill">LaTeX</span>
      <span class="skill-pill">Jupyter</span>
    </div>
  </div>

</div>
