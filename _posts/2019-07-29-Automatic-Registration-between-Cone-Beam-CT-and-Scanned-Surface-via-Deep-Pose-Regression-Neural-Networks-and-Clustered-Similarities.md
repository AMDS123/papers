---
layout: post
title: "Automatic Registration between Cone-Beam CT and Scanned Surface via Deep-Pose Regression Neural Networks and Clustered Similarities"
date: 2019-07-29 07:46:01
categories: arXiv_CV
tags: arXiv_CV Face
author: Minyoung Chung, Jingyu Lee, Wisoo Song, Youngchan Song, Il-Hyung Yang, Jeongjin Lee, Yeong-Gil Shin
mathjax: true
---

* content
{:toc}

##### Abstract
Computerized registration between maxillofacial cone-beam computed tomography (CT) images and a scanned dental model is an essential prerequisite in surgical planning for dental implants or orthognathic surgery. We propose a novel method that performs fully automatic registration between a cone-beam CT image and an optically scanned model. To build a robust and automatic initial registration method, our method applies deep-pose regression neural networks in a reduced domain (i.e., 2-dimensional image). Subsequently, fine registration is performed via optimal clusters. Majority voting system achieves globally optimal transformations while each cluster attempts to optimize local transformation parameters. The coherency of clusters determines their candidacy for the optimal cluster set. The outlying regions in the iso-surface are effectively removed based on the consensus among the optimal clusters. The accuracy of registration was evaluated by the Euclidean distance of 10 landmarks on a scanned model which were annotated by the experts in the field. The experiments show that the proposed method's registration accuracy, measured in landmark distance, outperforms other existing methods by 30.77% to 70%. In addition to achieving high accuracy, our proposed method requires neither human-interactions nor priors (e.g., iso-surface extraction). The main significance of our study is twofold: 1) the employment of light-weighted neural networks which indicates the applicability of neural network in extracting pose cues that can be easily obtained and 2) the introduction of an optimal cluster-based registration method that can avoid metal artifacts during the matching procedures.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12250](http://arxiv.org/abs/1907.12250)

##### PDF
[http://arxiv.org/pdf/1907.12250](http://arxiv.org/pdf/1907.12250)

