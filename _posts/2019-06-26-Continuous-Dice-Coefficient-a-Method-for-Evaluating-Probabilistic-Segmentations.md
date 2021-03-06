---
layout: post
title: "Continuous Dice Coefficient: a Method for Evaluating Probabilistic Segmentations"
date: 2019-06-26 12:35:00
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Reuben R Shamir, Yuval Duchin, Jinyoung Kim, Guillermo Sapiro, Noam Harel
mathjax: true
---

* content
{:toc}

##### Abstract
Objective: Overlapping measures are often utilized to quantify the similarity between two binary regions. However, modern segmentation algorithms output a probability or confidence map with continuous values in the zero-to-one interval. Moreover, these binary overlapping measures are biased to structure size. Addressing these challenges is the objective of this work. Methods: We extend the definition of the classical Dice coefficient (DC) overlap to facilitate the direct comparison of a ground truth binary image with a probabilistic map. We call the extended method continuous Dice coefficient (cDC) and show that 1) cDC is less or equal to 1 and cDC = 1 if-and-only-if the structures overlap is complete, and, 2) cDC is monotonically decreasing with the amount of overlap. We compare the classical DC and the cDC in a simulation of partial volume effects that incorporates segmentations of common targets for deep-brainstimulation. Lastly, we investigate the cDC for an automatic segmentation of the subthalamic-nucleus. Results: Partial volume effect simulation on thalamus (large structure) resulted with DC and cDC averages (SD) of 0.98 (0.006) and 0.99 (0.001), respectively. For subthalamic-nucleus (small structure) DC and cDC were 0.86 (0.025) and 0.97 (0.006), respectively. The DC and cDC for automatic STN segmentation were 0.66 and 0.80, respectively. Conclusion: The cDC is well defined for probabilistic segmentation, less biased to structure size and more robust to partial volume effects in comparison to DC. Significance: The proposed method facilitates a better evaluation of segmentation algorithms. As a better measurement tool, it opens the door for the development of better segmentation methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.11031](http://arxiv.org/abs/1906.11031)

##### PDF
[http://arxiv.org/pdf/1906.11031](http://arxiv.org/pdf/1906.11031)

