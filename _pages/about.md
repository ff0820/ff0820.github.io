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

# About Me
<span class='anchor' id='about-me'></span>
I am currently a final-year master's student in the [Colledge of Computer Science](https://cs.scu.edu.cn/) at [Sichuan University](https://www.scu.edu.cn/), supervised by [Prof. Min Zhu](https://cs.scu.edu.cn/info/1135/9894.htm) in [SCU VIS](https://scuvis.org/about/).
Before that, I received my bachelor's degree in Computer Science and Technology from Sichuan University in 2021.

My research interests primarily revolve around human-computer interaction, interactive tools for data science, presentation support for computational notebooks.

This passion, cultivated and refined during my research internships with [Prof. Huamin Qu](http://huamin.org/) at the [Hong Kong University of Science and Technology](https://cse.hkust.edu.hk/), and [Prof. Jian Zhao](https://www.jeffjianzhao.com/) at the [University of Waterloo](https://cs.uwaterloo.ca/).

<mark style="background-color: #96d1e9">I am looking for 2024 Fall PhD positions in Human-Computer Interaction and Visualization!</mark>

# 🔈 News
- *2024.01.19*: &nbsp;🎉 Our paper *\*\*\* Computational Notebooks through Outlines* is conditionally accepted to **CHI' 2024**.
- *2023.10.01*: &nbsp;🔥 Awarded the National Scholarship of China (Top 1%).
- *2023.09.30*: &nbsp;🔥 Awarded the Outstanding Graduate Students of Sichuan Province.
- *2023.09.01*: &nbsp;🔥 Awarded the First Class Scholarship of Sichuan University for Graduate Students.
- *2023.07.16*: &nbsp;🎉 Our paper *VideoPro: A Visual Analytics Approach for Interactive Video Programming* is accepted to **VIS'2023**. Congrats. to [Jianben He](https://jessiehe970311.github.io/). Check the paper [here](https://ieeexplore.ieee.org/abstract/document/10292616?casa_token=53ZRqOhT41cAAAAA:W4I9cl-2Op28eU5qNcSC7-_QHdXmh0I-9dU-FoBBrSlXepv1OcPRrB7OiB2L_wu4RZ_-mG7Ncg).
- *2023.03.03*: &nbsp;🎉 Our paper *Slide4N: Creating Presentation Slides from Computational Notebooks with Human-AI Collaboration* is accepted to **CHI'2023**. Check the paper [here](https://dl.acm.org/doi/abs/10.1145/3544548.3580753).


# 📝 Publications 
More publications can be found in [Google Scholar](https://scholar.google.com.hk/citations?user=IY0OI6kAAAAJ).

† indicates equal contribution.

<!-- 23_slide4n -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CHI 2023</div>
      <img src='images/23_slide4n.png' width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  [Slide4N: Creating Presentation Slides from Computational Notebooks with Human-AI Collaboration](https://dl.acm.org/doi/abs/10.1145/3544548.3580753)

  **Fengjie Wang<sup>†</sup>**, Xuye Liu<sup>†</sup>, Oujing Liu, Ali Neshati, Tengfei Ma, Min Zhu, Jian Zhao

  ACM CHI Conference on Human Factors in Computing Systems, 2023 (CHI 2023).

  [PDF](papers/23_slide4n.pdf)
  |
  [Demo](https://www.youtube.com/watch?v=5RP9ADh3mSg)
  |
  [Preview](https://www.youtube.com/watch?v=poS27Ju4LAw)
  |
  [Presentation](https://www.youtube.com/watch?v=8srkyc7Utr8&t=3s)
  </div>
</div>

<!-- 23_videopro -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">VIS 2023</div>
      <img src='images/23_videopro.png' width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  [VideoPro: A Visual Analytics Approach for Interactive Video Programming](https://ieeexplore.ieee.org/abstract/document/10292616?casa_token=53ZRqOhT41cAAAAA:W4I9cl-2Op28eU5qNcSC7-_QHdXmh0I-9dU-FoBBrSlXepv1OcPRrB7OiB2L_wu4RZ_-mG7Ncg)

  Jianben He, Xingbo Wang, Kam Kwai Wong, Xijie Huang, Changjian Chen, Zixin Chen, **Fengjie Wang**, Min Zhu, and Huamin Qu

  IEEE Transactions on Visualization and Computer Graphics (VIS 2023).

  [PDF](papers/23_videopro.pdf)
  |
  [Preview](https://www.youtube.com/watch?v=FCb64peiqBA)
  |
  [Presentation](https://www.youtube.com/watch?v=Hn2_KqSMDaY)
  </div>
</div>

<!-- 23_GBDT4CTRVis -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <!-- <div class="badge">CHI 2023</div> -->
      <img src='images/23_GBDT4CTRVis.png' width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  GBDT4CTRVis: Visual Analytics of Gradient Boosting Decision Tree for Advertisement Click-Through Rate Prediction

  Wenwen Gao, Shangsong Liu, Yi Zhou, **Fengjie Wang**, Feng Zhou and Min Zhu

  ChinaVis 2023.

  <!-- [PDF]()
  |
  [Demo]() -->
  </div>
</div>

<!-- 23_warehouselens -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <!-- <div class="badge">CHI 2023</div> -->
      <img src='images/23_warehouselens.png' width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  [WarehouseLens: Visualizing and Exploring Turnover Events of Digital Warehouse](https://link.springer.com/article/10.1007/s12650-023-00913-7)

  Fuqiu Chen, Jizhuo Li, **Fengjie Wang**, Shangsong Liu, Xiaolin Wen, Pengyuan Li and Min Zhu

  Journal of Visualization, 2023.

  [PDF](papers/23_warehouselens.pdf)
  </div>
</div>

<!-- 23_diffseer -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <!-- <div class="badge">CHI 2023</div> -->
      <img src='images/23_diffseer.png' width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  [	DiffSeer: Difference-based Dynamic Weighted Graph Visualization](https://ieeexplore.ieee.org/abstract/document/10078374)

  Xiaolin Wen, Yong Wang, Meixuan Wu, **Fengjie Wang**, Xuanwu Yue, Qiaomu Shen, Yuxin Ma, Min Zhu

  IEEE Computer Graphics and Application, 2023.
  
  [PDF](papers/23_diffseer.pdf)
  </div>
</div>

<!-- 22_triplan -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <!-- <div class="badge">CHI 2023</div> -->
      <img src='images/22_triplan.png' width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  [TriPlan: An Interactive Visual Analytics Approach for Better Tourism Route Planning](https://link.springer.com/article/10.1007/s12650-022-00861-8)

  Xinyi Zhang, Xiao Pang, Xiaolin Wen, **Fengjie Wang**, Changlin Li, Min Zhu.
  
  Journal of Visualization, 2022.
  
  [PDF](papers/22_triplan.pdf)
  </div>
</div>


# 🎓 Educations
- *2021.09 - 2024.06 (Expected)*, Sichuan University, China.
  - Master's Degree in Computer Science and Technology
  - Mentor: [Prof. Min Zhu](https://cs.scu.edu.cn/info/1135/9894.htm)
- *2017.09 - 2021.06*, Sichuan University, China.
  - Bachelar's Degree in Computer Science and Technology

<!-- - *2021.09 - 2024.06 (Expected)*, Master's Degree, Computer Science and Technology, Sichuan University, China.
- *2017.09 - 2021.06*, Bachelar's Degree, Computer Science and Technology, Sichuan University, China. -->

# 🌟 Experiences
- *2023.05 - 2023.10*, Hong Kong University of Science and Technology, Hong Kong, China.
  - Visiting Student Researcher at the [HKUST VisLab](http://vis.cse.ust.hk/index.html)
  - Mentor: [Prof. Huamin Qu](http://huamin.org/)
- *2022.05 - 2023.04*, University of Waterloo, Waterloo, Canada.
  - Visiting Student Researcher at the [Waterloo Visualization (WatVis) Group](https://www.jeffjianzhao.com/)
  - Mentor: [Prof. Jian Zhao](https://www.jeffjianzhao.com/)

<!-- - *2023.05 - 2023.10*, Visiting Student Researcher, HKUST VisLab, Hong Kong University of Science and Technology, Hong Kong, China.
- *2022.05 - 2023.04*, Visiting Student Researcher, the Waterloo Visualization (WatVis) Group, University of Waterloo, Waterloo, Canada. -->

# 💡 Activities
- *2024.01*, Organizer and host for the talk "Visualization for Emotion, Fraud, and Quantum Computing" with speakers [Xingyu Lan](https://olivialan.github.io/), [Shaolun Ruan](https://shaolun-ruan.com/index.html), [Xiaolin Wen](https://selvalim.github.io/homepage/), Sichuan University, Chengdu, China.
- *2023.04*, Paper Presentation ([Slide4N](https://www.youtube.com/watch?v=8srkyc7Utr8&t=3s)) in CHI 2023, Hamburg, Germany.
- *2022.07*, Participation in ChinaVis 2022, Xining, China.
- *2022.06*, Participation in ChinaVis Challenge 2022.
- *2021.07*, Participation in International Visualization Summer School, Peking Univerisity, China.
- *2021.07*, Participation in International Visualization Summer School, Zhejiang Univerisity, China.
- *2021.06*, Participation in ChinaVis Challenge 2021.


# 🏅 Honors and Awards
- *2024.01*, Comprehensive Quality A Grade Certificate of Sichuan Province
- *2023.10*, <mark style="background-color: #96d1e9">National Scholarship of China (Top 1%)</mark>
- *2023.09*, First Class Scholarship of Sichuan University for Graduate Students
- *2023.09*, Outstanding Graduate Students of Sichuan Province
- *2022.07*, Third Award, ChinaVis Challenge 2022
- *2021.06*, Star of Computer Science in Sichuan University
- *2021.04*, Outstanding Undergraduate Students of Sichuan Province
- *2020.06*, Excellent Completion of Provincial Student Innovation Training Project
- *2019.12*, <mark style="background-color: #96d1e9">National Scholarship of China (Top 1%)</mark>
- *2019.11*, First Class Scholarship of Sichuan University for Undergraduate Students
- *2019.05*, Meritorious Winner of the International Mathematical Contest in Modeling by COMAP


<!-- # 📃 CV
[Check my latest CV.](cv/CV_Fengjie_Wang_Jan_2024.pdf) -->
