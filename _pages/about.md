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

I am currently a second-year Master's student at the College of Computer Science and Artificial Intelligence, Fudan University.

My research interests lie in **Multi-modal large models(MLLM)** and **Controllable image/video generation**.

I am currently an Applied Research Intern at ByteDance, where I work on multimodal embedding models and post-training of multimodal large models.


<span class='anchor' id='news'></span>

# News
- *2026.02*: I joined ByteDance <img class="inline-logo bytedance-logo" src="images/ByteDance_logo_English.svg" alt="ByteDance logo"> as a Multimodal Large Model Algorithm Intern.
- *2025.10*: I joined Meituan <img class="inline-logo meituan-logo" src="images/meituan.png" alt="Meituan logo"> Intelligent Creation Team as a Research Intern.

<span class='anchor' id='publications'></span>

# Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Manuscript</div><img src='images/1.png' alt="Unified multimodal image inpainting" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Seamless Sketch-guided Image Inpainting via Flow-based Background Trajectory Alignment**

Lintao Zhang*, <strong>Runfeng Bao</strong>*, Quan Zhou, Xichen Ye, Xiangcheng Du, Yingbin Zheng, WEIZHONG ZHANG, Peizhu Gong, Cheng Jin

- Tackles the tension between structural controllability and visual consistency in sketch-guided image inpainting, where complex scenes often suffer from background drift and boundary discontinuities.
- Builds a unified text-sketch-mask inpainting framework with Region-Aware Sketch Control (RASC) for decoupled foreground/background guidance, and introduces FBTA/FBTA-fast to explicitly align background latent trajectories during diffusion sampling.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Ongoing Work</div><img src='images/2.png' alt="MLLM-guided video inpainting" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**SyncPainter: Caption-guided Video Inpainting with Multimodal Semantic Alignment**

**Runfeng Bao**,Yifan Wang,Chengmin Gao

- Studies the logical distortion problem of current state-of-the-art video inpainting models under complex occlusion, and explores an automated restoration paradigm guided by MLLMs.
- Develops Mask-Aware Dual-Path Attention (MAAF), which decouples generation and reference streams for precise semantic-background alignment, together with latent-space temporal propagation for flow-free feature transfer and flicker reduction.

</div>
</div>

<span class='anchor' id='educations'></span>

# Educations
- *2024.09 - 2027.06*, M.S. in Artificial Intelligence, Fudan University, Shanghai, China.
- *2020.10 - 2024.06*, B.E. in Data Science and Big Data Technology, Zhejiang University of Technology, Hangzhou, China.

<span class='anchor' id='internships'></span>

# Internships
- **ByteDance** <img class="internship-logo bytedance-logo" src="images/ByteDance_logo_English.svg" alt="ByteDance logo"><br>
  *2026.02 - Present*, Applied Research Intern, focusing on multimodal embedding models and post-training of multimodal large models.
- **Meituan** <img class="internship-logo meituan-logo" src="images/meituan.png" alt="Meituan logo"><br>
  *2025.10 - 2026.01*, Research Intern, Intelligent Creation Team, focusing on multimodal algorithms.
