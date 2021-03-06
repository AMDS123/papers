---
layout: post
title: "rVAD: An Unsupervised Segment-Based Robust Voice Activity Detection Method"
date: 2019-06-09 07:51:23
categories: arXiv_CL
tags: arXiv_CL Detection
author: Zheng-Hua Tan, Achintya kr. Sarkar, Najim Dehak
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an unsupervised segment-based method for robust voice activity detection (rVAD). The method consists of two passes of denoising followed by a voice activity detection (VAD) stage. In the first pass, high-energy segments in a speech signal are detected by using a posteriori signal-to-noise ratio (SNR) weighted energy difference and if no pitch is detected within a segment, the segment is considered as a high-energy noise segment and set to zero. In the second pass, the speech signal is denoised by a speech enhancement method, for which several methods are explored. Next, neighbouring frames with pitch are grouped together to form pitch segments, and based on speech statistics, the pitch segments are further extended from both ends in order to include both voiced and unvoiced sounds and likely non-speech parts as well. In the end, a posteriori SNR weighted energy difference is applied to the extended pitch segments of the denoised speech signal for detecting voice activity. We evaluate the VAD performance of the proposed method using two databases, RATS and Aurora-2, which contain a large variety of noise conditions. The rVAD method is further evaluated, in terms of speaker verification performance, on the RedDots 2016 challenge database and its noise-corrupted versions. Experiment results show that rVAD is compared favourably with a number of existing methods. In addition, we present a modified version of rVAD where computationally intensive pitch extraction is replaced by computationally efficient spectral flatness calculation. The modified version significantly reduces the computational complexity at the cost of moderately inferior VAD performance, which is an advantage when processing a large amount of data and running on low resource devices. The source code of rVAD is made publicly available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03588](http://arxiv.org/abs/1906.03588)

##### PDF
[http://arxiv.org/pdf/1906.03588](http://arxiv.org/pdf/1906.03588)

