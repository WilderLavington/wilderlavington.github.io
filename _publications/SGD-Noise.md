---
title: "Noise Is Not the Main Factor Behind the Gap Between Sgd and Adam on Transformers, But Sign Descent Might Be"
collection: publications
permalink: /publication/SGD-Noise 
date: 2023-02-11 
venue: 'ICLR-2023'
paperurl: https://www.proquest.com/openview/da3b1b61b3fd2f0ca38a3418172867d9/1?pq-origsite=gscholar&cbl=18750
citation: 'Kunstner, Frederik, et al. "Noise Is Not the Main Factor Behind the Gap Between Sgd and Adam on Transformers, But Sign Descent Might Be" '
---
The success of the Adam optimizer on a wide array of architectures has made it the default in settings where stochastic gradient descent (SGD) performs poorly. However, our theoretical understanding of this discrepancy is lagging, preventing the development of significant improvements on either algorithm. Recent work advances the hypothesis that Adam and other heuristics like gradient clipping outperform SGD on language tasks because the distribution of the error induced by sampling has heavy tails. This suggests that Adam outperform SGD because it uses a more robust gradient estimate. We evaluate this hypothesis by varying the batch size, up to the entire dataset, to control for stochasticity. We present evidence that stochasticity and heavy-tailed noise  are not major factors in the performance gap between SGD and Adam. Rather, Adam performs better as the batch size increases,  while SGD is less effective at taking advantage of the reduction in noise. This raises the question as to why Adam outperforms SGD in the full-batch setting. Through further investigation of simpler variants of SGD, we find that  the behavior of Adam with large batches is similar to sign descent with momentum. 

[Download paper here](https://openreview.net/pdf?id=a65YK0cqH8g)

```  
@inproceedings{
kunstner2023noise,
title={Noise Is Not the Main Factor Behind the Gap Between Sgd and Adam on Transformers, But Sign Descent Might Be},
author={Frederik Kunstner and Jacques Chen and Jonathan Wilder Lavington and Mark Schmidt},
booktitle={The Eleventh International Conference on Learning Representations },
year={2023},
url={https://openreview.net/forum?id=a65YK0cqH8g}
}
 ```