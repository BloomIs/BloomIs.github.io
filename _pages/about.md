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

I am currently a Master's student in Artificial Intelligence at Fudan University. Prior to this, I received my bachelor's degree in Data Science and Big Data Technology from Zhejiang University of Technology.

My research interests lie in multimodal large models, controllable image/video generation, and image/video restoration. I am particularly interested in building generation systems that preserve structural control, semantic consistency, and temporal stability in complex visual scenes.

I am currently a Multimodal Large Model Algorithm Intern at ByteDance, where I work on multimodal generation and restoration problems. Before that, I was a Multimodal Algorithm Intern at Meituan.

<span class='anchor' id='news'></span>

# News
- *2026.02*: I joined ByteDance as a Multimodal Large Model Algorithm Intern.
- *2025.10*: I joined Meituan as a Multimodal Algorithm Intern.
- *2024.09*: I started my M.S. in Artificial Intelligence at Fudan University.

<span class='anchor' id='publications'></span>

# Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Manuscript</div><img src='images/1.png' alt="Unified multimodal image inpainting" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Unified Multimodal Image Inpainting with Region-Aware Sketch Control**

**Runfeng Bao**

- Tackles the tension between structural controllability and visual consistency in sketch-guided image inpainting, where complex scenes often suffer from background drift and boundary discontinuities.
- Builds a unified text-sketch-mask inpainting framework with Region-Aware Sketch Control (RASC) for decoupled foreground/background guidance, and introduces FBTA/FBTA-fast to explicitly align background latent trajectories during diffusion sampling.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Ongoing Work</div><img src='images/2.png' alt="MLLM-guided video inpainting" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**MLLM-Guided Video Inpainting under Complex Occlusion**

**Runfeng Bao**

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
- *2026.02 - Present*, **ByteDance**, Multimodal Large Model Algorithm Intern.
- *2025.10 - 2026.01*, **Meituan**, Multimodal Algorithm Intern.
