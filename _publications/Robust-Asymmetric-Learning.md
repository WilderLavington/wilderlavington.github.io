---
title: "Robust Asymmetric Learning in POMDPs"
collection: publications
permalink: /publication/Robust-Asymmetric-Learning
excerpt: 'Policies for partially observed Markov decision processes can be efficiently learned by imitating policies for the corresponding fully observed Markov decision processes. Unfortunately, existing approaches for this kind of imitation learning have a serious flaw: the expert does not know what the trainee cannot see, and so may encourage actions that are sub-optimal, even unsafe, under partial information. We derive an objective to instead train the expert to maximize the expected reward of the imitating agent policy, and use it to construct an efficient algorithm, adaptive asymmetric DAgger (A2D), that jointly trains the expert and the agent. We show that A2D produces an expert policy that the agent can safely imitate, in turn outperforming policies learned by imitating a fixed expert.'
date: 2020-12-31
venue: 'ICML-2021'
paperurl: 'https://arxiv.org/abs/2012.15566'
citation: 'Warrington, Andrew, et al. "Robust Asymmetric Learning in POMDPs." arXiv preprint arXiv:2012.15566 (2020).'
---
Policies for partially observed Markov decision processes can be efficiently learned by imitating policies for the corresponding fully observed Markov decision processes. Unfortunately, existing approaches for this kind of imitation learning have a serious flaw: the expert does not know what the trainee cannot see, and so may encourage actions that are sub-optimal, even unsafe, under partial information. We derive an objective to instead train the expert to maximize the expected reward of the imitating agent policy, and use it to construct an efficient algorithm, adaptive asymmetric DAgger (A2D), that jointly trains the expert and the agent. We show that A2D produces an expert policy that the agent can safely imitate, in turn outperforming policies learned by imitating a fixed expert.

[Download paper here](https://arxiv.org/abs/2012.15566.pdf)

 ```   
@InProceedings{pmlr-v139-warrington21a,
  title = 	 {Robust Asymmetric Learning in POMDPs},
  author =       {Warrington, Andrew and Lavington, Jonathan W and Scibior, Adam and Schmidt, Mark and Wood, Frank},
  booktitle = 	 {Proceedings of the 38th International Conference on Machine Learning},
  pages = 	 {11013--11023},
  year = 	 {2021},
  editor = 	 {Meila, Marina and Zhang, Tong},
  volume = 	 {139},
  series = 	 {Proceedings of Machine Learning Research},
  month = 	 {18--24 Jul},
  publisher =    {PMLR},
  pdf = 	 {http://proceedings.mlr.press/v139/warrington21a/warrington21a.pdf},
  url = 	 {https://proceedings.mlr.press/v139/warrington21a.html},
  abstract = 	 {Policies for partially observed Markov decision processes can be efficiently learned by imitating expert policies generated using asymmetric information. Unfortunately, existing approaches for this kind of imitation learning have a serious flaw: the expert does not know what the trainee cannot see, and as a result may encourage actions that are sub-optimal or unsafe under partial information. To address this issue, we derive an update which, when applied iteratively to an expert, maximizes the expected reward of the trainee’s policy. Using this update, we construct a computationally efficient algorithm, adaptive asymmetric DAgger (A2D), that jointly trains the expert and trainee policies. We then show that A2D allows the trainee to safely imitate the modified expert, and outperforms policies learned either by imitating a fixed expert or through direct reinforcement learning.}
}
 ```