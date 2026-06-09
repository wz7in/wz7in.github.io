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

I am currently a Ph.D. student at the School of Artificial Intelligence, Beihang University, and a member of [CoLab](https://colalab.net/), advised by [Prof. Si Liu](https://scholar.google.com/citations?user=-QtVtNEAAAAJ&hl=en), with an expected graduation date of June 2027. I am also a research intern at Shanghai AI Laboratory, where I am supervised by [Prof. Jiangmiao Pang](https://oceanpang.github.io/) and [Prof. Jifeng Dai](https://jifengdai.org/). Prior to my Ph.D., I spent two years in the master's program at Beihang University under the supervision of [Prof. Lv Sheng](https://lucassheng.github.io/), and I received my B.Eng. from Beihang University.

My research interests lie in Robotics and Embodied AI, particularly Vision-Language-Action (VLA) models and World-Action-Model (WAM). I also have research interests and experience in multimodal large language models, reinforcement learning, and agent systems for UAVs and robots.

I am currently seeking 2027 new-graduate full-time opportunities in robotics and embodied AI, and I welcome inquiries regarding research collaborations and industry positions.

<span class='anchor' id='news'></span>

# 🔥 News

- 🔥 2026.06: *RoboInter++* was released as an extension of *RoboInter* toward embodied world modeling.
- 🎉 2026.05: *LLaVA-CMoE* was accepted to **ICML 2026**.
- 🔥 2026.02: Data, benchmarks, and models from *RoboInter* were open-sourced.
- 🎉 2026.02: As team leader, I led our team to the Second Place Award (2/62) in the **RoCo Challenge @ AAAI 2026: Robotic Collaborative Assembling for Human-Centered Manufacturing**.
- 🎉 2026.01: *RoboInter* was accepted to **ICLR 2026**.
- 🎉 2025.11: *VaccineRAG* was accepted to **AAAI 2026**.
- 🔥 2025.09: *InternVLA-M1* was released as a technical report.
- 🎉 2025.03: *AirStar* was accepted to **ACM MM 2025**.
- 🎉 2025.01: *OpenUAV* was accepted to **ICLR 2025**.
- 🎉 2024.09: *CooHOI* was accepted to **NeurIPS 2024** as a **Spotlight** paper.
-  2024.03: I joined **Shanghai AI Laboratory** as a research intern.
- 🎉 2024.01: **Octavius** was accepted to **ICLR 2024**.
-  2023.05: I joined **NIO** as a research intern.
- 🎉 2023.03: **VL-SAT** was accepted to **CVPR 2023** as a **Highlight** paper.
- 2021.09: I joined **Sensetime** as a research intern.

<span class='anchor' id='education'></span>

# <i class="fas fa-graduation-cap" style="color:#3b82f6;"></i> Education

- *2023.09 - Present*, Ph.D. student, School of Artificial Intelligence, Beihang University
- *2021.09 - 2023.06*, M.Eng., School of Software, Beihang University
- *2017.09 - 2021.06*, B.Eng., School of Software, Beihang University

<span class='anchor' id='publications'></span>

<div style="display:flex; justify-content:space-between; align-items:baseline; gap:12px; flex-wrap:wrap;">
  <h1 style="margin:0;"><i class="fas fa-file-alt" style="color:#14b8a6;"></i> Publications</h1>
  <span style="font-size:0.8em; font-style:italic; color:#666;">Equal-contribution authors are in bold.</span>
</div>

## 2026

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/paper_robointerpp.png' alt="RoboInter++ teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**RoboInter++: A Holistic Intermediate Representation Suite for Robotic Manipulation and Embodied World Modeling**  
<strong>Ziqin Wang</strong>, Hao Li, Weijun Wang, Junhao Cai, Jia Zeng, Jiangmiao Pang, Yilun Chen, Si Liu  
*Preprint*  
An extension of RoboInter toward embodied world modeling with dense intermediate representations and controllable long-horizon generation.

</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/paper_robointer.png' alt="RoboInter teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**RoboInter: A Holistic Intermediate Representation Suite Towards Robotic Manipulation**  
<strong>Ziqin Wang*</strong>, <strong>Hao Li* </strong>, Zi-han Ding, Shuai Yang, Yilun Chen, Yang Tian, Xiaolin Hu, Tai Wang, Dahua Lin, Feng Zhao, Si Liu, Jiangmiao Pang  
*ICLR 2026*  
An intermediate-representation suite for robotic manipulation, including data, tools, benchmarks, and VLA modeling components.

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/paper_cope.png' alt="LLaVA-CMoE teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**LLaVA-CMoE: Towards Continual Mixture of Experts for Large Vision-Language Models**  
Hengyuan Zhao, <strong>Ziqin Wang</strong>, Qixin Sun, Kaiyou Song, Yilin Li, Xiaolin Hu, Qingpei Guo, Si Liu  
*ICML, 2026*  
A continual mixture-of-experts framework for large vision-language models with strong retention and efficient parameter growth.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/paper_vaccinerag.png' alt="VaccineRAG teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**VaccineRAG: Boosting Multimodal Large Language Models' Immunity to Harmful RAG Samples**  
<strong>Qixin Sun*</strong>, <strong>Ziqin Wang*</strong>, <strong>Hengyuan Zhao*</strong>, Yilin Li, Kaiyou Song, Linjiang Huang, Xiaolin Hu, Qingpei Guo, Si Liu  
*AAAI 2026*  
A post-training and benchmark framework for improving the robustness of multimodal LLMs against harmful retrieved samples.

</div>
</div>

## 2025

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech Report</div><img src='images/paper_internvlam1.png' alt="InternVLA-M1 teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**InternVLA-M1: A Spatially Guided Vision-Language-Action Framework for Generalist Robot Policy**  
InternVLA-M1 Team  
*Technical Report, 2025*  
A spatially guided vision-language-action framework toward generalist robot policy learning.

</div>

</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/paper_openuav.png' alt="OpenUAV teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Towards Realistic UAV Vision-Language Navigation: Platform, Benchmark, and Methodology**  
<strong>Xiangyu Wang*</strong>, <strong>Ziqin Wang*</strong>, <strong>Donglin Yang*</strong>,  Hohin Kwan, Jinyu Chen, Wenjun Wu, Hongsheng Li, Yue Liao, Si Liu  
*ICLR 2025*  
A realistic UAV vision-language navigation platform and benchmark with collaborative large-small model planning.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='images/paper_airstar.png' alt="AirStar teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**UAVClaw: Hi AirStar, Guide Me to the Badminton Court.**  
<strong>Ziqin Wang</strong>, Jinyu Chen, Xiangyi Zheng, Qinan Liao, Linjiang Huang, Si Liu  
*ACM MM 2025*  
An agentic UAV assistant system that integrates LLM reasoning with low-level skills for embodied aerial interaction.

</div>
</div>

## 2024

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024 Spotlight</div><img src='images/paper_coohoi.png' alt="CooHOI teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**CooHOI: Learning Cooperative Human-Object Interaction with Manipulated Object Dynamics**  
<strong>Ziqin Wang*</strong>, <strong>Jiawei Gao*</strong>, Zeqi Xiao, Jingbo Wang, Tai Wang, Jinkun Cao, Xiaolin Hu, Si Liu, Jifeng Dai, Jiangmiao Pang  
*NeurIPS 2024, Spotlight*  
A cooperative embodied control framework that transfers single-agent priors to efficient multi-agent interaction learning.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/paper_asyncdriver.png' alt="AsyncDriver teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Asynchronous Large Language Model Enhanced Planner for Autonomous Driving**  
<strong>Yuan Chen*</strong>, <strong>Zi-han Ding*</strong>, <strong>Ziqin Wang*</strong>, Yan Wang, Lijun Zhang, Si Liu  
*ECCV 2024*  
An autonomous driving planner that decouples large-model reasoning from fast low-level planning for better deployment efficiency.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/paper_octavius.png' alt="Octavius teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Octavius: Mitigating Task Interference in MLLMs via LoRA-MoE**  
<strong>Zeren Chen*</strong>, <strong>Ziqin Wang*</strong>, Zhen Wang, Huayang Liu, Zhenfei Yin, Si Liu, Lu Sheng, Wanli Ouyang, Yu Qiao, Jing Shao  
*ICLR 2024*  
An early multimodal mixture-of-experts framework for mitigating interference across 2D and 3D tasks in multimodal large models.

</div>
</div>

## 2023

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023 Highlight</div><img src='images/paper_vlsat.png' alt="VL-SAT teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**VL-SAT: Visual-Linguistic Semantics Assisted Training for 3D Semantic Scene Graph Prediction in Point Cloud**  
<strong>Ziqin Wang</strong>, Bowen Cheng, Lichen Zhao, Dong Xu, Yang Tang, Lu Sheng  
*CVPR 2023, Highlight*  
A visual-linguistic training framework for improving long-tail and zero-shot semantic scene graph prediction in point clouds.

</div>
</div>

<span class='anchor' id='experience'></span>

# <i class="fas fa-briefcase" style="color:#f59e0b;"></i> Research and Industry Experience

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

# <i class="fas fa-rocket" style="color:#ef4444;"></i> Projects

### AirStar

An LLM-agent-based UAV assistant system. It integrates skill selection and tool calling to support campus navigation, photo capture, following, and visual question answering for UAVs.

### ScholarMind

An intelligent tool for improving research reading efficiency, including paper crawling, content analysis, report generation, and research idea summarization.

### UAV Planning with Large-Small Model Collaboration

A collaborative UAV navigation framework developed with the Chinese University of Hong Kong, where a large model handles multimodal understanding and a smaller model generates fine-grained trajectories.

<span class='anchor' id='honors'></span>

# <i class="fas fa-award" style="color:#eab308;"></i> Honors and Awards

- Second Place Award (2/62), **RoCo Challenge @ AAAI 2026: Robotic Collaborative Assembling for Human-Centered Manufacturing**, Team Leader
- Grand Prize, Beihang "Feng Ru Cup" Creativity Track
- Ranked 7/180 during undergraduate study
- First-Place Academic Scholarship, Beihang University
- First-Class Scholarship for Ph.D. Freshmen, Beihang University

<span class='anchor' id='service'></span>

# <i class="fas fa-users" style="color:#22c55e;"></i> Academic Service
- Reviewer for CVPR, ICCV, ECCV, ICLR, NeurIPS, ICML, and ACM MM

<span class='anchor' id='links'></span>

# <i class="fas fa-link" style="color:#06b6d4;"></i> Links
- Email: [wzqin@buaa.edu.cn](mailto:wzqin@buaa.edu.cn)
- WeChat: `wzqinTT`
