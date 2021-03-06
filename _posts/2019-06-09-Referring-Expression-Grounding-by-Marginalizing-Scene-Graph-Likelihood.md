---
layout: post
title: "Referring Expression Grounding by Marginalizing Scene Graph Likelihood"
date: 2019-06-09 04:29:06
categories: arXiv_CV
tags: arXiv_CV Inference Relation
author: Daqing Liu, Hanwang Zhang, Zheng-Jun Zha, Fanglin Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We focus on the task of grounding referring expressions in images, e.g., localizing "the white truck in front of a yellow one". To resolve this task fundamentally, one should first find out the contextual objects (e.g., the "yellow" truck) and then exploit them to disambiguate the referent from other similar objects, by using the attributes and relationships (e.g., "white", "yellow", "in front of"). However, it is extremely challenging to train such a model as the ground-truth of the contextual objects and their relationships are usually missing due to the prohibitive annotation cost. Therefore, nearly all existing methods attempt to evade the above joint grounding and reasoning process, but resort to a holistic association between the sentence and region feature. As a result, they suffer from heavy parameters of fully-connected layers, poor interpretability, and limited generalization to unseen expressions. In this paper, we tackle this challenge by training and inference with the proposed Marginalized Scene Graph Likelihood (MSGL). Specifically, we use scene graph: a graphical representation parsed from the referring expression, where the nodes are objects with attributes and the edges are relationships. Thanks to the conditional random field (CRF) built on scene graph, we can ground every object to its corresponding region, and perform reasoning with the unlabeled contexts by marginalizing out them using the sum-product belief propagation. Overall, our proposed MSGL is effective and interpretable, e.g., on three benchmarks, MSGL consistently outperforms the state-of-the-arts while offers a complete grounding of all the objects in a sentence.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03561](http://arxiv.org/abs/1906.03561)

##### PDF
[http://arxiv.org/pdf/1906.03561](http://arxiv.org/pdf/1906.03561)

