---
layout: post
title: "Homogeneous Vector Capsules Enable Adaptive Gradient Descent in Convolutional Neural Networks"
date: 2019-06-20 14:54:14
categories: arXiv_CV
tags: arXiv_CV CNN Classification Gradient_Descent
author: Adam Byerly, Tatiana Kalganova
mathjax: true
---

* content
{:toc}

##### Abstract
Capsules are the name given by Geoffrey Hinton to vector-valued neurons. Neural networks traditionally produce a scalar value for an activated neuron. Capsules, on the other hand, produce a vector of values, which Hinton argues correspond to a single, composite feature wherein the values of the components of the vectors indicate properties of the feature such as transformation or contrast. We present a new way of parameterizing and training capsules that we refer to as homogeneous vector capsules (HVCs). We demonstrate, experimentally, that altering a convolutional neural network (CNN) to use HVCs can achieve superior classification accuracy without increasing the number of parameters or operations in its architecture as compared to a CNN using a single final fully connected layer. Additionally, the introduction of HVCs enables the use of adaptive gradient descent, reducing the dependence a model's achievable accuracy has on the finely tuned hyperparameters of a non-adaptive optimizer. We demonstrate our method and results using two neural network architectures. First, a very simple monolithic CNN that when using HVCs achieved a 63% improvement in top-1 classification accuracy and a 35% improvement in top-5 classification accuracy over the baseline architecture. Second, with the CNN architecture referred to as Inception v3 that achieved similar accuracies both with and without HVCs. Additionally, the simple monolithic CNN when using HVCs showed no overfitting after more than 300 epochs whereas the baseline showed overfitting after 30 epochs. We use the ImageNet ILSVRC 2012 classification challenge dataset with both networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08676](http://arxiv.org/abs/1906.08676)

##### PDF
[http://arxiv.org/pdf/1906.08676](http://arxiv.org/pdf/1906.08676)

