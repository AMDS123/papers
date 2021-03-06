---
layout: post
title: "Watermark retrieval from 3D printed objects via synthetic data training"
date: 2019-05-23 15:12:01
categories: arXiv_CV
tags: arXiv_CV
author: Xin Zhang, Ning Jia, Ioannis Ivrissimtzis
mathjax: true
---

* content
{:toc}

##### Abstract
We present a deep neural network based method for the retrieval of watermarks from images of 3D printed objects. To deal with the variability of all possible 3D printing and image acquisition settings we train the network with synthetic data. The main simulator parameters such as texture, illumination and camera position are dynamically randomized in non-realistic ways, forcing the neural network to learn the intrinsic features of the 3D printed watermarks. At the end of the pipeline, the watermark, in the form of a two-dimensional bit array, is retrieved through a series of simple image processing and statistical operations applied on the confidence map generated by the neural network. The results demonstrate that the inclusion of synthetic DR data in the training set increases the generalization power of the network, which performs better on images from previously unseen 3D printed objects. We conclude that in our application domain of information retrieval from 3D printed objects, where access to the exact CAD files of the printed objects can be assumed, one can use inexpensive synthetic data to enhance neural network training, reducing the need for the labour intensive process of creating large amounts of hand labelled real data or the need to generate photorealistic synthetic data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09706](http://arxiv.org/abs/1905.09706)

##### PDF
[http://arxiv.org/pdf/1905.09706](http://arxiv.org/pdf/1905.09706)

