---
layout: post
title: "Revisiting Local Descriptor based Image-to-Class Measure for Few-shot Learning"
date: 2019-03-28 22:02:24
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Wenbin Li, Lei Wang, Jinglin Xu, Jing Huo, Yang Gao, Jiebo Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Few-shot learning in image classification aims to learn a classifier to classify images when only few training examples are available for each class. Recent work has achieved promising classification performance, where an image-level feature based measure is usually used. In this paper, we argue that a measure at such a level may not be effective enough in light of the scarcity of examples in few-shot learning. Instead, we think a local descriptor based image-to-class measure should be taken, inspired by its surprising success in the heydays of local invariant features. Specifically, building upon the recent episodic training mechanism, we propose a Deep Nearest Neighbor Neural Network (DN4 in short) and train it in an end-to-end manner. Its key difference from the literature is the replacement of the image-level feature based measure in the final layer by a local descriptor based image-to-class measure. This measure is conducted online via a $k$-nearest neighbor search over the deep local descriptors of convolutional feature maps. The proposed DN4 not only learns the optimal deep local descriptors for the image-to-class measure, but also utilizes the higher efficiency of such a measure in the case of example scarcity, thanks to the exchangeability of visual patterns across the images in the same class. Our work leads to a simple, effective, and computationally efficient framework for few-shot learning. Experimental study on benchmark datasets consistently shows its superiority over the related state-of-the-art, with the largest absolute improvement of $17\%$ over the next best. The source code can be available from \UrlFont{https://github.com/WenbinLee/DN4.git}.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.12290](http://arxiv.org/abs/1903.12290)

##### PDF
[http://arxiv.org/pdf/1903.12290](http://arxiv.org/pdf/1903.12290)

