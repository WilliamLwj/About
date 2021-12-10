---
title: "Optimum-statistical Collaboration Towards General and Efficient Black-box Optimization"
collection: publications
permalink: /publications/VHCT
excerpt: 
date: 2020-05-10
venue: arXiv
paperurl:
citation: <b>Wenjie Li</b><sup>*</sup>, Chi-Hua Wang<sup>*</sup>, Guang Cheng.
---
[[slides]()] [[arXiv](https://arxiv.org/abs/2106.09215)]  [[poster](https://williamlwj.github.io/About/files/posters/VHCT_poster.pdf)]
[[OPT Version](https://opt-ml.org/papers/2021/paper8.pdf)]

 In this paper, we make the key delineation on the roles of resolution and statistical uncertainty in black-box optimization, guiding a more general analysis and a more efficient algorithm design. We introduce \textit{optimum-statistical collaboration}, an algorithm framework of managing the interaction between optimization error flux and statistical error flux evolving in the optimization process. We provide a general analysis of the framework without specific forms of the statistical error and the uncertainty quantifier. Our framework and its analysis, because of their generality, can be applied to functions and partitions that satisfy different local smoothness assumptions and has different number of local optimums, which is much larger than the class of functions studied in prior works. Our framework also inspires us to propose a better measure of the statistical uncertainty and consequently a variance-adaptive algorithm \texttt{VHCT}. In theory, we prove the algorithm enjoys rate-optimal regret bounds under different local smoothness assumptions; in experiments, we show the algorithm outperforms prior efforts in different settings.
