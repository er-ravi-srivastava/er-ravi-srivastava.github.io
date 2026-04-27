---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---



<style>
.project-card {
  display: flex;
  background: var(--global-bg-color) !important;
  border: 1px solid var(--global-border-color) !important;
  border-radius: 12px;
  margin-bottom: 30px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  overflow: hidden;
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 12px 30px rgba(0,0,0,0.15);
}

.project-img-container {
  flex: 0 0 35%;
  min-height: 200px;
  background-color: #111;
  overflow: hidden;
  position: relative;
}

.project-img-container img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: transform 0.5s ease;
}

.project-card:hover .project-img-container img {
  transform: scale(1.05);
}

.project-content {
  flex: 1;
  padding: 30px !important;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.project-title {
  font-weight: 800;
  font-size: 1.4rem;
  color: var(--global-text-color) !important;
  margin-bottom: 10px;
  line-height: 1.3;
}

.project-category {
  font-weight: 600;
  color: var(--global-link-color) !important;
  font-size: 0.95rem;
  margin-bottom: 15px;
  text-transform: uppercase;
  letter-spacing: 0.05em;
}

.project-desc {
  font-size: 0.95rem;
  line-height: 1.6;
  color: var(--global-text-color) !important;
}

.project-desc ul {
  margin-top: 10px;
  padding-left: 20px;
  margin-bottom: 0;
}

.project-desc ul li {
  margin-bottom: 8px;
}

.project-desc ul li:last-child {
  margin-bottom: 0;
}

@media (max-width: 768px) {
  .project-card {
    flex-direction: column;
  }
  .project-img-container {
    flex: 0 0 200px;
  }
  .project-content {
    padding: 20px !important;
  }
}
</style>

<div style="margin-top:2rem;">

  <!-- Adversarial Prompt Injection -->
  <div class="project-card">
    <div class="project-img-container">
      <img src="/images/llm_security.png" alt="LLM Security Research" />
    </div>
    <div class="project-content">
      <div class="project-title">Adversarial Prompt Injection Attacks on LLMs: Cryptographic Key Leakage and Defense Strategies</div>
      <div class="project-category">Research Project</div>
      <div class="project-desc">
        <ul>
          <li>Conducted security analysis of LLM systems by designing prompt injection attack scenarios to exploit context leakage and unauthorized data exposure.</li>
          <li>Developed and evaluated mitigation strategies including prompt sanitization, input/output filtering, and instruction hierarchy enforcement to defend against injection-based attacks.</li>
          <li><strong>🏆 Best Paper Award — ICACA 2026</strong></li>
        </ul>
      </div>
    </div>
  </div>

  <!-- IoT-HITS -->
  <div class="project-card">
    <div class="project-img-container">
      <img src="/images/iot_border.png" alt="IoT Border Security" />
    </div>
    <div class="project-content">
      <div class="project-title">IoT-HITS: IoT-based Human Intrusion Detection System for Border Regions Using Deep Learning</div>
      <div class="project-category">Bachelor’s Thesis Project</div>
      <div class="project-desc">
        <ul>
          <li>Developed an IoT-based border security system using deep learning for real-time human intrusion detection, aligned with threat modeling (STRIDE) principles.</li>
          <li>Designed system architecture, integrated sensors, and implemented secure detection pipelines with alert mechanisms, incorporating basic security testing and risk mitigation.</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Master's Thesis -->
  <div class="project-card">
    <div class="project-img-container">
      <img src="/images/multilingual_nlp.png" alt="Multilingual NLP Research" />
    </div>
    <div class="project-content">
      <div class="project-title">Robust Multilingual Text Summarization for Indian Languages</div>
      <div class="project-category">Master’s Thesis (Ongoing)</div>
      <div class="project-desc">
        <ul>
          <li>Investigating transformer-based multilingual approaches (mT5, mBART-50, IndicBART) for low-resource Indian languages.</li>
          <li>Focusing on cross-lingual transfer, robustness, and fair evaluation across Hindi, Gujarati, and Bengali.</li>
        </ul>
      </div>
    </div>
  </div>

</div>
