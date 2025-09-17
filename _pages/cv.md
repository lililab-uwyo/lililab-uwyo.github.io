---
layout: cv
permalink: /cv/
title: Curriculum Vitae
nav: true
nav_order: 5
cv_pdf: CV-LiLi-20250909.pdf
description: Click the PDF icon to view my latest CV.
toc:
  sidebar: left
---

<!-- 这里调用 resume.json 自动渲染 CV -->
{% include cv-basics.html %}
{% include cv-work.html %}
{% include cv-education.html %}
{% include cv-awards.html %}

---

## Selected Publications

<!-- 这里调用 papers.bib 里标记 selected=true 的论文 -->
{% bibliography --query @*[selected=true] %}
