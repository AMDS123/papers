---
layout: post
title: "Progressive Feature Alignment for Unsupervised Domain Adaptation"
date: 2019-05-19 11:43:21
categories: arXiv_CV
tags: arXiv_CV Knowledge Classification
author: Chaoqi Chen, Weiping Xie, Wenbing Huang, Yu Rong, Xinghao Ding, Yue Huang, Tingyang Xu, Junzhou Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised domain adaptation (UDA) transfers knowledge from a label-rich source domain to a fully-unlabeled target domain. To tackle this task, recent approaches resort to discriminative domain transfer in virtue of pseudo-labels to enforce the class-level distribution alignment across the source and target domains. These methods, however, are vulnerable to the error accumulation and thus incapable of preserving cross-domain category consistency, as the pseudo-labeling accuracy is not guaranteed explicitly. In this paper, we propose the Progressive Feature Alignment Network (PFAN) to align the discriminative features across domains progressively and effectively, via exploiting the intra-class variation in the target domain. To be specific, we first develop an Easy-to-Hard Transfer Strategy (EHTS) and an Adaptive Prototype Alignment (APA) step to train our model iteratively and alternatively. Moreover, upon observing that a good domain adaptation usually requires a non-saturated source classifier, we consider a simple yet efficient way to retard the convergence speed of the source classification loss by further involving a temperature variate into the soft-max function. The extensive experimental results reveal that the proposed PFAN exceeds the state-of-the-art performance on three UDA datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08585](http://arxiv.org/abs/1811.08585)

##### PDF
[http://arxiv.org/pdf/1811.08585](http://arxiv.org/pdf/1811.08585)

