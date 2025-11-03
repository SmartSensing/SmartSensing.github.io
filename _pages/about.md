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

---
title: "Welcome, Mohamed gallai"
date: 2025-09-01
categories: [news]
---
:tada: **Mohamed gallai** joined our group as a **Ph.D. student** — welcome!
---
title: "Welcome, Azaz"
date: 2025-09-01
categories: [news]
---
:tada: **Azaz-Ur-rehman Nasir** joined our group as a **Ph.D. student** — welcome!
