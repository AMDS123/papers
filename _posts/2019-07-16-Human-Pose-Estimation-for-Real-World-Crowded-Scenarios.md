---
layout: post
title: "Human Pose Estimation for Real-World Crowded Scenarios"
date: 2019-07-16 09:53:27
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Detection Recognition
author: Thomas Golda, Tobias Kalb, Arne Schumann, J&#xfc;rgen Beyerer
mathjax: true
---

* content
{:toc}

##### Abstract
Human pose estimation has recently made significant progress with the adoption of deep convolutional neural networks. Its many applications have attracted tremendous interest in recent years. However, many practical applications require pose estimation for human crowds, which still is a rarely addressed problem. In this work, we explore methods to optimize pose estimation for human crowds, focusing on challenges introduced with dense crowds, such as occlusions, people in close proximity to each other, and partial visibility of people. In order to address these challenges, we evaluate three aspects of a pose detection approach: i) a data augmentation method to introduce robustness to occlusions, ii) the explicit detection of occluded body parts, and iii) the use of the synthetic generated datasets. The first approach to improve the accuracy in crowded scenarios is to generate occlusions at training time using person and object cutouts from the object recognition dataset COCO (Common Objects in Context). Furthermore, the synthetically generated dataset JTA (Joint Track Auto) is evaluated for the use in real-world crowd applications. In order to overcome the transfer gap of JTA originating from a low pose variety and less dense crowds, an extension dataset is created to ease the use for real-world applications. Additionally, the occlusion flags provided with JTA are utilized to train a model, which explicitly distinguishes between occluded and visible body parts in two distinct branches. The combination of the proposed additions to the baseline method help to improve the overall accuracy by 4.7% AP and thereby provide comparable results to current state-of-the-art approaches on the respective dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06922](http://arxiv.org/abs/1907.06922)

##### PDF
[http://arxiv.org/pdf/1907.06922](http://arxiv.org/pdf/1907.06922)

