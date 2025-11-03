---
layout: single
permalink: /
title: "Smart Sensing Lab"
author_profile: true
---

Welcome to the Smart Sensing Lab at Binghamton University (SUNY).

## 📰 Latest News
<ul>
{% for post in site.posts limit:5 %}
  {% if post.categories contains "news" %}
    <li>
      <strong>{{ post.date | date: "%b %-d, %Y" }}</strong> —
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endif %}
{% endfor %}
</ul>
