---
layout: post
title: "Simple Image Description Generator via a Linear Phrase-Based Approach"
date: 2015-04-11 03:53:26
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption CNN Language_Model
author: Remi Lebret, Pedro O. Pinheiro, Ronan Collobert
mathjax: true
---

* content
{:toc}

##### Abstract
Generating a novel textual description of an image is an interesting problem that connects computer vision and natural language processing. In this paper, we present a simple model that is able to generate descriptive sentences given a sample image. This model has a strong focus on the syntax of the descriptions. We train a purely bilinear model that learns a metric between an image representation (generated from a previously trained Convolutional Neural Network) and phrases that are used to described them. The system is then able to infer phrases from a given image sample. Based on caption syntax statistics, we propose a simple language model that can produce relevant descriptions for a given test image using the phrases inferred. Our approach, which is considerably simpler than state-of-the-art models, achieves comparable results on the recently release Microsoft COCO dataset.

##### Abstract (translated by Google)
生成图像的新颖文本描述是一个将计算机视觉和自然语言处理联系在一起的有趣问题。在本文中，我们提出一个简单的模型，能够生成描述性句子给出一个样本图像。这个模型非常注重描述的语法。我们训练一个纯粹的双线性模型，学习一个图像表示（从先前训练的卷积神经网络产生）与用来描述它们的短语之间的度量。系统然后能够从给定的图像样本中推断短语。基于字幕语法统计，我们提出了一个简单的语言模型，可以使用所推断的短语为给定的测试图像产生相关的描述。我们的方法比最先进的模型简单得多，可以在最近发布的Microsoft COCO数据集上获得可比的结果。

##### URL
[https://arxiv.org/abs/1412.8419](https://arxiv.org/abs/1412.8419)

##### PDF
[https://arxiv.org/pdf/1412.8419](https://arxiv.org/pdf/1412.8419)

