---
title: "How Does BN Increase Collapsed Neural Network Filters?"
collection: publications
permalink: /publications/BN-collapse
excerpt: 
date: 2019-01-30
venue: arXiv
paperurl:
citation: Sheng Zhou<sup>*</sup>, Xinjiang Wang<sup>*</sup>, Ping Luo, Litong Feng, <b>Wenjie Li</b>, Wei Zhang
---
[[arXiv](https://arxiv.org/abs/2001.11216)]

Improving sparsity of deep neural networks (DNNs) is essential for network compression and has
drawn much attention. In this work, we disclose a harmful sparsifying process called filter collapse,
which is common in DNNs with batch normalization (BN) and rectified linear activation functions
(e.g. ReLU, Leaky ReLU). It occurs even without explicit sparsity-inducing regularizations such as
L1. This phenomenon is caused by the normalization effect of BN, which induces a non-trainable
region in the parameter space and reduces the network capacity as a result. This phenomenon
becomes more prominent when the network is trained with large learning rates (LR) or adaptive LR
schedulers, and when the network is finetuned. We analytically prove that the parameters of BN tend
to become sparser during SGD updates with high gradient noise and that the sparsifying probability
is proportional to the square of learning rate and inversely proportional to the square of the scale
parameter of BN. To prevent the undesirable collapsed filters, we propose a simple yet effective
approach named post-shifted BN (psBN), which has the same representation ability as BN while
being able to automatically make BN parameters trainable again as they saturate during training.
With psBN, we can recover collapsed filters and increase the model performance in various tasks
such as classification on CIFAR-10 and object detection on MS-COCO2017.
