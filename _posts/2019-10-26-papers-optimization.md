---
title: "Papers-Optimization"
date: 2019-10-26
permalink: /posts/papers-optimization
tags:
  - papers
  - optimization
---

1. ### [Decoupled Weight Decay Regularization](https://arxiv.org/abs/1711.05101)
  * Talks about the differences between l2 regularization and weight decay in adaptive algorithms and derive AdamW.

2. ### [Adaptive Gradient Methods with Dynamic Bound of Learning Rate](https://arxiv.org/abs/1902.09843)
  * Talks about dynamic bounds on the adaptive learning rates and introduce AdaBound.
  
3. ### [Nostalgic Adam: Weighting more of the past gradients when designing the adaptive learning rate](https://arxiv.org/abs/1805.07557)
  * Talks about higher weights should be given to past gradients when designing the V_t's and introduce NosAdam.
  
4. ### [On the Convergence of A Class of Adam-Type Algorithms for Non-Convex Optimization](https://openreview.net/forum?id=H1x-x309tm)
  * Talks about the non-convex convergence of AMSGrad and AdaFom
  
5. ### [On the Convergence of Adam and Beyond](https://arxiv.org/abs/1904.09237)
  * Talks about the convergence problem of Adam in a convex case and introduce AMSGrad

6. ### [AdaShift: Decorrelation and Convergence of Adaptive Learning Rate Methods](https://openreview.net/forum?id=HkgTkhRcKQ)
  * Talks about temporary shifting g_t to g_{t-n} in designing the V_t so that the correlation can be removed.
  
7. 
