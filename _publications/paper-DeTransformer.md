---
title: "Communication-Efficient Model Parallelism for Distributed In-Situ Transformer Inference"
collection: publications
category: conferences
permalink: /publication/paper-DeTransformer
# excerpt: 'Adopting the concept of co-deign, we propose block parallelism through model structure decoupling, incorporated with a model adaptive execution method that dynamically balances the computing power, communication power, and memory capacity of devices.'
# date: 2023-11-
# venue: 'Valencia, Spain'
conference: 'Automation & Test in Europe (DATE), 2024, CCF-B'
slidesurl: 'http://yuanxinnn.github.io/files/DeTransformer_slide_DATE2024.pdf'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10546617'
author: 'Yuanxin Wei, Shengyuan Ye, Jiazhi Jiang, Xu Chen, Dan Huang*, Jiangsu Du*, Yutong Lu'
---

In this paper, we propose DeTransformer, a communication-efficient distributed in-situ Transformer inference system for edge scenarios. DeTransformer is based on a novel block parallelism approach, with the key idea of restructuring the original Transformer layer with a single block to the decoupled layer with multiple sub-blocks and exploit model parallelism between sub-blocks. Next, DeTransformer contains an adaptive placement approach to automatically select the optimal placement strategy by striking a trade-off among communication capability, computing power and memory budget.