---
layout: post
title: "Image classification and retrieval with random depthwise signed convolutional neural networks"
date: 2019-03-15 21:20:48
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Yunzhe Xue, Usman Roshan
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a random convolutional neural network to generate a feature space in which we study image classification and retrieval performance. Put briefly we apply random convolutional blocks followed by global average pooling to generate a new feature, and we repeat this k times to produce a k-dimensional feature space. This can be interpreted as partitioning the space of image patches with random hyperplanes which we formalize as a random depthwise convolutional neural network. In the network's final layer we perform image classification and retrieval with the linear support vector machine and k-nearest neighbor classifiers and study other empirical properties. We show that the ratio of image pixel distribution similarity across classes to within classes is higher in our network's final layer compared to the input space. When we apply the linear support vector machine for image classification we see that the accuracy is higher than if we were to train just the final layer of VGG16, ResNet18, and DenseNet40 with random weights. In the same setting we compare it to an unsupervised feature learning method and find our accuracy to be comparable on CIFAR10 but higher on CIFAR100 and STL10. We see that the accuracy is not far behind that of trained networks, particularly in the top-k setting. For example the top-2 accuracy of our network is near 90% on both CIFAR10 and a 10-class mini ImageNet, and 85% on STL10. We find that k-nearest neighbor gives a comparable precision on the Corel Princeton Image Similarity Benchmark than if we were to use the final layer of trained networks. As with other networks we find that our network fails to a black box attack even though we lack a gradient and use the sign activation. We highlight sensitivity of our network to background as a potential pitfall and an advantage. Overall our work pushes the boundary of what can be achieved with random weights.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.05789](http://arxiv.org/abs/1806.05789)

##### PDF
[http://arxiv.org/pdf/1806.05789](http://arxiv.org/pdf/1806.05789)

