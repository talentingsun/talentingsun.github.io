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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIM</div><img src='images/data.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CBDOD7K: A new benchmark dataset for Concrete Bridge Damage Object Detection] 

[**Project**]([https://speechresearch.github.io/fastspeech/](https://github.com/talentingsun/Multi-label_Concrete_Bridge_Damage)) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

This paper introduces a novel dataset called CBDOD7K. It comprises 7,354 real bridge inspection images captured in various concrete bridge inspection scenarios, encompassing six prevalent categories of concrete bridge damages. Furthermore, the dataset offers standardized box-level annotations. CBDOD7K represents a pioneering large-scale dataset in the realm of deep learning-based research on concrete bridge disease inspection, signifying a substantial advancement in terms of diversity, complexity, and scalability. secondly, this paper presents a robust yet straightforward baseline method called BL-CBDOD for CBDOD7K. BL-CBDOD adopts a two-stage architecture for object detection, utilizing a composite backbone network to extract image features. Subsequently, an enhanced Region Proposal Network (RPN) and confidence calibration approach are employed for accurate prediction and classification of target boxes. Finally, we conducted a benchmarking study of these methods against established advanced object detection networks using CBDOD7K. The results demonstrate that our BL-CBDOD achieves outstanding performance on the test set. Lastly, we discuss the challenges and potential research directions of CBDOD7K to lay the foundation for further research in this field.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIM</div><img src='images/mul.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-label Concrete Bridge Damage Classification Using Graph Convolution] \\
Jianxi Yang, **Hao Li**, Le Zhang, Lu Zhao, Shixin Jiang, Hong Xie

[**Project**]([https://speechresearch.github.io/fastspeech/](https://github.com/talentingsun/Multi-label_Concrete_Bridge_Damage)) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

we introduce an innovative algorithm that synergizes Graph Convolutional Neural Network (GCN) and MaxViT (Multi-Axis Vision Trans- former). Our approach leverages MaxViT to extract image features and subsequently models the co-occurrence correla- tion of labels. Additionally, we employ a graph convolutional neural network to extract features that capture the correlation between labels. Ultimately, we integrate these image features to enable the multi-label classification of damage images.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIM</div><img src='images/mul.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-label Concrete Bridge Damage Classification Using Graph Convolution] \\
Jianxi Yang, **Hao Li**, Le Zhang, Lu Zhao, Shixin Jiang, Hong Xie

[**Project**]([https://speechresearch.github.io/fastspeech/](https://github.com/talentingsun/Multi-label_Concrete_Bridge_Damage)) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

we introduce an innovative algorithm that synergizes Graph Convolutional Neural Network (GCN) and MaxViT (Multi-Axis Vision Trans- former). Our approach leverages MaxViT to extract image features and subsequently models the co-occurrence correla- tion of labels. Additionally, we employ a graph convolutional neural network to extract features that capture the correlation between labels. Ultimately, we integrate these image features to enable the multi-label classification of damage images.
</div>
</div>
