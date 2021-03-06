---
layout: post
title: "Fair-by-design algorithms: matching problems and beyond"
date: 2018-02-07 18:44:43
categories: arXiv_CV
tags: arXiv_CV Optimization
author: David García-Soriano, Francesco Bonchi
mathjax: true
---

* content
{:toc}

##### Abstract
In discrete search and optimization problems where the elements that may or not be included in a solution correspond to humans, individual fairness needs to be expressed in terms of each individual's satisfaction probability (the probability of being included in the solution). In this paper we introduce the maxmin fairness framework which provides, on any given input instance, the strongest guarantee possible for all individuals, in terms of satisfaction probability. A probability distribution over valid solutions is maxmin-fair if it is not possible to improve the satisfaction probability of any individual without decreasing it for some other individual which is no better off. We provide an efficient exact algorithm for maxmin-fair bipartite matching combining flow-based methods with algorithms for edge-coloring regular bipartite graphs. As shown in our experimental evaluation, our algorithm scales to graphs with millions of vertices and hundreds of millions of edges, taking only a few minutes on a simple architecture. We generalize our method to the case where the structure of valid solutions forms a matroid, in which case the price of fairness is zero, and show that then maxmin-fair distributions mini- mize social inequality among Pareto-efficient distributions. More generally, we prove that a maxmin-fair distribution of solutions to any combinatorial search problem may be found efficiently under the sole assumption that, given an arbitrary assignment of non-negative weights to individuals, a maximum-weight solution may be found in polynomial time. This class of problems extends beyond matchings and matroids, and includes the vast majority of search problems for which exact algorithms are known.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1802.02562](https://arxiv.org/abs/1802.02562)

##### PDF
[https://arxiv.org/pdf/1802.02562](https://arxiv.org/pdf/1802.02562)

