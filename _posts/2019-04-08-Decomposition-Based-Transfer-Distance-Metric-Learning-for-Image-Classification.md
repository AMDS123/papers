---
layout: post
title: "Decomposition-Based Transfer Distance Metric Learning for Image Classification"
date: 2019-04-08 05:39:46
categories: arXiv_CV
tags: arXiv_CV Sparse Image_Classification Transfer_Learning Optimization Classification Recognition
author: Yong Luo, Tongliang Liu, Dacheng Tao, Chao Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Distance metric learning (DML) is a critical factor for image analysis and pattern recognition. To learn a robust distance metric for a target task, we need abundant side information (i.e., the similarity/dissimilarity pairwise constraints over the labeled data), which is usually unavailable in practice due to the high labeling cost. This paper considers the transfer learning setting by exploiting the large quantity of side information from certain related, but different source tasks to help with target metric learning (with only a little side information). The state-of-the-art metric learning algorithms usually fail in this setting because the data distributions of the source task and target task are often quite different. We address this problem by assuming that the target distance metric lies in the space spanned by the eigenvectors of the source metrics (or other randomly generated bases). The target metric is represented as a combination of the base metrics, which are computed using the decomposed components of the source metrics (or simply a set of random bases); we call the proposed method, decomposition-based transfer DML (DTDML). In particular, DTDML learns a sparse combination of the base metrics to construct the target metric by forcing the target metric to be close to an integration of the source metrics. The main advantage of the proposed method compared with existing transfer metric learning approaches is that we directly learn the base metric coefficients instead of the target metric. To this end, far fewer variables need to be learned. We therefore obtain more reliable solutions given the limited side information and the optimization tends to be faster. Experiments on the popular handwritten image (digit, letter) classification and challenge natural image annotation tasks demonstrate the effectiveness of the proposed method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03846](http://arxiv.org/abs/1904.03846)

##### PDF
[http://arxiv.org/pdf/1904.03846](http://arxiv.org/pdf/1904.03846)

