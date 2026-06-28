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
      My research journey marks a deliberate transition from <strong>IoT security</strong> (focusing on anomaly detection and hardware-level monitoring) to <strong>NLP and LLM safety, privacy, and robustness</strong>. My current work sits at the intersection of <strong>adversarial machine learning</strong>, <strong>LLM security</strong>, and <strong>secure MLOps pipelines</strong> — combining theoretical foundations with practical system-level implementation to build robust defenses against prompt injection, model inversion, and data leakage.
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
  <div class="interest-tags">
    <span class="interest-tag">LLM Security</span>
    <span class="interest-tag">Adversarial Machine Learning</span>
    <span class="interest-tag">Deepfake Detection</span>
    <span class="interest-tag">Robust NLP</span>
    <span class="interest-tag">IoT Security</span>
    <span class="interest-tag">Multilingual AI</span>
    <span class="interest-tag">Prompt Injection Defense</span>
    <span class="interest-tag">MLOps Security</span>
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
