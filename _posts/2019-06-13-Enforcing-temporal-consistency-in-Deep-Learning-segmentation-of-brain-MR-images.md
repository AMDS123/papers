---
layout: post
title: "Enforcing temporal consistency in Deep Learning segmentation of brain MR images"
date: 2019-06-13 08:33:23
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Deep_Learning Relation
author: Malav Bateriwala, Pierrick Bourgeat
mathjax: true
---

* content
{:toc}

##### Abstract
Longitudinal analysis has great potential to reveal developmental trajectories and monitor disease progression in medical imaging. This process relies on consistent and robust joint 4D segmentation. Traditional techniques are dependent on the similarity of images over time and the use of subject-specific priors to reduce random variation and improve the robustness and sensitivity of the overall longitudinal analysis. This is however slow and computationally intensive as subject-specific templates need to be rebuilt every time. The focus of this work to accelerate this analysis with the use of deep learning. The proposed approach is based on deep CNNs and incorporates semantic segmentation and provides a longitudinal relationship for the same subject. The proposed approach is based on deep CNNs and incorporates semantic segmentation and provides a longitudinal relationship for the same subject. The state of art using 3D patches as inputs to modified Unet provides results around ${0.91 \pm 0.5}$ Dice and using multi-view atlas in CNNs provide around the same results. In this work, different models are explored, each offers better accuracy and fast results while increasing the segmentation quality. These methods are evaluated on 135 scans from the EADC-ADNI Harmonized Hippocampus Protocol. Proposed CNN based segmentation approaches demonstrate how 2D segmentation using prior slices can provide similar results to 3D segmentation while maintaining good continuity in the 3D dimension and improved speed. Just using 2D modified sagittal slices provide us a better Dice and longitudinal analysis for a given subject. For the ADNI dataset, using the simple UNet CNN technique gives us ${0.84 \pm 0.5}$ and while using modified CNN techniques on the same input yields ${0.89 \pm 0.5}$. Rate of atrophy and RMS error are calculated for several test cases using various methods and analyzed.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07160](http://arxiv.org/abs/1906.07160)

##### PDF
[http://arxiv.org/pdf/1906.07160](http://arxiv.org/pdf/1906.07160)

