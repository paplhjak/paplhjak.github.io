---
title: "A Call to Reflect on Evaluation Practices for Age Estimation: Comparative Analysis of the State-of-the-Art and a Unified Benchmark"
collection: publications
permalink: /publication/2023-12-09-age-estimation
excerpt: 'Comparing different age estimation methods poses a challenge due to the unreliability of published results. Previous studies have reported continuous performance improvements using specialized methods; however, our findings challenge these claims.'
date: 2023-12-09
venue: 'ArXiv'
paperurl: 'https://arxiv.org/abs/2307.04570'
citation: 'Jakub Paplham, and Vojtech Franc 2023. A Call to Reflect on Evaluation Practices for Age Estimation: Comparative Analysis of the State-of-the-Art and a Unified Benchmark. ArXiv, abs/2307.04570.'
---

Comparing different age estimation methods poses a challenge due to the unreliability of published results stemming from inconsistencies in the benchmarking process. Previous studies have reported continuous performance improvements over the past decade using specialized methods; however, our findings challenge these claims. This paper identifies two trivial, yet persistent issues with the currently used evaluation protocol and describes how to resolve them. We describe our evaluation protocol in detail and provide specific examples of how the protocol should be used. We utilize the protocol to offer an extensive comparative analysis for state-of-the-art facial age estimation methods. Surprisingly, we find that the performance differences between the methods are negligible compared to the effect of other factors, such as facial alignment, facial coverage, image resolution, model architecture, or the amount of data used for pretraining. We use the gained insights to propose using FaRL as the backbone model and demonstrate it's efficiency. The results emphasize the importance of consistent data preprocessing practices for reliable and meaningful comparisons.

[Download paper here](https://arxiv.org/abs/2307.04570)

BibTeX: 
{% include codeheader.html %}
```
@misc{paplham2023unraveling,
      title={A Call to Reflect on Evaluation Practices for Age Estimation: Comparative Analysis of the State-of-the-Art and a Unified Benchmark}, 
      author={Jakub Paplham and Vojtech Franc},
      year={2023},
      eprint={2307.04570},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
