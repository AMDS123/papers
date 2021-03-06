---
layout: post
title: "Multi-Similarity Loss with General Pair Weighting for Deep Metric Learning"
date: 2019-04-14 04:46:25
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval
author: Xun Wang, Xintong Han, Weiling Huang, Dengke Dong, Matthew R. Scott
mathjax: true
---

* content
{:toc}

##### Abstract
A family of loss functions built on pair-based computation have been proposed in the literature which provide a myriad of solutions for deep metric learning. In this paper, we provide a general weighting framework for understanding recent pair-based loss functions. Our contributions are three-fold: (1) we establish a General Pair Weighting (GPW) framework, which casts the sampling problem of deep metric learning into a unified view of pair weighting through gradient analysis, providing a powerful tool for understanding recent pair-based loss functions; (2) we show that with GPW, various existing pair-based methods can be compared and discussed comprehensively, with clear differences and key limitations identified; (3) we propose a new loss called multi-similarity loss (MS loss) under the GPW, which is implemented in two iterative steps (i.e., mining and weighting). This allows it to fully consider three similarities for pair weighting, providing a more principled approach for collecting and weighting informative pairs. Finally, the proposed MS loss obtains new state-of-the-art performance on four image retrieval benchmarks, where it outperforms the most recent approaches, such as ABE\cite{Kim_2018_ECCV} and HTL by a large margin: 60.6% to 65.7% on CUB200, and 80.9% to 88.0% on In-Shop Clothes Retrieval dataset at Recall@1. Code is available at https://github.com/MalongTech/research-ms-loss.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06627](http://arxiv.org/abs/1904.06627)

##### PDF
[http://arxiv.org/pdf/1904.06627](http://arxiv.org/pdf/1904.06627)

