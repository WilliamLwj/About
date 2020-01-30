---
title: "AdaX: Adaptive Gradient Descent with Exponential Long Term Memory"
collection: publications
permalink: /publication/AdaX
excerpt: 
date: 2019-09-25
venue: arXiv
paperurl:
citation:
---
[[Github](https://github.com/WilliamLwj/AdaX)]

Although adaptive optimization algorithms such as Adam show fast convergence in many machine learning tasks, this paper identifies a problem of Adam by analyzing its performance in a simple non-convex synthetic problem, showing that Adam's fast convergence would possibly lead the algorithm to local minimums. To address this problem, we improve Adam by proposing a novel adaptive gradient descent algorithm named AdaX. Unlike Adam that ignores the past gradients, AdaX exponentially accumulates the long-term gradient information in the past during training, to adaptively tune the learning rate. We thoroughly prove the convergence of AdaX in both the convex and non-convex settings. Extensive experiments show that AdaX outperforms Adam in various tasks of computer vision and natural language processing and can catch up with Stochastic Gradient Descent.
