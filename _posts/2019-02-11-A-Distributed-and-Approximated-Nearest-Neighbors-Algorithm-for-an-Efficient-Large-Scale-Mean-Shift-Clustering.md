---
layout: post
title: "A Distributed and Approximated Nearest Neighbors Algorithm for an Efficient Large Scale Mean Shift Clustering"
date: 2019-02-11 12:00:06
categories: arXiv_AI
tags: arXiv_AI Classification
author: Ga&#xeb;l Beck, Tarn Duong, Mustapha Lebbah, Hanane Azzag, Christophe C&#xe9;rin
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we target the class of modal clustering methods where clusters are defined in terms of the local modes of the probability density function which generates the data. The most well-known modal clustering method is the k-means clustering. Mean Shift clustering is a generalization of the k-means clustering which computes arbitrarily shaped clusters as defined as the basins of attraction to the local modes created by the density gradient ascent paths. Despite its potential, the Mean Shift approach is a computationally expensive method for unsupervised learning. Thus, we introduce two contributions aiming to provide clustering algorithms with a linear time complexity, as opposed to the quadratic time complexity for the exact Mean Shift clustering. Firstly we propose a scalable procedure to approximate the density gradient ascent. Second, our proposed scalable cluster labeling technique is presented. Both propositions are based on Locality Sensitive Hashing (LSH) to approximate nearest neighbors. These two techniques may be used for moderate sized datasets. Furthermore, we show that using our proposed approximations of the density gradient ascent as a pre-processing step in other clustering methods can also improve dedicated classification metrics. For the latter, a distributed implementation, written for the Spark/Scala ecosystem is proposed. For all these considered clustering methods, we present experimental results illustrating their labeling accuracy and their potential to solve concrete problems.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.03833](http://arxiv.org/abs/1902.03833)

##### PDF
[http://arxiv.org/pdf/1902.03833](http://arxiv.org/pdf/1902.03833)

