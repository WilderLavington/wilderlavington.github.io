---
title: "Target-based Surrogates for Stochastic Optimization"
collection: publications
permalink: /publication/Target-Based-Surrogates
date: 2023-02-01
venue: 'ICML-2023'
paperurl: 'https://proceedings.mlr.press/v202/lavington23a/lavington23a.pdf'
citation: 'Lavington, Jonathan, et al. "Target-based Surrogates for Stochastic Optimization." ICML 2023.'
---
We consider minimizing functions for which it is expensive to compute the (possibly stochastic) gradient. Such functions are prevalent in reinforcement learning, imitation learning and adversarial training. Our target optimization framework uses the (expensive) gradient computation to construct surrogate functions in a target space (e.g. the logits output by a linear model for classification) that can be minimized efficiently. This allows for multiple parameter updates to the model, amortizing the cost of gradient computation. In the full-batch setting, we prove that our surrogate is a global upper-bound on the loss, and can be (locally) minimized using a black-box optimization algorithm. We prove that the resulting majorization-minimization algorithm ensures convergence to a stationary point of the loss. Next, we instantiate our framework in the stochastic setting and propose the SSO algorithm, which can be viewed as projected stochastic gradient descent in the target space. This connection enables us to prove theoretical guarantees for SSO when minimizing convex functions. Our framework allows the use of standard stochastic optimization algorithms to construct surrogates which can be minimized by any deterministic optimization method. To evaluate our framework, we consider a suite of supervised learning and imitation learning problems. Our experiments indicate the benefits of target optimization and the effectiveness of SSO.

[Download paper here](https://proceedings.mlr.press/v202/lavington23a/lavington23a.pdf)

```  
@InProceedings{pmlr-v202-lavington23a,
  title = 	 {Target-based Surrogates for Stochastic Optimization},
  author =       {Lavington, Jonathan Wilder and Vaswani, Sharan and Babanezhad Harikandeh, Reza and Schmidt, Mark and Le Roux, Nicolas},
  booktitle = 	 {Proceedings of the 40th International Conference on Machine Learning},
  pages = 	 {18614--18651},
  year = 	 {2023},
  editor = 	 {Krause, Andreas and Brunskill, Emma and Cho, Kyunghyun and Engelhardt, Barbara and Sabato, Sivan and Scarlett, Jonathan},
  volume = 	 {202},
  series = 	 {Proceedings of Machine Learning Research},
  month = 	 {23--29 Jul},
  publisher =    {PMLR},
  pdf = 	 {https://proceedings.mlr.press/v202/lavington23a/lavington23a.pdf},
  url = 	 {https://proceedings.mlr.press/v202/lavington23a.html},
  abstract = 	 {We consider minimizing functions for which it is expensive to compute the (possibly stochastic) gradient. Such functions are prevalent in reinforcement learning, imitation learning and adversarial training. Our target optimization framework uses the (expensive) gradient computation to construct surrogate functions in a <em>target space</em> (e.g. the logits output by a linear model for classification) that can be minimized efficiently. This allows for multiple parameter updates to the model, amortizing the cost of gradient computation. In the full-batch setting, we prove that our surrogate is a global upper-bound on the loss, and can be (locally) minimized using a black-box optimization algorithm. We prove that the resulting majorization-minimization algorithm ensures convergence to a stationary point of the loss. Next, we instantiate our framework in the stochastic setting and propose the $SSO$ algorithm, which can be viewed as projected stochastic gradient descent in the target space. This connection enables us to prove theoretical guarantees for $SSO$ when minimizing convex functions. Our framework allows the use of standard stochastic optimization algorithms to construct surrogates which can be minimized by any deterministic optimization method. To evaluate our framework, we consider a suite of supervised learning and imitation learning problems. Our experiments indicate the benefits of target optimization and the effectiveness of $SSO$.}
}
 ```