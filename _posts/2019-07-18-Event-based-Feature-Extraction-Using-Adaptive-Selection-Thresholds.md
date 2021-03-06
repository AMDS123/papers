---
layout: post
title: "Event-based Feature Extraction Using Adaptive Selection Thresholds"
date: 2019-07-18 03:15:09
categories: arXiv_CV
tags: arXiv_CV Optimization Classification
author: Saeed Afshar, Ying Xu, Jonathan Tapson, Andr&#xe9; van Schaik, Gregory Cohen
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised feature extraction algorithms form one of the most important building blocks in machine learning systems. These algorithms are often adapted to the event-based domain to perform online learning in neuromorphic hardware. However, not designed for the purpose, such algorithms typically require significant simplification during implementation to meet hardware constraints, creating trade offs with performance. Furthermore, conventional feature extraction algorithms are not designed to generate useful intermediary signals which are valuable only in the context of neuromorphic hardware limitations. In this work a novel event-based feature extraction method is proposed that focuses on these issues. The algorithm operates via simple adaptive selection thresholds which allow a simpler implementation of network homeostasis than previous works by trading off a small amount of information loss in the form of missed events that fall outside the selection thresholds. The behavior of the selection thresholds and the output of the network as a whole are shown to provide uniquely useful signals indicating network weight convergence without the need to access network weights. A novel heuristic method for network size selection is proposed which makes use of noise events and their feature representations. The use of selection thresholds is shown to produce network activation patterns that predict classification accuracy allowing rapid evaluation and optimization of system parameters without the need to run back-end classifiers. The feature extraction method is tested on both the N-MNIST benchmarking dataset and a dataset of airplanes passing through the field of view. Multiple configurations with different classifiers are tested with the results quantifying the resultant performance gains at each processing stage.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07853](http://arxiv.org/abs/1907.07853)

##### PDF
[http://arxiv.org/pdf/1907.07853](http://arxiv.org/pdf/1907.07853)

