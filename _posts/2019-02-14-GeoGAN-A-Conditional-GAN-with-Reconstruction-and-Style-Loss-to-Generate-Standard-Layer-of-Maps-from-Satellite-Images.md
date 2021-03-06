---
layout: post
title: "GeoGAN: A Conditional GAN with Reconstruction and Style Loss to Generate Standard Layer of Maps from Satellite Images"
date: 2019-02-14 21:41:18
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Style_Transfer Survey Embedding Quantitative
author: Swetava Ganguli, Pedro Garzon, Noa Glaser
mathjax: true
---

* content
{:toc}

##### Abstract
Automatically generating maps from satellite images is an important task. There is a body of literature which tries to address this challenge. We created a more expansive survey of the task by experimenting with different models and adding new loss functions to improve results. We created a database of pairs of satellite images and the corresponding map of the area. Our model translates the satellite image to the corresponding standard layer map image using three main model architectures: (i) a conditional Generative Adversarial Network (GAN) which compresses the images down to a learned embedding, (ii) a generator which is trained as a normalizing flow (RealNVP) model, and (iii) a conditional GAN where the generator translates via a series of convolutions to the standard layer of a map and the discriminator input is the concatenation of the real/generated map and the satellite image. Model (iii) was by far the most promising of three models. To improve the results we also added a reconstruction loss and style transfer loss in addition to the GAN losses. The third model architecture produced the best quality of sampled images. In contrast to the other generative model where evaluation of the model is a challenging problem. since we have access to the real map for a given satellite image, we are able to assign a quantitative metric to the quality of the generated images in addition to inspecting them visually. While we are continuing to work on increasing the accuracy of the model, one challenge has been the coarse resolution of the data which upper-bounds the quality of the results of our model. Nevertheless, as will be seen in the results, the generated map is more accurate in the features it produces since the generator architecture demands a pixel-wise image translation/pixel-wise coloring. A video presentation summarizing this paper is available at: https://youtu.be/Ur0flOX-Ji0

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.05611](http://arxiv.org/abs/1902.05611)

##### PDF
[http://arxiv.org/pdf/1902.05611](http://arxiv.org/pdf/1902.05611)

