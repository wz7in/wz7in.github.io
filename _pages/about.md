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

I am currently a Ph.D. student at the School of Artificial Intelligence, Beihang University, advised by Prof. Si Liu, with an expected graduation date of June 2027. I am also a research intern at Shanghai AI Laboratory, where I am supervised by Prof. Jiangmiao Pang and Prof. Jifeng Dai. Prior to my Ph.D., I spent two years in the master's program at Beihang University under the supervision of Prof. Lv Sheng, and I received my B.Eng. from Beihang University.

My research interests lie in Robotics and Embodied AI, particularly Vision-Language-Action (VLA) models and World-Action-Model (WAM). I also have research interests and experience in multimodal large language models, reinforcement learning, and agent systems for UAVs and robots.

<span class='anchor' id='education'></span>

<span class='anchor' id='news'></span>

# <i class="fas fa-bullhorn"></i> News

- **2026.02**: **RoboInter** was accepted to **ICLR 2026**.
- **2026.01**: Our team won **Runner-up** in the **RoCo Challenge @ AAAI 2026**.
- **2025.09**: **InternVLA-M1** was released as a technical report.
- **2025.03**: Our work on realistic **UAV Vision-Language Navigation** continued to expand toward embodied aerial agents.
- **2024.06**: I joined **Shanghai AI Laboratory** as a research intern.
- **2024**: **CooHOI** was accepted to **NeurIPS 2024** as a **Spotlight** paper.
- **2023**: **VL-SAT** was accepted to **CVPR 2023** as a **Highlight** paper.

<span class='anchor' id='education'></span>

# <i class="fas fa-graduation-cap"></i> Education

- *2023.09 - Present*, Ph.D. student, School of Artificial Intelligence, Beihang University
- *2021.09 - 2023.06*, M.Eng., School of Software, Beihang University
- *2017.09 - 2021.06*, B.Eng., School of Software, Beihang University

<span class='anchor' id='publications'></span>

# <i class="fas fa-file-alt"></i> Selected Publications

## Technical Reports

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech Report</div><img src='images/paper_internvlam1.png' alt="InternVLA-M1 teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**InternVLA-M1: A Spatially Guided Vision-Language-Action Framework for Generalist Robot Policy**  
`InternVLA-M1 Team`  
*Technical Report*  
A spatially guided vision-language-action framework toward generalist robot policy learning.

</div>
</div>

## 2026

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/paper_robointer.png' alt="RoboInter teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**RoboInter: A Holistic Intermediate Representation Suite Towards Robotic Manipulation**  
`Ziqin Wang` et al.  
*ICLR 2026*  
An intermediate-representation suite for robotic manipulation, including data, tools, benchmarks, and VLA modeling components.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/paper_cope.png' alt="CoPE teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**CoPE: Continual Probe-guided Expansion for Large Vision-Language Models**  
`Ziqin Wang` et al.  
*ICML 2026*  
A parameter-efficient continual learning framework for large vision-language models based on adaptive expert expansion.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/paper_vaccinerag.png' alt="VaccineRAG teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**VaccineRAG: Boosting Multimodal Large Language Models' Immunity to Harmful RAG Samples**  
`Ziqin Wang` et al.  
*AAAI 2026*  
A post-training and benchmark framework for improving the robustness of multimodal LLMs against harmful retrieved samples.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PAMI Submission</div><img src='images/paper_robointerpp.png' alt="RoboInter++ teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**RoboInter++: A Holistic Intermediate Representation Suite for Robotic Manipulation and Embodied World Modeling**  
`Ziqin Wang` et al.  
*PAMI, under submission*  
An extension of RoboInter toward embodied world modeling with dense intermediate representations and controllable long-horizon generation.

</div>
</div>

## 2025

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/paper_openuav.png' alt="OpenUAV teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Towards Realistic UAV Vision-Language Navigation: Platform, Benchmark, and Methodology**  
`Ziqin Wang` et al.  
*ICLR 2025*  
A realistic UAV vision-language navigation platform and benchmark with collaborative large-small model planning.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='images/paper_airstar.png' alt="AirStar teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Hi AirStar, Guide Me to the Badminton Court.**  
`Ziqin Wang` et al.  
*ACM MM 2025*  
An agentic UAV assistant system that integrates LLM reasoning with low-level skills for embodied aerial interaction.

</div>
</div>

## 2024

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024 Spotlight</div><img src='images/paper_coohoi.png' alt="CooHOI teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**CooHOI: Learning Cooperative Human-Object Interaction with Manipulated Object Dynamics**  
`Ziqin Wang` et al.  
*NeurIPS 2024, Spotlight*  
A cooperative embodied control framework that transfers single-agent priors to efficient multi-agent interaction learning.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/paper_asyncdriver.png' alt="AsyncDriver teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Asynchronous Large Language Model Enhanced Planner for Autonomous Driving**  
`Ziqin Wang` et al.  
*ECCV 2024*  
An autonomous driving planner that decouples large-model reasoning from fast low-level planning for better deployment efficiency.

</div>
</div>

## 2023

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023 Highlight</div><img src='images/paper_vlsat.png' alt="VL-SAT teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**VL-SAT: Visual-Linguistic Semantics Assisted Training for 3D Semantic Scene Graph Prediction in Point Cloud**  
`Ziqin Wang` et al.  
*CVPR 2023, Highlight*  
A visual-linguistic training framework for improving long-tail and zero-shot semantic scene graph prediction in point clouds.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2023</div><img src='images/paper_octavius.png' alt="Octavius teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Octavius: Mitigating Task Interference in MLLMs via MoE**  
`Ziqin Wang` et al.  
*ICLR 2023*  
An early multimodal MoE architecture for mitigating interference across 2D and 3D tasks in multimodal large models.

</div>
</div>

<span class='anchor' id='experience'></span>

# <i class="fas fa-briefcase"></i> Research and Industry Experience

- *2024.06 - 2026.06*, Shanghai AI Laboratory
  - Worked on multi-agent collaboration, robotic manipulation, embodied world models, and VLA systems.
  - Co-first-author paper accepted to NeurIPS with Spotlight.
  - Deeply involved in InternVLA-M1, RoboInter, and RoboInter++ related projects.

- *2023.09 - 2024.05*, NIO
  - Worked on point-cloud perception foundation models.
  - Improved cone detection recall and optimized inference speed for deployment.

- *2022.05 - 2023.09*, SenseTime OpenGVLab
  - Participated in InternVL pretraining and CLIP reproduction/optimization.
  - Explored multimodal large models with mixture-of-experts architectures.

- *2021.05 - 2022.05*, SenseTime
  - Worked on core algorithm development for liveness detection, from data collection to iterative model improvement.

<span class='anchor' id='projects'></span>

# <i class="fas fa-rocket"></i> Projects

### AirStar

An LLM-agent-based UAV assistant system. It integrates skill selection and tool calling to support campus navigation, photo capture, following, and visual question answering for UAVs.

### ScholarMind

An intelligent tool for improving research reading efficiency, including paper crawling, content analysis, report generation, and research idea summarization.

### UAV Planning with Large-Small Model Collaboration

A collaborative UAV navigation framework developed with the Chinese University of Hong Kong, where a large model handles multimodal understanding and a smaller model generates fine-grained trajectories.

<span class='anchor' id='honors'></span>

# <i class="fas fa-award"></i> Honors and Awards

- Ranked 7/180 during undergraduate study
- Ranked 22/64 during Ph.D. study
- First-Class Scholarship for Ph.D. Freshmen, Beihang University
- Second-Class Academic Scholarship, Beihang University
- CVPR 2023 Highlight
- NeurIPS 2024 Spotlight
- Runner-up, AAAI 2026 RoCo Industrial Assembly Challenge
- Grand Prize, Beihang "Feng Ru Cup" Creativity Track

<span class='anchor' id='service'></span>

# <i class="fas fa-users"></i> Academic Service

- Reviewer for CVPR, ICCV, ECCV, ICLR, NeurIPS, and ACM MM
- Teaching assistant for courses including *Discrete Mathematics*, *Frontiers of Large Models*, and *Image Processing and Computer Vision*
