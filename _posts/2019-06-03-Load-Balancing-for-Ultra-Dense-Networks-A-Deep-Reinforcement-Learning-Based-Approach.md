---
layout: post
title: "Load Balancing for Ultra-Dense Networks: A Deep Reinforcement Learning Based Approach"
date: 2019-06-03 13:02:33
categories: arXiv_AI
tags: arXiv_AI Knowledge GAN Reinforcement_Learning
author: Yue Xu, Wenjun Xu, Zhi Wang, Jiaru Lin, Shuguang Cui
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a deep reinforcement learning (DRL) based mobility load balancing (MLB) algorithm along with a two-layer architecture to solve the large-scale load balancing problem for ultra-dense networks (UDNs). Our contribution is three-fold. First, this work proposes a two-layer architecture to solve the large-scale load balancing problem in a self-organized manner. The proposed architecture can alleviate the global traffic variations by dynamically grouping small cells into self-organized clusters according to their historical loads, and further adapt to local traffic variations through intra-cluster load balancing afterwards. Second, for the intra-cluster load balancing, this paper proposes an off-policy DRL-based MLB algorithm to autonomously learn the optimal MLB policy under an asynchronous parallel learning framework, without any prior knowledge assumed over the underlying UDN environments. Moreover, the algorithm enables joint exploration with multiple behavior policies, such that the traditional MLB methods can be used to guide the learning process thereby improving the learning efficiency and stability. Third, this work proposes an offline-evaluation based safeguard mechanism to ensure that the online system can always operate with the optimal and well-trained MLB policy, which not only stabilizes the online performance but also enables the exploration beyond current policies to make full use of machine learning in a safe way. Empirical results verify that the proposed framework outperforms the existing MLB methods in general UDN environments featured with irregular network topologies, coupled interferences, and random user movements, in terms of the load balancing performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00767](http://arxiv.org/abs/1906.00767)

##### PDF
[http://arxiv.org/pdf/1906.00767](http://arxiv.org/pdf/1906.00767)

