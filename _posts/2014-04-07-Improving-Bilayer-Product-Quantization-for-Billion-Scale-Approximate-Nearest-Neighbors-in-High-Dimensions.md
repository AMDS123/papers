---
layout: post
title: "Improving Bilayer Product Quantization for Billion-Scale Approximate Nearest Neighbors in High Dimensions"
date: 2014-04-07 16:08:13
categories: arXiv_CV
tags: arXiv_CV GAN
author: Artem Babenko, Victor Lempitsky
mathjax: true
---

* content
{:toc}

##### Abstract
The top-performing systems for billion-scale high-dimensional approximate nearest neighbor (ANN) search are all based on two-layer architectures that include an indexing structure and a compressed datapoints layer. An indexing structure is crucial as it allows to avoid exhaustive search, while the lossy data compression is needed to fit the dataset into RAM. Several of the most successful systems use product quantization (PQ) for both the indexing and the dataset compression layers. These systems are however limited in the way they exploit the interaction of product quantization processes that happen at different stages of these systems. Here we introduce and evaluate two approximate nearest neighbor search systems that both exploit the synergy of product quantization processes in a more efficient way. The first system, called Fast Bilayer Product Quantization (FBPQ), speeds up the runtime of the baseline system (Multi-D-ADC) by several times, while achieving the same accuracy. The second system, Hierarchical Bilayer Product Quantization (HBPQ) provides a significantly better recall for the same runtime at a cost of small memory footprint increase. For the BIGANN dataset of billion SIFT descriptors, the 10% increase in Recall@1 and the 17% increase in Recall@10 is observed.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1404.1831](https://arxiv.org/abs/1404.1831)

##### PDF
[https://arxiv.org/pdf/1404.1831](https://arxiv.org/pdf/1404.1831)

