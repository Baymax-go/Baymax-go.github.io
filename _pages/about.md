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


<!-- Be-JEPA -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/Be-JEPA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BeJEPA: A Goal-Conditioned Humanoid Behavior World Model via Unsupervised RL](https://ylyem9x.github.io/BeJEPA-project/)

Liyun Yan, Haoyang Li, **Yang Zhang**.  [Paper](https://arxiv.org/pdf/2610.23127)
- Learn a goal-conditioned behavior world model via unsupervised RL to jointly control humanoid posture, world position, and heading.
- Compose one-step dynamics with long-term successor prediction to guide policy improvement without long imagined rollouts.
- Reduce AMASS global tracking error by 61.7% over world-input BFM-Zero with online refinement, and demonstrate goal reaching and recovery on Unitree G1.
</div>
</div>



<!-- PartiGen -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/PartiGen.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PartiGen: Part-Aware Representations for Language-Conditioned Humanoid Motion Generation](https://arxiv.org/pdf/2610.13373)

Huang Chuxuan, Zhanxiang Cao, Tianyue Zhan, Haoyang Li, **Yang Zhang**.  [Paper](https://arxiv.org/pdf/2610.13373)
- Learn body-part-aware motion representations that combine local limb features with shared whole-body context.
- Generate language-conditioned humanoid motions through autoregressive latent diffusion, with kinematic supervision and frame-level endpoint prediction.
- Reduce segment-level FID by 16.8% over TextOp and demonstrate successful execution of 26/27 screened, manually selected motions on Unitree G1.
</div>
</div>




<!-- WorldOracle -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/WorldOracle.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[WorldOracle: Benchmarking Action-Conditioned World Models against Real-World Executions](https://worldoracle-benchmark.github.io/)

Haoyi Duan, Liliang Chen, Nan Wang, **Yang Zhang**.  [Paper](https://arxiv.org/pdf/2610.18826v1)
- Benchmark action-conditioned world models against real-world executions under identical initial observations and action sequences.
- Curate long-horizon trajectories across three embodiments, including successful and failed interactions.
- Evaluate physical correctness, spatial alignment, interaction-region fidelity, and multi-view action coherence.
</div>
</div>


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



<!-- HFPLP -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2026</div><img src='images/HFPLP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Disturbance-Aware Adaptive Compensation in Hybrid Force-Position Locomotion Policy for Legged Robots](https://arxiv.org/abs/2506.00472)

**Yang Zhang**, Buqing Nie, Zhanxiang Cao, Yangqing Fu, Yue Gao.  [Paper](https://arxiv.org/abs/2506.00472)
- Combine target joint positions and feedforward torques for robust legged locomotion.
- Estimate external disturbances and generate adaptive compensation torques.
- Enable a real quadruped to carry 20 kg payloads and recover more effectively from external impacts.
</div>
</div>


<!-- A2CF -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2026</div><img src='images/A2CF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Learning Motion Skills with Adaptive Assistive Curriculum Force in Humanoid Robots](https://arxiv.org/abs/2506.23125)

Zhanxiang Cao, **Yang Zhang**, Buqing Nie, Huangxuan Lin, Haoyang Li, Yue Gao. [Paper](https://arxiv.org/abs/2506.23125)
- Jointly train motion and assistive-force agents to accelerate humanoid skill learning.
- Gradually remove assistance through an adaptive force curriculum and random masking.
- Enable faster learning and deploy walking and dancing policies on real humanoids without external support.
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



<!-- LipsNet-policy -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L 2024</div><img src='images/LipsNet-Policy.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Robust Locomotion Policy with Adaptive Lipschitz Constraint for Legged Robots](https://ieeexplore.ieee.org/document/10767293/)

**Yang Zhang**, Buqing Nie, and Yue Gao.  [Paper](https://ieeexplore.ieee.org/document/10767293/)
- Constrain locomotion policy sensitivity through multi-dimensional gradient normalization to improve action smoothness and robustness to observation noise.
- Adapt local Lipschitz constants with a learned network to balance motion smoothness and responsiveness to terrain changes and external disturbances.
- Reduce joint power and improve velocity tracking, validated through zero-shot deployment on Unitree Go1 across challenging terrains.
</div>
</div>



<!-- MUTE -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2025</div><img src='images/MUTE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Minimizing Acoustic Noise: Enhancing Quiet Locomotion for Quadruped Robots in Indoor Applications](https://arxiv.org/abs/2506.23114)

Zhanxiang Cao, Buqing Nie, **Yang Zhang**, Yue Gao.  [Paper](https://arxiv.org/abs/2506.23114)
- Reduce foot-ground impact noise through phase-aware gait optimization.
- Introduce a tunable quiet factor to balance noise reduction and locomotion speed.
- Achieve approximately 8 dBA noise reduction on a real quadruped across indoor surfaces.
</div>
</div>


- ``RCAR 2024`` [Learning Capability to Enhance Locomotion Control and Planning for Legged Robots](https://ieeexplore.ieee.org/abstract/document/10671189), Yue Gao, Changda Tian, **Yang Zhang**.
- ``ROBIO 2022`` [Parameters identification of whole body dynamics for hexapod robot](https://ieeexplore.ieee.org/document/10011865), **Yang Zhang**, Yue Gao, Ming Sun.
  
# 📖 Educations
- *2022.09 - 2027.06*, PhD Candidate, Control Science and Engineering, School of Automation and Perception, Shanghai Jiao Tong University.
- *2018.09 - 2022.06*, Bachelor, Measurement and Control Technology (Honor class), School of Instrument Science and Electrical Engineering, Jilin University.

# 💻 Academic Services
<span class='anchor' id='academic-services'></span>
- I serve as a reviewer for AI/robotics conferences/journals, including ICLR, AAAI, ICRA, IROS, RA-L, etc.

# 🎖 Honors and Awards
- *2019-2021* Awarded the National Scholarship
