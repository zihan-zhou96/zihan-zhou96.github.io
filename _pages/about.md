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

I am a Ph.D. student in Computer Science at Johns Hopkins University, advised by Professor [Murat Kocaoglu](https://www.muratkocaoglu.com/). I moved to Johns Hopkins from Purdue ECE with my advisor in 2025. My research centers on causal machine learning, including causal discovery, Bayesian causal inference, and root-cause analysis, with broader interests in reliable and interpretable AI. Before my Ph.D., I received an M.S. in Electrical Engineering from Northwestern University (2021), supervised by Prof. [Thrasyvoulos Pappas](https://scholar.google.com/citations?user=FdtIIgkAAAAJ), and a B.S. in Space Science and Technology from Nanjing University (2019).

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
- ABE 59100 Machine Learning for CV and IoT (Spring 2023)

## 🔍 Service

Reviewer: ICML 2026; NeurIPS 2025, 2026; ICLR 2025, 2027; AISTATS 2025, 2026; UAI 2024, 2025, 2026

## 🏆 Awards

- ICML 2026 Silver Reviewer Award (2026)
- NeurIPS 2024 Scholar Award (2024)
- KDD 2022 Student Volunteer (2022)
