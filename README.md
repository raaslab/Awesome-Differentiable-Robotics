# Awesome Differentiable Optimization and Planning in Robotics [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This repo contains a curative list of **papers using Differentiable Optimization and Planning in Robotics**. Template from [Awesome-LLM-Robotics](https://github.com/GT-RIPL/Awesome-LLM-Robotics) <br>

#### Please feel free to send me [pull requests](https://github.com/raaslab/Awesome-Differentiable-Robotics/blob/main/how-to-PR.md) or [email](mailto:vishnuds-changetoat-umd--changetodot-changetoedu) to add papers! <br>

If you find this repository useful, please consider [citing](#citation) and STARing this list. Feel free to share this list with others!

---
## Overview

  - [Path Planning](#path-planning)
  - [State Estimation/Filters](#state-estimationfilters)
  - [Mapping](#mapping)
  - [Control](#control)
  - [Optimization](#optimization)
  - [Citation](#citation)

---
## Path Planning

* **D2CoPlan**: "D2CoPlan: A Differentiable Decentralized Planner for Multi-Robot Coverage", *ICRA 2023*. [[Paper](https://arxiv.org/pdf/2209.09292v1.pdf)]  [[Website](http://raaslab.org/projects/d2coplan.html)]

* **Calvin**: "Towards real-world navigation with deep differentiable planners", *CVPR 2022*. [[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Ishida_Towards_Real-World_Navigation_With_Deep_Differentiable_Planners_CVPR_2022_paper.pdf)] [[Blog](https://www.robots.ox.ac.uk/~vgg/blog/calvin-a-neural-network-that-can-learn-to-plan-and-navigate-unknown-environments.html)]  [[Code](https://github.com/shuishida/calvin)]

* **DiffStack**: "DiffStack: A Differentiable and Modular Control Stack for Autonomous Vehicles", *CoRL 2022*. [[Paper](https://openreview.net/forum?id=teEnA3L4aRe)]  [[Website](https://sites.google.com/view/diffstack)]  [[Code](https://github.com/NVlabs/diffstack)]

* **SPT**: "Differentiable Spatial Planning using Transformers", *ICLR 2021*. [[Paper](https://devendrachaplot.github.io/papers/icml21-spatial-planning-transformers.pdf)]  [[Website](https://devendrachaplot.github.io/projects/spatial-planning-transformers)]  [[Talk](https://www.youtube.com/watch?v=qwAwwgPju1A&feature=youtu.be)]

* **dGPMP2**: "Differentiable Gaussian Process Motion Planning", *ICRA 2020*. [[Paper](https://arxiv.org/abs/1907.09591)]  [[Code](https://github.com/mhmukadam/dgpmp2)]

* **Trajectron++**: "Trajectron++: Dynamically-Feasible Trajectory Forecasting With Heterogeneous Data", *ECCV 2020*. [[Paper](https://arxiv.org/abs/2001.03093)]  [[Code](https://github.com/StanfordASL/Trajectron-plus-plus)]

* **DAN**: "Differentiable Algorithm Networks for Composable Robot Learning", *RSS 2019*. [[Paper](https://arxiv.org/abs/1905.11602)]  [[Video](https://www.youtube.com/watch?v=4jcYlTSJF4Y&feature=youtu.be)]  [[Talk](https://youtu.be/A91AIgBuxxE?t=558)]

---
## State Estimation/Filters

* "How to Train Your Differentiable Filter", *AR 2021*. [[Paper](https://arxiv.org/abs/2012.14313v2)]  [[Code](https://github.com/akloss/differentiable_filters)]

* **DF-RNN**: "Particle Filter Recurrent Neural Networks", *AAAI 2020*. [[Paper](https://arxiv.org/pdf/1905.12885.pdf)]  [[Code](https://github.com/Yusufma03/pfrnns)]

* **PF-Net**: "Particle Filter Networks with Application to Visual Localization", *CoRL 2018*. [[Paper](http://proceedings.mlr.press/v87/karkus18a/karkus18a.pdf)]  [[Code](https://github.com/AdaCompNUS/pfnet)]

* **QMDP-Net**: "QMDP-Net: Deep Learning for Planning under Partial Observability", *NeurIPS 2017*. [[Paper](https://papers.nips.cc/paper/7055-qmdp-net-deep-learning-for-planning-under-partial-observability.pdf)]  [[Code](https://github.com/AdaCompNUS/qmdp-net)]

---
## Mapping

* **SLAM-Net**: "Differentiable SLAM-net: Learning Particle SLAM for Visual Navigation", *CVPR 2021*. [[Paper](https://arxiv.org/pdf/2105.07593.pdf)]  [[Website](https://sites.google.com/view/slamnet)]  [[Talk](https://www.youtube.com/watch?v=ugEKzydiXPY)]

* **DMN**: "Differentiable Mapping Networks: Learning Structured Map Representations for Sparse Visual Localization", *ICRA 2020*. [[Paper](https://arxiv.org/pdf/2005.09530.pdf)]  [[Website](https://sites.google.com/view/differentiable-mapping)]  [[Talk](https://www.youtube.com/watch?v=0p9snxxGicI)]

---
## Control

* "An End-to-End Differentiable Framework for Contact-Aware Robot Design", *RSS 2021*. [[Paper](https://people.csail.mit.edu/jiex/papers/DiffHand/paper.pdf)]  [[Website](http://diffhand.csail.mit.edu/)]  [[Code](https://github.com/eanswer/DiffHand)]

* **Deluca**: "Learning Constrained Adaptive Differentiable Predictive Control Policies With Guarantees", *DiffCVGP Workshop NeurIPS 2020*. [[Paper](https://arxiv.org/abs/2004.11184)]  [[Code](https://github.com/pnnl/deps_arXiv20204)]

* "Encoding Physical Constraints in Differentiable Newton-Euler Algorithm", *L4DC 2020*. [[Paper](https://arxiv.org/abs/2001.08861)]  [[Code](https://github.com/facebookresearch/differentiable-robot-model)]

---
## Optimization
Differentiable optimization-aided approaches

* "Learning to Sequence and Blend Robot Skills via Differentiable Optimization", *RAL 2022*. [[Paper](https://arxiv.org/abs/2206.00559)]  [[Code](https://github.com/NoemieJaquier/sequencing-blending/)]  [[Video](https://youtu.be/00NXvTpL-YU)]

* "Differentiable MPC for End-to-end Planning and Control", *NeurIPS 2018*. [[Paper](https://arxiv.org/abs/1810.13400)]  [[Code](https://github.com/locuslab/differentiable-mpc)]


----
## Citation
If you find this repository useful, please consider citing this list:
```
@misc{sharma2023differentiableroboticpaperslist,
    title = {Awesome Differentiable Optimization and Planning in Robotics},
    author = {Sharma, Vishnu Dutt and Tokekar, Pratap},
    journal = {GitHub repository},
    url = {https://github.com/raaslab/Awesome-Differentiable-Robotics},
    year = {2023},
}
```
