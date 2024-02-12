---
title: "Critic Sequential Monte Carlo"
collection: publications
permalink: /publication/Critic-SMC
date: 2023-02-01
venue: 'ICLR-2023'
paperurl: 'https://openreview.net/pdf?id=ObtGcyKmwna'
citation: 'Lioutas, Vasileios, et al. "Critic Sequential Monte Carlo." ICLR 2023.'
---
We introduce CriticSMC, a new algorithm for planning as inference built from a composition of sequential Monte Carlo with learned Soft-Q function heuristic factors. These heuristic factors, obtained from parametric approximations of the marginal likelihood ahead, more effectively guide SMC towards the desired target distribution, which is particularly helpful for planning in environments with hard constraints placed sparsely in time. Compared with previous work, we modify the placement of such heuristic factors, which allows us to cheaply propose and evaluate large numbers of putative action particles, greatly increasing inference and planning efficiency. CriticSMC is compatible with informative priors, whose density function need not be known, and can be used as a model-free control algorithm. Our experiments on collision avoidance in a high-dimensional simulated driving task show that CriticSMC significantly reduces collision rates at a low computational cost while maintaining realism and diversity of driving behaviors across vehicles and environment scenarios.

[Download paper here](https://openreview.net/pdf?id=ObtGcyKmwna)

 ```   
@inproceedings{
lioutas2023critic,
title={Critic Sequential Monte Carlo},
author={Vasileios Lioutas and Jonathan Wilder Lavington and Justice Sefas and Matthew Niedoba and Yunpeng Liu and Berend Zwartsenberg and Setareh Dabiri and Frank Wood and Adam Scibior},
booktitle={The Eleventh International Conference on Learning Representations },
year={2023},
url={https://openreview.net/forum?id=ObtGcyKmwna}
}
 ```