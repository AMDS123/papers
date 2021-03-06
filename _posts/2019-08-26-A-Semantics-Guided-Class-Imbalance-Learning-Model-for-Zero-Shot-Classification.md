---
layout: post
title: "A Semantics-Guided Class Imbalance Learning Model for Zero-Shot Classification"
date: 2019-08-26 15:38:33
categories: arXiv_CV
tags: arXiv_CV Knowledge Image_Classification Classification
author: Zhong Ji, Xuejie Yu, Yunlong Yu, Yanwei Pang, Zhongfei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-Shot Classification (ZSC) equips the learned model with the ability to recognize the visual instances from the novel classes via constructing the interactions between the visual and the semantic modalities. In contrast to the traditional image classification, ZSC is easily suffered from the class-imbalance issue since it is more concerned with the class-level knowledge transfer capability. In the real world, the class samples follow a long-tailed distribution, and the discriminative information in the sample-scarce seen classes is hard to be transferred to the related unseen classes in the traditional batch-based training manner, which degrades the overall generalization ability a lot. Towards alleviating the class imbalance issue in ZSC, we propose a sample-balanced training process to encourage all training classes to contribute equally to the learned model. Specifically, we randomly select the same number of images from each class across all training classes to form a training batch to ensure that the sample-scarce classes contribute equally as those classes with sufficient samples during each iteration. Considering that the instances from the same class differ in class representativeness, we further develop an efficient semantics-guided feature fusion model to obtain discriminative class visual prototype for the following visual-semantic interaction process via distributing different weights to the selected samples based on their class representativeness. Extensive experiments on three imbalanced ZSC benchmark datasets for both the Traditional ZSC (TZSC) and the Generalized ZSC (GZSC) tasks demonstrate our approach achieves promising results especially for the unseen categories those are closely related to the sample-scarce seen categories.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09745](http://arxiv.org/abs/1908.09745)

##### PDF
[http://arxiv.org/pdf/1908.09745](http://arxiv.org/pdf/1908.09745)

