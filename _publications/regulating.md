---
title: "Regulating Intermediate 3D Features for Vision-Centric Autonomous Driving"
collection: publications
permalink: /publication/regulating
excerpt: '**Junkai Xu**, [Liang Peng](https://spengliang.github.io/), Haoran Cheng, Linxuan Xia, Qi Zhou, Dan Deng, Wei Qian, [Wenxiao Wang](https://www.wenxiaowang.com/), [Deng Cai](http://www.cad.zju.edu.cn/home/dengcai/)'
date: 2023-12-09
venue: '2024 AAAI Conference on Artificial Intelligence (AAAI)'
paperurl: 'https://arxiv.org/abs/2312.11837'
citation: "http://cskkxjk.github.io/files/bibtex/regulating.html"
code: 'https://github.com/cskkxjk/Vampire'
year: '2023'
---
![regulating](https://cskkxjk.github.io/images/publications/vampire.gif)
<b>Abstract:</b>
Multi-camera perception tasks have gained significant attention in the field of autonomous driving. However, existing frameworks based on Lift-Splat-Shoot (LSS) in the multi-camera setting cannot produce suitable dense 3D features due to the projection nature and uncontrollable densification process. To resolve this problem, we propose to regulate intermediate dense 3D features with the help of volume rendering. Specifically, we employ volume rendering to process the dense 3D features to obtain corresponding 2D features (e.g., depth maps, semantic maps), which are supervised by associated labels in the training. This manner regulates the generation of dense 3D features on the feature level, providing appropriate dense and unified features for multiple perception tasks. Therefore, our approach is termed Vampire, stands for "Volume rendering As Multi-camera Perception Intermediate feature REgulator". Experimental results on the Occ3D and nuScenes datasets demonstrate that Vampire facilitates fine-grained and appropriate extraction of dense 3D features, and is competitive with existing SOTA methods across diverse downstream perception tasks like 3D occupancy prediction, LiDAR segmentation and 3D objection detection, while utilizing moderate GPU resources. We provide a video demonstration in the supplementary materials and Codes are available at this http URL.

Recommended citation: 
```
@article{xu2023regulating,
      title={Regulating Intermediate 3D Features for Vision-Centric Autonomous Driving}, 
      author={Xu, Junkai and Peng, Liang and Cheng, Haoran and Xia, Linxuan and Zhou, Qi and Deng, Dan and Qian, Wei and Wang, Wenxiao and Cai, Deng},
      journal={arXiv preprint arXiv:2312.11837},
      year={2023},
}
```
