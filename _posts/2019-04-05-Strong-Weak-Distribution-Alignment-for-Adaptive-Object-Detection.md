---
layout: post
title: "Strong-Weak Distribution Alignment for Adaptive Object Detection"
date: 2019-04-05 19:26:15
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Detection
author: Kuniaki Saito, Yoshitaka Ushiku, Tatsuya Harada, Kate Saenko
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an approach for unsupervised adaptation of object detectors from label-rich to label-poor domains which can significantly reduce annotation costs associated with detection. Recently, approaches that align distributions of source and target images using an adversarial loss have been proven effective for adapting object classifiers. However, for object detection, fully matching the entire distributions of source and target images to each other at the global image level may fail, as domains could have distinct scene layouts and different combinations of objects. On the other hand, strong matching of local features such as texture and color makes sense, as it does not change category level semantics. This motivates us to propose a novel method for detector adaptation based on strong local alignment and weak global alignment. Our key contribution is the weak alignment model, which focuses the adversarial alignment loss on images that are globally similar and puts less emphasis on aligning images that are globally dissimilar. Additionally, we design the strong domain alignment model to only look at local receptive fields of the feature map. We empirically verify the effectiveness of our method on four datasets comprising both large and small domain shifts. Our code is available at \url{this https URL}

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1812.04798](https://arxiv.org/abs/1812.04798)

##### PDF
[https://arxiv.org/pdf/1812.04798](https://arxiv.org/pdf/1812.04798)

