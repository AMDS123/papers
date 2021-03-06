---
layout: post
title: "Deep Active Learning for Axon-Myelin Segmentation on Histology Data"
date: 2019-07-11 12:31:30
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation Face Semantic_Segmentation Deep_Learning
author: Melanie Lubrano di Scandalea, Christian S. Perone, Mathieu Boudreau, Julien Cohen-Adad
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic segmentation is a crucial task in biomedical image processing, which recent breakthroughs in deep learning have allowed to improve. However, deep learning methods in general are not yet widely used in practice since they require large amount of data for training complex models. This is particularly challenging for biomedical images, because data and ground truths are a scarce resource. Annotation efforts for biomedical images come with a real cost, since experts have to manually label images at pixel-level on samples usually containing many instances of the target anatomy (e.g. in histology samples: neurons, astrocytes, mitochondria, etc.). In this paper we provide a framework for Deep Active Learning applied to a real-world scenario. Our framework relies on the U-Net architecture and overall uncertainty measure to suggest which sample to annotate. It takes advantage of the uncertainty measure obtained by taking Monte Carlo samples while using Dropout regularization scheme. Experiments were done on spinal cord and brain microscopic histology samples to perform a myelin segmentation task. Two realistic small datasets of 14 and 24 images were used, from different acquisition settings (Serial Block-Face Electron Microscopy and Transmitting Electron Microscopy) and showed that our method reached a maximum Dice value after adding 3 uncertainty-selected samples to the initial training set, versus 15 randomly-selected samples, thereby significantly reducing the annotation effort. We focused on a plausible scenario and showed evidence that this straightforward implementation achieves a high segmentation performance with very few labelled samples. We believe our framework may benefit any biomedical researcher willing to obtain fast and accurate image segmentation on their own dataset. The code is freely available at https://github.com/neuropoly/deep-active-learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05143](http://arxiv.org/abs/1907.05143)

##### PDF
[http://arxiv.org/pdf/1907.05143](http://arxiv.org/pdf/1907.05143)

