---
title: "Federated X-Armed Bandit"
collection: publications
permalink: /publications/Fed-X
excerpt: 
date: 2022-05-16
venue: arXiv
paperurl:
citation: Wenjie Li, Qifan Song, Jean Honorio, Guang Lin. 
---
[[arXiv]()]

This work establishes the first framework of federated $\mathcal{X}$-armed bandit, where different clients face heterogeneous local objective functions defined on the same domain and are required to collaboratively figure out the global optimum. We propose the first federated algorithm for such problems, named \texttt{Fed-PNE}. By utilizing the topological structure of the global objective inside the hierarchical partitioning and the weak smoothness property, our algorithm achieves sublinear cumulative regret with respect to both the number of clients and the evaluation budget. Meanwhile, it only requires logarithmic communications between the central server and clients, protecting the client privacy. Experimental results on synthetic functions and real datasets validate the advantages of \texttt{Fed-PNE} over single-client algorithms and federated multi-armed bandit algorithms. 