---
layout: post
title: "RxNN: A Framework for Evaluating Deep Neural Networks on Resistive Crossbars"
date: 2019-01-18 15:20:13
categories: arXiv_CV
tags: arXiv_CV Knowledge Quantitative
author: Shubham Jain, Abhronil Sengupta, Kaushik Roy, Anand Raghunathan
mathjax: true
---

* content
{:toc}

##### Abstract
Resistive crossbars have emerged as promising building blocks for realizing DNNs due to their ability to compactly and efficiently realize the dominant DNN computational kernel, viz., vector-matrix multiplication. However, a key challenge with resistive crossbars is that they suffer from a range of device and circuit level non-idealities such as interconnect parasitics, peripheral circuits, sneak paths, and process variations. These non-idealities can lead to errors in vector-matrix multiplication that eventually degrade the DNN's accuracy. There has been no study of the impact of non-idealities on the accuracy of large-scale DNNs, in part because existing device and circuit models are infeasible to use in application-level evaluation. In this work, we present a fast and accurate simulation framework to enable evaluation and re-training of large-scale DNNs on resistive crossbar based hardware fabrics. 
 We first characterize the impact of crossbar non-idealities on errors incurred in the realized vector-matrix multiplications and observe that the errors have significant data and hardware-instance dependence that should be considered. We propose a Fast Crossbar Model (FCM) to accurately capture the errors arising due to crossbar non-idealities while being four-to-five orders of magnitude faster than circuit simulation. Finally, we develop RxNN, a software framework to evaluate and re-train DNNs on resistive crossbar systems. RxNN is based on the popular Caffe machine learning framework, and we use it to evaluate a suite of large-scale DNNs developed for the ImageNet Challenge (ILSVRC). Our experiments reveal that resistive crossbar non-idealities can lead to significant accuracy degradations (9.6%-32%) for these large-scale DNNs. To the best of our knowledge, this work is the first quantitative evaluation of the accuracy of large-scale DNNs on resistive crossbar based hardware.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.00072](http://arxiv.org/abs/1809.00072)

##### PDF
[http://arxiv.org/pdf/1809.00072](http://arxiv.org/pdf/1809.00072)

