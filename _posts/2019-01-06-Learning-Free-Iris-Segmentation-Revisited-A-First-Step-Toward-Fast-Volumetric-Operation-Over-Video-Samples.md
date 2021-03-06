---
layout: post
title: "Learning-Free Iris Segmentation Revisited: A First Step Toward Fast Volumetric Operation Over Video Samples"
date: 2019-01-06 17:22:08
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Jeffery Kinnison, Mateusz Trokielewicz, Camila Carballo, Adam Czajka, Walter Scheirer
mathjax: true
---

* content
{:toc}

##### Abstract
Subject matching performance in iris biometrics is contingent upon fast, high-quality iris segmentation. In many cases, iris biometrics acquisition equipment takes a number of images in sequence and combines the segmentation and matching results for each image to strengthen the result. To date, segmentation has occurred in 2D, operating on each image individually. But such methodologies, while powerful, do not take advantage of potential gains in performance afforded by treating sequential images as volumetric data. As a first step in this direction, we apply the Flexible Learning-Free Reconstructoin of Neural Volumes (FLoRIN) framework, an open source segmentation and reconstruction framework originally designed for neural microscopy volumes, to volumetric segmentation of iris videos. Further, we introduce a novel dataset of near-infrared iris videos, in which each subject's pupil rapidly changes size due to visible-light stimuli, as a test bed for FLoRIN. We compare the matching performance for iris masks generated by FLoRIN, deep-learning-based (SegNet), and Daugman's (OSIRIS) iris segmentation approaches. We show that by incorporating volumetric information, FLoRIN achieves a factor of 3.6 to an order of magnitude increase in throughput with only a minor drop in subject matching performance. We also demonstrate that FLoRIN-based iris segmentation maintains this speedup on low-resource hardware, making it suitable for embedded biometrics systems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.01575](http://arxiv.org/abs/1901.01575)

##### PDF
[http://arxiv.org/pdf/1901.01575](http://arxiv.org/pdf/1901.01575)

