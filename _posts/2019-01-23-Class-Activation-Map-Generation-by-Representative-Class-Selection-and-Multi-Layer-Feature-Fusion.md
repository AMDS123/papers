---
layout: post
title: "Class Activation Map Generation by Representative Class Selection and Multi-Layer Feature Fusion"
date: 2019-01-23 01:39:08
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification
author: Fanman Meng, Kaixu Huang, Hongliang Li, Qingbo Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Existing method generates class activation map (CAM) by a set of fixed classes (i.e., using all the classes), while the discriminative cues between class pairs are not considered. Note that activation maps by considering different class pair are complementary, and therefore can provide more discriminative cues to overcome the shortcoming of the existing CAM generation that the highlighted regions are usually local part regions rather than global object regions due to the lack of object cues. In this paper, we generate CAM by using a few of representative classes, with aim of extracting more discriminative cues by considering each class pair to obtain CAM more globally. The advantages are twofold. Firstly, the representative classes are able to obtain activation regions that are complementary to each other, and therefore leads to generating activation map more accurately. Secondly, we only need to consider a small number of representative classes, making the CAM generation suitable for small networks. We propose a clustering based method to select the representative classes. Multiple binary classification models rather than a multiple class classification model are used to generate the CAM. Moreover, we propose a multi-layer fusion based CAM generation method to simultaneously combine high-level semantic features and low-level detail features. We validate the proposed method on the PASCAL VOC and COCO database in terms of segmentation groundtruth. Various networks such as classical network (Resnet-50, Resent-101 and Resnet-152) and small network (VGG-19, Resnet-18 and Mobilenet) are considered. Experimental results show that the proposed method improves the CAM generation obviously.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07683](http://arxiv.org/abs/1901.07683)

##### PDF
[http://arxiv.org/pdf/1901.07683](http://arxiv.org/pdf/1901.07683)

