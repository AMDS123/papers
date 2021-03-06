---
layout: post
title: "Data Augmentation for Object Detection via Progressive and Selective Instance-Switching"
date: 2019-06-02 07:31:36
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Hao Wang, Qilong Wang, Fan Yang, Weiqi Zhang, Wangmeng Zuo
mathjax: true
---

* content
{:toc}

##### Abstract
Collection of massive well-annotated samples is effective in improving object detection performance but is extremely laborious and costly. Instead of data collection and annotation, the recently proposed Cut-Paste methods [12, 15] show the potential to augment training dataset by cutting foreground objects and pasting them on proper new backgrounds. However, existing Cut-Paste methods cannot guarantee synthetic images always precisely model visual context, and all of them require external datasets. To handle above issues, this paper proposes a simple yet effective instance-switching (IS) strategy, which generates new training data by switching instances of same class from different images. Our IS naturally preserves contextual coherence in the original images while requiring no external dataset. For guiding our IS to obtain better object performance, we explore issues of instance imbalance and class importance in datasets, which frequently occur and bring adverse effect on detection performance. To this end, we propose a novel Progressive and Selective Instance-Switching (PSIS) method to augment training data for object detection. The proposed PSIS enhances instance balance by combining selective re-sampling with a class-balanced loss, and considers class importance by progressively augmenting training dataset guided by detection performance. The experiments are conducted on the challenging MS COCO benchmark, and results demonstrate our PSIS brings clear improvement over various state-of-the-art detectors (e.g., Faster R-CNN, FPN, Mask R-CNN and SNIPER), showing the superiority and generality of our PSIS. Code and models are available at: https://github.com/Hwang64/PSIS.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00358](http://arxiv.org/abs/1906.00358)

##### PDF
[http://arxiv.org/pdf/1906.00358](http://arxiv.org/pdf/1906.00358)

