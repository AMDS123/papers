---
layout: post
title: "Boosting Resolution and Recovering Texture of micro-CT Images with Deep Learning"
date: 2019-07-15 04:32:50
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution Object_Detection GAN Deep_Learning Detection
author: Ying Da Wang, Ryan T. Armstrong, Peyman Mostaghimi
mathjax: true
---

* content
{:toc}

##### Abstract
Digital Rock Imaging is constrained by detector hardware, and a trade-off between the image field of view (FOV) and the image resolution must be made. This can be compensated for with super resolution (SR) techniques that take a wide FOV, low resolution (LR) image, and super resolve a high resolution (HR), high FOV image. The Enhanced Deep Super Resolution Generative Adversarial Network (EDSRGAN) is trained on the Deep Learning Digital Rock Super Resolution Dataset, a diverse compilation 12000 of raw and processed uCT images. The network shows comparable performance of 50% to 70% reduction in relative error over bicubic interpolation. GAN performance in recovering texture shows superior visual similarity compared to SRCNN and other methods. Difference maps indicate that the SRCNN section of the SRGAN network recovers large scale edge (grain boundaries) features while the GAN network regenerates perceptually indistinguishable high frequency texture. Network performance is generalised with augmentation, showing high adaptability to noise and blur. HR images are fed into the network, generating HR-SR images to extrapolate network performance to sub-resolution features present in the HR images themselves. Results show that under-resolution features such as dissolved minerals and thin fractures are regenerated despite the network operating outside of trained specifications. Comparison with Scanning Electron Microscope images shows details are consistent with the underlying geometry of the sample. Recovery of textures benefits the characterisation of digital rocks with a high proportion of under-resolution micro-porous features, such as carbonate and coal samples. Images that are normally constrained by the mineralogy of the rock (coal), by fast transient imaging (waterflooding), or by the energy of the source (microporosity), can be super resolved accurately for further analysis downstream.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07131](http://arxiv.org/abs/1907.07131)

##### PDF
[http://arxiv.org/pdf/1907.07131](http://arxiv.org/pdf/1907.07131)

