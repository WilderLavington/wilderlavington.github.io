---
title: "Video Killed the HD-Map: Predicting Driving Behavior Directly From Drone Images"
collection: publications
permalink: /publication/Video-Killed
date: 2023-06-15
venue: 'IEEE-ITSC-2023'
paperurl: 'https://arxiv.org/abs/2305.11856'
citation: 'Liu, Yunpeng, et al. "Video Killed the HD-Map: Predicting Driving Behavior Directly From Drone Images" IEEE-ITSC 2023.'
---
The development of algorithms that learn behavioral driving models using human demonstrations has led to increasingly realistic simulations. In general, such models learn to jointly predict trajectories for all controlled agents by exploiting road context information such as drivable lanes obtained from manually annotated high-definition (HD) maps. Recent studies show that these models can greatly benefit from increasing the amount of human data available for training. However, the manual annotation of HD maps which is necessary for every new location puts a bottleneck on efficiently scaling up human traffic datasets. We propose a drone birdview image-based map (DBM) representation that requires minimal annotation and provides rich road context information. We evaluate multi-agent trajectory prediction using the DBM by incorporating it into a differentiable driving simulator as an image-texture-based differentiable rendering module. Our results demonstrate competitive multi-agent trajectory prediction performance when using our DBM representation as compared to models trained with rasterized HD maps.

[Download paper here](https://arxiv.org/abs/2305.11856)

 ```   
@misc{liu2023video,
      title={Video Killed the HD-Map: Predicting Multi-Agent Behavior Directly From Aerial Images}, 
      author={Yunpeng Liu and Vasileios Lioutas and Jonathan Wilder Lavington and Matthew Niedoba and Justice Sefas and Setareh Dabiri and Dylan Green and Xiaoxuan Liang and Berend Zwartsenberg and Adam Ścibior and Frank Wood},
      year={2023},
      eprint={2305.11856},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
 ```