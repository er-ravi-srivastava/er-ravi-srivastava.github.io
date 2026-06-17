---
layout: single
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
---

<style>
/* ===== CV Page Styles ===== */
.cv-download {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  background: var(--global-link-color);
  color: #fff !important;
  padding: 14px 28px;
  border-radius: 8px;
  font-size: 1rem;
  font-weight: 700;
  font-family: 'Inter', sans-serif;
  text-decoration: none;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  margin-bottom: 2.5rem;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
}

.cv-download:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 24px rgba(0,0,0,0.2);
  color: #fff !important;
  text-decoration: none;
}

.cv-section {
  margin-bottom: 2.5rem;
}

.cv-section-title {
  font-size: 1.25rem;
  font-weight: 700;
  color: var(--global-text-color);
  font-family: 'Inter', sans-serif;
  display: flex;
  align-items: center;
  gap: 10px;
  margin-bottom: 1rem;
  padding-bottom: 8px;
  border-bottom: 2px solid var(--global-link-color);
}

.cv-section-title i {
  color: var(--global-link-color);
  font-size: 1.1rem;
}

.cv-entry {
  background: var(--global-bg-color);
  border: 1px solid var(--global-border-color);
  border-radius: 10px;
  padding: 20px;
  margin-bottom: 16px;
  box-shadow: 0 1px 6px rgba(0,0,0,0.04);
  transition: transform 0.2s ease;
}

.cv-entry:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 16px rgba(0,0,0,0.08);
}

.cv-entry-header {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  flex-wrap: wrap;
  gap: 8px;
  margin-bottom: 6px;
}

.cv-entry-title {
  font-weight: 700;
  font-size: 1.05rem;
  color: var(--global-text-color);
  font-family: 'Inter', sans-serif;
}

.cv-entry-date {
  font-size: 0.84rem;
  font-weight: 600;
  color: var(--global-link-color);
  white-space: nowrap;
}

.cv-entry-sub {
  font-size: 0.88rem;
  color: var(--global-link-color);
  font-weight: 600;
  margin-bottom: 8px;
}

.cv-entry-desc {
  font-size: 0.95rem;
  color: var(--global-text-color);
  line-height: 1.6;
}

.cv-entry-desc ul {
  margin: 6px 0 0 0;
  padding-left: 18px;
}

.cv-entry-desc ul li {
  margin-bottom: 4px;
}

.cv-pub-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.cv-pub-item {
  padding: 12px 0;
  border-bottom: 1px solid var(--global-border-color);
  font-size: 0.95rem;
  line-height: 1.5;
}

.cv-pub-item:last-child {
  border-bottom: none;
}

.cv-pub-venue {
  color: var(--global-link-color);
  font-weight: 500;
}

.cv-award-item {
  display: flex;
  align-items: center;
  gap: 12px;
  padding: 14px 20px;
  background: var(--global-bg-color);
  border: 1px solid var(--global-border-color);
  border-radius: 10px;
  margin-bottom: 12px;
  box-shadow: 0 1px 6px rgba(0,0,0,0.04);
}

.cv-award-icon {
  font-size: 1.5rem;
}

.cv-award-text {
  font-size: 0.95rem;
  color: var(--global-text-color);
}

.cv-award-text strong {
  color: var(--global-link-color);
}

.cv-skills-compact {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-bottom: 10px;
}

.cv-skill-tag {
  background: var(--global-border-color);
  color: var(--global-text-color);
  padding: 5px 12px;
  border-radius: 16px;
  font-size: 0.84rem;
  font-weight: 500;
  font-family: 'Inter', sans-serif;
}

@media (max-width: 768px) {
  .cv-entry-header { flex-direction: column; }
}
</style>

<a href="/files/Ravi_Prakash_Srivastava_CV.pdf" class="cv-download" target="_blank">
  <i class="fas fa-file-pdf"></i> Download Full CV (PDF)
</a>

<!-- Education -->
<div class="cv-section">
  <div class="cv-section-title"><i class="fas fa-graduation-cap"></i> Education</div>
  <div class="cv-entry">
    <div class="cv-entry-header">
      <span class="cv-entry-title">B.Tech in Information Technology</span>
      <span class="cv-entry-date">Aug 2018 – Jun 2022</span>
    </div>
    <div class="cv-entry-sub">North Eastern Hill University (NEHU), Shillong</div>
    <div class="cv-entry-desc">CGPA: 7.85/10</div>
  </div>
</div>

<!-- Experience -->
<div class="cv-section">
  <div class="cv-section-title"><i class="fas fa-briefcase"></i> Professional Experience</div>
  <div class="cv-entry">
    <div class="cv-entry-header">
      <span class="cv-entry-title">Software Engineer</span>
      <span class="cv-entry-date">Mar 2026 – Present</span>
    </div>
    <div class="cv-entry-sub">SS Software Solutions LLC, Hyderabad</div>
    <div class="cv-entry-desc">
      <ul>
        <li>Defined and enforced ML pipeline standards including versioning, logging, and monitoring.</li>
        <li>Currently learning and applying Threat Modeling to proactively identify design-level risks.</li>
        <li>Automated security testing under DevSecOps by integrating tools into CI/CD pipelines.</li>
      </ul>
    </div>
  </div>
  <div class="cv-entry">
    <div class="cv-entry-header">
      <span class="cv-entry-title">DevOps Engineer</span>
      <span class="cv-entry-date">Apr 2023 – Feb 2026</span>
    </div>
    <div class="cv-entry-sub">Pantech e-learning, Chennai</div>
    <div class="cv-entry-desc">
      <ul>
        <li>Designed and deployed ML-based intrusion and anomaly detection models on real-world datasets (10K+ samples).</li>
        <li>Assisted in identifying and documenting security misconfigurations across web applications and CI/CD pipelines.</li>
      </ul>
    </div>
  </div>
  <div class="cv-entry">
    <div class="cv-entry-header">
      <span class="cv-entry-title">Machine Learning Intern</span>
      <span class="cv-entry-date">Aug 2022 – Feb 2023</span>
    </div>
    <div class="cv-entry-sub">C-DAC (Govt. of India), Hyderabad</div>
    <div class="cv-entry-desc">
      <ul>
        <li>Performed data preprocessing and feature engineering on student activity logs.</li>
        <li>Benchmarked ML models including Decision Trees, Random Forests, and SVMs.</li>
      </ul>
    </div>
  </div>
</div>

<!-- Skills -->
<div class="cv-section">
  <div class="cv-section-title"><i class="fas fa-cogs"></i> Technical Skills</div>
  <div class="cv-entry">
    <div class="cv-entry-sub">AI & Machine Learning</div>
    <div class="cv-skills-compact">
      <span class="cv-skill-tag">Deep Learning</span>
      <span class="cv-skill-tag">Transformers</span>
      <span class="cv-skill-tag">Adversarial ML</span>
      <span class="cv-skill-tag">Prompt Injection</span>
      <span class="cv-skill-tag">Deepfake Detection</span>
      <span class="cv-skill-tag">Feature Engineering</span>
    </div>
    <div class="cv-entry-sub">Cybersecurity</div>
    <div class="cv-skills-compact">
      <span class="cv-skill-tag">Threat Modeling</span>
      <span class="cv-skill-tag">OWASP Top 10</span>
      <span class="cv-skill-tag">Vulnerability Assessment</span>
      <span class="cv-skill-tag">Burp Suite</span>
      <span class="cv-skill-tag">Nmap</span>
      <span class="cv-skill-tag">Wireshark</span>
    </div>
    <div class="cv-entry-sub">Programming & Tools</div>
    <div class="cv-skills-compact">
      <span class="cv-skill-tag">Python</span>
      <span class="cv-skill-tag">C++</span>
      <span class="cv-skill-tag">SQL</span>
      <span class="cv-skill-tag">Bash</span>
      <span class="cv-skill-tag">PyTorch</span>
      <span class="cv-skill-tag">Hugging Face</span>
      <span class="cv-skill-tag">Scikit-learn</span>
      <span class="cv-skill-tag">Git</span>
      <span class="cv-skill-tag">Linux</span>
      <span class="cv-skill-tag">LaTeX</span>
    </div>
  </div>
</div>

<!-- Publications -->
<div class="cv-section">
  <div class="cv-section-title"><i class="fas fa-file-alt"></i> Selected Publications</div>
  <ul class="cv-pub-list">
    <li class="cv-pub-item">
      <strong>Adversarial Prompt Injection Attacks on LLMs: Cryptographic Key Leakage and Defense Strategies</strong><br>
      <span class="cv-pub-venue">ICACA-2026 (Under Publication) — 🏆 Best Paper Award</span>
    </li>
    <li class="cv-pub-item">
      <strong>Deepfake Video Detection Using Face-Centric Processing and Frame Sampling</strong><br>
      <span class="cv-pub-venue">ICACA-2026 (Under Publication)</span>
    </li>
    <li class="cv-pub-item">
      <strong>IoT-HITS: IoT-based Human Intrusion Detection System for Border Regions Using Deep Learning</strong><br>
      <span class="cv-pub-venue">IETE Journal of Research (2025)</span>
    </li>
    <li class="cv-pub-item">
      <strong>Balanced Few-Shot Episodic Learning for Accurate Retinal Disease Diagnosis</strong><br>
      <span class="cv-pub-venue">arXiv Preprint (2025)</span>
    </li>
    <li class="cv-pub-item">
      <strong>Smart City Vehicle Accident Monitoring and Detection System Using MEMS, GSM, GPS Raspberry Pi 4</strong><br>
      <span class="cv-pub-venue">IETE Journal of Research (2022)</span>
    </li>
  </ul>
</div>

<!-- Awards -->
<div class="cv-section">
  <div class="cv-section-title"><i class="fas fa-trophy"></i> Awards & Achievements</div>
  <div class="cv-award-item">
    <span class="cv-award-icon">🏆</span>
    <span class="cv-award-text"><strong>Best Paper Award</strong> — International Conference on Advanced Computing and Applications (ICACA 2026)</span>
  </div>
  <div class="cv-award-item">
    <span class="cv-award-icon">🎓</span>
    <span class="cv-award-text"><strong>IETE Scholarship</strong> — Awarded by the Institution of Electronics and Telecommunication Engineers for academic excellence</span>
  </div>
</div>
