---
title: "Optimum-statistical Collaboration Towards Efficient Black-box Optimization"
collection: publications
permalink: /publications/VHCT
excerpt: 
date: 2020-05-10
venue: arXiv
paperurl:
citation: <b>Wenjie Li</b><sup>*</sup>, Chihua Wang<sup>*</sup>, Guang Cheng.
---
[[slides]()] [[arXiv]()]

With increasingly more hyperparameters involved in their training, machine learning systems demand a better understanding of hyperparameter tuning automation. This has raised interest in studies of provably black-box optimization, which is made more practical by better exploration mechanism implemented in algorithm design, managing the flux of both optimization and statistical errors. Prior efforts focus on delineating optimization errors, but this is deficient: black-box optimization algorithms can be inefficient without considering heterogeneity among reward samples. In this paper, we make the key delineation on the role of statistical uncertainty in black-box optimization, guiding a more efficient algorithm design. We introduce \textit{optimum-statistical collaboration}, a framework of managing the interaction between optimization error flux and statistical error flux evolving in the optimization process. Inspired by this framework, we propose the \texttt{VHCT} algorithms for objective functions with only local-smoothness assumptions. In theory, we prove our algorithm enjoys rate-optimal regret bounds; in experiments, we show the algorithm outperforms prior efforts in extensive settings.
