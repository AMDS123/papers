---
layout: post
title: "Local Label Propagation for Large-Scale Semi-Supervised Learning"
date: 2019-05-28 02:57:42
categories: arXiv_CV
tags: arXiv_CV Embedding Recognition
author: Chengxu Zhuang, Xuehao Ding, Divyanshu Murli, Daniel Yamins
mathjax: true
---

* content
{:toc}

##### Abstract
A significant issue in training deep neural networks to solve supervised learning tasks is the need for large numbers of labelled datapoints. The goal of semi-supervised learning is to leverage ubiquitous unlabelled data, together with small quantities of labelled data, to achieve high task performance. Though substantial recent progress has been made in developing semi-supervised algorithms that are effective for comparatively small datasets, many of these techniques do not scale readily to the large (unlaballed) datasets characteristic of real-world applications. In this paper we introduce a novel approach to scalable semi-supervised learning, called Local Label Propagation (LLP). Extending ideas from recent work on unsupervised embedding learning, LLP first embeds datapoints, labelled and otherwise, in a common latent space using a deep neural network. It then propagates pseudolabels from known to unknown datapoints in a manner that depends on the local geometry of the embedding, taking into account both inter-point distance and local data density as a weighting on propagation likelihood. The parameters of the deep embedding are then trained to simultaneously maximize pseudolabel categorization performance as well as a metric of the clustering of datapoints within each psuedo-label group, iteratively alternating stages of network training and label propagation. We illustrate the utility of the LLP method on the ImageNet dataset, achieving results that outperform previous state-of-the-art scalable semi-supervised learning algorithms by large margins, consistently across a wide variety of training regimes. We also show that the feature representation learned with LLP transfers well to scene recognition in the Places 205 dataset.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11581](https://arxiv.org/abs/1905.11581)

##### PDF
[https://arxiv.org/pdf/1905.11581](https://arxiv.org/pdf/1905.11581)

