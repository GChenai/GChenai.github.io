---
layout: archive
permalink: /
title: "GChen - 顾志成"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. student at **Zhejiang University**, advised by Prof. [Pengcheng Nie](https://person.zju.edu.cn/npc). My research focuses on **Smart Agriculture**, especially agricultural computer vision and multispectral image analysis for crop monitoring and phenotyping. My recent work explores tomato fruit detection and phenotype calculation with improved transformer-based detectors, as well as lightweight drought recognition from soybean multispectral images.

**Email:** GChen AT zju.edu.cn

News
======

- **2026:** The preprint *Lightweight Computation Method for Tomato Fruit Phenotyping Based on an Improved Deep Learning Model* is under revision for *Engineering Computations*.
- **October 2025:** *Lightweight drought recognition model based on feature extraction of soybean multispectral images* was accepted by *Chemometrics and Intelligent Laboratory Systems*.
- **October 2024:** *Tomato fruit detection and phenotype calculation method based on the improved RTDETR model* was accepted by *Computers and Electronics in Agriculture*.
- **March 2024:** *A corn canopy organs detection method based on improved DBi-YOLOv8 network* was accepted by *European Journal of Agronomy*.

Publications
======

{% for post in site.publications reversed %}
  {% if post.category != "preprints" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

Preprints
======

{% for post in site.publications reversed %}
  {% if post.category == "preprints" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

Education
======

- **Ph.D. Student** @ Zhejiang University<br>
  **2026 - Present**<br>
  Ph.D. student advised by Prof. [Pengcheng Nie](https://person.zju.edu.cn/npc).
