---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<style>
.pub-table {
  width: 100%;
  border-collapse: separate !important;
  border-spacing: 0 15px !important;
  border: none !important;
  margin-top: -15px;
}

.pub-table thead {
  background: transparent !important;
  border: none !important;
}

.pub-table thead th {
  border: none !important;
  color: var(--global-text-color-light) !important;
  font-weight: 600;
  text-transform: uppercase;
  font-size: 0.75rem;
  letter-spacing: 0.05rem;
  padding: 0 20px !important;
}

.pub-table tbody tr {
  background: var(--global-bg-color) !important;
  box-shadow: 0 2px 8px rgba(0,0,0,0.06);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.pub-table tbody tr:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.12);
}

.pub-table tbody td {
  border: none !important;
  padding: 20px !important;
  vertical-align: top;
  border-top: 1px solid var(--global-border-color) !important;
  border-bottom: 1px solid var(--global-border-color) !important;
}

.pub-table tbody td:first-child {
  border-left: 1px solid var(--global-border-color) !important;
  border-top-left-radius: 8px;
  border-bottom-left-radius: 8px;
  font-weight: 700;
  color: var(--global-link-color) !important;
  width: 100px;
  text-align: center;
  font-size: 1.2rem;
}

.pub-table tbody td:last-child {
  border-right: 1px solid var(--global-border-color) !important;
  border-top-right-radius: 8px;
  border-bottom-right-radius: 8px;
  text-align: right;
  width: 140px;
}

.pub-title {
  font-weight: 700;
  font-size: 1.15rem;
  color: var(--global-text-color);
  margin-bottom: 8px;
  line-height: 1.3;
}

.pub-title a {
  text-decoration: none;
  color: inherit;
}

.pub-title a:hover {
  color: var(--global-link-color);
}

.pub-venue {
  font-weight: 500;
  color: var(--global-link-color);
  font-size: 0.95rem;
  margin-bottom: 8px;
  display: block;
}

.pub-excerpt {
  font-size: 0.9rem;
  color: var(--global-text-color-light);
  line-height: 1.5;
  margin-top: 10px;
}

.pub-links {
  display: flex;
  gap: 10px;
  justify-content: flex-end;
  margin-top: 10px;
}

@media (max-width: 768px) {
  .pub-table, .pub-table tbody, .pub-table tr, .pub-table td {
    display: block !important;
    width: 100% !important;
  }
  .pub-table thead { display: none !important; }
  .pub-table tr { margin-bottom: 25px; border-radius: 8px; border: 1px solid var(--global-border-color) !important; }
  .pub-table td:first-child { background: var(--global-border-color); border-radius: 8px 8px 0 0 !important; font-size: 1rem; }
  .pub-links { justify-content: flex-start; }
}
</style>

<div style="margin-top:2rem;"> <!-- noticeable space below the title -->


<table class="pub-table">
  <thead>
    <tr>
      <th>Year</th>
      <th>Publication Details</th>
      <th>Links</th>
    </tr>
  </thead>
  <tbody>
    {% for post in site.publications reversed %}
    <tr>
      <td>{{ post.date | date: "%Y" }}</td>
      <td>
        <div class="pub-title">
          <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        </div>
        <span class="pub-venue">{{ post.venue }}</span>
        {% if post.excerpt %}
        <div class="pub-excerpt">{{ post.excerpt | strip_html | truncatewords: 30 }}</div>
        {% endif %}
      </td>
      <td>
        <div class="pub-links">
          {% if post.paperurl %}
          <a href="{{ post.paperurl }}" class="btn btn--primary btn--small" target="_blank">PDF</a>
          {% endif %}
          <a href="{{ post.url | relative_url }}" class="btn btn--info btn--small">Details</a>
        </div>
      </td>
    </tr>
    {% endfor %}
  </tbody>
</table>
