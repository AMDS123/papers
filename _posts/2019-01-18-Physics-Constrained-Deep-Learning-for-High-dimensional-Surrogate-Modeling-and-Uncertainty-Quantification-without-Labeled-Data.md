---
layout: post
title: "Physics-Constrained Deep Learning for High-dimensional Surrogate Modeling and Uncertainty Quantification without Labeled Data"
date: 2019-01-18 15:59:30
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Yinhao Zhu, Nicholas Zabaras, Phaedon-Stelios Koutsourelakis, Paris Perdikaris
mathjax: true
---

* content
{:toc}

##### Abstract
Surrogate modeling and uncertainty quantification tasks for PDE systems are most often considered as supervised learning problems where input and output data pairs are used for training. The construction of such emulators is by definition a small data problem which poses challenges to deep learning approaches that have been developed to operate in the big data regime. Even in cases where such models have been shown to have good predictive capability in high dimensions, they fail to address constraints in the data implied by the PDE model. This paper provides a methodology that incorporates the governing equations of the physical model in the loss/likelihood functions. The resulting physics-constrained, deep learning models are trained without any labeled data (e.g. employing only input data) and provide comparable predictive responses with data-driven models while obeying the constraints of the problem at hand. This work employs a convolutional encoder-decoder neural network approach as well as a conditional flow-based generative model for the solution of PDEs, surrogate model construction, and uncertainty quantification tasks. The methodology is posed as a minimization problem of the reverse Kullback-Leibler (KL) divergence between the model predictive density and the reference conditional density, where the later is defined as the Boltzmann-Gibbs distribution at a given inverse temperature with the underlying potential relating to the PDE system of interest. The generalization capability of these models to out-of-distribution input is considered. Quantification and interpretation of the predictive uncertainty is provided for a number of problems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06314](http://arxiv.org/abs/1901.06314)

##### PDF
[http://arxiv.org/pdf/1901.06314](http://arxiv.org/pdf/1901.06314)

