---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

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
