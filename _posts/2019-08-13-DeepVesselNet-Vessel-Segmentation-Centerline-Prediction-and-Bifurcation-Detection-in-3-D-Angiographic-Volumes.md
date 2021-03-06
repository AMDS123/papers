---
layout: post
title: "DeepVesselNet: Vessel Segmentation, Centerline Prediction, and Bifurcation Detection in 3-D Angiographic Volumes"
date: 2019-08-13 12:50:47
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Transfer_Learning Deep_Learning Prediction Detection
author: Giles Tetteh, Velizar Efremov, Nils D. Forkert, Matthias Schneider, Jan Kirschke, Bruno Weber, Claus Zimmer, Marie Piraud, Bjoern H. Menze
mathjax: true
---

* content
{:toc}

##### Abstract
We present DeepVesselNet, an architecture tailored to the challenges faced when extracting vessel networks or trees and corresponding features in 3-D angiographic volumes using deep learning. We discuss the problems of low execution speed and high memory requirements associated with full 3-D convolutional networks, high-class imbalance arising from the low percentage of vessel voxels, and unavailability of accurately annotated training data - and offer solutions as the building blocks of DeepVesselNet. 
 First, we formulate 2-D orthogonal cross-hair filters which make use of 3-D context information at a reduced computational burden. Second, we introduce a class balancing cross-entropy loss function with false positive rate correction to handle the high-class imbalance and high false positive rate problems associated with existing loss functions. Finally, we generate synthetic dataset using a computational angiogenesis model capable of generating vascular trees under physiological constraints on local network structure and topology and use these data for transfer learning. 
 DeepVesselNet is optimized for segmenting and analyzing vessels, and we test the performance on a range of angiographic volumes including clinical MRA data of the human brain, as well as X-ray tomographic microscopy scans of the rat brain. Our experiments show that, by replacing 3-D filters with cross-hair filters in our network, we achieve over 23% improvement in speed, lower memory footprint, lower network complexity which prevents overfitting and comparable accuracy (with a Cox-Wilcoxon paired sample significance test p-value of 0.07 when compared to full 3-D filters). Our class balancing metric is crucial for training the network and transfer learning with synthetic data is an efficient, robust, and very generalizable approach leading to a network that excels in a variety of angiography segmentation tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.09340](http://arxiv.org/abs/1803.09340)

##### PDF
[http://arxiv.org/pdf/1803.09340](http://arxiv.org/pdf/1803.09340)

