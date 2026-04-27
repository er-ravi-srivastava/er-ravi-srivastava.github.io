---
layout: archive
title: "About Me"
permalink: /
author_profile: true
---

<style>
/* ===== Homepage Styles ===== */
.home-intro {
  font-size: 1.05rem;
  line-height: 1.8;
  color: var(--global-text-color);
  margin-bottom: 2rem;
  font-family: 'Inter', sans-serif;
}

.highlight-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  margin-bottom: 2.5rem;
}

.highlight-card {
  background: var(--global-bg-color);
  border: 1px solid var(--global-border-color);
  border-radius: 12px;
  padding: 24px 20px;
  text-align: center;
  box-shadow: 0 2px 10px rgba(0,0,0,0.06);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.highlight-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 8px 24px rgba(0,0,0,0.12);
}

.highlight-icon {
  font-size: 2rem;
  margin-bottom: 10px;
  display: block;
}

.highlight-number {
  font-size: 1.6rem;
  font-weight: 800;
  color: var(--global-link-color);
  font-family: 'Inter', sans-serif;
  display: block;
  margin-bottom: 4px;
}

.highlight-label {
  font-size: 0.85rem;
  color: var(--global-text-color-light);
  text-transform: uppercase;
  letter-spacing: 0.05em;
  font-weight: 600;
}

.section-title {
  font-size: 1.3rem;
  font-weight: 700;
  color: var(--global-text-color);
  margin-bottom: 1rem;
  font-family: 'Inter', sans-serif;
  border-bottom: 2px solid var(--global-link-color);
  padding-bottom: 8px;
  display: inline-block;
}

.interest-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-bottom: 2.5rem;
}

.interest-tag {
  background: var(--global-link-color);
  color: #fff;
  padding: 8px 18px;
  border-radius: 25px;
  font-size: 0.88rem;
  font-weight: 600;
  font-family: 'Inter', sans-serif;
  transition: transform 0.2s ease, opacity 0.2s ease;
}

.interest-tag:hover {
  transform: scale(1.05);
  opacity: 0.9;
}

.news-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.news-item {
  display: flex;
  align-items: flex-start;
  gap: 16px;
  padding: 14px 0;
  border-bottom: 1px solid var(--global-border-color);
}

.news-item:last-child {
  border-bottom: none;
}

.news-date {
  flex: 0 0 100px;
  font-size: 0.85rem;
  font-weight: 700;
  color: var(--global-link-color);
  font-family: 'Inter', sans-serif;
}

.news-text {
  font-size: 0.95rem;
  line-height: 1.5;
  color: var(--global-text-color);
}

@media (max-width: 768px) {
  .highlight-grid {
    grid-template-columns: 1fr;
    gap: 15px;
  }
  .news-item {
    flex-direction: column;
    gap: 4px;
  }
  .news-date {
    flex: none;
  }
}
</style>

<div class="home-intro">
  I am a Software Engineer and AI Researcher with a strong focus on <strong>LLM Security</strong>, <strong>Deepfake Detection</strong>, and <strong>Robust NLP</strong>. I hold an M.Tech in Data Science & AI from <a href="https://www.iiitranchi.ac.in/">IIIT Ranchi</a>, and my research has been published in the <a href="https://www.tandfonline.com/journals/tijr20">IETE Journal of Research</a> (Taylor & Francis) and on <a href="https://arxiv.org/abs/2512.04967v1">arXiv</a>. Two papers are currently under publication in Springer's <a href="https://www.springer.com/series/15179">Lecture Notes in Networks and Systems</a>.
</div>

<!-- Highlight Cards -->
<div class="highlight-grid">
  <div class="highlight-card">
    <span class="highlight-icon">🏆</span>
    <span class="highlight-number">Best Paper</span>
    <span class="highlight-label">Award — ICACA 2026</span>
  </div>
  <div class="highlight-card">
    <span class="highlight-icon">📄</span>
    <span class="highlight-number">5</span>
    <span class="highlight-label">Research Papers</span>
  </div>
  <div class="highlight-card">
    <span class="highlight-icon">🎓</span>
    <span class="highlight-number">M.Tech</span>
    <span class="highlight-label">DS & AI — IIIT Ranchi</span>
  </div>
</div>

<!-- Research Interests -->
<div class="section-title">Research Interests</div>
<div class="interest-tags">
  <span class="interest-tag">LLM Security</span>
  <span class="interest-tag">Adversarial Machine Learning</span>
  <span class="interest-tag">Deepfake Detection</span>
  <span class="interest-tag">Robust NLP</span>
  <span class="interest-tag">IoT Security</span>
  <span class="interest-tag">DevSecOps</span>
  <span class="interest-tag">Multilingual AI</span>
</div>

<!-- News -->
<div class="section-title">News & Updates</div>
<ul class="news-list">
  <li class="news-item">
    <span class="news-date">Mar 2026</span>
    <span class="news-text">Joined <strong>SS Software Solutions LLC</strong> as a Software Engineer, working on ML pipelines and DevSecOps.</span>
  </li>
  <li class="news-item">
    <span class="news-date">Jan 2026</span>
    <span class="news-text">🏆 Received the <strong>Best Paper Award</strong> at ICACA 2026 for research on adversarial prompt injection attacks on LLMs.</span>
  </li>
  <li class="news-item">
    <span class="news-date">2025</span>
    <span class="news-text"><em>IoT-HITS</em> published in <strong>IETE Journal of Research</strong> (Taylor & Francis).</span>
  </li>
  <li class="news-item">
    <span class="news-date">2025</span>
    <span class="news-text"><em>Balanced Few-Shot Episodic Learning</em> preprint released on <strong>arXiv</strong>.</span>
  </li>
  <li class="news-item">
    <span class="news-date">Aug 2024</span>
    <span class="news-text">Started <strong>M.Tech in Data Science & AI</strong> at IIIT Ranchi with IETE Scholarship.</span>
  </li>
</ul>
