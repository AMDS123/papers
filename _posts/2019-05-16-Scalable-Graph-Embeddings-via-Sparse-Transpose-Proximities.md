---
layout: post
title: "Scalable Graph Embeddings via Sparse Transpose Proximities"
date: 2019-05-16 05:20:09
categories: arXiv_AI
tags: arXiv_AI Sparse Embedding Optimization
author: Yuan Yin, Zhewei Wei
mathjax: true
---

* content
{:toc}

##### Abstract
Graph embedding learns low-dimensional representations for nodes in a graph and effectively preserves the graph structure. Recently, a significant amount of progress has been made toward this emerging research area. However, there are several fundamental problems that remain open. First, existing methods fail to preserve the out-degree distributions on directed graphs. Second, many existing methods employ random walk based proximities and thus suffer from conflicting optimization goals on undirected graphs. Finally, existing factorization methods are unable to achieve scalability and non-linearity simultaneously. 
 This paper presents an in-depth study on graph embedding techniques on both directed and undirected graphs. We analyze the fundamental reasons that lead to the distortion of out-degree distributions and to the conflicting optimization goals. We propose {\em transpose proximity}, a unified approach that solves both problems. Based on the concept of transpose proximity, we design \strap, a factorization based graph embedding algorithm that achieves scalability and non-linearity simultaneously. \strap makes use of the {\em backward push} algorithm to efficiently compute the sparse {\em Personalized PageRank (PPR)} as its transpose proximities. By imposing the sparsity constraint, we are able to apply non-linear operations to the proximity matrix and perform efficient matrix factorization to derive the embedding vectors. Finally, we present an extensive experimental study that evaluates the effectiveness of various graph embedding algorithms, and we show that \strap outperforms the state-of-the-art methods in terms of effectiveness and scalability.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07245](http://arxiv.org/abs/1905.07245)

##### PDF
[http://arxiv.org/pdf/1905.07245](http://arxiv.org/pdf/1905.07245)

