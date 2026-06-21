---
layout: single
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@400;600;700;800&family=Inter:wght@400;500;600&display=swap');

/* ===== Download Button ===== */
.cv-download {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  background: #3084de;
  color: #fff !important;
  padding: 13px 28px;
  border-radius: 8px;
  font-size: 0.95rem;
  font-weight: 700;
  font-family: 'Nunito', sans-serif;
  text-decoration: none !important;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  margin-bottom: 2.5rem;
  box-shadow: 0 4px 14px rgba(48,132,222,0.3);
}
.cv-download:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 24px rgba(48,132,222,0.4);
  color: #fff !important;
}

/* ===== Section Title ===== */
.cv-section { margin-bottom: 2.2rem; }

.cv-section-title {
  font-size: 1.1rem;
  font-weight: 800;
  color: var(--global-text-color);
  font-family: 'Nunito', sans-serif;
  display: flex;
  align-items: center;
  gap: 10px;
  margin-bottom: 1rem;
  padding-bottom: 7px;
  border-bottom: 2px solid #3084de;
}
.cv-section-title i { color: #3084de; font-size: 1rem; }

/* ===== Entry Card ===== */
.cv-entry {
  background: var(--global-bg-color);
  border: 1px solid var(--global-border-color);
  border-left: 4px solid #3084de;
  border-radius: 8px;
  padding: 18px 20px;
  margin-bottom: 14px;
  box-shadow: 0 1px 6px rgba(0,0,0,0.04);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}
.cv-entry:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 18px rgba(48,132,222,0.1);
}

/* ===== Entry Header ===== */
.cv-entry-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  flex-wrap: wrap;
  gap: 6px;
  margin-bottom: 2px;
}
.cv-entry-title {
  font-weight: 800;
  font-size: 1rem;
  color: var(--global-text-color);
  font-family: 'Nunito', sans-serif;
}
.cv-entry-date {
  font-size: 0.8rem;
  font-weight: 700;
  color: #3084de;
  background: rgba(48,132,222,0.1);
  padding: 3px 11px;
  border-radius: 20px;
  white-space: nowrap;
  border: 1px solid rgba(48,132,222,0.2);
}
.cv-entry-sub {
  font-size: 0.86rem;
  color: #3084de;
  font-weight: 700;
  margin-bottom: 10px;
  font-family: 'Nunito', sans-serif;
}
.cv-entry-meta {
  font-size: 0.82rem;
  color: var(--global-text-color-light);
  font-style: italic;
  margin-bottom: 4px;
  font-family: 'Nunito', sans-serif;
}

/* ===== Bullet List ===== */
.cv-entry-desc ul {
  margin: 4px 0 0 0;
  padding-left: 0;
  list-style: none;
}
.cv-entry-desc ul li {
  font-size: 0.92rem;
  line-height: 1.65;
  margin-bottom: 8px;
  color: var(--global-text-color);
  padding-left: 1.1em;
  position: relative;
  font-family: 'Nunito', sans-serif;
}
.cv-entry-desc ul li::before {
  content: '▸';
  position: absolute;
  left: 0;
  color: #3084de;
  font-size: 0.72rem;
  top: 4px;
}
.cv-entry-desc ul li:last-child { margin-bottom: 0; }

/* ===== Publications ===== */
.cv-pub-list { list-style: none; padding: 0; margin: 0; }
.cv-pub-item {
  padding: 12px 0;
  border-bottom: 1px solid var(--global-border-color);
  font-size: 0.93rem;
  line-height: 1.55;
  font-family: 'Nunito', sans-serif;
}
.cv-pub-item:last-child { border-bottom: none; }
.cv-pub-venue { color: #3084de; font-weight: 600; }
.cv-pub-badge {
  display: inline-block;
  background: #f59e0b;
  color: #fff;
  font-size: 0.74rem;
  font-weight: 700;
  padding: 2px 9px;
  border-radius: 12px;
  margin-left: 6px;
  vertical-align: middle;
  font-family: 'Nunito', sans-serif;
}

/* ===== Awards ===== */
.cv-award-item {
  display: flex;
  align-items: flex-start;
  gap: 14px;
  padding: 14px 18px;
  background: var(--global-bg-color);
  border: 1px solid var(--global-border-color);
  border-radius: 8px;
  margin-bottom: 10px;
  box-shadow: 0 1px 6px rgba(0,0,0,0.04);
}
.cv-award-icon { font-size: 1.4rem; margin-top: 1px; }
.cv-award-text { font-size: 0.93rem; color: var(--global-text-color); line-height: 1.55; font-family: 'Nunito', sans-serif; }
.cv-award-text strong { color: var(--global-text-color); }
.cv-award-year { font-size: 0.8rem; color: var(--global-text-color-light); font-style: italic; }

/* ===== Skills ===== */
.cv-skills-group { margin-bottom: 14px; }
.cv-skill-label {
  font-size: 0.78rem;
  font-weight: 800;
  color: #3084de;
  text-transform: uppercase;
  letter-spacing: 0.06em;
  margin-bottom: 7px;
  font-family: 'Nunito', sans-serif;
}
.cv-skills-compact { display: flex; flex-wrap: wrap; gap: 7px; }
.cv-skill-tag {
  background: rgba(48,132,222,0.08);
  color: var(--global-text-color);
  padding: 5px 12px;
  border-radius: 16px;
  font-size: 0.82rem;
  font-weight: 600;
  font-family: 'Nunito', sans-serif;
  border: 1px solid rgba(48,132,222,0.2);
  transition: background 0.2s ease, color 0.2s ease;
}
.cv-skill-tag:hover { background: #3084de; color: #fff; }

@media (max-width: 768px) {
  .cv-entry-header { flex-direction: column; }
}
</style>

<!-- Download Button -->
<a href="/files/Ravi_Prakash_Srivastava_CV.pdf" class="cv-download" target="_blank">
  <i class="fas fa-file-pdf"></i> Download Full CV (PDF)
</a>

<!-- ═══════════ EDUCATION ═══════════ -->
<div class="cv-section">
  <div class="cv-section-title"><i class="fas fa-graduation-cap"></i> Education</div>

  <div class="cv-entry">
    <div class="cv-entry-header">
      <span class="cv-entry-title">M.Tech — Data Science &amp; Artificial Intelligence</span>
      <span class="cv-entry-date">Aug 2024 – May 2026</span>
    </div>
    <div class="cv-entry-sub"><i class="fas fa-university fa-sm"></i>&nbsp; Indian Institute of Information Technology Ranchi (IIIT Ranchi)</div>
    <div class="cv-entry-meta">Institute of National Importance, Govt. of India</div>
    <div class="cv-entry-meta">CGPA: 8.79 / 10.00</div>
  </div>

  <div class="cv-entry">
    <div class="cv-entry-header">
      <span class="cv-entry-title">B.Tech — Information Technology</span>
      <span class="cv-entry-date">Aug 2018 – Jun 2022</span>
    </div>
    <div class="cv-entry-sub"><i class="fas fa-university fa-sm"></i>&nbsp; North Eastern Hill University (NEHU), Shillong</div>
    <div class="cv-entry-meta">Central University, Govt. of India</div>
    <div class="cv-entry-meta">CGPA: 7.85 / 10.00</div>
  </div>
</div>

<!-- ═══════════ EXPERIENCE ═══════════ -->
<div class="cv-section">
  <div class="cv-section-title"><i class="fas fa-briefcase"></i> Professional Experience</div>

  <div class="cv-entry">
    <div class="cv-entry-header">
      <span class="cv-entry-title">Software Engineer</span>
      <span class="cv-entry-date">Mar 2026 – Present</span>
    </div>
    <div class="cv-entry-sub"><i class="fas fa-building fa-sm"></i>&nbsp; SS Software Solutions LLC, Hyderabad, India</div>
    <div class="cv-entry-desc">
      <ul>
        <li><strong>ML Pipeline Governance.</strong> Standardised model versioning (MLflow / DVC), structured JSON logging with distributed trace IDs, and drift-detection alerting — reduced incident diagnosis time by ~40% across 3 production models.</li>
        <li><strong>AI Threat Modeling.</strong> Applied STRIDE to ML systems; identified 8 design-level risks (data poisoning, model inversion) — cut mean time-to-debug by ~35% and eliminated untracked deployments.</li>
        <li><strong>DevSecOps Automation.</strong> Integrated SAST tools (Bandit, Semgrep) and dependency-vulnerability scanning into GitHub Actions CI/CD — reduced manual security-review effort by ~60%.</li>
      </ul>
    </div>
  </div>

  <div class="cv-entry">
    <div class="cv-entry-header">
      <span class="cv-entry-title">Machine Learning Research Intern</span>
      <span class="cv-entry-date">Aug 2022 – Feb 2023</span>
    </div>
    <div class="cv-entry-sub"><i class="fas fa-landmark fa-sm"></i>&nbsp; C-DAC — Centre for Development of Advanced Computing, Govt. of India, Hyderabad</div>
    <div class="cv-entry-desc">
      <ul>
        <li><strong>Feature Engineering.</strong> Preprocessed 10,000+ student activity log records (attendance, assignments, quiz scores) and engineered predictive features for academic-performance modeling.</li>
        <li><strong>Model Benchmarking.</strong> Implemented and compared Decision Tree, Random Forest, and SVM classifiers; documented results in internal technical reports.</li>
      </ul>
    </div>
  </div>
</div>

<!-- ═══════════ PUBLICATIONS ═══════════ -->
<div class="cv-section">
  <div class="cv-section-title"><i class="fas fa-file-alt"></i> Publications</div>
  <ul class="cv-pub-list">
    <li class="cv-pub-item">
      <strong>Adversarial Prompt Injection Attacks on LLMs: Cryptographic Key Leakage and Defense Strategies</strong>
      <span class="cv-pub-badge">Best Paper Award</span><br>
      <span class="cv-pub-venue">ICACA-2026 (Under Publication)</span> &nbsp;·&nbsp;
      <a href="https://rtcit.ac.in/icaca-2026/" target="_blank">Conference Link</a>
    </li>
    <li class="cv-pub-item">
      <strong>IoT-HITS: IoT-based Human Intrusion Detection System for Border Regions Using Deep Learning</strong><br>
      <span class="cv-pub-venue">IETE Journal of Research, Taylor &amp; Francis (2025)</span> &nbsp;·&nbsp;
      <a href="https://doi.org/10.1080/03772063.2025.2521688" target="_blank">DOI</a>
    </li>
    <li class="cv-pub-item">
      <strong>Deepfake Video Detection Using Face-Centric Processing and Frame Sampling</strong><br>
      <span class="cv-pub-venue">ICACA-2026 (Under Publication)</span> &nbsp;·&nbsp;
      <a href="https://rtcit.ac.in/icaca-2026/" target="_blank">Conference Link</a>
    </li>
    <li class="cv-pub-item">
      <strong>Balanced Few-Shot Episodic Learning for Accurate Retinal Disease Diagnosis</strong><br>
      <span class="cv-pub-venue">arXiv Preprint (2024)</span> &nbsp;·&nbsp;
      <a href="https://arxiv.org/abs/2512.04967v1" target="_blank">arXiv:2512.04967</a>
    </li>
    <li class="cv-pub-item">
      <strong>Smart City Vehicle Accident Monitoring and Detection System Using MEMS, GSM, GPS &amp; Raspberry Pi 4</strong><br>
      <span class="cv-pub-venue">IETE Journal of Research, Taylor &amp; Francis (2022)</span> &nbsp;·&nbsp;
      <a href="https://doi.org/10.1080/03772063.2022.2043787" target="_blank">DOI</a>
    </li>
  </ul>
</div>

<!-- ═══════════ AWARDS ═══════════ -->
<div class="cv-section">
  <div class="cv-section-title"><i class="fas fa-trophy"></i> Awards &amp; Honours</div>

  <div class="cv-award-item">
    <span class="cv-award-icon">🏆</span>
    <div>
      <div class="cv-award-text"><strong>Best Paper Award</strong> — International Conference on Advanced Computing and Applications (ICACA-2026)</div>
      <div class="cv-award-year">For <em>Adversarial Prompt Injection Attacks on LLMs: Cryptographic Key Leakage and Defense Strategies</em></div>
    </div>
  </div>

  <div class="cv-award-item">
    <span class="cv-award-icon">🎓</span>
    <div>
      <div class="cv-award-text"><strong>IETE Scholarship</strong> — Institution of Electronics and Telecommunication Engineers (IETE), New Delhi, India</div>
      <div class="cv-award-year">2024 · Awarded for academic excellence during M.Tech studies in Data Science &amp; Artificial Intelligence</div>
    </div>
  </div>
</div>

<!-- ═══════════ SKILLS ═══════════ -->
<div class="cv-section">
  <div class="cv-section-title"><i class="fas fa-cogs"></i> Technical Skills</div>
  <div class="cv-entry">

    <div class="cv-skills-group">
      <div class="cv-skill-label"><i class="fas fa-shield-alt"></i>&nbsp; AI Security</div>
      <div class="cv-skills-compact">
        <span class="cv-skill-tag">Adversarial ML</span>
        <span class="cv-skill-tag">LLM Prompt Injection</span>
        <span class="cv-skill-tag">Deepfake Detection</span>
        <span class="cv-skill-tag">Threat Modeling (STRIDE)</span>
        <span class="cv-skill-tag">OWASP Top 10</span>
        <span class="cv-skill-tag">IDS / IPS</span>
        <span class="cv-skill-tag">Penetration Testing</span>
      </div>
    </div>

    <div class="cv-skills-group">
      <div class="cv-skill-label"><i class="fas fa-project-diagram"></i>&nbsp; MLOps &amp; DevSecOps</div>
      <div class="cv-skills-compact">
        <span class="cv-skill-tag">MLflow</span>
        <span class="cv-skill-tag">DVC</span>
        <span class="cv-skill-tag">Docker</span>
        <span class="cv-skill-tag">GitHub Actions (CI/CD)</span>
        <span class="cv-skill-tag">Semgrep</span>
        <span class="cv-skill-tag">Bandit</span>
        <span class="cv-skill-tag">Observability</span>
      </div>
    </div>

    <div class="cv-skills-group">
      <div class="cv-skill-label"><i class="fas fa-brain"></i>&nbsp; ML &amp; Deep Learning</div>
      <div class="cv-skills-compact">
        <span class="cv-skill-tag">PyTorch</span>
        <span class="cv-skill-tag">Hugging Face Transformers</span>
        <span class="cv-skill-tag">Scikit-learn</span>
        <span class="cv-skill-tag">Few-Shot Learning</span>
        <span class="cv-skill-tag">Deep Learning</span>
        <span class="cv-skill-tag">Feature Engineering</span>
      </div>
    </div>

    <div class="cv-skills-group">
      <div class="cv-skill-label"><i class="fas fa-code"></i>&nbsp; Programming &amp; Tools</div>
      <div class="cv-skills-compact">
        <span class="cv-skill-tag">Python</span>
        <span class="cv-skill-tag">C++</span>
        <span class="cv-skill-tag">Bash</span>
        <span class="cv-skill-tag">SQL</span>
        <span class="cv-skill-tag">Linux</span>
        <span class="cv-skill-tag">Git</span>
        <span class="cv-skill-tag">LaTeX</span>
        <span class="cv-skill-tag">Jupyter</span>
      </div>
    </div>

  </div>
</div>
