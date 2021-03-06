---
layout: post
title: "Neural Architecture Search for Deep Face Recognition"
date: 2019-04-21 01:05:41
categories: arXiv_CV
tags: arXiv_CV Knowledge GAN Face Reinforcement_Learning CNN Image_Classification Classification Recognition Face_Recognition
author: Ning Zhu, Xiaolong Bai
mathjax: true
---

* content
{:toc}

##### Abstract
By the widespread popularity of electronic devices, the emergence of biometric technology has brought significant convenience to user authentication compared with the traditional password and mode unlocking. Among many biological characteristics, the face is a universal and irreplaceable feature that does not need too much cooperation and can significantly improve the user's experience at the same time. Face recognition is one of the main functions of electronic equipment propaganda. Hence it's virtually worth researching in computer vision. Previous work in this field has focused on two directions: converting loss function to improve recognition accuracy in traditional deep convolution neural networks (Resnet); combining the latest loss function with the lightweight system (MobileNet) to reduce network size at the minimal expense of accuracy. But none of these has changed the network structure. With the development of AutoML, neural architecture search (NAS) has shown excellent performance in the benchmark of image classification. In this paper, we integrate NAS technology into face recognition to customize a more suitable network. We quote the framework of neural architecture search which trains child and controller network alternately. At the same time, we mutate NAS by incorporating evaluation latency into rewards of reinforcement learning and utilize policy gradient algorithm to search the architecture automatically with the most classical cross-entropy loss. The network architectures we searched out have got state-of-the-art accuracy in the large-scale face dataset, which achieves 98.77% top-1 in MS-Celeb-1M and 99.89% in LFW with relatively small network size. To the best of our knowledge, this proposal is the first attempt to use NAS to solve the problem of Deep Face Recognition and achieve the best results in this domain.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09523](http://arxiv.org/abs/1904.09523)

##### PDF
[http://arxiv.org/pdf/1904.09523](http://arxiv.org/pdf/1904.09523)

