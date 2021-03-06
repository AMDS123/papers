---
layout: post
title: "Supervised Online Hashing via Similarity Distribution Learning"
date: 2019-05-31 02:12:41
categories: arXiv_AI
tags: arXiv_AI Attention Gradient_Descent Relation
author: Mingbao Lin, Rongrong Ji, Shen Chen, Feng Zheng, Xiaoshuai Sun, Baochang Zhang, Liujuan Cao, Guodong Guo, Feiyue Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Online hashing has attracted extensive research attention when facing streaming data. Most online hashing methods, learning binary codes based on pairwise similarities of training instances, fail to capture the semantic relationship, and suffer from a poor generalization in large-scale applications due to large variations. In this paper, we propose to model the similarity distributions between the input data and the hashing codes, upon which a novel supervised online hashing method, dubbed as Similarity Distribution based Online Hashing (SDOH), is proposed, to keep the intrinsic semantic relationship in the produced Hamming space. Specifically, we first transform the discrete similarity matrix into a probability matrix via a Gaussian-based normalization to address the extremely imbalanced distribution issue. And then, we introduce a scaling Student t-distribution to solve the challenging initialization problem, and efficiently bridge the gap between the known and unknown distributions. Lastly, we align the two distributions via minimizing the Kullback-Leibler divergence (KL-diverence) with stochastic gradient descent (SGD), by which an intuitive similarity constraint is imposed to update hashing model on the new streaming data with a powerful generalizing ability to the past data. Extensive experiments on three widely-used benchmarks validate the superiority of the proposed SDOH over the state-of-the-art methods in the online retrieval task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13382](http://arxiv.org/abs/1905.13382)

##### PDF
[http://arxiv.org/pdf/1905.13382](http://arxiv.org/pdf/1905.13382)

