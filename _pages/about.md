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
<!-- # Oop! I am updating this page. Please come back later. 😄 -->
<span class='anchor' id='about-me'></span>
# 💬 About Me

Hi, my name is Xinyu Yang (杨心妤), an incoming Information Science PhD student at Cornell University.

Previously, I got my bachelor's degree in Computer Science and Technology from Zhejiang University, China. During my undergraduate, I was fortunate to be a research intern at [Stanford AI Lab](https://ai.stanford.edu/) advised by [Prof. James Zou](https://www.james-zou.com/). I also experienced a wonderful research internship at Zhejiang University DCD Lab advised by [Prof. Fei Wu](https://person.zju.edu.cn/en/wufei).

My research interest lies in Computational Social Science, Science of Science and AI for social good. At present, my focus lies in conducting large-scale scientific data analyses using cutting-edge computational and machine learning techniques. 
<!-- Through this, he aims to gain a deeper understanding of the principles of science and innovation, with the ultimate goal of making meaningful contributions to society.
I would like to explore how to utilize AI and other computational tools for social good.  -->
Through this, I aim to apply and develop cutting-edge tools to understand the fundamental questions about individuals and collectives, unpack major problems and thereby address substantive questions both in the scientific and social realms.

# 📖 Educations
- *2019.09 - 2023.06*, B.E. in Computer Science and Technology, Zhejiang University, Hangzhou, China
  - *GPA:* Overall 90.19/100 (3.95/4.00); *Rank:* Top 5% among 226 students
  - *Minor:* Advanced Honor Class of Engineering Education Program (Honors program of Zhejiang University)


<!-- 
# 🔥 News
- Working on a project jointly advised by [Prof. James Zou](https://www.james-zou.com/) (Stanford Univeristy) and [Dr. Nazneen Rajani](https://www.nazneenrajani.com/) (Hugging Face). Will submit soon. -->


# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><img src='images/moonshape.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**AccuracyontheCurve: On the Nonlinear Correlation of ML Performance Between Data Subpopulation**

[Weixin Liang](https://ai.stanford.edu/~wxliang/)\*, [Yining Mao](https://yining-mao.github.io/)\*, [Yongchan Kwon](https://www.yongchanstat.com/)\*, **Xinyu Yang**, [James Zou](https://www.james-zou.com/)
( * equal contribution)

**ICML 2023**

<!-- **ICML 2022** Workshop on [Principles of Distribution Shift](https://sites.google.com/view/icml-2022-pods/)

**ICML 2022** Workshop on [Spurious Correlations, Invariance, and Stability](https://sites.google.com/view/scis-workshop/) -->

[[PDF]](https://arxiv.org/pdf/2305.02995.pdf), [[Website]](https://moonshape.readthedocs.io/), [[Video]](https://slideslive.com/38986287/on-the-nonlinear-correlation-of-ml-performance-berween-data-subpopulations), [[Code]](https://anonymous.4open.science/r/moonshape_subpopulation/)

- We show that there is a “moon shape” correlation (parabolic uptrend curve) between the test performance on the majority subpopulation and the minority subpopulation.
This nonlinear correlations hold across model architectures, training settings, datasets, and the imbalance between subpopulations.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/MetaShift.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1"> 

 **MetaShift: A Dataset of Datasets for Evaluating Contextual Distribution Shifts and Training Conflicts**]

[Weixin Liang](https://ai.stanford.edu/~wxliang/)\*, **Xinyu Yang\***, [James Zou](https://www.james-zou.com/)
( * equal contribution)

**Contributed Talk** at **ICML 2022** Workshop on [Shift happens: Crowdsourcing metrics and test datasets beyond
ImageNet](https://shift-happens-benchmark.github.io/)

[[PDF]](https://openreview.net/forum?id=iuSDDiqacPj), [[Website]](https://metadataset.readthedocs.io/), [[Video]](https://slideslive.com/38987455/metashift-a-dataset-of-datasets-for-evaluating-contextual-distribution-shifts), [[Code]](https://github.com/YoungXinyu1802/icml-2022/tree/main/shifthappens/tasks/imagenet_metashift)


- MetaShift introduces a collection of >10K sets of images with annotated contexts. It enables evaluating how ML works in different contexts (e.g. indoor cat vs outdoor cat). 
- We provided a distance score that measures the amount of distribution shift between any two of the data sets.
- We presented methods to match labels to ImageNet hierarchy via WordNet ID and construct classification tasks over MetaShift to enable evaluating off-the-shelf ImageNet models.
</div>
</div>

# 🎖 Honors and Awards
- *2022 - 2023* Outstanding Graduates of Zhejiang Province
- *2022 - 2023* Outstanding Graduates of Zhejiang University
- *2021 – 2022* First-Class Scholarship for Outstanding Students of Zhejiang University (Top 3%)
- *2020 – 2021* Second-Class Scholarship for Outstanding Students of Zhejiang University (Top 8%)
- *2019 – 2020* National Scholarship (Top 1%)
- *2019 – 2020* First-Class Scholarship for Outstanding Students of Zhejiang University (Top 3%) 
- *2019 – 2020* Outstanding Student Awards in Yunfeng College (15 out of 800 students) 



<!-- # 💬 💻Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 🎉 Misc
- I started learning Chinese Calligraphy (a traditional form of writing characters from the Chinese language through the use of ink and a brush) and sketchy when I was nine. [\[Gallery\]](images/gallery.png)
- I love art and sports. I enjoy painting, photography, table tennis, piano, and classical music.
