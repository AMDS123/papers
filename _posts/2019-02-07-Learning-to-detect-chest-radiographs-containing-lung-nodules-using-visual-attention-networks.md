---
layout: post
title: "Learning to detect chest radiographs containing lung nodules using visual attention networks"
date: 2019-02-07 10:52:39
categories: arXiv_CV
tags: arXiv_CV Salient Attention Reinforcement_Learning CNN Classification Detection
author: Emanuele Pesce, Petros-Pavlos Ypsilantis, Samuel Withey, Robert Bakewell, Vicky Goh, Giovanni Montana
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning approaches hold great potential for the automated detection of lung nodules in chest radiographs, but training the algorithms requires vary large amounts of manually annotated images, which are difficult to obtain. Weak labels indicating whether a radiograph is likely to contain pulmonary nodules are typically easier to obtain at scale by parsing historical free-text radiological reports associated to the radiographs. Using a repositotory of over 700,000 chest radiographs, in this study we demonstrate that promising nodule detection performance can be achieved using weak labels through convolutional neural networks for radiograph classification. We propose two network architectures for the classification of images likely to contain pulmonary nodules using both weak labels and manually-delineated bounding boxes, when these are available. Annotated nodules are used at training time to deliver a visual attention mechanism informing the model about its localisation performance. The first architecture extracts saliency maps from high-level convolutional layers and compares the estimated position of a nodule against the ground truth, when this is available. A corresponding localisation error is then back-propagated along with the softmax classification error. The second approach consists of a recurrent attention model that learns to observe a short sequence of smaller image portions through reinforcement learning. When a nodule annotation is available at training time, the reward function is modified accordingly so that exploring portions of the radiographs away from a nodule incurs a larger penalty. Our empirical results demonstrate the potential advantages of these architectures in comparison to competing methodologies.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1712.00996](http://arxiv.org/abs/1712.00996)

##### PDF
[http://arxiv.org/pdf/1712.00996](http://arxiv.org/pdf/1712.00996)

