---
layout: post
title: "GreyReID: A Two-stream Deep Framework with RGB-grey Information for Person Re-identification"
date: 2019-08-14 14:24:34
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification
author: Lei Qi, Lei Wang, Jing Huo, Yinghuan Shi, Yang Gao
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we observe that most false positive images (i.e., different identities with query images) in the top ranking list usually have the similar color information with the query image in person re-identification (Re-ID). Meanwhile, when we use the greyscale images generated from RGB images to conduct the person Re-ID task, some hard query images can obtain better performance compared with using RGB images. Therefore, RGB and greyscale images seem to be complementary to each other for person Re-ID. In this paper, we aim to utilize both RGB and greyscale images to improve the person Re-ID performance. To this end, we propose a novel two-stream deep neural network with RGB-grey information, which can effectively fuse RGB and greyscale feature representations to enhance the generalization ability of Re-ID. Firstly, we convert RGB images to greyscale images in each training batch. Based on these RGB and greyscale images, we train the RGB and greyscale branches, respectively. Secondly, to build up connections between RGB and greyscale branches, we merge the RGB and greyscale branches into a new joint branch. Finally, we concatenate the features of all three branches as the final feature representation for Re-ID. Moreover, in the training process, we adopt the joint learning scheme to simultaneously train each branch by the independent loss function, which can enhance the generalization ability of each branch. Besides, a global loss function is utilized to further fine-tune the final concatenated feature. The extensive experiments on multiple benchmark datasets fully show that the proposed method can outperform the state-of-the-art person Re-ID methods. Furthermore, using greyscale images can indeed improve the person Re-ID performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.05142](http://arxiv.org/abs/1908.05142)

##### PDF
[http://arxiv.org/pdf/1908.05142](http://arxiv.org/pdf/1908.05142)

