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

Hi, I'm Qin Zhao, a first-year Ph.D. student at the School of Computer Science and Technology, Zhejiang University, co-supervised by [Prof. Bo Dai](https://scholar.google.com/citations?user=KNWTvgEAAAAJ&hl=en) and [Prof. Dahua Lin](https://scholar.google.com/citations?user=GMzzRRUAAAAJ&hl=en). 
<!-- I am also closely collaborating with [Dr. Junting Dong](https://jtdong.com/) at the Shanghai Artificial Intelligence Laboratory. -->

My long-term research goal is to develop general-purpose intelligence. Currently, I focus on World Models, which lie at the intersection of Generative AI and Embodied AI.


# 🔥 News
- *2025.06*: &nbsp;🎉🎉 Two papers: [GAS](https://humansensinglab.github.io/GAS/) and [SIGMAN](https://yyvhang.github.io/SIGMAN_3D/) get accepted to ICCV2025.
- *2025.05*: &nbsp;🎉🎉 Our paper: "TeleOpBench: A Simulator-Centric Benchmark for Dual-Arm Dexterous Teleoperation" has released on [arXiv](https://arxiv.org/abs/2505.12748). 

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">preprint</div><video src='videos/TeleOpbench.mp4' alt="TeleOpBench" style="max-width: 360px;" autoplay loop muted playsinline></video></div></div>
<div class='paper-box-text' markdown="1">

[TeleOpBench: A Simulator-Centric Benchmark for Dual-Arm Dexterous Teleoperation](https://gorgeous2002.github.io/TeleOpBench/)


**Qin Zhao <sup>\*</sup>**, Hangyu Li <sup>\*</sup>, Haoran Xu, Xinyu Jiang, Qingwei Ben, Feiyu Jia, Haoyu Zhao, Liang Xu, Jia Zeng, Hanqing Wang, Bo Dai, Junting Dong<sup>†</sup>, Jiangmiao Pang

<sup>\*</sup> Equal contribution. <sup>†</sup> Corresponding author.

[**[Project website]**](https://gorgeous2002.github.io/TeleOpBench/) 
[**[Paper]**](https://arxiv.org/pdf/2505.12748)
[**[Code]**](https://github.com/cyjdlhy/TeleOpBench)

<!-- We present TeleOpBench, the first standardized benchmark for dual-arm dexterous teleoperation. Our framework enables fair comparison of different control modalities (motion capture, VR, exoskeletons, vision-based) across 30 manipulation tasks. Strong sim-to-real correlation validates the benchmark's effectiveness for advancing robotic manipulation research. -->

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">preprint</div><video src='videos/SynthVerse.mp4' alt="SynthVerse" width="100%" autoplay loop muted playsinline></video></div></div>
<div class='paper-box-text' markdown="1">

[SynthVerse: A Large-Scale Diverse Synthetic Dataset for Point Tracking](https://arxiv.org/abs/2602.04441)


Weiguang Zhao <sup>\*</sup>, Haoran Xu <sup>\*</sup>, Xingyu Miao, **Qin Zhao**, Rui Zhang<sup>†</sup>, Kaizhu Huang<sup>†</sup>, Ning Gao, Peizhou Cao, Mingze Sun, Mulin Yu, Tao Lu, Linning Xu, Junting Dong<sup>†</sup><sup>‡</sup>, Jiangmiao Pang

<sup>\*</sup> Equal contribution. <sup>†</sup><sup>‡</sup> Corresponding author.

[**[Project page]**](https://weiguangzhao.github.io/SynthVerse/)
[**[Dataset]**](https://huggingface.co/datasets/InternRobotics/SynthVerse)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">preprint</div><video src='videos/Dense_prediction.mp4' alt="Dense Prediction" width="100%" autoplay loop muted playsinline></video></div></div>
<div class='paper-box-text' markdown="1">

[From Frames to Sequences: Temporally Consistent Human-Centric Dense Prediction](https://arxiv.org/abs/2602.01661)


Xingyu Miao, Junting Dong<sup>†</sup><sup>‡</sup>, **Qin Zhao**, Yuhang Yang, Junhao Chen, Yang Long<sup>†</sup>

<sup>†</sup> Corresponding authors. <sup>‡</sup> Project leader.

[**[Project page]**](https://xingy038.github.io/F2S/)
[**[Paper]**](https://arxiv.org/pdf/2602.01661)
[**[Code]**](https://github.com/xingy038/F2S)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><video src='videos/GAS.mp4' alt="GAS" width="100%" autoplay loop muted playsinline></video></div></div>
<div class='paper-box-text' markdown="1">

[GAS: Generative Avatar Synthesis from a Single Image](https://humansensinglab.github.io/GAS/)


Yixing Lu, Junting Dong<sup>†</sup>, Youngjoong Kwon, **Qin Zhao**, Bo Dai, Fernando De la Torre

<sup>†</sup> Corresponding author.

[**[Project page]**](https://humansensinglab.github.io/GAS/)
[**[Code]**](https://github.com/humansensinglab/gas)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><video src='videos/SIGMAN.mp4' alt="SIGMAN" width="100%" autoplay loop muted playsinline></video></div></div>
<div class='paper-box-text' markdown="1">

[SIGMAN: Scaling 3D Human Gaussian Generation with Millions of Assets](https://arxiv.org/abs/2504.06982)


Yuhang Yang <sup>\*</sup>, Fengqi Liu <sup>\*</sup>, Yixing Lu, **Qin Zhao**, Pingyu Wu, Zhai Wei<sup>†</sup>, Ran Yi, Yang Cao, Lizhuang Ma, Zheng-jun Zha, Junting Dong<sup>†</sup>

<sup>\*</sup> Equal contribution. <sup>†</sup> Corresponding authors.

[**[Project page]**](https://yyvhang.github.io/SIGMAN_3D/)
[**[Code]**](https://github.com/yyvhang/SIGMAN_release)

</div>
</div>

# 🎖 Honors and Awards
- *2025.06* Outstanding Graduate
- *2024.10, 2023.10, 2022.10* Second Class University Scholarship
- *2024.10, 2023.10* Outstanding Student Leader
- *2023.10* Enterprise Scholarship
- *2022.10* Outstanding Student

# 📖 Educations
- *2025.09 - present*, Zhejiang University, Ph.D candidate in Computer Science
- *2021.09 - 2025.06*, Xi'an Jiaotong University, Bachelor of Automation


# 💬 Academic Services
- *2025*, Reviewer for [CoRL 2025](https://www.corl.org/)

# 💻 Internships
- *2024.08 - 2026.03*, [Shanghai Artificial Intelligence Laboratory](https://www.shlab.org.cn/), Shanghai, China.