---
title: "Learning Occupancy for Monocular 3D Object Detection"
collection: publications
permalink: /publication/occm3d
excerpt: '[Liang Peng](https://spengliang.github.io/), **Junkai Xu**, Haoran Cheng, Zheng Yang, Xiaopei Wu, Wei Qian, Wenxiao Wang, Boxi Wu, [Deng Cai](http://www.cad.zju.edu.cn/home/dengcai/)'
date: 2023-05-25
venue: 'arxiv'
paperurl: 'https://arxiv.org/abs/2305.15694'
citation: 'http://cskkxjk.github.io/files/bibtex/occm3d.html'
code: 'https://github.com/SPengLiang/OccupancyM3D'
year: '2023'
---
![occm3d](https://cskkxjk.github.io/images/publication/occm3d.png)
<b>Abstract:</b>
Monocular 3D detection is a challenging task due to the lack of accurate 3D information. Existing approaches typically rely on geometry constraints and dense depth estimates to facilitate the learning, but often fail to fully exploit the benefits of three-dimensional feature extraction in frustum and 3D space. In this paper, we propose \textbf{OccupancyM3D}, a method of learning occupancy for monocular 3D detection. It directly learns occupancy in frustum and 3D space, leading to more discriminative and informative 3D features and representations. Specifically, by using synchronized raw sparse LiDAR point clouds, we define the space status and generate voxel-based occupancy labels. We formulate occupancy prediction as a simple classification problem and design associated occupancy losses. Resulting occupancy estimates are employed to enhance original frustum/3D features. As a result, experiments on KITTI and Waymo open datasets demonstrate that the proposed method achieves a new state of the art and surpasses other methods by a significant margin.

Recommended citation: 
```
@misc{peng2023learning,
      title={Learning Occupancy for Monocular 3D Object Detection}, 
      author={Peng, Liang and Xu, Junkai and Cheng, Haoran and Yang, Zheng and Wu, Xiaopei and Qian, Wei and Wang, Wenxiao and Wu, Boxi and Cai, Deng},
      year={2023},
      eprint={2305.15694},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
