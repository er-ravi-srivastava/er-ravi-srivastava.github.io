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
<a href="/files/Reviewer_Ravi_Prakash_Srivastava.pdf" class="cv-download" style="background:#10b981; box-shadow: 0 4px 14px rgba(16,185,129,0.3);" target="_blank">
  <i class="fas fa-certificate"></i> Reviewer Profile (PDF)
</a>
