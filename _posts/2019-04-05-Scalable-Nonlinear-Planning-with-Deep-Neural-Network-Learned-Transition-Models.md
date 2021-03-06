---
layout: post
title: "Scalable Nonlinear Planning with Deep Neural Network Learned Transition Models"
date: 2019-04-05 05:21:46
categories: arXiv_AI
tags: arXiv_AI Optimization RNN
author: Ga Wu, Buser Say, Scott Sanner
mathjax: true
---

* content
{:toc}

##### Abstract
In many real-world planning problems with factored, mixed discrete and continuous state and action spaces such as Reservoir Control, Heating Ventilation, and Air Conditioning, and Navigation domains, it is difficult to obtain a model of the complex nonlinear dynamics that govern state evolution. However, the ubiquity of modern sensors allows us to collect large quantities of data from each of these complex systems and build accurate, nonlinear deep neural network models of their state transitions. But there remains one major problem for the task of control -- how can we plan with deep network learned transition models without resorting to Monte Carlo Tree Search and other black-box transition model techniques that ignore model structure and do not easily extend to mixed discrete and continuous domains? In this paper, we introduce two types of nonlinear planning methods that can leverage deep neural network learned transition models: Hybrid Deep MILP Planner (HD-MILP-Plan) and Tensorflow Planner (TF-Plan). In HD-MILP-Plan, we make the critical observation that the Rectified Linear Unit transfer function for deep networks not only allows faster convergence of model learning, but also permits a direct compilation of the deep network transition model to a Mixed-Integer Linear Program encoding. Further, we identify deep network specific optimizations for HD-MILP-Plan that improve performance over a base encoding and show that we can plan optimally with respect to the learned deep networks. In TF-Plan, we take advantage of the efficiency of auto-differentiation tools and GPU-based computation where we encode a subclass of purely continuous planning problems as Recurrent Neural Networks and directly optimize the actions through backpropagation. We compare both planners and show that TF-Plan is able to approximate the optimal plans found by HD-MILP-Plan in less computation time...

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.02873](https://arxiv.org/abs/1904.02873)

##### PDF
[https://arxiv.org/pdf/1904.02873](https://arxiv.org/pdf/1904.02873)

