---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* **Ph.D in Computer Science**, Hong Kong University of Science and Technology (HKUST), 2024-Present
  * NLP Group, advised by Prof. Junxian He
* **B.Eng. in Computer Science**, Shanghai Jiao Tong University (SJTU), 2020-2024
  * Graduated in June 2024

## Research Experience

* **Research Intern**, MINIMAX, Feb 2025 – Present
* **Research Intern**, Tencent WXG, Jun 2024 – Sep 2024
  * Advisor: Zifei Shan
* **Research Intern**, Shanghai AI Lab, Jun 2023 – Dec 2023
  * Advisor: Prof. Yu Cheng

## Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Selected Awards

* Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

{% if site.teaching.size > 0 %}
## Teaching

  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% endif %}
