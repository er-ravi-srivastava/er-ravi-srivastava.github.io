---
layout: post
title: "Projects"
subtitle: "My Projects"
permalink: /projects/
---

<style>
.project-card {
  background: var(--global-bg-color) !important;
  border: 1px solid var(--global-border-color) !important;
  border-radius: 12px;
  margin-bottom: 30px;
  padding: 28px 30px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 12px 30px rgba(0,0,0,0.15);
}

.project-title {
  font-weight: 700;
  font-size: 1.15rem;
  color: var(--global-text-color) !important;
  margin-bottom: 10px;
  line-height: 1.3;
  font-family: 'Inter', sans-serif;
}

.project-category {
  font-weight: 600;
  color: var(--global-link-color) !important;
  font-size: 0.88rem;
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
</style>

<div style="margin-top:2rem;">

  <!-- Master's Thesis -->
  <div class="project-card">
    <div class="project-title">Cross-Domain Text Summarization Using Transformer Models</div>
    <div class="project-category">Master's Thesis (Completed)</div>
    <div class="project-desc">
      <ul>
        <li>Investigated the domain shift and catastrophic forgetting challenges in abstractive summarization, adapting news-trained models (BART-large-CNN) to structurally distinct domains like legal documents (BillSum).</li>
        <li>Implemented and evaluated parameter-efficient fine-tuning (PEFT) using LoRA, combined with Elastic Weight Consolidation (EWC) regularization to preserve pre-trained knowledge.</li>
        <li>Achieved superior cross-domain generalization while dramatically reducing GPU memory requirements by training only ~1-2% (2M out of 406M) of total parameters.</li>
      </ul>
    </div>
  </div>

  <!-- Adversarial Prompt Injection -->
  <div class="project-card">
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

  <!-- LLM Semantic Cache -->
  <div class="project-card">
    <div class="project-title">LLM Semantic Cache &amp; Analytics Dashboard</div>
    <div class="project-category">Engineering Project &nbsp;·&nbsp; <a href="https://llm-semantic-cache.streamlit.app/" target="_blank" style="text-decoration: underline;"><i class="fas fa-external-link-alt fa-sm"></i> Live Demo</a></div>
    <div class="project-desc">
      <ul>
        <li>Designed a semantic caching layer for LLMs that retrieves responses based on semantic similarity rather than exact keyword matching, optimizing API costs and latency.</li>
        <li>Integrated a web dashboard to track similarity thresholds, analyze query latency, and visualize real-time hit/miss metrics and system performance.</li>
      </ul>
    </div>
  </div>

  <!-- Vulnerability Management Platform -->
  <div class="project-card">
    <div class="project-title">AI-Powered Vulnerability Management Platform (SAST + DAST)</div>
    <div class="project-category">Engineering Project &nbsp;·&nbsp; <a href="https://vulnerability-management-app.streamlit.app/" target="_blank" style="text-decoration: underline;"><i class="fas fa-external-link-alt fa-sm"></i> Live Demo</a></div>
    <div class="project-desc">
      <ul>
        <li>Automated static analysis via Semgrep and dynamic testing (SQLi, XSS, CSRF) for live web applications; built an interactive Streamlit dashboard for real-time vulnerability visualisation and remediation guidance.</li>
        <li>Dockerised, CI/CD-compatible DevSecOps architecture; integrated into GitHub Actions for continuous security coverage.</li>
      </ul>
    </div>
  </div>

  <!-- IoT-HITS -->
  <div class="project-card">
    <div class="project-title">IoT-HITS: IoT-based Human Intrusion Detection System for Border Regions Using Deep Learning</div>
    <div class="project-category">Bachelor's Thesis Project</div>
    <div class="project-desc">
      <ul>
        <li>Developed an IoT-based border security system using deep learning for real-time human intrusion detection, aligned with threat modeling (STRIDE) principles.</li>
        <li>Designed system architecture, integrated sensors, and implemented secure detection pipelines with alert mechanisms, incorporating basic security testing and risk mitigation.</li>
      </ul>
    </div>
  </div>

</div>
