---
title: "Optimum-statistical Collaboration Towards General and Efficient Black-box Optimization"
collection: publications
permalink: /publications/VHCT
excerpt: 
date: 2023-05-30
venue:  Transactions on Machine Learning Research (Previously at OPT@NeurIPS'21)
paperurl: https://openreview.net/forum?id=ClIcmwdlxn
citation: <b>Wenjie Li</b><sup>*</sup>, Chi-Hua Wang<sup>*</sup>, Guang Cheng, Qifan Song. Optimum-statistical Collaboration Towards General and Efficient Black-box Optimization.  Transactions on Machine Learning Research. 2023
---
[[TMLR paper](https://openreview.net/forum?id=ClIcmwdlxn)] [[Github](https://github.com/WilliamLwj/PyXAB)] [[arXiv](https://arxiv.org/abs/2106.09215)]  [[OPT poster](https://williamlwj.github.io/About/files/posters/VHCT_poster.pdf)]
[[OPT paper](https://opt-ml.org/papers/2021/paper8.pdf)]

 In this paper, we make the key delineation on the roles of resolution and statistical uncertainty in hierarchical bandits-based black-box optimization algorithms, guiding a more general analysis and a more efficient algorithm design. We introduce the \textit{optimum-statistical collaboration}, an algorithm framework of managing the interaction between optimization error flux and statistical error flux evolving in the optimization process. We provide a general analysis of this framework without specifying the forms of statistical error and uncertainty quantifier. Our framework and its analysis, due to their generality, can be applied to a large family of functions and partitions that satisfy different local smoothness assumptions and have different numbers of local optimums, which is much richer than the class of functions studied in prior works. Our framework also inspires us to propose a better measure of the statistical uncertainty and consequently a variance-adaptive algorithm \texttt{VHCT}. In theory, we prove the algorithm enjoys rate-optimal regret bounds under different local smoothness assumptions; in experiments, we show the algorithm outperforms prior efforts in different settings.
