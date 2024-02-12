---
title: "Conditional Permutation Invariant Flows"
collection: publications
permalink: /publication/Flows
date: 2023-06-15
venue: 'TMLR-2023'
paperurl: 'https://openreview.net/forum?id=DUsgPi3oCC'
citation: 'Berend, Zwartsenberg, et al. "Conditional Permutation Invariant Flows." TMLR 2023.'
---
We present a novel, conditional generative probabilistic model of set-valued data with a tractable log density. This model is a continuous normalizing flow governed by permutation equivariant dynamics. These dynamics are driven by a learnable per-set-element term and pairwise interactions, both parametrized by deep neural networks. We illustrate the utility of this model via applications including (1) complex traffic scene generation conditioned on visually specified map information, and (2) object bounding box generation conditioned directly on images. We train our model by maximizing the expected likelihood of labeled conditional data under our flow, with the aid of a penalty that ensures the dynamics are smooth and hence efficiently solvable. Our method significantly outperforms non-permutation invariant baselines in terms of log likelihood and domain-specific metrics (offroad, collision, and combined infractions), yielding realistic samples that are difficult to distinguish from real data.

[Download paper here](https://openreview.net/forum?id=DUsgPi3oCC)

 ```   
@article{
zwartsenberg2023conditional,
title={Conditional Permutation Invariant Flows},
author={Berend Zwartsenberg and Adam Scibior and Matthew Niedoba and Vasileios Lioutas and Justice Sefas and Yunpeng Liu and Setareh Dabiri and Jonathan Wilder Lavington and Trevor Campbell and Frank Wood},
journal={Transactions on Machine Learning Research},
issn={2835-8856},
year={2023},
url={https://openreview.net/forum?id=DUsgPi3oCC},
note={}
}
 ```