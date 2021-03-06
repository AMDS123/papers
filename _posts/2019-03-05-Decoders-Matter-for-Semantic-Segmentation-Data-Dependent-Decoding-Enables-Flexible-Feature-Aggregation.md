---
layout: post
title: "Decoders Matter for Semantic Segmentation: Data-Dependent Decoding Enables Flexible Feature Aggregation"
date: 2019-03-05 23:59:41
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Prediction
author: Zhi Tian, Chunhua Shen, Tong He, Youliang Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Recent semantic segmentation methods exploit encoder-decoder architectures to produce the desired pixel-wise segmentation prediction. The last layer of the decoders is typically a bilinear upsampling procedure to recover the final pixel-wise prediction. We empirically show that this oversimple and data-independent bilinear upsampling may lead to sub-optimal results. 
 In this work, we propose a data-dependent upsampling (DUpsampling) to replace bilinear, which takes advantages of the redundancy in the label space of semantic segmentation and is able to recover the pixel-wise prediction from low-resolution outputs of CNNs. The main advantage of the new upsampling layer lies in that with a relatively lower-resolution feature map such as $\frac{1}{16}$ or $\frac{1}{32}$ of the input size, we can achieve even better segmentation accuracy, significantly reducing computation complexity. This is made possible by 1) the new upsampling layer's much improved reconstruction capability; and more importantly 2) the DUpsampling based decoder's flexibility in leveraging almost arbitrary combinations of the CNN encoders' features. Experiments demonstrate that our proposed decoder outperforms the state-of-the-art decoder, with only $\sim$20\% of computation. Finally, without any post-processing, the framework equipped with our proposed decoder achieves new state-of-the-art performance on two datasets: 88.1\% mIOU on PASCAL VOC with 30\% computation of the previously best model; and 52.5\% mIOU on PASCAL Context.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.02120](http://arxiv.org/abs/1903.02120)

##### PDF
[http://arxiv.org/pdf/1903.02120](http://arxiv.org/pdf/1903.02120)

