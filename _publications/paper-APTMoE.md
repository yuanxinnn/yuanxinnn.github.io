---
title: "APTMoE: Affinity-aware Pipeline Tuning for MoE Models on Bandwidth-constrained GPU Nodes"
collection: publications
category: conferences
permalink: /publication/paper-APTMoE
# excerpt: 'Propose a hierarchical loading strategy for computing affinity awareness by strategically offloading a portion of experts to CPU for computation'
# date: 2024-06
# venue: 'Atlanta, U.S.'
conference: 'International Conference for High Performance Computing, Networking, Storage, and Analysis (SC) 2024, CCF-A'
paperurl: 'http://yuanxinnn.github.io/files/APTMoE_paper.pdf'
author: 'Yuanxin Wei, Jiangsu Du*, Jiazhi Jiang, Xiao Shi, Xianwei Zhang, Dan Huang, Nong Xiao, Yutong Lu*'
---



In this paper, we introduce APTMoE, which employs affinity-aware pipeline parallelism for fine-tuning MoE models on bandwidth-constrained GPU nodes.
We propose an affinity-aware offloading technique that enhances pipeline parallelism for both computational efficiency and model size, and it benefits from a hierarchical loading strategy and a demand-priority scheduling strategy.
To improve the computation efficiency and reduce the data movement volume, the hierarchical loading strategy designs three loading phases and efficiently allocates computation across GPUs and CPUs during these phases, leveraging different levels of expert popularity and computation affinity.
With the aim of alleviating the mutual interference among the three loading phases and maximizing the bandwidth utilization, the demand-priority scheduling strategy proactively and dynamically coordinates the loading execution order.
