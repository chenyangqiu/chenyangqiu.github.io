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

I am now a Research Assistant working with Prof. [Zongli Lin](https://scholar.google.com/citations?user=n4fG76YAAAAJ&hl=en) at [University of Virginia](https://www.virginia.edu/). I got my master's degree from [ShanghaiTech University](https://www.shanghaitech.edu.cn/eng/), advised by Prof. [Jie Lu](https://scholar.google.se/citations?user=ShCBK4oAAAAJ&hl=en). Before that, I received my bachelor's degree from [Shandong University](https://www.en.sdu.edu.cn/).

I have a broad interest in optimization problems and network-related issues, and I aim to combine theoretical research with practical applications. I have published several papers and am currently engaged in related research projects. Additionally, I have been invited to serve as a reviewer for academic conferences and journals. 

My long-term research interest includes:

- Optimization
- Distributed learning/Federated learning
- Multiagent systems and decision-making

<!-- <div style="color: red;">
    I'm actively applying for Ph.D. positions in related field in 2025 Spring and Fall. Feel free to email me for academic cooperations or potential interviews.
 </div> --> 

# 🔥 News
- _2024.11_: &nbsp;🎉🎉 “Distributed optimization for the trade-off between state-of-charge balancing and strategic battery usage in a networked BESS” was accepted by [Journal of Energy Storage](https://www.sciencedirect.com/journal/journal-of-energy-storage)!.
- _2024.07_: &nbsp;🎉🎉 “Distributed Task Offloading in Cooperative Mobile Edge Computing Networks” was accepted by [IEEE Transactions on Vehicular Technology](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10423182)!.
- _2024.03_: &nbsp;🎉🎉 “A Mixing-Accelerated Primal-Dual Proximal Algorithm for Distributed Nonconvex Optimization” was accepted by [ACC 2024](https://doi.org/10.48550/arXiv.2304.02830)!.
- _2023.08_: &nbsp;🎉🎉 Chenyang served as Research Assistant in [University of Virginia](https://www.virginia.edu/)!.
- _2023.02_: &nbsp;🎉🎉 “A Stochastic Second-Order Proximal Method for Distributed Optimization” was accepted by [IEEE Control Systems Letters](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10044149)!.

# 📝 Publications and In Preparation

<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">IEEE Transactions on Vehicular Technology, 2024</div><img src='images/Pub1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Distributed Task Offloading in Cooperative Mobile Edge Computing Networks](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10423182)

Dandan Wang, Hongbin Zhu, **Chenyang Qiu**, Yong Zhou, Jie Lu
<br>
<span class='show_paper_citations' data='bGAj1sgAAAAJ:2osOgNQ5qMEC'></span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACC, 2024</div><img src='images/Pub2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mixing-accelerated Primal-dual Proximal Algorithm for Distributed Nonconvex Optimization](https://arxiv.org/pdf/2304.02830)

Zichong Ou, **Chenyang Qiu**, Jie Lu

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE Control Systems Letters, 2023</div><img src='images/Pub3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Stochastic Second-Order Proximal Method for Distributed Optimization](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10044149)

**Chenyang Qiu**, Shanying Zhu, Zichong Ou, Jie Lu

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal of Energy Storage, 2025</div><img src='images/sketch map 3-1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Distributed optimization for the trade-off between state-of-charge balancing and strategic battery usage in a networked BESS](https://www.sciencedirect.com/science/article/pii/S2352152X24041367)

**Chenyang Qiu**, Yangyang Qian, Zongli Lin, Yacov A. Shamash

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE Transactions on Automatic Control,<br> accepted, 2025 (second round)</div></div></div>
<div class='paper-box-text' markdown="1">

New Conditions and Controllers for State-of-Charge Balancing in Battery Energy Storage Systems

Yangyang Qian, **Chenyang Qiu**, Zongli Lin, Yacov A. Shamash

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">In Preparation</div></div></div>
<div class='paper-box-text' markdown="1">

Accelerated Distributed Algorithms for Resource Allocation

**Chenyang Qiu**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">In Preparation</div></div></div>
<div class='paper-box-text' markdown="1">

A Variance-Reduced Second-Order Proximal Method for Distributed Stochastic Optimization

**Chenyang Qiu**, Shanying Zhu, Zichong Ou, Jie Lu

</div>
</div>

# 📖 Educations

- _2020.09 - 2023.06_, MSc, **ShanghaiTech University** (Co-Founded by the Chinese Academy of Sciences), Communication and Information Systems
- _2016.09 - 2020.06_, Bachelor, **Shandong University**, Control Science and Technology (Elite Experimental Class for Talents)

# 📝 Research Project

- (2020.09 - 2023.06) **Distributed Second-Order Algorithms for Large-Scale Stochastic Optimization**

  - Stochastic second-order proximal algorithm:

    The first stochastic second-order method for addressing smooth, restricted strongly convex optimization over undirected networks which linearly converges to the suboptimum in expectation.

  - Variance-reduced second-order proximal algorithm:

    An exact distributed second-order stochastic algorithm with variance-reduced methods algorithm which linearly converges to the exact optimum in expectation.

- (2021.09 – 2023.06) **Distributed Mixing-Accelerated Algorithm for Nonconvex Optimization**

  - A distributed mixing-accelerated primal-dual proximal algorithm for distributed nonconvex smooth optimization which sublinearly converges to the stationary solution with general nonconvex assumption
    and linearly converges to the optimal solution with P-Ł condition.

- (2023.09 – Now) **Distributed Battery Energy Storage Systems**

  - Trade-off strategy between the usage preference of battery and state-of-charge (SoC) balancing:

    A novel optimization problem formulation that considers the trade-off between the usage preference of battery units and SoC balancing and reformulated it into a distributed optimization problem by estimating a certain global variable.

  - Fast SoC balancing algorithm:

    A novel sufficient condition on the power of each battery for achieving SoC balancing of the battery network; A new power allocating controllers such that accelerated SoC balancing is achieved.

- (2024.04 – Now) **Distributed Accelerated algorithm for Resource Allocation**
  - An accelerated Lagrangian-based algorithm solving the dual problem of the resource allocation problem which converges to the optimal solution with the strongly convex assumption at a nonergodic $O(1/k^2)$ rate.

# 🎖 Honors and Awards

- _2023_ Outstanding Graduate Student, ShanghaiTech University
- _2021 - 2022_ Merit Student, ShanghaiTech University
<!-- - _2019 – 2020_ Third Academic Scholarship, Shandong University -->
- _2019_ Advanced Individual in Social Practice, Shandong University 
- _2018 – 2019_ "Research and Innovation" Scholarship, Shandong University
- _2019_ First Prize in Engineering Robot Competition Fighting Robot Group, Jiangsu Province, China
- _2018_ Second Prize in Mathematical Contest in Modeling, Shandong Province, China
- _2018_ Second Prize in National Undergraduate Electronic Design Contest, Shandong Province, China



# 💻 Professional Service

External Reviewer:

- 2024 IEEE Conference on Decision and Control (CDC)
- 2024 American Control Conference (ACC)
- 2024 International Conference on Unmanned Aircraft Systems (ICUAS)
- Transactions of the Institute of Measurement and Control

<script type="text/javascript" id="mapmyvisitors" src="//mapmyvisitors.com/map.js?d=mlY8dMekd730lg6uKpYtv87fUU1atpiGYVSbMrq_ryY&cl=ffffff&w=a"></script>
