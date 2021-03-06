---
layout: post
title: "Semantic Image Networks for Human Action Recognition"
date: 2019-01-21 05:27:24
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Action_Recognition RNN Recognition
author: Sunder Ali Khowaja, Seok-Lyong Lee
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose the use of a semantic image, an improved representation for video analysis, principally in combination with Inception networks. The semantic image is obtained by applying localized sparse segmentation using global clustering (LSSGC) prior to the approximate rank pooling which summarizes the motion characteristics in single or multiple images. It incorporates the background information by overlaying a static background from the window onto the subsequent segmented frames. The idea is to improve the action-motion dynamics by focusing on the region which is important for action recognition and encoding the temporal variances using the frame ranking method. We also propose the sequential combination of Inception-ResNetv2 and long-short-term memory network (LSTM) to leverage the temporal variances for improved recognition performance. Extensive analysis has been carried out on UCF101 and HMDB51 datasets which are widely used in action recognition studies. We show that (i) the semantic image generates better activations and converges faster than its original variant, (ii) using segmentation prior to approximate rank pooling yields better recognition performance, (iii) The use of LSTM leverages the temporal variance information from approximate rank pooling to model the action behavior better than the base network, (iv) the proposed representations can be adaptive as they can be used with existing methods such as temporal segment networks to improve the recognition performance, and (v) our proposed four-stream network architecture comprising of semantic images and semantic optical flows achieves state-of-the-art performance, 95.9% and 73.5% recognition accuracy on UCF101 and HMDB51, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06792](http://arxiv.org/abs/1901.06792)

##### PDF
[http://arxiv.org/pdf/1901.06792](http://arxiv.org/pdf/1901.06792)

