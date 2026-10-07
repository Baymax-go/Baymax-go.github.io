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

<!-- Rollback -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/Rollback.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Rollback: Experience Backtracking in World Models for Policy improvement](https://anonymous.4open.science/w/Rollback/)

Jiayi Luo, **Yang Zhang**.  [Paper](https://anonymous.4open.science/w/Rollback/)
- Revisit critical decisions through experience-backtracking tree search in world models.
- Derive action-level supervision from counterfactual outcomes without a learned value model.
- Achieve higher real-robot success rates and more stable policy improvement.
</div>
</div>


<!-- ActSafeGuard -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/ActSafeGuard.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ActSafeGuard: Differentiable and Training-Aligned Constraint Enforcement for Flow-Matching Policies](https://arxiv.org/pdf/2609.11697)

Jianming Ma, Rongjun Jin, Xiaxi Si, **Yang Zhang**, Yue Gao.  [Paper](https://arxiv.org/pdf/2609.11697)
- Enforce hard action constraints during policy training and inference.
- Enable boundary-aware learning through differentiable ray scaling.
- Achieve 100% step safety with competitive task success.
</div>
</div>


<!-- P3 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/P3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[P3: Probabilistic Policy Propagation for Stable VAE-Based Robot Learning](https://arxiv.org/pdf/2607.25541)

Liyun Yan, Jianming Ma, **Yang Zhang**, Shengcheng Fu, Yue Gao.  [Paper](https://arxiv.org/pdf/2607.25541)
- Propose distribution-aware PPO for stable VAE-based robot learning.
- Combine moment matching with sampling-based calibration under latent uncertainty.
- Improve data efficiency and accelerate convergence in humanoid parkour.
</div>
</div>


<!-- Global-Local -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L 2026</div><img src='images/global-local.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Global-Local Attention Decomposition for Terrain Encoding in Humanoid Perceptive Locomotion](https://arxiv.org/pdf/2606.00637)

Shengcheng Fu, **Yang Zhang**, Zhanxiang Cao, Liyun Yan, Yue Gao.  [Paper](https://arxiv.org/pdf/2606.00637)
- Decompose terrain attention into global context and local foothold geometry.
- Enable precise foothold selection and emergent terrain-aware navigation.
- Achieve zero-shot sim-to-real transfer using onboard LiDAR.
</div>
</div>


<!-- PolyFlow -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/PolyFlow.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PolyFlow: Safe and Efficient Polytope-Constrained Flow Matching with Constraint Embedding and Projection-free Update](https://arxiv.org/abs/2606.13400)

Jianming Ma, Qiyue Yang, **Yang Zhang**, Liyun Yan, Zhanxiang Cao, Yazhou Zhang, Yue Gao.  [Paper](https://arxiv.org/abs/2606.13400)
- Discrete-time flow matching with guaranteed zero constraint violation.
- Projection-free update via differentiable ray shooting boosts efficiency.
- Favorable trade-off across safety, fidelity and inference speed.
</div>
</div>


<!-- HiWET -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RSS 2026</div><img src='images/HiWET.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HiWET: Hierarchical World-Frame End-Effector Tracking for Long-Horizon Humanoid Loco-Manipulation](https://arxiv.org/abs/2602.06341)

Zhanxiang Cao, Liyun Yan, **Yang Zhang**, Sirui Chen, Jianming Ma, Tianyue Zhan, Shengcheng Fu, Yufei Jia, Cewu Lu, Yue Gao.  [Paper](https://arxiv.org/abs/2602.06341)
- HiWET enhances global end-effector tracking accuracy.
- KMP improves manipulation manifold consistency.
- Enhancing loco-manipulation performance in real humanoid robots.
</div>
</div>


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


<!-- Lipsnet policy -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L 2024</div><img src='images/lipsnet_policy.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Robust Locomotion Policy with Adaptive Lipschitz Constraint for Legged Robots](https://ieeexplore.ieee.org/document/10767293/)

**Yang Zhang**, Buqing Nie, and Yue Gao.  [Paper](https://ieeexplore.ieee.org/document/10767293/)
- Induce adaptive Lipschitz constraint for quadruped locomotion tasks.
- Action smooth, lower energy cost, robust to obs. noise and disturbances.
</div>
</div>



- ``ICRA 2026`` [Disturbance-Aware Adaptive Compensation in Hybrid Force-Position Locomotion Policy for Legged Robots](https://arxiv.org/abs/2506.00472), **Yang Zhang**, Buqing Nie, Zhanxiang Cao, Yangqing Fu, Yue Gao.
- ``ICRA 2026`` [Learning Motion Skills with Adaptive Assistive Curriculum Force in Humanoid Robots](https://arxiv.org/abs/2506.23125). Zhanxiang Cao, **Yang Zhang**, Buqing Nie, Huangxuan Lin, Haoyang Li, Yue Gao.
- ``IROS 2025`` [Minimizing Acoustic Noise: Enhancing Quiet Locomotion for Quadruped Robots in Indoor Applications](https://arxiv.org/abs/2506.23114), Zhanxiang Cao, Buqing Nie, **Yang Zhang**, Yue Gao.
- ``RCAR 2024`` [Learning Capability to Enhance Locomotion Control and Planning for Legged Robots](https://ieeexplore.ieee.org/abstract/document/10671189), Yue Gao, Changda Tian, **Yang Zhang**.
- ``ROBIO 2022`` [Parameters identification of whole body dynamics for hexapod robot](https://ieeexplore.ieee.org/document/10011865), **Yang Zhang**, Yue Gao, Ming Sun.
  
# 📖 Educations
- *2022.09 - 2027.06*, PhD Candidate, Control Science and Engineering, School of Automation and Perception, Shanghai Jiao Tong University.
- *2018.09 - 2022.06*, Bachelor, Measurement and Control Technology (Honor class), School of Instrument Science and Electrical Engineering, Jilin University.

# 💻 Academic Services
<span class='anchor' id='academic-services'></span>
- I serve as a reviewer for AI/robotics conferences/journals, including AAAI 2026, ICRA 2026, IROS 2025, RA-L, etc.

# 🎖 Honors and Awards
- *2019-2021* Awarded the National Scholarship
