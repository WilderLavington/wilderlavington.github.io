---
title: "Semantically consistent video inpainting with conditional diffusion models"
collection: publications
permalink: /publication/consistant_diff.md 
date: 2021-10-31
venue: 'ArXiv'
paperurl: https://openreview.net/pdf?id=bR0K-nz1-6p
citation: 'Dylan, Green, et al. "Semantically consistent video inpainting with conditional diffusion models" '
---
Current state-of-the-art methods for video inpainting typically rely on optical flow or attention-based approaches to inpaint masked regions by propagating visual information across frames. While such approaches have led to significant progress on standard benchmarks, they struggle with tasks that require the synthesis of novel content that is not present in other frames. In this paper, we reframe video inpainting as a conditional generative modeling problem and present a framework for solving such problems with conditional video diffusion models. We introduce inpainting-specific sampling schemes which capture crucial long-range dependencies in the context, and devise a novel method for conditioning on the known pixels in incomplete frames. We highlight the advantages of using a generative approach for this task, showing that our method is capable of generating diverse, high-quality inpaintings and synthesizing new content that is spatially, temporally, and semantically consistent with the provided context.
[Download paper here](https://arxiv.org/abs/2405.00251)

```  
@misc{green2024semanticallyconsistentvideoinpainting,
      title={Semantically Consistent Video Inpainting with Conditional Diffusion Models}, 
      author={Dylan Green and William Harvey and Saeid Naderiparizi and Matthew Niedoba and Yunpeng Liu and Xiaoxuan Liang and Jonathan Lavington and Ke Zhang and Vasileios Lioutas and Setareh Dabiri and Adam Scibior and Berend Zwartsenberg and Frank Wood},
      year={2024},
      eprint={2405.00251},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2405.00251}, 
}
 ```
