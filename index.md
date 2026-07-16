---
layout: post
title: "Ravi Prakash Srivastava"
subtitle: "About me"
permalink: /
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
    <div style="display: grid; grid-template-columns: 2fr 1fr; gap: 20px; align-items: start;">
      <div style="text-align: justify;">
        <p>
          Hello! I hold a master’s degree in <strong>Data Science and Artificial Intelligence</strong> from the <a href="https://iiitranchi.ac.in/" target="_blank">Indian Institute of Information Technology, Ranchi, India</a>. In 2024, I received a postgraduate fellowship from the <strong>Institution of Electronics and Telecommunication Engineers (IETE), New Delhi</strong>, which supported my master’s studies at IIIT Ranchi. My master’s thesis is on <em>“Cross-Domain Text Summarization using Transformer Models”</em>. I completed my B.Tech in Information Technology from <a href="https://nehu.ac.in/" target="_blank">NEHU</a>, where I completed my thesis on <em>“IoT-HITS: An IoT Based Human Intrusion Detection System for Border Region Using Deep Learning”</em>.
        </p>

        <p>
          My research focuses on <strong>Natural Language Processing (NLP)</strong>, <strong>AutoML &amp; Foundation Models</strong>, <strong>Trustworthy AI</strong>, and <strong>Multimodal Learning</strong>. I am particularly interested in designing foundation models that exhibit robust generalization, efficient adaptation, and reliable reasoning across diverse modalities. My research aims to integrate automated machine learning, self-supervised representation learning, parameter-efficient fine-tuning, multimodal fusion, and uncertainty-aware inference to develop scalable AI systems that remain interpretable, robust to distributional shifts and adversarial perturbations, and deployable in safety-critical, real-world applications.
        </p>

      </div>
      <div style="text-align: center;">
        <img src="/images/picture_resized.png" alt="Ravi Prakash Srivastava" style="border-radius: 8px; width: 100%; max-width: 220px; box-shadow: 0 4px 12px rgba(0,0,0,0.15);">
        <div style="margin-top: 18px; font-size: 0.9rem; text-align: left; display: inline-block; width: 100%; max-width: 220px; box-shadow: 0 4px 12px rgba(0,0,0,0.02); border: 1px solid var(--border-color); padding: 14px; border-radius: 8px; background: var(--bg-card);">
          <div style="font-weight: 700; margin-bottom: 10px; color: var(--text-primary); font-size: 0.95rem;">Connect with me:</div>
          <div style="margin-bottom: 8px;"><a href="https://www.linkedin.com/in/ravi-prakash-sri/" target="_blank"><i class="fab fa-linkedin" style="width: 16px;"></i> LinkedIn</a></div>
          <div style="margin-bottom: 8px;"><a href="https://github.com/er-ravi-srivastava" target="_blank"><i class="fab fa-github" style="width: 16px;"></i> GitHub</a></div>
          <div style="margin-bottom: 8px;"><a href="https://scholar.google.com/citations?user=sElDRIMAAAAJ&hl=en" target="_blank"><i class="ai ai-google-scholar" style="width: 16px;"></i> Scholar</a></div>
          <div><a href="/files/Ravi_Prakash_Srivastava_CV.pdf" target="_blank"><i class="fas fa-file-pdf" style="width: 16px;"></i> View CV</a></div>
        </div>
      </div>
    </div>
  </div>



  <!-- News -->
  <div class="section-heading">News</div>
  <ul class="news-list">
    <li class="news-item">
      <span class="news-date">June 2026</span>
      <span class="news-text">📄 Appointed as a Peer Reviewer — view my <a href="/files/Reviewer_Ravi_Prakash_Srivastava.pdf" target="_blank">Reviewer Profile</a>.</span>
    </li>
    <li class="news-item">
      <span class="news-date">Mar 2026</span>
      <span class="news-text">Started a new position as a <strong>Software Engineer</strong> at SS Software Solutions LLC.</span>
    </li>
    <li class="news-item">
      <span class="news-date">Jan 2026</span>
      <span class="news-text">🏆 <a href="/files/Best_Paper_Award.pdf" target="_blank"><strong>Best Paper Award</strong></a> at ICACA 2026 for <em>Adversarial Prompt Injection Attacks on Large Language Models: Cryptographic Key Leakage and Defense Strategies</em>.</span>
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
