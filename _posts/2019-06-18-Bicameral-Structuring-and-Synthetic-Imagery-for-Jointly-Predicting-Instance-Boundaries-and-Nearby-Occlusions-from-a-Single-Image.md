---
layout: post
title: "Bicameral Structuring and Synthetic Imagery for Jointly Predicting Instance Boundaries and Nearby Occlusions from a Single Image"
date: 2019-06-18 10:20:17
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Detection
author: Matthieu Grard (imagine), Liming Chen (imagine), Emmanuel Dellandr&#xe9;a (imagine)
mathjax: true
---

* content
{:toc}

##### Abstract
Oriented boundary detection is a challenging task aimed at both delineating category-agnostic object instances and inferring their spatial layout from a single RGB image. State-of-the-art deep convolutional networks for this task rely on two independent streams that predict boundaries and occlusions respectively, although both require similar local and global cues, and occlusions cause boundaries. We therefore propose a fully convolutional bicameral structuring, composed of two cascaded decoders sharing one deep encoder, linked altogether by skip connections to combine local and global features, for jointly predicting instance boundaries and their unoccluded side. Furthermore, state-of-the-art datasets contain real images with few instances and occlusions mostly due to objects occluding the background, thereby missing meaningful occlusions between instances. For evaluating the missing scenario of dense piles of objects as well, we introduce synthetic data (Mikado), which extensibly contains more instances and inter-instance occlusions per image than the PASCAL Instance Occlusion Dataset (PIOD), the COCO Amodal dataset (COCOA), and the Densely Segmented Supermarket Amodal dataset (D2SA). We show that the proposed network design outperforms the two-stream baseline and alternative archiectures for oriented boundary detection on both PIOD and Mikado, and the amodal segmentation approach on COCOA as well. Our experiments on D2SA also show that Mikado is plausible in the sense that it enables the learning of performance-enhancing representations transferable to real data, while drastically reducing the need of hand-made annotations for finetuning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07480](http://arxiv.org/abs/1906.07480)

##### PDF
[http://arxiv.org/pdf/1906.07480](http://arxiv.org/pdf/1906.07480)

