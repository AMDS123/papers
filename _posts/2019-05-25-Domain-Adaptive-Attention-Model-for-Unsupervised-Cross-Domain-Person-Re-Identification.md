---
layout: post
title: "Domain Adaptive Attention Model for Unsupervised Cross-Domain Person Re-Identification"
date: 2019-05-25 06:05:49
categories: arXiv_CV
tags: arXiv_CV Re-identification Attention Person_Re-identification Classification
author: Yangru Huang, Peixi Peng, Yi Jin, Junliang Xing, Congyan Lang, Songhe Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (Re-ID) across multiple datasets is a challenging yet important task due to the possibly large distinctions between different datasets and the lack of training samples in practical applications. This work proposes a novel unsupervised domain adaption framework which transfers discriminative representations from the labeled source domain (dataset) to the unlabeled target domain (dataset). We propose to formulate the domain adaption task as an one-class classification problem with a novel domain similarity loss. Given the feature map of any image from a backbone network, a novel domain adaptive attention model (DAAM) first automatically learns to separate the feature map of an image to a domain-shared feature (DSH) map and a domain-specific feature (DSP) map simultaneously. Specially, the residual attention mechanism is designed to model DSP feature map for avoiding negative transfer. Then, a DSH branch and a DSP branch are introduced to learn DSH and DSP feature maps respectively. To reduce domain divergence caused by that the source and target datasets are collected from different environments, we force to project the DSH feature maps from different domains to a new nominal domain, and a novel domain similarity loss is proposed based on one-class classification. In addition, a novel unsupervised person Re-ID loss is proposed to take full use of unlabeled target data. Extensive experiments on the Market-1501 and DukeMTMC-reID benchmarks demonstrate state-of-the-art performance of the proposed method. Code will be released to facilitate further studies on the cross-domain person re-identification task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10529](http://arxiv.org/abs/1905.10529)

##### PDF
[http://arxiv.org/pdf/1905.10529](http://arxiv.org/pdf/1905.10529)

