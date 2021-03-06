---
layout: post
title: "Equivalent and Approximate Transformations of Deep Neural Networks"
date: 2019-05-27 18:05:28
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial
author: Abhinav Kumar, Thiago Serra, Srikumar Ramalingam
mathjax: true
---

* content
{:toc}

##### Abstract
Two networks are equivalent if they produce the same output for any given input. In this paper, we study the possibility of transforming a deep neural network to another network with a different number of units or layers, which can be either equivalent, a local exact approximation, or a global linear approximation of the original network. On the practical side, we show that certain rectified linear units (ReLUs) can be safely removed from a network if they are always active or inactive for any valid input. If we only need an equivalent network for a smaller domain, then more units can be removed and some layers collapsed. On the theoretical side, we constructively show that for any feed-forward ReLU network, there exists a global linear approximation to a 2-hidden-layer shallow network with a fixed number of units. This result is a balance between the increasing number of units for arbitrary approximation with a single layer and the known upper bound of $\lceil log(n_0+1)\rceil +1$ layers for exact representation, where $n_0$ is the input dimension. While the transformed network may require an exponential number of units to capture the activation patterns of the original network, we show that it can be made substantially smaller by only accounting for the patterns that define linear regions. Based on experiments with ReLU networks on the MNIST dataset, we found that $l_1$-regularization and adversarial training reduces the number of linear regions significantly as the number of stable units increases due to weight sparsity. Therefore, we can also intentionally train ReLU networks to allow for effective loss-less compression and approximation.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11428](https://arxiv.org/abs/1905.11428)

##### PDF
[https://arxiv.org/pdf/1905.11428](https://arxiv.org/pdf/1905.11428)

