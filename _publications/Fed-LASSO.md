---
title: "Federated Online Sparse Decision Making"
collection: publications
permalink: /publications/Fed-LASSO
excerpt: 
date: 2022-01-30
venue: arXiv
paperurl:
citation: Chi-Hua Wang, <b>Wenjie Li</b>, Guang Cheng, Guang Lin
---
 [[arXiv](https://arxiv.org/abs/2202.13448)]

This paper presents a novel federated linear contextual bandits model, where individual clients face different K-armed stochastic bandits with high-dimensional decision context and coupled through common global parameters. By leveraging the sparsity structure of the linear reward , a collaborative algorithm named \texttt{Fedego Lasso} is proposed to cope with the heterogeneity across clients without exchanging local decision context vectors or raw reward data. \texttt{Fedego Lasso} relies on a novel multi-client teamwork-selfish bandit policy design, and achieves near-optimal regrets for shared parameter cases with logarithmic communication costs. In addition, a new conceptual tool called federated-egocentric policies is introduced to delineate exploration-exploitation trade-off. Experiments demonstrate the effectiveness of the proposed algorithms on both synthetic and real-world datasets.