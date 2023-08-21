---
title: "MonoNeRD: NeRF-like Representations for Monocular 3D Object Detection"
collection: publications
permalink: /publication/mononerd
excerpt: '**Junkai Xu**, [Liang Peng](https://spengliang.github.io/), Haoran Cheng, Hao Li, Wei Qian, Ke Li, [Wenxiao Wang](https://www.wenxiaowang.com/), [Deng Cai](http://www.cad.zju.edu.cn/home/dengcai/)'
date: 2023-08-30
venue: '2023 IEEE/CVF International Conference on Computer Vision (ICCV)'
paperurl: 'https://arxiv.org/abs/2308.09421'
code: 'https://github.com/cskkxjk/MonoNeRD'
supplementary_materials: 'comming soon'
year: '2023'
---
![mononerd](https://cskkxjk.github.io/images/publications/mononerd.gif)
<b>Abstract:</b>
In the field of monocular 3D detection, it is common practice to utilize scene geometric clues to enhance the detector's performance. However, many existing works adopt these clues explicitly such as estimating a depth map and back-projecting it into 3D space. This explicit methodology induces sparsity in 3D representations due to the increased dimensionality from 2D to 3D, and leads to substantial information loss, especially for distant and occluded objects. To alleviate this issue, we propose MonoNeRD, a novel detection framework that can infer dense 3D geometry and occupancy. Specifically, we model scenes with Signed Distance Functions (SDF), facilitating the production of dense 3D representations. We treat these representations as Neural Radiance Fields (NeRF) and then employ volume rendering to recover RGB images and depth maps. To the best of our knowledge, this work is the first to introduce volume rendering for M3D, and demonstrates the potential of implicit reconstruction for image-based 3D perception. Extensive experiments conducted on the KITTI-3D benchmark and Waymo Open Dataset demonstrate the effectiveness of MonoNeRD. Codes are available at this https URL.

Recommended citation: 
```
@inproceedings{xu2023mononerd,
      title={MonoNeRD: NeRF-like Representations for Monocular 3D Object Detection},
      author={Xu, Junkai and Peng, Liang and Cheng, Haoran and Li, Hao and Qian, Wei and Li, Ke and Wang, WenXiao and Cai, Deng},
      year={2023},
      booktitle={ICCV},
}
```
