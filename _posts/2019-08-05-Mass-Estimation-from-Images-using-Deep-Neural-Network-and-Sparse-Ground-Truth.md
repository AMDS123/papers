---
layout: post
title: "Mass Estimation from Images using Deep Neural Network and Sparse Ground Truth"
date: 2019-08-05 02:59:18
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge Optimization Classification Deep_Learning Prediction
author: Muhammad K A Hamdan, John Just
mathjax: true
---

* content
{:toc}

##### Abstract
Supervised learning is the workhorse for regression and classification tasks, but the standard approach presumes ground truth for every measurement. In real world applications, limitations due to expense or general in-feasibility due to the specific application are common. In the context of agriculture applications, yield monitoring is one such example where simple-physics based measurements such as volume or force-impact have been used to quantify mass flow, which incur error due to sensor calibration. By utilizing semi-supervised deep learning with gradient aggregation and a sequence of images, in this work it is shown we can accurate estimate a physical quantity (mass) with complex data structures and sparse ground truth. Using a vision system capturing images of a sugarcane elevator and running bamboo under controlled testing as a surrogate material to harvesting sugarcane, mass is accurately predicted from images by training a DNN using only final load weights. The DNN succeeds in capturing the complex density physics of random stacking of slender rods internally as part of the mass prediction model, and surpasses older volumetric-based methods for mass prediction. Furthermore, by incorporating knowledge about the system physics through the DNN architecture and penalty terms, improvements in prediction accuracy and stability, as well as faster learning are obtained. It is shown that the classic nonlinear regression optimization can be reformulated with an aggregation term with some independence assumptions to achieve this feat. Since the number of images for any given run are too large to fit on many GPUs, an implementation is shown that compensates for the limited memory but still achieve fast training times. The same approach presented herein could be applied to other applications like yield monitoring on grain combines or other harvesters using vision or other instrumentation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.04387](http://arxiv.org/abs/1908.04387)

##### PDF
[http://arxiv.org/pdf/1908.04387](http://arxiv.org/pdf/1908.04387)

