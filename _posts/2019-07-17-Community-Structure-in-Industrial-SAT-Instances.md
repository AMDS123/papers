---
layout: post
title: "Community Structure in Industrial SAT Instances"
date: 2019-07-17 21:07:48
categories: arXiv_AI
tags: arXiv_AI
author: Carlos Ans&#xf3;tegui, Maria Luisa Bonet, Jes&#xfa;s Gir&#xe1;ldez-Cru, Jordi Levy, Laurent Simon
mathjax: true
---

* content
{:toc}

##### Abstract
Modern SAT solvers have experienced a remarkable progress on solving industrial instances. Most of the techniques have been developed after an intensive experimental process. It is believed that these techniques exploit the underlying structure of industrial instances. However, there are few works trying to exactly characterize the main features of this structure. 
 The research community on complex networks has developed techniques of analysis and algorithms to study real-world graphs that can be used by the SAT community. Recently, there have been some attempts to analyze the structure of industrial SAT instances in terms of complex networks, with the aim of explaining the success of SAT solving techniques, and possibly improving them. 
 In this paper, inspired by the results on complex networks, we study the community structure, or modularity, of industrial SAT instances. In a graph with clear community structure, or high modularity, we can find a partition of its nodes into communities such that most edges connect variables of the same community. In our analysis, we represent SAT instances as graphs, and we show that most application benchmarks are characterized by a high modularity. On the contrary, random SAT instances are closer to the classical Erd\"os-R\'enyi random graph model, where no structure can be observed. We also analyze how this structure evolves by the effects of the execution of a CDCL SAT solver. In particular, we use the community structure to detect that new clauses learned by the solver during the search contribute to destroy the original structure of the formula. This is, learned clauses tend to contain variables of distinct communities.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1606.03329](http://arxiv.org/abs/1606.03329)

##### PDF
[http://arxiv.org/pdf/1606.03329](http://arxiv.org/pdf/1606.03329)

