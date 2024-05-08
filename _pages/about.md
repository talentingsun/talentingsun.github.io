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

I am a third-year PhD student at the School of Transportation and Communications, Chongqing Jiaotong University, supervised by Prof. Jianxi Yang. Prior to that, I received my master's degree in computer science from Chongqing Jiaotong University in 2021. My research interests are computer vision, especially computer vision applications for transportation infrastructure.





# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIM</div><img src='images/mul.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-label Concrete Bridge Damage Classification Using Graph Convolution] \\
Jianxi Yang, **Hao Li**, Le Zhang, Lu Zhao, Shixin Jiang, Hong Xie

[**Project**]([https://speechresearch.github.io/fastspeech/](https://github.com/talentingsun/Multi-label_Concrete_Bridge_Damage)) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

we introduce an innovative algorithm that synergizes Graph Convolutional Neural Network (GCN) and MaxViT (Multi-Axis Vision Trans- former). Our approach leverages MaxViT to extract image features and subsequently models the co-occurrence correla- tion of labels. Additionally, we employ a graph convolutional neural network to extract features that capture the correlation between labels. Ultimately, we integrate these image features to enable the multi-label classification of damage images.
</div>
</div>

