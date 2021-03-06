---
layout: post
title: "Online Multi-Object Tracking Framework with the GMPHD Filter and Occlusion Group Management"
date: 2019-07-31 07:36:09
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Detection
author: Young-min Song, Kwangjin Yoon, Young-Chul Yoon, Kin-Choong Yow, Moongu Jeon
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an efficient online multi-object tracking framework based on the GMPHD filter and occlusion group management scheme where the GMPHD filter utilizes hierarchical data association to reduce the false negatives caused by miss detection. The hierarchical data association consists of two steps: detection-to-track and track-to-track associations, which can recover the lost tracks and their switched IDs. In addition, the proposed framework is equipped with an object grouping management scheme which handles occlusion problems with two main parts. The first part is "track merging" which can merge the false positive tracks caused by false positive detections from occlusions, where the false positive tracks are usually occluded with a measure. The measure is the occlusion ratio between visual objects, sum-of-intersection-over-area (SIOA) we defined instead of the IOU metric. The second part is "occlusion group energy minimization (OGEM)" which prevents the occluded true positive tracks from false "track merging". We define each group of the occluded objects as an energy function and find an optimal hypothesis which makes the energy minimal. We evaluate the proposed tracker in benchmark datasets such as MOT15 and MOT17 which are built for multi-person tracking. An ablation study in training dataset shows that not only "track merging" and "OGEM" complement each other but also the proposed tracking method has more robust performance and less sensitive to parameters than baseline methods. Also, SIOA works better than IOU for various sizes of false positives. Experimental results show that the proposed tracker efficiently handles occlusion situations and achieves competitive performance compared to the state-of-the-art methods. Especially, our method shows the best multi-object tracking accuracy among the online and real-time executable methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.13347](http://arxiv.org/abs/1907.13347)

##### PDF
[http://arxiv.org/pdf/1907.13347](http://arxiv.org/pdf/1907.13347)

