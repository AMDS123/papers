---
layout: post
title: "Plug and play methods for magnetic resonance imaging"
date: 2019-03-20 16:59:04
categories: arXiv_CV
tags: arXiv_CV Review Deep_Learning
author: Rizwan Ahmad, Charles A. Bouman, Gregery T. Buzzard, Stanley Chan, Edward T. Reehorst, Philip Schniter
mathjax: true
---

* content
{:toc}

##### Abstract
Magnetic Resonance Imaging (MRI) is a non-invasive diagnostic tool that provides excellent soft-tissue contrast without the use of ionizing radiation. But, compared to other clinical imaging modalities (e.g., CT or ultrasound), the data acquisition process for MRI is inherently slow. Furthermore, dynamic applications demand collecting a series of images in quick succession. As a result, reducing acquisition time and improving imaging quality for undersampled datasets have been active areas of research for the last two decades. The combination of parallel imaging and compressive sensing (CS) has been shown to benefit a wide range of MRI applications. More recently, deep learning techniques have been shown to outperform CS methods. Some of these techniques pose the MRI reconstruction as a direct inversion problem and tackle it by training a deep neural network (DNN) to map from the measured Fourier samples and the final image. Considering that the forward model in MRI changes from one dataset to the next, such methods have to be either trained over a large and diverse corpus of data or limited to a specific application, and even then they cannot ensure data consistency. An alternative is to use "plug-and-play" (PnP) algorithms, which iterate image denoising with forward-model based signal recovery. PnP algorithms are an excellent fit for compressive MRI because they decouple image modeling from the forward model, which can change significantly among different scans due to variations in the coil sensitivity maps, sampling patterns, and image resolution. Consequently, with PnP, state-of-the-art image-denoising techniques, such as those based on DNNs, can be directly exploited for compressive MRI image reconstruction. The objective of this article is two-fold: i) to review recent advances in plug-and-play methods, and ii) to discuss their application to compressive MRI image reconstruction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.08616](http://arxiv.org/abs/1903.08616)

##### PDF
[http://arxiv.org/pdf/1903.08616](http://arxiv.org/pdf/1903.08616)

