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

I am a PhD student in the School of Computing at the Australian National University, supervised by Prof. [Hongdong Li](https://users.cecs.anu.edu.au/~hongdong/). I worked on a wide range of topics in computer vision, including 3D pose tracking and extended reality (with [Pan Ji](https://sites.google.com/view/panji530) at Tencent XR Vision Labs); avatar reconstruction and animation (with [Fabian Prada](https://scholar.google.com/citations?user=s35rxJwAAAAJ&hl=es) and [Jason Saragih](https://scholar.google.com/citations?user=ss-IvjMAAAAJ&hl=en) at Meta Codec Avatars Lab); 3D asset generation and video creation (with [Pulak Purkait](https://scholar.google.com/citations?user=fb5zcbUAAAAJ&hl=en) at Amazon IML). Please find more details in my [CV](https://rongakowang.github.io/files/CV.pdf).

Prior to my PhD student, I obtained my Bachelor degree in the College of Engineering and Computer Science at the Australian National University, and was awarded with [University Medal](https://www.anu.edu.au/students/program-administration/prizes/university-medal-and-postgraduate-medal-for-academic-excellence) and [Erin Brent Computer Science Prize](https://www.anu.edu.au/students/program-administration/prizes/erin-brent-computer-science-prize#:~:text=The%20prize%20shall%20be%20awarded,Computer%20Science%2C%20Software%20Engineering%20or). I was also awarded with First Class Honours under the supervision of [Dongxu Li](https://sites.google.com/view/dongxu-li/home) and Hongdong Li.

# 💻 Work Experience
- *2022.07 - 2023.04*, XR Vision Labs, [Tencent](https://www.tencent.com/), Research Intern.
- *2024.06 - 2024.11*, Codec Avatars Lab, [Meta](https://about.meta.com/realitylabs/), Research Intern.
- *2025.01 - 2025.07*, International Machine Learning, [Amazon](https://www.amazon.science/research-areas/machine-learning), Research Intern.


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/cvpr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FRESA: Feedforward Reconstruction of Personalized Skinned Avatars from Few Images](https://cvpr.thecvf.com/virtual/2025/poster/32467)

**Rong Wang**, Fabian Prada, Ziyan Wang, Zhongshi Jiang, Chengxiang Yin, Junxuan Li, Shunsuke Saito, Igor Santesteban, Javier Romero, Rohan Joshi, Hongdong Li, Jason Saragih, Yaser Sheikh

[**GitHub**](https://github.com/rongakowang/FRESA),  [**Project**](https://rongakowang.github.io/fresa/fresa.html)

- We learn a universal prior from over a thousand clothed humans to achieve instant feedforward generation and zero-shot generalization, aiming for reconstructing personalized 3D human avatars with realistic animation from only a few images.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/eccv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards High-Quality 3D Motion Transfer with Realistic Apparel Animation](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/05572.pdf)

**Rong Wang**, Wei Mao, Changsheng Lu, Hongdong Li

[**GitHub**](https://github.com/rongakowang/MMDMC)

-  We present a novel method aiming for high-quality motion transfer with realistic apparel animation, and also build a new dataset named MMDMC combining stylized characters from the MikuMikuDance community with real-world Motion Capture data.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/nips.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DeepSimHO: Stable Pose Estimation for Hand-Object Interaction via Physics Simulation](https://proceedings.neurips.cc/paper_files/paper/2023/file/fbdaea4878318e214c0577dae4b8bc43-Paper-Conference.pdf)

**Rong Wang**, Wei Mao, Hongdong Li

[**GitHub**](https://github.com/rongakowang/DeepSimHO)

-  We present DeepSimHO: a novel deep-learning pipeline that combines forward physics simulation and backward gradient approximation with a neural network.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WACV 2023</div><img src='images/wacv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Interacting hand-object pose estimation via dense mutual attention](https://openaccess.thecvf.com/content/WACV2023/papers/Wang_Interacting_Hand-Object_Pose_Estimation_via_Dense_Mutual_Attention_WACV_2023_paper.pdf)

**Rong Wang**, Wei Mao, Hongdong Li

[**GitHub**](https://github.com/rongakowang/DenseMutualAttention)

- We propose a novel dense mutual attention mechanism that is able to model fine-grained dependencies between the hand and the object.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2021</div><img src='images/aaai.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Transcribing natural languages for the deaf via neural editing programs](https://cdn.aaai.org/ojs/21457/21457-13-25470-1-2-20220628.pdf)

Dongxu Li, Chenchen Xu, Liu Liu, Yiran Zhong, **Rong Wang**, Lars Petersson, Hongdong Li 

- We design a new neural agent that learns to synthesize and execute editing programs, conditioned on sentence contexts and partial editing results.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WSDM 2021</div><img src='images/wsdm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AttentionFlow: Visualising Influence in Networks of Time Series](https://dl.acm.org/doi/pdf/10.1145/3437963.3441703)

Minjeong Shin, Alasdair Tran, Siqi Wu, Alexander Mathews, **Rong Wang**, Georgiana Lyall, Lexing Xie

[**GitHub**](https://github.com/alasdairtran/attentionflow)
- We present AttentionFlow, a new system to visualise networks of time series and the dynamic influence they have on one another.
</div>
</div>

# 🎖 Honors and Awards
- *2018*, ANU Excellence Scholarship.
- *2019 – 2021*, ANU Summer Research Scholarship.
- *2019 – 2021*, Terrell International Undergraduate Scholarships.
- *2021*, University Medal.
- *2021*, Erin Brent Computer Science Prize.
- *2022*, Australian Government Research Training Program International Scholarship.

# 📖 Educations
- *2018.02 - 2021.12*, Bachelor of Advanced Computing (Research & Development).
- *2022.02 - 2025.12*, Doctor of Philosophy, School of Computing.

