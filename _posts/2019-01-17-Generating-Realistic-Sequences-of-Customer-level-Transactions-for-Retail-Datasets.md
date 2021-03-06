---
layout: post
title: "Generating Realistic Sequences of Customer-level Transactions for Retail Datasets"
date: 2019-01-17 01:24:24
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Face Embedding RNN Prediction
author: Thang Doan, Neil Veira, Brian Keng
mathjax: true
---

* content
{:toc}

##### Abstract
In order to better engage with customers, retailers rely on extensive customer and product databases which allows them to better understand customer behaviour and purchasing patterns. This has long been a challenging task as customer modelling is a multi-faceted, noisy and time-dependent problem. The most common way to tackle this problem is indirectly through task-specific supervised learning prediction problems, with relatively little literature on modelling a customer by directly simulating their future transactions. In this paper we propose a method for generating realistic sequences of baskets that a given customer is likely to purchase over a period of time. Customer embedding representations are learned using a Recurrent Neural Network (RNN) which takes into account the entire sequence of transaction data. Given the customer state at a specific point in time, a Generative Adversarial Network (GAN) is trained to generate a plausible basket of products for the following week. The newly generated basket is then fed back into the RNN to update the customer's state. The GAN is thus used in tandem with the RNN module in a pipeline alternating between basket generation and customer state updating steps. This allows for sampling over a distribution of a customer's future sequence of baskets, which then can be used to gain insight into how to service the customer more effectively. The methodology is empirically shown to produce baskets that appear similar to real baskets and enjoy many common properties, including frequencies of different product types, brands, and prices. Furthermore, the generated data is able to replicate most of the strongest sequential patterns that exist between product types in the real data.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.05577](https://arxiv.org/abs/1901.05577)

##### PDF
[https://arxiv.org/pdf/1901.05577](https://arxiv.org/pdf/1901.05577)

