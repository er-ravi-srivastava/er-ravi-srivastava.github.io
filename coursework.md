---
layout: archive
title: "Key Coursework"
permalink: /coursework/
author_profile: true
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@300;400;600;700;800;900&family=Inter:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;500&display=swap');

/* ═══════ Keyframes ═══════ */
@keyframes gradientShift {
  0%   { background-position: 0% 50%; }
  50%  { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}
@keyframes fadeInUp {
  from { opacity: 0; transform: translateY(20px); }
  to   { opacity: 1; transform: translateY(0); }
}
@keyframes shimmer {
  0%   { background-position: -200% 0; }
  100% { background-position: 200% 0; }
}
@keyframes floatOrb {
  0%, 100% { transform: translate(0, 0) scale(1); }
  33%  { transform: translate(12px, -18px) scale(1.05); }
  66%  { transform: translate(-8px, 10px) scale(0.97); }
}

/* ═══════ Hero ═══════ */
.cw-hero {
  background: linear-gradient(135deg, #0c1222 0%, #162037 35%, #1a1040 65%, #0c1222 100%);
  background-size: 300% 300%;
  animation: gradientShift 12s ease infinite;
  border-radius: 20px;
  padding: 42px 38px 38px;
  margin-bottom: 2.8rem;
  position: relative;
  overflow: hidden;
  border: 1px solid rgba(255,255,255,0.05);
}

/* Floating orbs */
.cw-hero::before {
  content: '';
  position: absolute;
  top: -40%;
  right: -15%;
  width: 380px;
  height: 380px;
  background: radial-gradient(circle, rgba(48,132,222,0.14) 0%, transparent 65%);
  border-radius: 50%;
  pointer-events: none;
  animation: floatOrb 10s ease-in-out infinite;
}
.cw-hero::after {
  content: '';
  position: absolute;
  bottom: -35%;
  left: -12%;
  width: 320px;
  height: 320px;
  background: radial-gradient(circle, rgba(124,58,237,0.10) 0%, transparent 65%);
  border-radius: 50%;
  pointer-events: none;
  animation: floatOrb 14s ease-in-out infinite reverse;
}

.cw-hero-label {
  font-family: 'JetBrains Mono', monospace;
  font-size: 0.68rem;
  font-weight: 500;
  color: #60a5fa;
  text-transform: uppercase;
  letter-spacing: 0.22em;
  margin-bottom: 14px;
  position: relative;
  z-index: 1;
  display: inline-flex;
  align-items: center;
  gap: 8px;
}
.cw-hero-label::before {
  content: '';
  width: 18px;
  height: 2px;
  background: #60a5fa;
  border-radius: 2px;
}

.cw-hero-title {
  font-family: 'Nunito', sans-serif;
  font-size: 1.65rem;
  font-weight: 900;
  color: #f1f5f9;
  line-height: 1.3;
  margin-bottom: 16px;
  position: relative;
  z-index: 1;
  background: linear-gradient(90deg, #f1f5f9, #93c5fd, #f1f5f9);
  background-size: 200% auto;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  animation: shimmer 6s linear infinite;
}

.cw-hero-desc {
  font-family: 'Nunito', sans-serif;
  font-size: 0.91rem;
  color: #94a3b8;
  line-height: 1.8;
  max-width: 600px;
  position: relative;
  z-index: 1;
}
.cw-hero-desc strong { color: #cbd5e1; }
.cw-hero-desc a { color: #60a5fa; font-weight: 600; text-decoration: none; transition: color 0.2s; }
.cw-hero-desc a:hover { color: #93bbfc; text-decoration: underline; }

/* ═══════ Stats Row ═══════ */
.cw-stats {
  display: flex;
  gap: 0;
  margin-top: 24px;
  position: relative;
  z-index: 1;
}
.cw-stat {
  padding: 0 22px;
  border-left: 1px solid rgba(255,255,255,0.08);
  text-align: center;
}
.cw-stat:first-child { border-left: none; padding-left: 0; }
.cw-stat-num {
  font-family: 'JetBrains Mono', monospace;
  font-size: 1.35rem;
  font-weight: 500;
  color: #e2e8f0;
  line-height: 1;
}
.cw-stat-label {
  font-family: 'Nunito', sans-serif;
  font-size: 0.68rem;
  font-weight: 600;
  color: #64748b;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  margin-top: 5px;
}

/* ═══════ Degree Section ═══════ */
.degree-section {
  margin-bottom: 3rem;
  animation: fadeInUp 0.5s ease both;
}
.degree-section:nth-child(2) { animation-delay: 0.1s; }

/* ═══════ Degree Banner ═══════ */
.degree-banner {
  display: flex;
  align-items: stretch;
  border-radius: 14px;
  overflow: hidden;
  margin-bottom: 1.4rem;
  border: 1px solid var(--global-border-color);
  box-shadow: 0 2px 16px rgba(0,0,0,0.05);
  transition: all 0.3s cubic-bezier(0.25,0.46,0.45,0.94);
}
.degree-banner:hover {
  box-shadow: 0 8px 32px rgba(48,132,222,0.10);
  transform: translateY(-2px);
}
.degree-accent {
  width: 5px;
  flex-shrink: 0;
}
.degree-accent.mtech { background: linear-gradient(180deg, #3084de, #7c3aed); }
.degree-accent.btech { background: linear-gradient(180deg, #059669, #0891b2); }

.degree-body {
  flex: 1;
  padding: 20px 26px;
  background: var(--global-bg-color);
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  gap: 12px;
}
.degree-left { flex: 1; min-width: 220px; }

.degree-program {
  font-family: 'Nunito', sans-serif;
  font-weight: 900;
  font-size: 1.12rem;
  color: var(--global-text-color);
  margin-bottom: 3px;
}
.degree-institution {
  font-family: 'Nunito', sans-serif;
  font-size: 0.82rem;
  color: var(--global-text-color-light);
  display: flex;
  align-items: center;
  gap: 6px;
}
.degree-right {
  display: flex;
  gap: 8px;
  flex-wrap: wrap;
  align-items: center;
}
.degree-chip {
  font-family: 'JetBrains Mono', monospace;
  font-size: 0.67rem;
  font-weight: 500;
  padding: 4px 12px;
  border-radius: 6px;
  white-space: nowrap;
  letter-spacing: 0.02em;
}
.degree-chip.year {
  background: rgba(48,132,222,0.1);
  color: #3084de;
  border: 1px solid rgba(48,132,222,0.2);
}
.degree-chip.tag {
  background: rgba(124,58,237,0.08);
  color: #7c3aed;
  border: 1px solid rgba(124,58,237,0.15);
}
.degree-chip.tag-green {
  background: rgba(5,150,105,0.08);
  color: #059669;
  border: 1px solid rgba(5,150,105,0.15);
}

/* ═══════ Thesis Card ═══════ */
.thesis-card {
  background: var(--global-bg-color);
  border: 1px solid var(--global-border-color);
  border-radius: 14px;
  padding: 22px 26px;
  margin-bottom: 1.4rem;
  display: flex;
  align-items: flex-start;
  gap: 18px;
  transition: all 0.3s cubic-bezier(0.25,0.46,0.45,0.94);
  text-decoration: none !important;
  position: relative;
  overflow: hidden;
}
.thesis-card::before {
  content: '';
  position: absolute;
  top: 0; left: 0; right: 0;
  height: 3px;
}
.thesis-card.mtech::before {
  background: linear-gradient(90deg, #3084de, #7c3aed, #a855f7, #3084de);
  background-size: 300% 100%;
  animation: gradientShift 5s ease infinite;
}
.thesis-card.btech::before {
  background: linear-gradient(90deg, #059669, #0891b2, #06b6d4, #059669);
  background-size: 300% 100%;
  animation: gradientShift 5s ease infinite;
}
.thesis-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 12px 36px rgba(48,132,222,0.10);
}

.thesis-icon {
  width: 44px;
  height: 44px;
  border-radius: 12px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.25rem;
  flex-shrink: 0;
  margin-top: 2px;
}
.thesis-card.mtech .thesis-icon {
  background: linear-gradient(135deg, rgba(48,132,222,0.12), rgba(124,58,237,0.12));
  border: 1px solid rgba(48,132,222,0.1);
}
.thesis-card.btech .thesis-icon {
  background: linear-gradient(135deg, rgba(5,150,105,0.12), rgba(8,145,178,0.12));
  border: 1px solid rgba(5,150,105,0.1);
}

.thesis-content { flex: 1; }

.thesis-label {
  font-family: 'JetBrains Mono', monospace;
  font-size: 0.64rem;
  font-weight: 500;
  text-transform: uppercase;
  letter-spacing: 0.16em;
  margin-bottom: 6px;
  display: inline-flex;
  align-items: center;
  gap: 8px;
}
.thesis-card.mtech .thesis-label { color: #7c3aed; }
.thesis-card.btech .thesis-label { color: #059669; }

.thesis-pub-badge {
  font-family: 'Nunito', sans-serif;
  font-size: 0.6rem;
  font-weight: 800;
  padding: 2px 8px;
  border-radius: 4px;
  text-transform: uppercase;
  letter-spacing: 0.06em;
  background: rgba(16,185,129,0.12);
  color: #059669;
  border: 1px solid rgba(16,185,129,0.2);
}

.thesis-title {
  font-family: 'Nunito', sans-serif;
  font-weight: 700;
  font-size: 0.94rem;
  color: var(--global-text-color);
  line-height: 1.55;
  margin-bottom: 8px;
}

.thesis-venue {
  font-family: 'Nunito', sans-serif;
  font-size: 0.79rem;
  color: var(--global-text-color-light);
  line-height: 1.55;
}
.thesis-venue strong { color: var(--global-text-color); }

.thesis-actions {
  display: flex;
  gap: 8px;
  margin-top: 12px;
  flex-wrap: wrap;
}

.thesis-btn {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  font-family: 'Nunito', sans-serif;
  font-size: 0.74rem;
  font-weight: 700;
  padding: 6px 14px;
  border-radius: 8px;
  text-decoration: none;
  transition: all 0.25s ease;
}
.thesis-btn.primary {
  background: linear-gradient(135deg, #3084de, #2563eb);
  color: #fff;
  border: none;
  box-shadow: 0 2px 10px rgba(48,132,222,0.3);
}
.thesis-btn.primary:hover {
  box-shadow: 0 4px 18px rgba(48,132,222,0.45);
  transform: translateY(-1px);
  color: #fff;
  text-decoration: none;
}
.thesis-btn.outline {
  background: transparent;
  color: #3084de;
  border: 1px solid rgba(48,132,222,0.25);
}
.thesis-btn.outline:hover {
  background: rgba(48,132,222,0.08);
  border-color: #3084de;
  text-decoration: none;
}

/* ═══════ Domain Grid ═══════ */
.domain-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 14px;
  margin-bottom: 0.5rem;
}

/* ═══════ Domain Card ═══════ */
.domain-card {
  background: var(--global-bg-color);
  border: 1px solid var(--global-border-color);
  border-radius: 14px;
  padding: 22px 24px;
  position: relative;
  overflow: hidden;
  transition: all 0.3s cubic-bezier(0.25,0.46,0.45,0.94);
  box-shadow: 0 1px 4px rgba(0,0,0,0.03);
}
.domain-card::before {
  content: '';
  position: absolute;
  top: 0; left: 0;
  width: 100%; height: 100%;
  opacity: 0;
  transition: opacity 0.35s ease;
  pointer-events: none;
  border-radius: 14px;
}
.domain-card::after {
  content: '';
  position: absolute;
  top: 0; left: 0;
  width: 100%; height: 3px;
  opacity: 0;
  transition: opacity 0.3s ease;
}
.domain-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 16px 48px rgba(0,0,0,0.08);
  border-color: transparent;
}
.domain-card:hover::before { opacity: 1; }
.domain-card:hover::after { opacity: 1; }

/* Subtle BG gradient on hover */
.domain-card.ai::before { background: linear-gradient(135deg, rgba(124,58,237,0.03), rgba(168,85,247,0.03)); }
.domain-card.data::before { background: linear-gradient(135deg, rgba(48,132,222,0.03), rgba(96,165,250,0.03)); }
.domain-card.security::before { background: linear-gradient(135deg, rgba(220,38,38,0.03), rgba(248,113,113,0.03)); }
.domain-card.systems::before { background: linear-gradient(135deg, rgba(5,150,105,0.03), rgba(52,211,153,0.03)); }
.domain-card.programming::before { background: linear-gradient(135deg, rgba(234,88,12,0.03), rgba(251,146,60,0.03)); }
.domain-card.math::before { background: linear-gradient(135deg, rgba(8,145,178,0.03), rgba(34,211,238,0.03)); }
.domain-card.research::before { background: linear-gradient(135deg, rgba(202,138,4,0.03), rgba(250,204,21,0.03)); }

/* Top accent line */
.domain-card.ai::after { background: linear-gradient(90deg, #7c3aed, #a855f7); }
.domain-card.data::after { background: linear-gradient(90deg, #3084de, #60a5fa); }
.domain-card.security::after { background: linear-gradient(90deg, #dc2626, #f87171); }
.domain-card.systems::after { background: linear-gradient(90deg, #059669, #34d399); }
.domain-card.programming::after { background: linear-gradient(90deg, #ea580c, #fb923c); }
.domain-card.math::after { background: linear-gradient(90deg, #0891b2, #22d3ee); }
.domain-card.research::after { background: linear-gradient(90deg, #ca8a04, #facc15); }

/* ═══════ Domain Head ═══════ */
.domain-head {
  display: flex;
  align-items: center;
  gap: 12px;
  margin-bottom: 16px;
  position: relative;
  z-index: 1;
}
.domain-icon {
  width: 38px;
  height: 38px;
  border-radius: 10px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.05rem;
  flex-shrink: 0;
  transition: transform 0.3s ease;
}
.domain-card:hover .domain-icon { transform: scale(1.1); }

.domain-card.ai .domain-icon { background: linear-gradient(135deg, rgba(124,58,237,0.12), rgba(168,85,247,0.08)); border: 1px solid rgba(124,58,237,0.1); }
.domain-card.data .domain-icon { background: linear-gradient(135deg, rgba(48,132,222,0.12), rgba(96,165,250,0.08)); border: 1px solid rgba(48,132,222,0.1); }
.domain-card.security .domain-icon { background: linear-gradient(135deg, rgba(220,38,38,0.12), rgba(248,113,113,0.08)); border: 1px solid rgba(220,38,38,0.1); }
.domain-card.systems .domain-icon { background: linear-gradient(135deg, rgba(5,150,105,0.12), rgba(52,211,153,0.08)); border: 1px solid rgba(5,150,105,0.1); }
.domain-card.programming .domain-icon { background: linear-gradient(135deg, rgba(234,88,12,0.12), rgba(251,146,60,0.08)); border: 1px solid rgba(234,88,12,0.1); }
.domain-card.math .domain-icon { background: linear-gradient(135deg, rgba(8,145,178,0.12), rgba(34,211,238,0.08)); border: 1px solid rgba(8,145,178,0.1); }
.domain-card.research .domain-icon { background: linear-gradient(135deg, rgba(202,138,4,0.12), rgba(250,204,21,0.08)); border: 1px solid rgba(202,138,4,0.1); }

.domain-name {
  font-family: 'Nunito', sans-serif;
  font-weight: 800;
  font-size: 0.76rem;
  text-transform: uppercase;
  letter-spacing: 0.06em;
  color: var(--global-text-color);
  line-height: 1.35;
}

/* ═══════ Subject List ═══════ */
.subject-list {
  list-style: none;
  padding: 0;
  margin: 0;
  position: relative;
  z-index: 1;
}
.subject-list li {
  font-family: 'Nunito', sans-serif;
  font-size: 0.85rem;
  font-weight: 500;
  color: var(--global-text-color);
  padding: 8px 0 8px 24px;
  position: relative;
  line-height: 1.4;
  border-bottom: 1px solid rgba(0,0,0,0.035);
  transition: all 0.25s ease;
}
.subject-list li:last-child { border-bottom: none; }

.subject-list li::before {
  content: '';
  position: absolute;
  left: 3px;
  top: 50%;
  transform: translateY(-50%);
  width: 7px;
  height: 7px;
  border-radius: 50%;
  transition: all 0.3s ease;
}
.subject-list li:hover {
  padding-left: 30px;
}
.subject-list li:hover::before {
  transform: translateY(-50%) scale(1.4);
  box-shadow: 0 0 8px currentColor;
}

/* Dot colors */
.domain-card.ai .subject-list li::before { background: #7c3aed; }
.domain-card.data .subject-list li::before { background: #3084de; }
.domain-card.security .subject-list li::before { background: #dc2626; }
.domain-card.systems .subject-list li::before { background: #059669; }
.domain-card.programming .subject-list li::before { background: #ea580c; }
.domain-card.math .subject-list li::before { background: #0891b2; }
.domain-card.research .subject-list li::before { background: #ca8a04; }

/* Glow on hover */
.domain-card.ai .subject-list li:hover::before { box-shadow: 0 0 10px rgba(124,58,237,0.5); }
.domain-card.data .subject-list li:hover::before { box-shadow: 0 0 10px rgba(48,132,222,0.5); }
.domain-card.security .subject-list li:hover::before { box-shadow: 0 0 10px rgba(220,38,38,0.5); }
.domain-card.systems .subject-list li:hover::before { box-shadow: 0 0 10px rgba(5,150,105,0.5); }
.domain-card.programming .subject-list li:hover::before { box-shadow: 0 0 10px rgba(234,88,12,0.5); }
.domain-card.math .subject-list li:hover::before { box-shadow: 0 0 10px rgba(8,145,178,0.5); }
.domain-card.research .subject-list li:hover::before { box-shadow: 0 0 10px rgba(202,138,4,0.5); }

/* Full-width card */
.domain-card.full-width { grid-column: 1 / -1; }
.domain-card.full-width .subject-list {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 0 32px;
}

/* ═══════ Section Divider ═══════ */
.section-divider {
  height: 1px;
  background: linear-gradient(90deg, transparent 0%, var(--global-border-color) 20%, var(--global-border-color) 80%, transparent 100%);
  margin: 2.5rem 0 0.8rem 0;
  position: relative;
}
.section-divider::after {
  content: '';
  position: absolute;
  left: 50%;
  top: -3px;
  width: 7px;
  height: 7px;
  border-radius: 50%;
  background: #3084de;
  transform: translateX(-50%);
}

/* ═══════ Dark Mode ═══════ */
html[data-theme="dark"] .cw-hero { border-color: rgba(255,255,255,0.05); }
html[data-theme="dark"] .subject-list li { border-bottom-color: rgba(255,255,255,0.04); }
html[data-theme="dark"] .domain-card { box-shadow: 0 1px 6px rgba(0,0,0,0.25); }
html[data-theme="dark"] .domain-card:hover { box-shadow: 0 16px 48px rgba(0,0,0,0.35); }
html[data-theme="dark"] .thesis-btn.primary { box-shadow: 0 2px 10px rgba(48,132,222,0.4); }

/* ═══════ Responsive ═══════ */
@media (max-width: 768px) {
  .domain-grid { grid-template-columns: 1fr; }
  .degree-body { flex-direction: column; gap: 10px; }
  .cw-hero { padding: 28px 22px 26px; }
  .cw-hero-title { font-size: 1.25rem; }
  .domain-card.full-width .subject-list { grid-template-columns: 1fr; }
  .thesis-card { flex-direction: column; gap: 12px; }
  .cw-stats { flex-wrap: wrap; gap: 12px; }
  .cw-stat { border-left: none; padding: 0 16px 0 0; }
}
</style>

<!-- ═══════════ Hero ═══════════ -->

<div class="cw-hero">
  <div class="cw-hero-label">Academic Foundation</div>
  <div class="cw-hero-title">Key Coursework & Thesis Research</div>
  <div class="cw-hero-desc">
    A curated overview of graduate and undergraduate coursework underpinning my research in
    <strong>AI Security</strong>, <strong>Adversarial Machine Learning</strong>, and
    <strong>Secure Software Systems</strong> — alongside thesis research published in
    internationally indexed journals.
  </div>
</div>

<!-- ═══════════════════════════════════ -->
<!--  M.TECH                             -->
<!-- ═══════════════════════════════════ -->

<div class="degree-section">

  <div class="degree-banner">
    <div class="degree-accent mtech"></div>
    <div class="degree-body">
      <div class="degree-left">
        <div class="degree-program">M.Tech — Data Science & Artificial Intelligence</div>
        <div class="degree-institution">
          <i class="fas fa-university fa-sm"></i>
          Indian Institute of Information Technology Ranchi
        </div>
      </div>
      <div class="degree-right">
        <span class="degree-chip year">2024 – 2026</span>
        <span class="degree-chip tag">Institute of National Importance</span>
      </div>
    </div>
  </div>

  <!-- Thesis -->
  <div class="thesis-card mtech">
    <div class="thesis-icon">📜</div>
    <div class="thesis-content">
      <div class="thesis-label">
        Master's Thesis
      </div>
      <div class="thesis-title">Cross-Domain Text Summarization Using Transformer Models</div>
      <div class="thesis-venue">
        Department of Computer Science & Engineering · <strong>IIIT Ranchi</strong>
      </div>
    </div>
  </div>

  <div class="domain-grid">

    <div class="domain-card ai">
      <div class="domain-head">
        <div class="domain-icon">🧠</div>
        <div class="domain-name">Artificial Intelligence &<br/>Machine Learning</div>
      </div>
      <ul class="subject-list">
        <li>Advanced Artificial Intelligence</li>
        <li>Advanced Machine Learning</li>
        <li>Pattern Recognition</li>
        <li>Advanced Soft Computing</li>
        <li>Evolutionary & Randomized Algorithms</li>
      </ul>
    </div>

    <div class="domain-card data">
      <div class="domain-head">
        <div class="domain-icon">📊</div>
        <div class="domain-name">Data Science & Mining</div>
      </div>
      <ul class="subject-list">
        <li>Fundamentals of Data Science</li>
        <li>Data Mining & Data Warehousing</li>
        <li>Software Defect & Quality Prediction</li>
      </ul>
    </div>

    <div class="domain-card research full-width">
      <div class="domain-head">
        <div class="domain-icon">🔬</div>
        <div class="domain-name">Research Methodology</div>
      </div>
      <ul class="subject-list">
        <li>Research Methodology & Intellectual Property Rights</li>
        <li>M.Tech Project & Dissertation</li>
      </ul>
    </div>

  </div>
</div>

<div class="section-divider"></div>

<!-- ═══════════════════════════════════ -->
<!--  B.TECH                             -->
<!-- ═══════════════════════════════════ -->

<div class="degree-section">

  <div class="degree-banner">
    <div class="degree-accent btech"></div>
    <div class="degree-body">
      <div class="degree-left">
        <div class="degree-program">B.Tech — Information Technology</div>
        <div class="degree-institution">
          <i class="fas fa-university fa-sm"></i>
          North-Eastern Hill University (NEHU), Shillong
        </div>
      </div>
      <div class="degree-right">
        <span class="degree-chip year">2018 – 2022</span>
        <span class="degree-chip tag-green">Central University, Govt. of India</span>
      </div>
    </div>
  </div>

  <!-- Thesis -->
  <div class="thesis-card btech">
    <div class="thesis-icon">📜</div>
    <div class="thesis-content">
      <div class="thesis-label">
        Bachelor's Thesis
        <span class="thesis-pub-badge">Published</span>
      </div>
      <div class="thesis-title">IoT-HITS: An IoT-Based Human Intrusion Detection System for Border Region Using Deep Learning</div>
      <div class="thesis-venue">
        <strong>IETE Journal of Research</strong> (Taylor & Francis) · Scopus & SCI Indexed
      </div>
      <div class="thesis-actions">
        <a href="https://www.tandfonline.com/doi/full/10.1080/03772063.2025.2521688" target="_blank" class="thesis-btn primary">
          <i class="fas fa-external-link-alt fa-xs"></i> View Publication
        </a>
        <a href="https://doi.org/10.1080/03772063.2025.2521688" target="_blank" class="thesis-btn outline">
          <i class="fas fa-link fa-xs"></i> DOI
        </a>
      </div>
    </div>
  </div>

  <div class="domain-grid">

    <div class="domain-card ai">
      <div class="domain-head">
        <div class="domain-icon">🧠</div>
        <div class="domain-name">AI & Intelligent Systems</div>
      </div>
      <ul class="subject-list">
        <li>Artificial Intelligence</li>
        <li>Soft Computing</li>
      </ul>
    </div>

    <div class="domain-card security">
      <div class="domain-head">
        <div class="domain-icon">🔐</div>
        <div class="domain-name">Security & Cryptography</div>
      </div>
      <ul class="subject-list">
        <li>Cryptography & Network Security</li>
        <li>Advanced Cryptography</li>
      </ul>
    </div>

    <div class="domain-card programming full-width">
      <div class="domain-head">
        <div class="domain-icon">💻</div>
        <div class="domain-name">Algorithms, Programming & Software Engineering</div>
      </div>
      <ul class="subject-list">
        <li>Data Structures & Algorithms</li>
        <li>Algorithm Analysis & Design</li>
        <li>Object-Oriented Programming & Methodology</li>
        <li>Compiler Design</li>
        <li>Software Engineering</li>
        <li>Web Technology</li>
      </ul>
    </div>

    <div class="domain-card systems">
      <div class="domain-head">
        <div class="domain-icon">🖥️</div>
        <div class="domain-name">Systems & Networks</div>
      </div>
      <ul class="subject-list">
        <li>Operating Systems</li>
        <li>Computer Networks</li>
        <li>Computer Organization & Architecture</li>
        <li>Wireless Networks</li>
        <li>Data Communication</li>
      </ul>
    </div>

    <div class="domain-card math">
      <div class="domain-head">
        <div class="domain-icon">📐</div>
        <div class="domain-name">Mathematics & Theory</div>
      </div>
      <ul class="subject-list">
        <li>Discrete Mathematics</li>
        <li>Statistics & Random Processes</li>
        <li>Formal Language & Automata Theory</li>
      </ul>
    </div>

    <div class="domain-card data">
      <div class="domain-head">
        <div class="domain-icon">🗄️</div>
        <div class="domain-name">Data Management</div>
      </div>
      <ul class="subject-list">
        <li>Relational Database Management Systems</li>
        <li>Management Information Systems</li>
      </ul>
    </div>

    <div class="domain-card research full-width">
      <div class="domain-head">
        <div class="domain-icon">🔬</div>
        <div class="domain-name">Research & Projects</div>
      </div>
      <ul class="subject-list">
        <li>B.Tech Major Project (Published in IETE Journal of Research)</li>
      </ul>
    </div>

  </div>
</div>
