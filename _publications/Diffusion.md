---
title: "A Diffusion-Model of Joint Interactive Navigation"
collection: publications
permalink: /publication/Diffusion
date: 2023-06-15
venue: 'NuerIPS-2023'
paperurl: 'https://openreview.net/pdf?id=2yXExAl0FW'
citation: 'Niedoba, Matthew, et al. "A Diffusion-Model of Joint Interactive Navigation." NuerIPS 2023.'
---
Simulation of autonomous vehicle systems requires that simulated traffic participants exhibit diverse and realistic behaviors. The use of prerecorded real-world traffic scenarios in simulation ensures realism but the rarity of safety critical events makes large scale collection of driving scenarios expensive. In this paper, we present DJINN -- a diffusion based method of generating traffic scenarios. Our approach jointly diffuses the trajectories of all agents, conditioned on a flexible set of state observations from the past, present, or future. On popular trajectory forecasting datasets, we report state of the art performance on joint trajectory metrics. In addition, we demonstrate how DJINN flexibly enables direct test-time sampling from a variety of valuable conditional distributions including goal-based sampling, behavior-class sampling, and scenario editing.

[Download paper here](https://openreview.net/pdf?id=2yXExAl0FW)

 ```   
@inproceedings{
niedoba2023a,
title={A Diffusion-Model of Joint Interactive Navigation},
author={Matthew Niedoba and Jonathan Wilder Lavington and Yunpeng Liu and Vasileios Lioutas and Justice Sefas and Xiaoxuan Liang and Dylan Green and Setareh Dabiri and Berend Zwartsenberg and Adam Scibior and Frank Wood},
booktitle={Thirty-seventh Conference on Neural Information Processing Systems},
year={2023},
url={https://openreview.net/forum?id=2yXExAl0FW}
}
 ```