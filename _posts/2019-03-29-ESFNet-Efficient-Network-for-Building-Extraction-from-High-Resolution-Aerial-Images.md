---
layout: post
title: "ESFNet: Efficient Network for Building Extraction from High-Resolution Aerial Images"
date: 2019-03-29 03:13:19
categories: arXiv_CV
tags: arXiv_CV Inference
author: Jingbo Lin, Houbing Song, Weipeng Jing
mathjax: true
---

* content
{:toc}

##### Abstract
Building footprint extraction from high-resolution aerial images is always an essential part of urban dynamic monitoring, planning and management. It has also been a challenging task in remote sensing research, due to complex environments and land cover objects in the high-resolution aerial images. In recent years, deep neural networks have made great achievement in improving accuracy of building extraction from remote sensing imagery. However, most of existing approaches usually requiring a large number of parameters and floating point operations for high accuracy, it leads to high memory consumption and low inference speed which are harmful to research. In this paper, we proposed a novel deep architecture named ESFNet which employs separable factorized residual block and utilizes the dilated convolutions, aiming to preserve slight accuracy loss with low computational cost and memory consumption. This is the first time introducing efficiency view of deep neural networks in remote sensing area. Our ESFNet is able to run at over 100 FPS on single Tesla V100, requires 6x less FLOPs and has 18x less parameters than state-of-the-art real-time architecture ERFNet while preserving similar accuracy without any additional context module, post-processing and pre-trained scheme. We evaluated our networks on WHU Building Dataset and compared it with other state-of-the-art architectures. The result and comprehensive analysis show that our networks are benefit to efficient remote sensing researches and applications, and can further extended to other areas. The code is public available at: https://github.com/mrluin/ESFNet-Pytorch

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.12337](http://arxiv.org/abs/1903.12337)

##### PDF
[http://arxiv.org/pdf/1903.12337](http://arxiv.org/pdf/1903.12337)

