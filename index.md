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
- *2024.11*: Our paper on Adap-RPF is submitted to ICRA 2026!
- *2024.09*: Our paper on Follow-Bench is under review!

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

Under Review (ICRA 2026)

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