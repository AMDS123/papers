---
layout: post
title: "Spatial Semantic Regularisation for Large Scale Object Detection"
date: 2015-10-10 15:15:45
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Detection Relation
author: Damian Mrowca, Marcus Rohrbach, Judy Hoffman, Ronghang Hu, Kate Saenko, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
Large scale object detection with thousands of classes introduces the problem of many contradicting false positive detections, which have to be suppressed. Class-independent non-maximum suppression has traditionally been used for this step, but it does not scale well as the number of classes grows. Traditional non-maximum suppression does not consider label- and instance-level relationships nor does it allow an exploitation of the spatial layout of detection proposals. We propose a new multi-class spatial semantic regularisation method based on affinity propagation clustering, which simultaneously optimises across all categories and all proposed locations in the image, to improve both the localisation and categorisation of selected detection proposals. Constraints are shared across the labels through the semantic WordNet hierarchy. Our approach proves to be especially useful in large scale settings with thousands of classes, where spatial and semantic interactions are very frequent and only weakly supervised detectors can be built due to a lack of bounding box annotations. Detection experiments are conducted on the ImageNet and COCO dataset, and in settings with thousands of detected categories. Our method provides a significant precision improvement by reducing false positives, while simultaneously improving the recall.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1510.02949](https://arxiv.org/abs/1510.02949)

##### PDF
[https://arxiv.org/pdf/1510.02949](https://arxiv.org/pdf/1510.02949)

