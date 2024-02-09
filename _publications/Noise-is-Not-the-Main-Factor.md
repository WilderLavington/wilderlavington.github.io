---
title: "A Closer Look at Gradient Estimators with Reinforcement Learning as Inference"
collection: publications
permalink: /publication/Noise-is-Not-the-Main-Factor.md
excerpt: 'The concept of reinforcement learning as inference (RLAI) has led to the creation of a variety of popular algorithms in deep reinforcement learning. Unfortunately, most research in this area relies on wider algorithmic innovations not necessarily relevant to such frameworks. Additionally, many seemingly unimportant modifications made to these algorithms, actually produce inconsistencies with the original inference problem posed by RLAI. Taking a divergence minimization perspective, this work considers some of the practical merits and theoretical issues created by the choice of loss function minimized in the policy update in off-policy reinforcement learning. Our results show that while the choice of divergence rarely has a major affect on the sample efficiency of the algorithm, it can have important practical repercussions on ease of implementation, computational efficiency, and restrictions to the distribution over actions.'
date: 2021-10-31
venue: 'Nuerips-2021 Deep RL Workshop'
paperurl: https://openreview.net/pdf?id=bR0K-nz1-6p
citation: 'Lavington, Jonathan, et al. "A Closer Look at Gradient Estimators with Reinforcement Learning as Inference." '
---
The concept of reinforcement learning as inference (RLAI) has led to the creation of a variety of popular algorithms in deep reinforcement learning. Unfortunately, most research in this area relies on wider algorithmic innovations not necessarily relevant to such frameworks. Additionally, many seemingly unimportant modifications made to these algorithms, actually produce inconsistencies with the original inference problem posed by RLAI. Taking a divergence minimization perspective, this work considers some of the practical merits and theoretical issues created by the choice of loss function minimized in the policy update in off-policy reinforcement learning. Our results show that while the choice of divergence rarely has a major affect on the sample efficiency of the algorithm, it can have important practical repercussions on ease of implementation, computational efficiency, and restrictions to the distribution over actions.

[Download paper here](https://openreview.net/pdf?id=bR0K-nz1-6p)

```  
@inproceedings{lavington2021closer,
  title={A closer look at gradient estimators with reinforcement learning as inference},
  author={Lavington, Jonathan Wilder and Teng, Michael and Schmidt, Mark and Wood, Frank},
  booktitle={Deep RL Workshop NeurIPS 2021}
  url = {https://openreview.net/forum?id=bR0K-nz1-6p}, 
  pdf = 	 {https://openreview.net/pdf?id=bR0K-nz1-6p},
  abstract = 	{The concept of reinforcement learning as inference (RLAI) has led to the creation of a variety of popular algorithms in deep reinforcement learning. Unfortunately, most research in this area relies on wider algorithmic innovations not necessarily relevant to such frameworks. Additionally, many seemingly unimportant modifications made to these algorithms, actually produce inconsistencies with the original inference problem posed by RLAI. Taking a divergence minimization perspective, this work considers some of the practical merits and theoretical issues created by the choice of loss function minimized in the policy update in off-policy reinforcement learning. Our results show that while the choice of divergence rarely has a major affect on the sample efficiency of the algorithm, it can have important practical repercussions on ease of implementation, computational efficiency, and restrictions to the distribution over actions.}
}
 ```