---
title: TAIL 
subtitle: A Terrain-Aware Multi-Modal SLAM Dataset in Deformable Granular Environments  
# title: TAIL (Terrain-Aware Multi-Model) Datasets
# subtitle: A SLAM Datasets for Diverse Robots Traveling in Deformable, Granular Ground 
# subtitle: A terrain-aware SLAM dataset for multi-robot traveling
layout: page
# callouts: home_callouts
show_sidebar: false
hide_footer: false
hero_height: is-large
# hero_height: is-medium
# hero_height: is-normal 
hero_image: /img/travel3.gif

# hero_link_text: Sensor Suite
# hero_link: /system/system/
# hero_link_text2: Datasets
# hero_link2: /download/download/

---

# TAIL (**T**errain-**A**ware Mult**I**-Mode**L**) SLAM dataset

Terrain-aware perception holds the potential to improve the robustness and accuracy of autonomous robot navigation in unstructured environments, thereby facilitating effective off-road traversals. TAIL (**T**errain-**A**ware Mult**I**-Mode**L**) dataset is proposed to support research in navitation for traversing through **deformable, granular terrains** utilizing wheeled and legged robots. The overall goal of the TAIL dataset is to help developing SLAM techniques for different robot platforms in unstructured, deformable sandy terrains.
<!-- that lack textless cues. -->
<!-- that are commonly found in urban autonmous SLAM datasets. -->



### Main characteristics

- Recorded data are from multiple sensors, including a 3D LiDAR, a stereo frame camera, three ground-pointing RGB-D cameras, an IMU and an RTK-GPS device. Moreover, it provides kinematic parameters of both wheeled and quadruped robots within similar scenes while considering distinct motion characteristics. Detailed information is shown in [[Dataset System]](/system/).


- The data were collected on two beaches at the Double-Moon Bay, covering a wide scope of environmental perception data (surrounding and ground-pointing), terrain complexities (texture-less sandy soil, fine sand, coarse sand), and scene changes (illumination, moving objects, flowing sand). More related information is shown in [[Dataset Description]](/datasets/tail.md/).


- Several state-of-the-art (SOTA) SLAM algorithms are benchmarked using TAIL dataset and their performances are analyzed with the provided ground truth. 


- TAIL dataset and related resources would be released publicly on this website.



### News
<!-- Our work has been accepted by -->
<!-- The preprint version is available at arXiv. -->
<!-- Driver code and time synchronization of event cameras are now available -->
<!-- * 2024-03-05: Calibration results and rosbag are avaliable (Plan). 
* 2024-03-01: Dataset sequences released (Plan).  -->
* 2024-5-5: The [download links](/download/) are available.
* 2024-3-26: The [preprint](https://arxiv.org/abs/2403.16875) of our paper is aviliable on arxiv.
* 2024-3-25: Our dataset website is released.
* 2023-6-25: Our dataset begins.




### Publications

We would appreciate it if you use our dataset and cite our [paper](https://arxiv.org/abs/2403.16875). 
```
@article{tail2023yao,
  title={TAIL: A Terrain-Aware Multi-Modal SLAM Dataset for Robot Locomotion in Deformable Granular Environments},
  author={Yao, Chen and Ge, Yangtao and Shi, Guowei and Wang, Zirui and Yang, Ningbo and Zhu, zheng and Wei, Hexiang and Zhao, Yuntian and Wu, Jing and Jia, Zhenzhong},
  journal = {arXiv preprint arXiv:2403.16875},
  year = {2024}
}
```


## License 

This work is released under GPLv3 license. For commercial use, please contact [Chen Yao](mailto:yaoc@mail.sustech.edu.cn).