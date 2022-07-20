---
title: "A Simple Unified Framework for High Dimensional Bandit Problems"
collection: publications
permalink: /publications/Bandit_framework
excerpt: 
date: 2022-05-14
venue: ICML 2022
paperurl:
citation: Wenjie Li, Adarsh Barik, Jean Honorio. A Simple Unified Framework for High Dimensional Bandit Problems. Proceedings of the 39th International Conference on Machine Learning. 
---
[[arXiv](https://arxiv.org/abs/2102.09626)] [[ICML paper](https://proceedings.mlr.press/v162/li22a/li22a.pdf)] [[ICML poster](https://williamlwj.github.io/About/files/posters/Bandit_framework_poster.pdf)] [[ICML recording](https://recorder-v3.slideslive.com/?share=69489&s=741ffb7f-fc69-4807-bf43-bf3294cf993d)]

Stochastic high dimensional bandit problems with low dimensional structures are useful in different applications such as online advertising and drug discovery. In this work, we propose a simple unified algorithm for such problems and present a general analysis framework for the regret upper bound of our algorithm. We show that under some mild unified assumptions, our algorithm can be applied to different high-dimensional bandit problems. Our framework utilizes the low dimensional structure to guide the parameter estimation in the problem, therefore our algorithm achieves the comparable regret bounds in the LASSO bandit as a sanity check, as well as novel bounds that depend logarithmically on dimensions in the low-rank matrix bandit, the group sparse matrix bandit, and in a new problem: the multi-agent LASSO bandit.