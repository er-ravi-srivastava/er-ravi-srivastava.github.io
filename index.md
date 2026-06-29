---
layout: archive
title: "About Me"
permalink: /
author_profile: true
---

<style>
/* ===== Google Fonts ===== */
@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@300;400;500;600;700;800&family=Inter:wght@300;400;500;600;700&display=swap');

/* ===== Base Font Override ===== */
body, p, li, span, div {
  font-family: 'Nunito', 'Inter', sans-serif;
}

/* ===== Page Content Wrapper ===== */
.home-content {
  font-family: 'Nunito', 'Inter', sans-serif;
  font-size: 1rem;
  line-height: 1.78;
  color: var(--global-text-color);
}

/* ===== About Me Section ===== */
.about-section {
  margin-bottom: 2.2rem;
}

.about-section p {
  font-size: 0.97rem;
  line-height: 1.8;
  margin-bottom: 1rem;
  color: var(--global-text-color);
  font-family: 'Nunito', sans-serif;
}

.about-section a {
  color: #3084de;
  font-weight: 600;
  text-decoration: none;
}

.about-section a:hover {
  text-decoration: underline;
}

/* ===== Section Heading ===== */
.section-heading {
  font-size: 1.3rem;
  font-weight: 700;
  font-family: 'Nunito', sans-serif;
  color: var(--global-text-color);
  margin-top: 2rem;
  margin-bottom: 1rem;
  padding-bottom: 6px;
  border-bottom: 2px solid #3084de;
  display: inline-block;
}

/* ===== Interest Tags ===== */
.interest-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-bottom: 2.2rem;
  margin-top: 0.8rem;
}

.interest-tag {
  background: #3084de;
  color: #fff;
  padding: 6px 16px;
  border-radius: 20px;
  font-size: 0.83rem;
  font-weight: 600;
  font-family: 'Nunito', sans-serif;
  transition: transform 0.2s ease, background 0.2s ease;
  text-decoration: none;
  display: inline-block;
}

.interest-tag:hover {
  transform: scale(1.05);
  background: #2066b8;
  color: #fff;
  text-decoration: none;
}

/* ===== News Section ===== */
.news-list {
  list-style: none;
  padding: 0;
  margin: 0.8rem 0 2.2rem 0;
}

.news-item {
  display: flex;
  align-items: flex-start;
  gap: 18px;
  padding: 11px 0;
  border-bottom: 1px solid var(--global-border-color);
  font-family: 'Nunito', sans-serif;
}

.news-item:last-child {
  border-bottom: none;
}

.news-date {
  flex: 0 0 88px;
  font-size: 0.83rem;
  font-weight: 700;
  color: #3084de;
  font-family: 'Nunito', sans-serif;
  padding-top: 2px;
}

.news-text {
  font-size: 0.95rem;
  line-height: 1.65;
  color: var(--global-text-color);
}

.news-text a {
  color: #3084de;
  font-weight: 600;
  text-decoration: none;
}

.news-text a:hover {
  text-decoration: underline;
}

/* ===== Open to Opportunities Callout ===== */
.callout-box {
  background: #fff7ed;
  border-left: 4px solid #f59e0b;
  border-radius: 6px;
  padding: 14px 18px;
  margin-bottom: 2rem;
  font-family: 'Nunito', sans-serif;
  font-size: 0.93rem;
  line-height: 1.65;
  color: #78350f;
}

html[data-theme="dark"] .callout-box {
  background: #2a2010;
  color: #fcd34d;
  border-left-color: #f59e0b;
}

.callout-box a {
  color: #b45309;
  font-weight: 700;
  text-decoration: none;
}

.callout-box a:hover {
  text-decoration: underline;
}

/* ===== Responsive ===== */
@media (max-width: 768px) {
  .news-item {
    flex-direction: column;
    gap: 2px;
  }
  .news-date {
    flex: none;
  }
  .section-heading {
    font-size: 1.1rem;
  }
}

/* ===== Niche Focus Themes ===== */
.niche-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  margin-top: 1rem;
  margin-bottom: 2.2rem;
}

.niche-card {
  background: var(--global-card-bg, #fcfcfc);
  border: 1px solid var(--global-border-color, #e5e7eb);
  border-radius: 8px;
  padding: 18px;
  transition: transform 0.25s ease, box-shadow 0.25s ease, border-color 0.25s ease;
  font-family: 'Nunito', sans-serif;
}

.niche-card:hover {
  transform: translateY(-3px);
  border-color: #3084de;
  box-shadow: 0 4px 20px rgba(48, 132, 222, 0.15);
}

.niche-card-title {
  font-size: 1.02rem;
  font-weight: 700;
  color: #3084de;
  margin-bottom: 12px;
  display: flex;
  align-items: center;
  gap: 8px;
  line-height: 1.3;
}

.niche-list {
  list-style: none;
  padding-left: 0;
  margin: 0;
}

.niche-list li {
  position: relative;
  padding-left: 15px;
  margin-bottom: 8px;
  font-size: 0.9rem;
  color: var(--global-text-color);
  line-height: 1.4;
}

.niche-list li::before {
  content: "•";
  color: #3084de;
  font-weight: bold;
  position: absolute;
  left: 0;
  top: 0;
}

html[data-theme="dark"] .niche-card {
  background: #1e293b;
  border-color: #334155;
}

@media (max-width: 900px) {
  .niche-grid {
    grid-template-columns: 1fr 1fr;
  }
}

@media (max-width: 600px) {
  .niche-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="home-content">

  <!-- About Me -->
  <div class="about-section">
    <p>
      I am a <strong>Software Engineer</strong> with a focused research interest in
      <strong>Cybersecurity</strong>, <strong>MLOps</strong>, and <strong>AI Security</strong>.
      I hold a Masters in Data Science and AI from <a href="https://iiitranchi.ac.in/" target="_blank">IIIT Ranchi</a> and a B.Tech in Information Technology from
      <a href="https://nehu.ac.in/" target="_blank">NEHU</a> and have published work in the
      <a href="https://www.tandfonline.com/journals/tijr20" target="_blank">IETE Journal of Research</a>
      (Taylor &amp; Francis) and on <a href="https://arxiv.org/abs/2512.04967v1" target="_blank">arXiv</a>.
      Two of my papers are under publication at the
      <strong>International Conference on Advanced Computing and Applications (ICACA-2026)</strong>.
    </p>

    <p>
      My research focuses on the design of <strong>intelligent, trustworthy, and scalable computational systems</strong>, spanning <strong>artificial intelligence</strong>, <strong>computer vision</strong>, <strong>language models</strong>, <strong>quantum computing</strong>, and <strong>hardware–software co-design</strong>. A central theme of my work is the integration of algorithmic intelligence with efficient and secure system architectures, ensuring that advanced AI techniques are both practically deployable and responsibly engineered.
    </p>

    <p>
      Currently, I work as a <strong>Software Engineer at SS Software Solutions LLC</strong>, where I apply
      security-first engineering principles to real-world software systems. I am actively seeking opportunities
      to contribute to research and engineering teams working at the frontier of AI safety, alignment, and security.
    </p>
  </div>

  <!-- Open to Opportunities Callout -->
  <div class="callout-box">
    I am <strong>open to research collaborations and engineering opportunities</strong> in AI Security, LLM Robustness,
    and Cybersecurity. Feel free to reach out via
    <a href="mailto:raviprakashshrivastav7@gmail.com">email</a> or view my
    <a href="/cv/">CV</a>.
  </div>

  <!-- Research Interests -->
  <div class="section-heading">Research Interests</div>
  <div class="niche-grid">
    <div class="niche-card">
      <div class="niche-card-title">🛡️ Trustworthy AI &amp; LLM Security</div>
      <ul class="niche-list">
        <li>Prompt Injection</li>
        <li>AI Agents</li>
        <li>Red Teaming</li>
        <li>Secure Code Generation</li>
      </ul>
    </div>
    
    <div class="niche-card">
      <div class="niche-card-title">🧬 Biomedical AI</div>
      <ul class="niche-list">
        <li>Clinical NLP</li>
        <li>Medical Foundation Models</li>
        <li>Drug Discovery</li>
      </ul>
    </div>

    <div class="niche-card">
      <div class="niche-card-title">🔒 Privacy-Preserving &amp; Robust ML</div>
      <ul class="niche-list">
        <li>Federated Learning</li>
        <li>Differential Privacy</li>
        <li>Adversarial ML</li>
      </ul>
    </div>
  </div>

  <!-- News -->
  <div class="section-heading">News</div>
  <ul class="news-list">
    <li class="news-item">
      <span class="news-date">Mar 2026</span>
      <span class="news-text">Started a new position as a <strong>Software Engineer</strong> at SS Software Solutions LLC.</span>
    </li>
    <li class="news-item">
      <span class="news-date">Jan 2026</span>
      <span class="news-text">🏆 <strong>Best Paper Award</strong> at ICACA 2026 for <em>Adversarial Prompt Injection Attacks on Large Language Models: Cryptographic Key Leakage and Defense Strategies</em>.</span>
    </li>
    <li class="news-item">
      <span class="news-date">July 2025</span>
      <span class="news-text"><em>IoT-HITS: IoT Hybrid Intrusion Detection System</em> published in the <strong>IETE Journal of Research</strong> (Taylor &amp; Francis).</span>
    </li>
    <li class="news-item">
      <span class="news-date">Dec 2024</span>
      <span class="news-text"><em>Balanced Few-Shot Episodic Learning for Accurate Retinal Disease Diagnosis</em> preprint released on <a href="https://arxiv.org/abs/2512.04967v1" target="_blank">arXiv</a>.</span>
    </li>
    <li class="news-item">
      <span class="news-date">Sept 2024</span>
      <span class="news-text">🎓 Received the <strong>IETE Scholarship</strong> from the <strong>Institution of Electronics and Telecommunication Engineers (IETE), New Delhi, India</strong> for academic excellence during M.Tech studies in Computer Science and Engineering.</span>
    </li>
  </ul>

</div>
