---
layout: post
title: "Spatial Group-wise Enhance: Improving Semantic Feature Learning in Convolutional Networks"
date: 2019-05-23 13:36:54
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention CNN Detection Recognition
author: Xiang Li, Xiaolin Hu, Jian Yang
mathjax: true
---

* content
{:toc}

##### Abstract
The Convolutional Neural Networks (CNNs) generate the feature representation of complex objects by collecting hierarchical and different parts of semantic sub-features. These sub-features can usually be distributed in grouped form in the feature vector of each layer, representing various semantic entities. However, the activation of these sub-features is often spatially affected by similar patterns and noisy backgrounds, resulting in erroneous localization and identification. We propose a Spatial Group-wise Enhance (SGE) module that can adjust the importance of each sub-feature by generating an attention factor for each spatial location in each semantic group, so that every individual group can autonomously enhance its learnt expression and suppress possible noise. The attention factors are only guided by the similarities between the global and local feature descriptors inside each group, thus the design of SGE module is extremely lightweight with \emph{almost no extra parameters and calculations}. Despite being trained with only category supervisions, the SGE component is extremely effective in highlighting multiple active areas with various high-order semantics (such as the dog's eyes, nose, etc.). When integrated with popular CNN backbones, SGE can significantly boost the performance of image recognition tasks. Specifically, based on ResNet50 backbones, SGE achieves 1.2\% Top-1 accuracy improvement on the ImageNet benchmark and 1.0$\sim$2.0\% AP gain on the COCO benchmark across a wide range of detectors (Faster/Mask/Cascade RCNN and RetinaNet). Codes and pretrained models are available at https://github.com/implus/PytorchInsight.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09646](http://arxiv.org/abs/1905.09646)

##### PDF
[http://arxiv.org/pdf/1905.09646](http://arxiv.org/pdf/1905.09646)

