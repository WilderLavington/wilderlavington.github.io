---
title: "Vehicle Type Specific Waypoint Generation"
collection: publications
permalink: /publication/Vehicle-Type
date: 2022-12-22
venue: 'ICLR-2023'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9981421'
citation: 'Liu, Yunpeng, et al. "Vehicle Type Specific Waypoint Generation." IROS 2022.'
---
We develop a generic mechanism for generating vehicle-type specific sequences of waypoints from a probabilistic foundation model of driving behavior. Many foundation behavior models are trained on data that does not include vehicle information, which limits their utility in downstream applications such as planning. Our novel methodology conditionally specializes such a behavior predictive model to a vehicle-type by utilizing byproducts of the reinforcement learning algorithms used to produce vehicle specific controllers. We show how to compose a vehicle specific value function estimate with a generic probabilistic behavior model to generate vehicle-type specific waypoint sequences that are more likely to be physically plausible then their vehicle-agnostic counterparts.

[Download paper here](https://ieeexplore.ieee.org/abstract/document/9981421)

 ```   
@INPROCEEDINGS{9981421,
  author={Liu, Yunpeng and Lavington, Jonathan Wilder and Scibior, Adam and Wood, Frank},
  booktitle={2022 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)}, 
  title={Vehicle Type Specific Waypoint Generation}, 
  year={2022},
  volume={},
  number={},
  pages={12225-12230},
  keywords={Reinforcement learning;Predictive models;Probabilistic logic;Prediction algorithms;Data models;Behavioral sciences;Planning},
  doi={10.1109/IROS47612.2022.9981421}}
 ```