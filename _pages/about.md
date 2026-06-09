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

I am currently seeking 2027 new-graduate full-time opportunities in *embodied AI* and *MLLM*, welcome to reach out to me via email or WeChat!

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

# <i class="fas fa-graduation-cap" style="color:#0f766e;"></i> Education

- *2023.09 - Present*, Ph.D. student, School of Artificial Intelligence, Beihang University
- *2021.09 - 2023.06*, M.Eng., School of Software, Beihang University
- *2017.09 - 2021.06*, B.Eng., School of Software, Beihang University

<span class='anchor' id='publications'></span>

<div style="display:flex; justify-content:space-between; align-items:baseline; gap:12px; flex-wrap:wrap;">
  <h1 style="margin:0;"><i class="fas fa-file-alt" style="color:#0f766e;"></i> Publications</h1>
  <span style="font-size:0.8em; font-style:italic; color:#666;">Equal-contribution authors are marked with *.</span>
</div>

<div class="pub-year-divider"><span>2026</span></div>
<div class="pub-year-group">

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech Report</div><img src='images/paper_robointerpp.png' alt="RoboInter++ teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**RoboInter++: A Holistic Intermediate Representation Suite for Robotic Manipulation and Embodied World Modeling**  
<strong>Ziqin Wang</strong>, Hao Li, Weijun Wang, Junhao Cai, Jia Zeng, Jiangmiao Pang, Yilun Chen, Si Liu  
*Technical Report*  

</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/paper_robointer.png' alt="RoboInter teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**RoboInter: A Holistic Intermediate Representation Suite Towards Robotic Manipulation**  
<strong>Ziqin Wang* </strong>, Hao Li* , Zi-han Ding, Shuai Yang, Yilun Chen, Yang Tian, Xiaolin Hu, Tai Wang, Dahua Lin, Feng Zhao, Si Liu, Jiangmiao Pang  
*ICLR 2026*  

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/paper_cope.png' alt="LLaVA-CMoE teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**LLaVA-CMoE: Towards Continual Mixture of Experts for Large Vision-Language Models**  
<strong>Ziqin Wang* </strong>, <strong>Hengyuan Zhao* </strong> , Qixin Sun, Kaiyou Song, Yilin Li, Xiaolin Hu, Qingpei Guo, Si Liu  
*ICML, 2026*  

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/paper_vaccinerag.png' alt="VaccineRAG teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**VaccineRAG: Boosting Multimodal Large Language Models' Immunity to Harmful RAG Samples**  
Qixin Sun*, <strong>Ziqin Wang* </strong>, Hengyuan Zhao*, Yilin Li, Kaiyou Song, Linjiang Huang, Xiaolin Hu, Qingpei Guo, Si Liu  
*AAAI 2026*  

</div>
</div>
</div>

<div class="pub-year-divider"><span>2025</span></div>
<div class="pub-year-group">

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech Report</div><img src='images/paper_internvlam1.png' alt="InternVLA-M1 teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**InternVLA-M1: A Spatially Guided Vision-Language-Action Framework for Generalist Robot Policy**  
InternVLA-M1 Team  
*Technical Report, 2025*  

</div>

</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/paper_openuav.png' alt="OpenUAV teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Towards Realistic UAV Vision-Language Navigation: Platform, Benchmark, and Methodology**  
Xiangyu Wang* , <strong>Ziqin Wang* </strong>, Donglin Yang* ,  Hohin Kwan, Jinyu Chen, Wenjun Wu, Hongsheng Li, Yue Liao, Si Liu  
*ICLR 2025*  

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='images/paper_airstar.png' alt="AirStar teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**UAVClaw: Hi AirStar, Guide Me to the Badminton Court.**  
<strong>Ziqin Wang</strong>, Jinyu Chen, Xiangyi Zheng, Qinan Liao, Linjiang Huang, Si Liu  
*ACM MM 2025*  

</div>
</div>
</div>

<div class="pub-year-divider"><span>2024</span></div>
<div class="pub-year-group">

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024 Spotlight</div><img src='images/paper_coohoi.png' alt="CooHOI teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**CooHOI: Learning Cooperative Human-Object Interaction with Manipulated Object Dynamics**  
<strong>Ziqin Wang* </strong>, Jiawei Gao* , Zeqi Xiao, Jingbo Wang, Tai Wang, Jinkun Cao, Xiaolin Hu, Si Liu, Jifeng Dai, Jiangmiao Pang  
*NeurIPS 2024, Spotlight*  

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/paper_asyncdriver.png' alt="AsyncDriver teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Asynchronous Large Language Model Enhanced Planner for Autonomous Driving**  
Yuan Chen* , Zi-han Ding* , <strong>Ziqin Wang* </strong>, Yan Wang, Lijun Zhang, Si Liu  
*ECCV 2024*  

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/paper_octavius.png' alt="Octavius teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Octavius: Mitigating Task Interference in MLLMs via LoRA-MoE**  
<strong>Zeren Chen* </strong>, <strong>Ziqin Wang* </strong>, Zhen Wang, Huayang Liu, Zhenfei Yin, Si Liu, Lu Sheng, Wanli Ouyang, Yu Qiao, Jing Shao  
*ICLR 2024*  

</div>
</div>
</div>

<div class="pub-year-divider"><span>2023</span></div>
<div class="pub-year-group">

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023 Highlight</div><img src='images/paper_vlsat.png' alt="VL-SAT teaser" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**VL-SAT: Visual-Linguistic Semantics Assisted Training for 3D Semantic Scene Graph Prediction in Point Cloud**  
<strong>Ziqin Wang</strong>, Bowen Cheng, Lichen Zhao, Dong Xu, Yang Tang, Lu Sheng  
*CVPR 2023, Highlight*  

</div>
</div>
</div>

<span class='anchor' id='experience'></span>

# <i class="fas fa-briefcase" style="color:#0f766e;"></i> Research and Industry Experience

<div class="experience-list">
  <div class="experience-item">
    <div class="experience-item-head">
      <strong>Shanghai AI Laboratory</strong>
      <span>*Research Intern, 2024.06 - 2026.06*</span>
    </div>
    <p>Worked on multi-agent collaboration, robotic manipulation, embodied world models, and VLA systems. Contributed to InternVLA-M1, RoboInter, and RoboInter++ related projects, including a co-first-author NeurIPS Spotlight paper.</p>
  </div>

  <div class="experience-item">
    <div class="experience-item-head">
      <strong>NIO</strong>
      <span>*Research Intern, 2023.09 - 2024.05*</span>
    </div>
    <p>Worked on point-cloud perception foundation models for autonomous driving and improved cone detection recall while optimizing inference speed for deployment.</p>
  </div>

  <div class="experience-item">
    <div class="experience-item-head">
      <strong>SenseTime OpenGVLab</strong>
      <span>*Research Intern, 2022.05 - 2023.09*</span>
    </div>
    <p>Participated in InternVL pretraining and CLIP reproduction and optimization, and explored multimodal large models with mixture-of-experts architectures.</p>
  </div>

  <div class="experience-item">
    <div class="experience-item-head">
      <strong>SenseTime</strong>
      <span>*Algorithm Intern, 2021.05 - 2022.05*</span>
    </div>
    <p>Worked on liveness detection algorithms, covering data collection, model iteration, and practical system improvement for real-world deployment.</p>
  </div>
</div>

<span class='anchor' id='projects'></span>

# <i class="fas fa-rocket" style="color:#0f766e;"></i> Projects

<div class='paper-box compact-card'><div class='paper-box-image'><div><img src='images/project_airstar.png' alt="AirStar visual" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**AirStar**  
*LLM-Agent UAV Assistant*  
An LLM-agent-based UAV assistant system that integrates skill selection and tool calling to support campus navigation, photo capture, following, and visual question answering for UAVs.

[Code](https://github.com/wz7in/airstar) | [Project Page](https://buaa-colalab.github.io/airstar.github.io/)

</div>
</div>

<div class='paper-box compact-card'><div class='paper-box-image'><div><img src='images/project_scholarmind.png' alt="ScholarMind visual" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**ScholarMind**  
*Research Productivity Tool*  
An intelligent tool for improving research reading efficiency, including paper crawling, content analysis, report generation, and research idea summarization.

[Code](https://github.com/wz7in/ScholarMind?tab=readme-ov-file)

</div>
</div>

<span class='anchor' id='honors'></span>

# <i class="fas fa-award" style="color:#0f766e;"></i> Honors and Awards

<ul class="honors-list">
  <li>Second Place Award (2/62), <strong>RoCo Challenge @ AAAI 2026: Robotic Collaborative Assembling for Human-Centered Manufacturing</strong>, Team Leader</li>
  <li>Grand Prize, Beihang "Feng Ru Cup" Creativity Track</li>
  <li>Ranked 7/180 during undergraduate study</li>
  <li>First-Place Academic Scholarship, Beihang University</li>
  <li>First-Class Scholarship for Ph.D. Freshmen, Beihang University</li>
</ul>

<span class='anchor' id='service'></span>

# <i class="fas fa-users" style="color:#0f766e;"></i> Academic Service
- Reviewer for CVPR, ICCV, ECCV, ICLR, NeurIPS, ICML, and ACM MM

<span class='anchor' id='links'></span>

# <i class="fas fa-link" style="color:#0f766e;"></i> Links
- Email: [wzqin@buaa.edu.cn](mailto:wzqin@buaa.edu.cn)
- WeChat: `wzqinTT`
