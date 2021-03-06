---
layout: post
title: "Towards Fair and Decentralized Privacy-Preserving Deep Learning with Blockchain"
date: 2019-06-04 02:43:42
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Deep_Learning
author: Lingjuan Lyu, Jiangshan Yu, Karthik Nandakumar, Yitong Li, Xingjun Ma, Jiong Jin
mathjax: true
---

* content
{:toc}

##### Abstract
In collaborative deep learning, current learning frameworks follow either a centralized architecture or a distributed architecture. Whilst centralized architecture deploys a central server to train a global model over the massive amount of joint data from all parties, distributed architecture aggregates parameter updates from participating parties' local model training, via a parameter server. These two server-based architectures present security and robustness vulnerabilities such as single-point-of-failure, single-point-of-breach, privacy leakage, and lack of fairness. To address these problems, we design, implement, and evaluate a purely decentralized privacy-preserving deep learning framework, called DPPDL. DPPDL makes the first investigation on the research problem of fairness in collaborative deep learning, and simultaneously provides fairness and privacy by proposing two novel algorithms: initial benchmarking and privacy-preserving collaborative deep learning. During initial benchmarking, each party trains a local Differentially Private Generative Adversarial Network (DPGAN) and publishes the generated privacy-preserving artificial samples for other parties to label, based on the quality of which to initialize local credibility list for other parties. The local credibility list reflects how much one party contributes to another party, and it is used and updated during collaborative learning to ensure fairness. To protect gradients transaction during privacy-preserving collaborative deep learning, we further put forward a three-layer onion-style encryption scheme. We experimentally demonstrate, on benchmark image datasets, that accuracy, privacy and fairness in collaborative deep learning can be effectively addressed at the same time by our proposed DPPDL framework. Moreover, DPPDL provides a viable solution to detect and isolate the cheating party in the system.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01167](http://arxiv.org/abs/1906.01167)

##### PDF
[http://arxiv.org/pdf/1906.01167](http://arxiv.org/pdf/1906.01167)

