---
title: "An Empirical Study of Non-Uniform Sampling in Off-Policy Reinforcement Learning for Continuous Control"
collection: publications
permalink: /publication/Realistic
date: 2021-05-12
venue: 'NuerIPS Workshop 2021'
paperurl: 'https://openreview.net/pdf?id=KvDedKtOX7B'
citation: 'Nicholas,  Ioannidis, et al. "An Empirical Study of Non-Uniform Sampling in Off-Policy Reinforcement Learning for Continuous Control" NuerIPS Workshop 2021.'
---
Off-policy reinforcement learning (RL) algorithms can take advantage of samples generated from all previous interactions with the environment through "experience replay". Such methods outperform almost all on-policy and model-based alternatives in complex tasks where a structured or well parameterized model of the world does not exist. This makes them desirable for practitioners who lack domain specific knowledge, but who still require high sample efficiency. However this high performance can come at a cost. Because of additional hyperparameters introduced to efficiently learn function approximators, off-policy RL can perform poorly on new problems. To address parameter sensitivity, we show how the correct choice of non-uniform sampling for experience replay can stabilize model performance under varying environmental conditions and hyper-parameters.

[Download paper here](https://openreview.net/pdf?id=KvDedKtOX7B)

 ```   
@inproceedings{
ioannidis2021an,
title={An Empirical Study of Non-Uniform Sampling in Off-Policy Reinforcement Learning for Continuous Control},
author={Nicholas Ioannidis and Jonathan Wilder Lavington and Mark Schmidt},
booktitle={Deep RL Workshop NeurIPS 2021},
year={2021},
url={https://openreview.net/forum?id=KvDedKtOX7B}
}
 ```