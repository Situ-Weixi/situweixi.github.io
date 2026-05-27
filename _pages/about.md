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

I am a second-year Master's student at <a href="https://www.sustech.edu.cn/en/">Southern University of Science and Technology (SUSTech)</a>, working in the <a href="https://faculty.sustech.edu.cn/zhangh/en/">Robotics and Computer Vision Lab</a> under the supervision of <a href="https://faculty.sustech.edu.cn/zhangh/en/">Prof. Hong Zhang</a>. My research focuses on **Robot Person Following (RPF)** in dynamic and crowded environments, with particular interests in motion planning, trajectory optimization, and human-robot interaction.

My work aims to enable robots to naturally and safely follow people in complex real-world scenarios, addressing challenges such as occlusions, dynamic obstacles, and social navigation. I am passionate about developing practical solutions that bridge the gap between robotics research and real-world applications.

# 🔥 News
- *2026.05*: [Follow-Bench](https://github.com/MedlarTea/follow-bench) is now released.
- *2026.03*: 🥳🥳 [TPT-Bench](https://medlartea.github.io/tpt-bench/) is accepted by IJRR 2026.
- *2026.02*: 🥳🥳 [Adap-RPF](https://adap-rpf.github.io/) is accepted by ICRA 2026.
- *2025.10*: Check out our latest work, "[Adap-RPF: Adaptive Trajectory Sampling for Robot Person Following in Dynamic Crowded Environments](https://adap-rpf.github.io/)." This work adopts a *sample-evaluate-plan* paradigm with a multiple-objective cost function design and a prediction-aware MPPI controller, enabling smooth and safe person following in dynamic crowded environments.
- *2025.09*: Check out our latest work, "[Follow-Bench: A Unified Motion Planning Benchmark for Socially-Aware Robot Person Following](https://follow-bench.github.io/)." This work provides a comprehensive review of RPF scenarios, evaluation metrics, and planners, with a particular emphasis on requirements of safety and comfort.

# 📝 Publications 

<!-- adap-rpf -->
<div class='paper-box'>
<div class='paper-box-image'>
<a href="https://adap-rpf.github.io/">
    <video width="100%" autoplay loop muted playsinline>
    <source src="files/adap-rpf.mp4" type="video/mp4">
    Your browser does not support the video tag.
    </video>
</a>
</div>
<div class='paper-box-text' markdown="1">

**Adap-RPF: Adaptive Trajectory Sampling for Robot Person Following in Dynamic Crowded Environments**

<u>Weixi Situ</u>, Hanjing Ye, Jianwei Peng, Yu Zhan, Bingyi Xia, Kuanqi Cai, Hong Zhang

2026 IEEE International Conference on Robotics and Automation (ICRA)

[[site](https://adap-rpf.github.io/)]
</div>
</div>

<!-- follow-bench -->
<div class='paper-box'>
<div class='paper-box-image'>
<a href="https://follow-bench.github.io/">
    <video width="100%" autoplay loop muted playsinline>
    <source src="files/follow-bench-teaser-1080.mp4" type="video/mp4">
    Your browser does not support the video tag.
    </video>
</a>
</div>
<div class='paper-box-text' markdown="1">

**Follow-Bench: A Unified Motion Planning Benchmark for Socially-Aware Robot Person Following**

Hanjing Ye, <u>Weixi Situ</u>, Jianwei Peng, Yu Zhan, Bingyi Xia, Kuanqi Cai, Hong Zhang

Under Review

[[arXiv](https://arxiv.org/abs/2509.10796)] [[site](https://follow-bench.github.io/)] [[github](https://github.com/MedlarTea/follow-bench)]
</div>
</div>

<!-- tpt-bench -->
<div class='paper-box'><div class='paper-box-image'><a href="https://medlartea.github.io/tpt-bench/"><img src='files/tpt_bench.gif' alt="sym" width="100%"></a></div>
<div class='paper-box-text' markdown="1">

**TPT-Bench: A Large-Scale, Long-Term and Robot-Egocentric Dataset for Benchmarking Target Person Tracking**

Hanjing Ye, Yu Zhan, <u>Weixi Situ</u>, Guangcheng Chen, Jingwen Yu, Ziqi Zhao, Kuanqi Cai, Arash Ajoudani, Hong Zhang

2026 International Journal of Robotics Research (IJRR)

[[arXiv](http://arxiv.org/abs/2505.07446)] [[video](https://youtu.be/LLZT9cEa6K0)] [[site](https://medlartea.github.io/tpt-bench/)]
</div>
</div>

# 🎖 Honors and Awards
- *2024, 2025*: National Scholarship (Top 1%), Southern University of Science and Technology
- *2024*: Outstanding Undergraduate Graduate (Top 1%), South China Agricultural University
- *2023*: First Prize, Guangdong Provincial College Student Electronic Design Competition
- *2021, 2022*: National Scholarship, South China Agricultural University
- *2021*: Second Prize (Top 5%), National College Student Electronic Design Competition