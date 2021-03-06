---
layout: post
title: "Accurate and Robust Pulmonary Nodule Detection by 3D Feature Pyramid Network with Self-supervised Feature Learning"
date: 2019-07-25 21:00:29
categories: arXiv_CV
tags: arXiv_CV Tracking Deep_Learning Detection
author: Jingya Liu, Liangliang Cao, Oguz Akin, Yingli Tian
mathjax: true
---

* content
{:toc}

##### Abstract
Accurate detection of pulmonary nodules with high sensitivity and specificity is essential for automatic lung cancer diagnosis from CT scans. Although many deep learning-based algorithms make great progress for improving the accuracy of nodule detection, the high false positive rate is still a challenging problem which limits the automatic diagnosis in routine clinical practice. Moreover, the CT scans collected from multiple manufacturers may affect the robustness of Computer-aided diagnosis (CAD) due to the differences in intensity scales and machine noises. In this paper, we propose a novel self-supervised learning assisted pulmonary nodule detection framework based on a 3D Feature Pyramid Network (3DFPN) to improve the sensitivity of nodule detection by employing multi-scale features to increase the resolution of nodules, as well as a parallel top-down path to transit the high-level semantic features to complement low-level general features. Furthermore, a High Sensitivity and Specificity (HS2) network is introduced to eliminate the false positive nodule candidates by tracking the appearance changes in continuous CT slices of each nodule candidate on Location History Images (LHI). In addition, in order to improve the performance consistency of the proposed framework across data captured by different CT scanners without using additional annotations, an effective self-supervised learning schema is applied to learn spatiotemporal features of CT scans from large-scale unlabeled data. The performance and robustness of our method are evaluated on several publicly available datasets with significant performance improvements. The proposed framework is able to accurately detect pulmonary nodules with high sensitivity and specificity and achieves 90.6% sensitivity with 1/8 false positive per scan which outperforms the state-of-the-art results 15.8% on LUNA16 dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11704](http://arxiv.org/abs/1907.11704)

##### PDF
[http://arxiv.org/pdf/1907.11704](http://arxiv.org/pdf/1907.11704)

