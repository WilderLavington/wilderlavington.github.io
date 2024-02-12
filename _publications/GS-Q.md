---
title: "Analyzing and Improving Greedy 2-Coordinate Updates for Equality-Constrained Optimization via Steepest Descent in the 1-Norm"
collection: publications
permalink: /publication/GS-Q
date: 2023-06-15
venue: 'Arxiv-2023'
paperurl: 'https://arxiv.org/abs/2307.01169'
citation: 'Ramesh, Amrutha, et al. "Analyzing and Improving Greedy 2-Coordinate Updates for Equality-Constrained Optimization via Steepest Descent in the 1-Norm" Arxiv 2023.'
---
We consider minimizing a smooth function subject to a summation constraint over its variables. By exploiting a connection between the greedy 2-coordinate update for this problem and equality-constrained steepest descent in the 1-norm, we give a convergence rate for greedy selection under a proximal Polyak-Lojasiewicz assumption that is faster than random selection and independent of the problem dimension n. We then consider minimizing with both a summation constraint and bound constraints, as arises in the support vector machine dual problem. Existing greedy rules for this setting either guarantee trivial progress only or require O(n^2) time to compute. We show that bound- and summation-constrained steepest descent in the L1-norm guarantees more progress per iteration than previous rules and can be computed in only O(nlogn) time.

[Download paper here](https://arxiv.org/abs/2307.01169)

 ```   
@misc{ramesh2023analyzing,
      title={Analyzing and Improving Greedy 2-Coordinate Updates for Equality-Constrained Optimization via Steepest Descent in the 1-Norm}, 
      author={Amrutha Varshini Ramesh and Aaron Mishkin and Mark Schmidt and Yihan Zhou and Jonathan Wilder Lavington and Jennifer She},
      year={2023},
      eprint={2307.01169},
      archivePrefix={arXiv},
      primaryClass={math.OC}
}
 ```