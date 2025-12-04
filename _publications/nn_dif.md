---
title: "Nearest Neighbour Score Estimators for Diffusion Generative Models
"
collection: publications
permalink: /publication/nn_diff.md
date: 2024-07-16
venue: 'ICML-2024'
paperurl: 'https://arxiv.org/abs/2402.08018'
citation: 'Niedoba, Matthew, et al. "Nearest Neighbour Score Estimators for Diffusion Generative Models." '
---
Score function estimation is the cornerstone of both training and sampling from diffusion generative models. Despite this fact, the most commonly used estimators are either biased neural network approximations or high variance Monte Carlo estimators based on the conditional score. We introduce a novel nearest neighbour score function estimator which utilizes multiple samples from the training set to dramatically decrease estimator variance. We leverage our low variance estimator in two compelling applications. Training consistency models with our estimator, we report a significant increase in both convergence speed and sample quality. In diffusion models, we show that our estimator can replace a learned network for probability-flow ODE integration, opening promising new avenues of future research.

[Download paper here](https://arxiv.org/pdf/2402.08018)

 ```   
@inproceedings{
niedoba2024nearest,
title={Nearest Neighbour Score Estimators for Diffusion Generative Models},
author={Matthew Niedoba and Dylan Green and Saeid Naderiparizi and Vasileios Lioutas and Jonathan Wilder Lavington and Xiaoxuan Liang and Yunpeng Liu and Ke Zhang and Setareh Dabiri and Adam Scibior and Berend Zwartsenberg and Frank Wood},
booktitle={Forty-first International Conference on Machine Learning},
year={2024},
url={https://openreview.net/forum?id=hqNz4LDuhn}
}
 ```
