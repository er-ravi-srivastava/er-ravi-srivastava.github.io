---
layout: archive
title: "Experience"
permalink: /experience/
author_profile: true
---

<style>
/* ===== Timeline Styles ===== */
.timeline {
  position: relative;
  padding: 0;
  margin: 2rem 0 0 0;
  list-style: none;
}

.timeline::before {
  content: '';
  position: absolute;
  left: 16px;
  top: 0;
  bottom: 0;
  width: 3px;
  background: linear-gradient(180deg, var(--global-link-color), var(--global-border-color));
  border-radius: 2px;
}

.timeline-item {
  position: relative;
  padding-left: 50px;
  margin-bottom: 35px;
}

.timeline-item::before {
  content: '';
  position: absolute;
  left: 8px;
  top: 6px;
  width: 19px;
  height: 19px;
  border-radius: 50%;
  background: var(--global-link-color);
  border: 3px solid var(--global-bg-color);
  box-shadow: 0 0 0 3px var(--global-link-color);
  z-index: 1;
}

.timeline-card {
  background: var(--global-bg-color);
  border: 1px solid var(--global-border-color);
  border-radius: 12px;
  padding: 24px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.06);
  transition: transform 0.25s ease, box-shadow 0.25s ease;
}

.timeline-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 10px 28px rgba(0,0,0,0.12);
}

.tl-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  flex-wrap: wrap;
  gap: 8px;
  margin-bottom: 8px;
}

.tl-role {
  font-weight: 700;
  font-size: 1.15rem;
  color: var(--global-text-color);
  font-family: 'Inter', sans-serif;
  line-height: 1.3;
}

.tl-date {
  font-size: 0.84rem;
  font-weight: 600;
  color: #fff;
  background: var(--global-link-color);
  padding: 4px 14px;
  border-radius: 20px;
  white-space: nowrap;
}

.tl-company {
  font-weight: 600;
  color: var(--global-link-color);
  font-size: 0.95rem;
  margin-bottom: 12px;
  display: block;
}

.tl-desc ul {
  margin: 0;
  padding-left: 20px;
}

.tl-desc ul li {
  font-size: 0.95rem;
  line-height: 1.6;
  margin-bottom: 8px;
  color: var(--global-text-color);
}

.tl-desc ul li:last-child {
  margin-bottom: 0;
}

/* Education cards inside timeline */
.edu-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 16px;
}

.edu-card {
  background: var(--global-bg-color);
  border: 1px solid var(--global-border-color);
  border-radius: 10px;
  padding: 20px;
  transition: transform 0.2s ease;
}

.edu-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 18px rgba(0,0,0,0.1);
}

.edu-degree {
  font-weight: 700;
  font-size: 1rem;
  color: var(--global-text-color);
  margin-bottom: 4px;
}

.edu-school {
  font-size: 0.88rem;
  color: var(--global-link-color);
  font-weight: 600;
  margin-bottom: 4px;
}

.edu-meta {
  font-size: 0.84rem;
  color: var(--global-text-color-light);
  font-style: italic;
}

/* ===== Skills Section ===== */
.section-divider {
  font-size: 1.25rem;
  font-weight: 700;
  color: var(--global-text-color);
  font-family: 'Inter', sans-serif;
  margin: 3rem 0 1.5rem 0;
  border-bottom: 2px solid var(--global-link-color);
  padding-bottom: 10px;
}

.skills-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 20px;
  margin-bottom: 2rem;
}

.skill-category {
  background: var(--global-bg-color);
  border: 1px solid var(--global-border-color);
  border-radius: 12px;
  padding: 24px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.06);
  transition: transform 0.2s ease;
}

.skill-category:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 22px rgba(0,0,0,0.1);
}

.skill-cat-title {
  font-weight: 700;
  font-size: 0.95rem;
  color: var(--global-link-color);
  margin-bottom: 14px;
  font-family: 'Inter', sans-serif;
  text-transform: uppercase;
  letter-spacing: 0.04em;
}

.skill-pills {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}

.skill-pill {
  background: var(--global-border-color);
  color: var(--global-text-color);
  padding: 6px 14px;
  border-radius: 20px;
  font-size: 0.84rem;
  font-weight: 500;
  font-family: 'Inter', sans-serif;
  transition: background 0.2s ease, color 0.2s ease;
}

.skill-pill:hover {
  background: var(--global-link-color);
  color: #fff;
}

@media (max-width: 768px) {
  .tl-header { flex-direction: column; }
  .edu-grid { grid-template-columns: 1fr; }
  .skills-grid { grid-template-columns: 1fr; }
  .timeline-item { padding-left: 40px; }
}
</style>

<!-- ===== Experience Timeline ===== -->
<div class="timeline">

  <!-- Software Engineer -->
  <div class="timeline-item">
    <div class="timeline-card">
      <div class="tl-header">
        <span class="tl-role">Software Engineer</span>
        <span class="tl-date">Mar 2026 – Present</span>
      </div>
      <span class="tl-company"><i class="fas fa-building"></i> SS Software Solutions LLC, Hyderabad, India</span>
      <div class="tl-desc">
        <ul>
          <li>Defined and enforced ML pipeline standards including versioning, logging, and monitoring to improve system reliability and debuggability.</li>
          <li>Currently learning and applying Threat Modeling to proactively identify design-level risks.</li>
          <li>Automated security testing under DevSecOps by integrating tools into CI/CD pipelines, reducing manual effort and improving efficiency.</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- DevOps Engineer -->
  <div class="timeline-item">
    <div class="timeline-card">
      <div class="tl-header">
        <span class="tl-role">DevOps Engineer</span>
        <span class="tl-date">Apr 2023 – Feb 2026</span>
      </div>
      <span class="tl-company"><i class="fas fa-server"></i> Pantech e-learning, Chennai, India</span>
      <div class="tl-desc">
        <ul>
          <li>Designed and deployed ML-based intrusion and anomaly detection models on real-world datasets (10K+ samples), improving threat detection accuracy by 15–20% under noisy and incomplete data conditions.</li>
          <li>Assisted in identifying and documenting security misconfigurations across web applications and CI/CD pipelines, supporting remediation efforts and contributing to secure software development practices within a DevOps workflow.</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Machine Learning Intern -->
  <div class="timeline-item">
    <div class="timeline-card">
      <div class="tl-header">
        <span class="tl-role">Machine Learning Intern</span>
        <span class="tl-date">Aug 2022 – Feb 2023</span>
      </div>
      <span class="tl-company"><i class="fas fa-laptop-code"></i> C-DAC (Govt. of India), Hyderabad, India</span>
      <div class="tl-desc">
        <ul>
          <li>Performed large-scale data preprocessing and feature engineering on student activity logs (attendance, assignments, quizzes) to support predictive modeling.</li>
          <li>Implemented and benchmarked multiple machine learning models, including Decision Trees, Random Forests, and Support Vector Machines, for academic performance prediction.</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Education -->
  <div class="timeline-item">
    <div class="timeline-card">
      <div class="tl-header">
        <span class="tl-role"><i class="fas fa-graduation-cap"></i> Education</span>
      </div>
      <div class="edu-grid">
        <div class="edu-card" style="grid-column: span 2;">
          <div class="edu-degree">B.Tech — Information Technology</div>
          <div class="edu-school">NEHU, Shillong, India</div>
          <div class="edu-meta">Aug 2018 – Jun 2022 · CGPA: 7.85/10</div>
        </div>
      </div>
    </div>
  </div>

</div>

<!-- ===== Skills Section ===== -->
<div class="section-divider">Skills</div>

<div class="skills-grid">

  <div class="skill-category">
    <div class="skill-cat-title"><i class="fas fa-brain"></i> AI & Machine Learning</div>
    <div class="skill-pills">
      <span class="skill-pill">Deep Learning</span>
      <span class="skill-pill">Transformers</span>
      <span class="skill-pill">Adversarial ML</span>
      <span class="skill-pill">Prompt Injection</span>
      <span class="skill-pill">Deepfake Detection</span>
      <span class="skill-pill">Feature Engineering</span>
    </div>
  </div>

  <div class="skill-category">
    <div class="skill-cat-title"><i class="fas fa-shield-alt"></i> Cybersecurity</div>
    <div class="skill-pills">
      <span class="skill-pill">Threat Modeling</span>
      <span class="skill-pill">OWASP Top 10</span>
      <span class="skill-pill">Vuln Assessment</span>
      <span class="skill-pill">Burp Suite</span>
      <span class="skill-pill">Nmap</span>
      <span class="skill-pill">Wireshark</span>
    </div>
  </div>

  <div class="skill-category">
    <div class="skill-cat-title"><i class="fas fa-code"></i> Programming & Frameworks</div>
    <div class="skill-pills">
      <span class="skill-pill">Python</span>
      <span class="skill-pill">C++</span>
      <span class="skill-pill">SQL</span>
      <span class="skill-pill">Bash</span>
      <span class="skill-pill">PyTorch</span>
      <span class="skill-pill">Hugging Face</span>
      <span class="skill-pill">Scikit-learn</span>
    </div>
  </div>

  <div class="skill-category">
    <div class="skill-cat-title"><i class="fas fa-tools"></i> Platforms & DevOps</div>
    <div class="skill-pills">
      <span class="skill-pill">Linux</span>
      <span class="skill-pill">Git</span>
      <span class="skill-pill">Docker</span>
      <span class="skill-pill">CI/CD</span>
      <span class="skill-pill">Jupyter</span>
      <span class="skill-pill">LaTeX</span>
    </div>
  </div>

</div>
