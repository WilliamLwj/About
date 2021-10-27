---
title: "Variance Reduction on General Adaptive Stochastic Mirror Descent"
collection: publications
permalink: /publications/SVRGMD
excerpt: 
date: 2020-10-30
venue: The 34th Conference on Neural Information Processing Systems (NeurIPS 2020) OPT 2020 Workshop 
paperurl:
citation: <b>Wenjie Li</b>, Zhanyu Wang, Yichen Zhang, Guang Cheng
---
[[OPT2020 Workshop paper](https://opt-ml.org/papers/2020/paper_19.pdf)] [[slides](https://williamlwj.github.io/About/files/slides/SVRGMD_paper_slides.pdf)] [[arXiv](https://arxiv.org/abs/2012.13760)] [[poster](https://williamlwj.github.io/About/files/slides/SVRGMD_poster.pdf)]

In this work, we study the idea of variance reduction applied to adaptive stochastic mirror descent algorithms in the nonsmooth nonconvex finite-sum optimization problems. We propose a simple yet generalized adaptive mirror descent algorithm with variance reduction named SVRAMD and provide its convergence analysis in different settings. We prove that variance reduction reduces the SFO complexity of most adaptive mirror descent algorithms and accelerates their convergence. In particular, our general theory implies that variance reduction can be applied to algorithms using time-varying step sizes and self-adaptive algorithms such as AdaGrad and RMSProp. Moreover, the convergence rates of SVRAMD recover the best existing rates of non-adaptive variance reduced mirror descent algorithms. We check the validity of our claims using experiments in deep learning.
