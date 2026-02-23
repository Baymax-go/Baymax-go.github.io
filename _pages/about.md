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

I am a PhD student in Control Science and Engineering at Shanghai Jiao Tong University (SJTU), supervised by Prof. [Yue Gao](https://gaoyue.sjtu.edu.cn/).
Currently, I am conducting researches on Embodied AI at [Shanghai Innovation Institute](https://www.sii.edu.cn/) and [MoE key lab of Artificial Intelligence](https://ailab-moe.sjtu.edu.cn/).
Previously, I received my bachelor's degree in Measurement and Control Technology from Jilin University. 

My research interest includes: Vision-Language-Action (VLA), World Model, RL Post-training, Robust Whole-body control for humanoid robots; 

I am a **final-year PhD candidate** at SJTU, expected to **graduate in June 2027**. Currently, I am actively **seeking research internships or jobs about Embodied AI.**



# 📝 Publications 

<!-- Keep on Going SA2RT -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026 Oral</div><img src='images/keep_on_going.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Keep on Going: Learning Robust Humanoid Motion Skills via Selective Adversarial Training](https://arxiv.org/abs/2507.08303)

**Yang Zhang**, Zhanxiang Cao, Buqing Nie, Haoyang Li, Zhong Jiangwei, Qiao Sun, Xiaoyi Hu, Xiaokang Yang, Yue Gao.  [Paper](https://arxiv.org/abs/2507.08303)
- Selective adversarial attack for the humanoid robot.
- Identify vulnerability and improve robustness.
- Improve long horizon mobility and tracking performance on real robot.
</div>
</div>


<!-- FocusNav -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/focusnav.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FocusNav: Spatial Selective Attention with Waypoint Guidance for Humanoid Local Navigation](https://arxiv.org/abs/2601.12790)

**Yang Zhang**, Jianming Ma, Liyun Yan, Zhanxiang Cao, and Yue Gao.  [Paper](https://arxiv.org/abs/2601.12790)
- Propose spatial selective attention navigation framework.
- Design waypoint-guided and stability-aware modules.
- Improve humanoid robot navigation robustness.
</div>
</div>


<!-- Lipsnet policy -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L 2024</div><img src='images/lipsnet_policy.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Robust Locomotion Policy with Adaptive Lipschitz Constraint for Legged Robots](https://ieeexplore.ieee.org/document/10767293/)

**Yang Zhang**, Buqing Nie, and Yue Gao.  [Paper](https://ieeexplore.ieee.org/document/10767293/)
- Induce adaptive Lipschitz constraint for quadruped locomotion tasks.
- Action smooth, lower energy cost, robust to obs. noise and disturbances.
</div>
</div>


<!-- SE-Policy -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/SE-Policy.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Coordinated Humanoid Robot Locomotion with Symmetry Equivariant Reinforcement Learning Policy](https://arxiv.org/abs/2508.01247)

Buqing Nie, **Yang Zhang**, Rongjun Jin, Zhanxiang Cao, Huangxuan Lin, Xiaokang Yang, Yue Gao. [Paper](https://arxiv.org/abs/2508.01247)
- DRL-based humanoid robot policy with strict symmetry equivariance.
- Simple to implement without additional hyper-parameters.
- Higher tracking accuracy with coordinated motions.
</div>
</div>



<!-- Fault-Tolerant -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CoRL 2025</div><img src='images/fault_tolerant.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Contrastive Forward Prediction Reinforcement Learning for Adaptive Fault-Tolerant Legged Robots](https://proceedings.mlr.press/v305/fu25b.html)

Yangqing Fu, **Yang Zhang**, Qiyue Yang, Liyun Yan, Zhanxiang Cao, Yue Gao. [Paper](https://proceedings.mlr.press/v305/fu25b.html)
- Propose contrastive forward prediction RL framework.
- Enhance legged robot fault tolerance via error feedback.
- Achieve zero-shot adaptation to unseen joint damages.
</div>
</div>

- ``ICRA 2026`` [Disturbance-Aware Adaptive Compensation in Hybrid Force-Position Locomotion Policy for Legged Robots](https://arxiv.org/abs/2506.00472), **Yang Zhang**, Buqing Nie, Zhanxiang Cao, Yangqing Fu, Yue Gao.
- ``ROBIO 2022`` [Parameters identification of whole body dynamics for hexapod robot](https://ieeexplore.ieee.org/document/10011865), **Yang Zhang**, Yue Gao, Ming Sun.
- ``ICRA 2026`` [Learning Motion Skills with Adaptive Assistive Curriculum Force in Humanoid Robots](https://arxiv.org/abs/2506.23125). Zhanxiang Cao, **Yang Zhang**, Buqing Nie, Huangxuan Lin, Haoyang Li, Yue Gao.
- ``IROS 2025`` [Minimizing Acoustic Noise: Enhancing Quiet Locomotion for Quadruped Robots in Indoor Applications](https://arxiv.org/abs/2506.23114), Zhanxiang Cao, Buqing Nie, **Yang Zhang**, Yue Gao.
- ``RCAR 2024`` [Learning Capability to Enhance Locomotion Control and Planning for Legged Robots](https://ieeexplore.ieee.org/abstract/document/10671189), Yue Gao, Changda Tian, **Yang Zhang**.

# 📖 Educations
- *2022.09 - 2027.06*, PhD Candidate (direct-entry PhD program), Control Science and Engineering, School of Automation and Perception, Shanghai Jiao Tong University.
- *2018.09 - 2022.06*, Bachelor, Measurement and Control Technology (Honor class), School of Instrument Science and Electrical Engineering, Jilin University.

# 💻 Academic Services
<span class='anchor' id='academic-services'></span>
- I serve as a reviewer for AI/robotics conferences/journals, including AAAI 2026, ICRA 2026, IROS 2025, RA-L, etc.

# 🎖 Honors and Awards
- *2019-2021* Awarded the National Scholarship
