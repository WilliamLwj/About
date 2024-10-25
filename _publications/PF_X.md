---
title: "Personalized Federated X-Armed Bandit"
collection: publications
permalink: /publications/PF-X
excerpt: 
date: 2024-01-19
venue: AISTATS 2024
paperurl:
citation: Wenjie Li, Jean Honorio, Qifan Song. Personalized Federated X-Armed Bandit. Proceedings of the 27th International Conference on Artificial Intelligence and Statistics (AISTATS) 2024
---

[[AISTATS](https://proceedings.mlr.press/v238/li24a/li24a.pdf)] [[arXiv](https://arxiv.org/abs/2310.16323)]

In this work, we study the personalized federated X -armed bandit problem, where
the heterogeneous local objectives of the clients are optimized simultaneously in
the federated learning paradigm. We propose the PF-PNE algorithm with a unique
double elimination strategy, which safely eliminates the non-optimal regions while
encouraging federated collaboration through biased but effective evaluations of the
local objectives. The proposed PF-PNE algorithm is able to optimize local objectives with arbitrary levels of heterogeneity, and its limited communications protects 
the confidentiality of the client-wise reward data. Our theoretical analysis shows
the benefit of the proposed algorithm over single-client algorithms. Experimentally,
PF-PNE outperforms multiple baselines on both synthetic and real-life datasets.