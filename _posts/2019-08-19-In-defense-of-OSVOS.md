---
layout: post
title: "In defense of OSVOS"
date: 2019-08-19 11:07:17
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Detection
author: Yu Liu, Yutong Dai, Anh-Dzung Doan, Lingqiao Liu, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
As a milestone for video object segmentation, one-shot video object segmentation (OSVOS) has achieved a large margin compared to the conventional optical-flow based methods regarding to the segmentation accuracy. Its excellent performance mainly benefit from the three-step training mechanism, that are: (1) acquiring object features on the base dataset (i.e. ImageNet), (2) training the parent network on the training set of the target dataset (i.e. DAVIS-2016) to be capable of differentiating the object of interest from the background. (3) online fine-tuning the interested object on the first frame of the target test set to overfit its appearance, then the model can be utilized to segment the same object in the rest frames of that video. In this paper, we argue that for the step (2), OSVOS has the limitation to 'overemphasize' the generic semantic object information while 'dilute' the instance cues of the object(s), which largely block the whole training process. Through adding a common module, video loss, which we formulate with various forms of constraints (including weighted BCE loss, high-dimensional triplet loss, as well as a novel mixed instance-aware video loss), to train the parent network in the step (2), the network is then better prepared for the step (3), i.e. online fine-tuning on the target instance. Through extensive experiments using different network structures as the backbone, we show that the proposed video loss module can improve the segmentation performance significantly, compared to that of OSVOS. Meanwhile, since video loss is a common module, it can be generalized to other fine-tuning based methods and similar vision tasks such as depth estimation and saliency detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06692](http://arxiv.org/abs/1908.06692)

##### PDF
[http://arxiv.org/pdf/1908.06692](http://arxiv.org/pdf/1908.06692)

