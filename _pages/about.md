---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 👨🏻‍💻 About Me
I am currently a first-year PHD student with the [School of Artificial Intelligence (SAI), Shanghai Jiao Tong University (SJTU) (上海交通大学人工智能学院)](https://sai.sjtu.edu.cn). I have been a member of [ReThinkLab](https://github.com/Thinklab-SJTU) since 2022 and supervised by [Prof. Junchi Yan (严骏驰)](https://thinklab.sjtu.edu.cn) who leads the lab. I achieved the Bachelor degree from [School of Computer Science](https://www.cs.sjtu.edu.cn/) at SJTU, and transitioned directly to the current PhD program. My research interests lie in machine learning, especially deep generative models and combinatorial optimization on graphs.

## 📖 Educations
---
- *2025.09 - now*, School of Artificial Intelligence, SJTU (pursuing the PHD's Degree)
- *2021.09 - 2025.06*, Department of Computer Science and Engineering (***IEEE Honors Class***), SJTU (B.E. Degree obtained)
    - Overall: ![gpa](https://img.shields.io/badge/GPA-3.93-blue) ![grade](https://img.shields.io/badge/Grade-90.81-blue) ![rank](https://img.shields.io/badge/Ranking-top_10%25-blue)
    - Courses: ![course-above-a](https://img.shields.io/badge/Above_A-_-67%25-orange)  ![course-above-a+](https://img.shields.io/badge/Above_A+-29%25-orange)

## 🎖 Honors and Awards
---
- *2025.06* Outstanding Graduate of Shanghai (上海市优秀毕业生 **top 3%** citywide)
- *2024.12* First-Class Cybersecurity Scholarship (一流网安奖学金 **top 10%** in Dept.) 
- *2022.12* National Scholarship for Undergraduate Stuedent (本科生国家奖学金 **top 0.2%** nationwide)
- *2022.12* First-class Academic Scholarship of SJTU (上海交通大学A等优秀奖学金 **top 1%** in SJTU)
- *2022.10* Merit Student of Shanghai Jiao Tong University (上海交通大学三好学生 **top 8%** in SJTU) 

## 🔥 News
---
- *2026.05*: 🔍 I served as a **reviewer** for **NeurIPS 2026**!
- *2026.05*: 🎉 One paper was accepted by **ICML 2026**!
- *2026.02*: 🔍 I served as a **reviewer** for **ICML 2026**!
- *2026.01*: 🎉 One paper was accepted by **ICLR 2026**!
- *2025.10*: 🔍 I served as a **reviewer** for **ICLR 2026** and **AAMAS 2026**!
- *2025.09*: 🎉 One paper was accepted by **NeurIPS 2025**!
- *2025.05*: 🎉 Two papers were accepted by **ICML 2025**!
- *2025.01*: 🎉 Two papers were accepted by **ICLR 2025**!
- *2024.10*: 🔍 I served as a **reviewer** for **ICLR 2025**!
- *2024.01*: 🎉 One paper was accepted by **JMLR**!

{% include_relative pubs.md %}

<span class='anchor' id='-open-source-projects'></span>
## ⚙️ Open Source Projects
---
- [Awesome-ML4CO ![github-stars](https://img.shields.io/github/stars/Thinklab-SJTU/awesome-ml4co?style=social)](https://github.com/Thinklab-SJTU/awesome-ml4co), a curated collection of literature in the ML4CO field, organized to support researchers in accessing both foundational and recent developments. This repository is maintained with a joint effort by members in SJTU-Thinklab as well as contributors from the community.

- [ML4CO-Kit ![github-stars](https://img.shields.io/github/stars/Thinklab-SJTU/ML4CO-Kit?style=social)](https://github.com/Thinklab-SJTU/ML4CO-Kit), a general-purpose toolkit that provides implementations of common algorithms used in ML4CO, along with basic training frameworks, traditional solvers and data generation tools. It aims to simplify the implementation of key techniques and offer a solid base for developing machine learning models for COPs.

- [ML4TSPBench ![github-stars](https://img.shields.io/github/stars/Thinklab-SJTU/ML4TSPBench?style=social)](https://github.com/Thinklab-SJTU/ML4TSPBench), a benchmark focusing on exploring the TSP for representativeness. It offers a deep dive into various methodology designs, enabling comparisons and the development of specialized algorithms.

- [ML4CO-Bench-101 ![github-stars](https://img.shields.io/github/stars/Thinklab-SJTU/ML4CO-Bench-101?style=social)](https://github.com/Thinklab-SJTU/ML4CO-Bench-101), a benchmark that categorizes neural combinatorial optimization (NCO) solvers by solving paradigms, model designs, and learning strategies. It evaluates applicability and generalization of different NCO approaches across a broad range of combinatorial optimization problems to uncover universal insights that can be transferred across various domains of ML4CO.

- [Pygmtools ![github-stars](https://img.shields.io/github/stars/Thinklab-SJTU/pygmtools?style=social)](https://github.com/Thinklab-SJTU/pygmtools), a Python graph matching toolkit that implements a comprehensive collection of two-graph matching and multi-graph matching solvers, covering both learning-free solvers as well as learning-based neural graph matching solvers. Our implementation supports numerical backends including Numpy, PyTorch, Jittor, Paddle, runs on Windows, MacOS and Linux, and is friendly to install and configure.