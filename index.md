---
layout: archive
title: "About Me"
permalink: /
author_profile: true
---

<style>
/* ===== Hero Banner ===== */
.hero-banner {
  background: linear-gradient(135deg, #0d9488 0%, #0891b2 50%, #6366f1 100%);
  color: #fff;
  border-radius: 14px;
  padding: 32px 36px;
  margin-bottom: 2.5rem;
  text-align: center;
  box-shadow: 0 6px 24px rgba(13, 148, 136, 0.25);
  position: relative;
  overflow: hidden;
}

.hero-banner::before {
  content: '';
  position: absolute;
  top: -50%;
  left: -50%;
  width: 200%;
  height: 200%;
  background: radial-gradient(circle, rgba(255,255,255,0.06) 0%, transparent 70%);
  animation: shimmer 8s linear infinite;
}

@keyframes shimmer {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}

.hero-text {
  font-size: 1.2rem;
  font-weight: 700;
  font-family: 'Inter', sans-serif;
  letter-spacing: 0.01em;
  position: relative;
  z-index: 1;
  line-height: 1.5;
}

.hero-sub {
  font-size: 0.9rem;
  font-weight: 400;
  opacity: 0.9;
  margin-top: 8px;
  position: relative;
  z-index: 1;
}

/* ===== Homepage Content ===== */
.home-intro {
  font-size: 0.95rem;
  line-height: 1.7;
  color: var(--global-text-color);
  margin-bottom: 2.5rem;
  font-family: 'Inter', sans-serif;
}

.section-title {
  font-size: 1.25rem;
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
  padding: 7px 16px;
  border-radius: 20px;
  font-size: 0.84rem;
  font-weight: 600;
  font-family: 'Inter', sans-serif;
  transition: transform 0.2s ease, opacity 0.2s ease;
  text-decoration: none;
}

.interest-tag:hover {
  transform: scale(1.05);
  opacity: 0.88;
  color: #fff;
  text-decoration: none;
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
  padding: 12px 0;
  border-bottom: 1px solid var(--global-border-color);
}

.news-item:last-child {
  border-bottom: none;
}

.news-date {
  flex: 0 0 90px;
  font-size: 0.84rem;
  font-weight: 700;
  color: var(--global-link-color);
  font-family: 'Inter', sans-serif;
}

.news-text {
  font-size: 0.95rem;
  line-height: 1.6;
  color: var(--global-text-color);
}

@media (max-width: 768px) {
  .hero-banner { padding: 24px 20px; }
  .hero-text { font-size: 1.1rem; }
  .news-item { flex-direction: column; gap: 4px; }
  .news-date { flex: none; }
}
</style>

<!-- Hero Banner -->
<div class="hero-banner">
  <div class="hero-text">🎯 Actively seeking PhD opportunities in Computer Science</div>
  <div class="hero-sub">Research interests: LLM Security · Adversarial ML · Deepfake Detection · Robust NLP</div>
</div>

<!-- Bio -->
<div class="home-intro">
  I am an AI Researcher with a strong focus on <strong>LLM Security</strong>, <strong>Deepfake Detection</strong>, and <strong>Robust NLP</strong>. I hold an M.Tech in Data Science & AI from <a href="https://www.iiitranchi.ac.in/">IIIT Ranchi</a> and have published in the <a href="https://www.tandfonline.com/journals/tijr20">IETE Journal of Research</a> (Taylor & Francis) and on <a href="https://arxiv.org/abs/2512.04967v1">arXiv</a>. Two papers are under publication in Springer's <a href="https://www.springer.com/series/15179">Lecture Notes in Networks and Systems</a>.
</div>

<!-- Research Interests -->
<div class="section-title">Research Interests</div>
<div class="interest-tags">
  <span class="interest-tag">LLM Security</span>
  <span class="interest-tag">Adversarial Machine Learning</span>
  <span class="interest-tag">Deepfake Detection</span>
  <span class="interest-tag">Robust NLP</span>
  <span class="interest-tag">IoT Security</span>
  <span class="interest-tag">Multilingual AI</span>
</div>

<!-- News -->
<div class="section-title">News</div>
<ul class="news-list">
  <li class="news-item">
    <span class="news-date">Jan 2026</span>
    <span class="news-text">🏆 <strong>Best Paper Award</strong> at ICACA 2026 for <em>Adversarial Prompt Injection Attacks on LLMs</em>.</span>
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
