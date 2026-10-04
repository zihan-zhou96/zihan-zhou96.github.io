---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Biography
======

I am a Ph.D. student in Computer Science at Johns Hopkins University, advised by Professor [Murat Kocaoglu](https://www.muratkocaoglu.com/). I moved to Johns Hopkins from Purdue ECE with my advisor in 2025. My research centers on causal inference and causal discovery. Before my Ph.D., I received an M.S. in Electrical Engineering from Northwestern University (2021), supervised by Prof. [Thrasyvoulos Pappas](https://scholar.google.com/citations?user=FdtIIgkAAAAJ), and a B.S. from the School of Astronomy and Space Science at Nanjing University (2019), supervised by Prof. [Hui Zhang](https://scholar.google.com/citations?user=Bvha2SkAAAAJ).

## 📰 News

{% for item in site.data.news %}
- **{{ item.date | date: "%b %Y" }}**: {{ item.description }}
{% endfor %}

## 📝 Publications

{% include publication-list.html %}

## 🧑‍🏫 Teaching

Teaching Assistant at Purdue University:

- ECE 57000 Intro to AI (Fall 2023, Spring 2025)
- ECE 62900 Intro to Neural Networks (Fall 2024)
- ECE 50024 Machine Learning (Spring 2024)
- ABE 59100 Machine Learning and Computer Vision for IoT (Spring 2023)

## 🔍 Service

Reviewer: ICML 2026; NeurIPS 2025, 2026; ICLR 2025; AISTATS 2025, 2026; UAI 2024, 2025, 2026
