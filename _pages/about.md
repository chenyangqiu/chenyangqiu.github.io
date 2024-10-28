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

I am now a Research Assistant working with Prof. [Zongli Lin](https://scholar.google.com/citations?user=n4fG76YAAAAJ&hl=en) and Postdoc [Xiongnan He](https://scholar.google.com/citations?user=5eMfCQoAAAAJ&hl=en) at [University of Virginia](https://www.virginia.edu/). I got my master's degree from [ShanghaiTech University](https://www.shanghaitech.edu.cn/eng/), advised by Prof. [Jie Lu](https://scholar.google.se/citations?user=ShCBK4oAAAAJ&hl=en). Before that, I received my bachelor's degree from [Shandong University](https://www.en.sdu.edu.cn/).

I have published 7 papers and am still doing some related research project until now. My research interest includes:

* Distributed optimization
* Distributed learning
* Stochastic optimization

<div style="color: red;">
    I'm actively applying for Ph.D. positions in related field in 2025 Fall. Feel free to email me for academic cooperations or potential interviews.
</div>

# 🔥 News
- *2024.07*: &nbsp;🎉🎉 “Distributed Task Offloading in Cooperative Mobile Edge Computing Networks” was accepted by [IEEE Transactions on Vehicular Technology](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10423182)!. 
- *2024.03*: &nbsp;🎉🎉 “A Mixing-Accelerated Primal-Dual Proximal Algorithm for Distributed Nonconvex Optimization” was accepted by [ACC2024](https://doi.org/10.48550/arXiv.2304.02830)!.
- *2023.08*: &nbsp;🎉🎉 Chenyang served as Research Assistant in [University of Virginia](https://www.virginia.edu/)!.
- *2023.02*: &nbsp;🎉🎉 “A Stochastic Second-Order Proximal Method
for Distributed Optimization” was accepted by [IEEE](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10044149)!.

# 📝 Publications & In Preparation

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE Transactions on Vehicular Technology, 2024</div><img src='images/Pub1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Distributed Task Offloading in Cooperative Mobile Edge Computing Networks](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10423182)

Dandan Wang, Hongbin Zhu, **Chenyang Qiu**, Yong Zhou, Jie Lu

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACC2024</div><img src='images/Pub2.png' alt="sym" width="100%"></div></div>
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

<div class='paper-box'>
    <div class='paper-box-text' markdown="1">
        <div class="badge">Journal of Energy Storage, minor revision</div>
        
        [On the Trade-off Between SoC Balancing and Strategic Usage of Batteries in a BESS]
        
        **Chenyang Qiu**, Xiongnan He
    </div>
</div>


<div class='paper-box'>
    <div class='paper-box-text' markdown="1">
        <div class="badge">IEEE Transactions on Automatic Control, under review (second round)</div>
        
        [New Conditions and Controllers for State-of-Charge Balancing in Battery Energy Storage Systems]
        
        Yangyang Qian, **Chenyang Qiu**, Zongli Lin, Yacov A. Shamash
    </div>
</div>


<div class='paper-box'>
    <div class='paper-box-text' markdown="1">
        <div class="badge">In Preparation</div>
        
        [Accelerated Distributed Algorithms for Resource Allocation]
        
        **Chenyang Qiu**, Zhicheng Deng, Xiongnan He
    </div>
</div>


<div class='paper-box'>
    <div class='paper-box-text' markdown="1">
        <div class="badge">In Preparation</div>
        
        [A Variance-Reduced Second-Order Proximal Method for Distributed Stochastic Optimization]
        
        **Chenyang Qiu**, Shanying Zhu, Zichong Ou, Jie Lu
    </div>
</div>


# 📝 Research Project

- [Distributed Second-Order Algorithms for Large-Scale Stochastic Optimization](2020 September – Now)
- Stochastic second-order proximal algorithm:
The first stochastic second-order method for addressing smooth, restricted strongly convex optimization over undirected networks which linearly converges to the suboptimum in expectation.
- Variance-reduced second-order proximal algorithm:
An exact distributed second-order stochastic algorithm with variance-reduced methods algorithm which linearly converges to the exact optimum in expectation.

</div>
</div>

- [Distributed Mixing-Accelerated Algorithm for Nonconvex Optimization](2021 September – 2023 June)
- A distributed mixing-accelerated primal-dual proximal algorithm for distributed nonconvex smooth optimization which sublinearly converges to the stationary solution with general nonconvex assumption
and linearly converges to the optimal solution with P-Ł condition.

</div>
</div>

- [Distributed Battery Energy Storage Systems](2023 September – Now)
- Trade-off strategy between the usage preference of battery and state-of-charge (SoC) balancing:
A novel optimization problem formulation that considers the trade-off between the usage preference of battery units and SoC balancing and reformulated it into a distributed optimization problem by estimating a certain global variable.
- Fast SoC balancing algorithm:
A novel sufficient condition on the power of each battery for achieving SoC balancing of the battery network; A new power allocating controllers such that accelerated SoC balancing is achieved.

</div>
</div>

- [Distributed Accelerated algorithm for Resource Allocation](2024 April – Now)
- An accelerated Lagrangian-based algorithm solving the dual problem of the resource allocation problem which converges to the optimal solution with convex assumption at a nonergodic O(1/k) rate.

</div>
</div>

# 🎖 Honors and Awards
- *2023* Outstanding Student, ShanghaiTech University
- *2021 - 2022* Merit Student, ShanghaiTech University 
- *2019 – 2020* Third Academic Scholarship, Shandong University
- *2019* Advanced Individual in Social Practice, Shandong University
- *2018 – 2019* "Research and Innovation" Scholarship, Shandong University
- *2019* First Prize in Engineering Robot Competition Fighting Robot Group, Jiangsu Province, China
- *2018* Second Prize in Mathematical Contest in Modeling, Shandong Province, China
- *2018* Second Prize in National Undergraduate Electronic Design Contest, Shandong Province, China

# 📖 Educations

- *2020.09 - 2023.06*, MSc, **ShanghaiTech University**, Communication and Information Systems
- *2016.09 - 2020.06*, Bachelor, **Shanghai University**, Control Science and Technology

# 💻 Professional Service

External Reviewer:
- 2024 IEEE Conference on Decision and Control (CDC)
- 2024 American Control Conference (ACC)
- 2024 International Conference on Unmanned Aircraft Systems (ICUAS)
- Transactions of the Institute of Measurement and Control

<script type="text/javascript" id="mapmyvisitors" src="https://mapmyvisitors.com/map.js?d=DpZkNL3LsLmeQRxUKn0lTTI5TvgkpddDlnJpErWoftQ&cl=ffffff&w=a"></script>
