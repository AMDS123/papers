---
layout: post
title: "An active search strategy for efficient object class detection"
date: 2015-04-14 11:29:51
categories: arXiv_CV
tags: arXiv_CV Object_Detection GAN Detection Relation
author: Abel Gonzalez-Garcia, Alexander Vezhnevets, Vittorio Ferrari
mathjax: true
---

* content
{:toc}

##### Abstract
Object class detectors typically apply a window classifier to all the windows in a large set, either in a sliding window manner or using object proposals. In this paper, we develop an active search strategy that sequentially chooses the next window to evaluate based on all the information gathered before. This results in a substantial reduction in the number of classifier evaluations and in a more elegant approach in general. Our search strategy is guided by two forces. First, we exploit context as the statistical relation between the appearance of a window and its location relative to the object, as observed in the training set. This enables to jump across distant regions in the image (e.g. observing a sky region suggests that cars might be far below) and is done efficiently in a Random Forest framework. Second, we exploit the score of the classifier to attract the search to promising areas surrounding a highly scored window, and to keep away from areas near low scored ones. Our search strategy can be applied on top of any classifier as it treats it as a black-box. In experiments with R-CNN on the challenging SUN2012 dataset, our method matches the detection accuracy of evaluating all windows independently, while evaluating 9x fewer windows.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1412.3709](https://arxiv.org/abs/1412.3709)

##### PDF
[https://arxiv.org/pdf/1412.3709](https://arxiv.org/pdf/1412.3709)

