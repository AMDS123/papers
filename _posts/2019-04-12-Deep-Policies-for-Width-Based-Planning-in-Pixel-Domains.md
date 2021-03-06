---
layout: post
title: "Deep Policies for Width-Based Planning in Pixel Domains"
date: 2019-04-12 10:50:12
categories: arXiv_AI
tags: arXiv_AI
author: Miquel Junyent, Anders Jonsson, Vicen&#xe7; G&#xf3;mez
mathjax: true
---

* content
{:toc}

##### Abstract
Width-based planning has demonstrated great success in recent years due to its ability to scale independently of the size of the state space. For example, Bandres et al. (2018) introduced a rollout version of the Iterated Width algorithm whose performance compares well with humans and learning methods in the pixel setting of the Atari games suite. In this setting, planning is done on-line using the "screen" states and selecting actions by looking ahead into the future. However, this algorithm is purely exploratory and does not leverage past reward information. Furthermore, it requires the state to be factored into features that need to be pre-defined for the particular task, e.g., the B-PROST pixel features. In this work, we extend width-based planning by incorporating an explicit policy in the action selection mechanism. Our method, called $\pi$-IW, interleaves width-based planning and policy learning using the state-actions visited by the planner. The policy estimate takes the form of a neural network and is in turn used to guide the planning step, thus reinforcing promising paths. Surprisingly, we observe that the representation learned by the neural network can be used as a feature space for the width-based planner without degrading its performance, thus removing the requirement of pre-defined features for the planner. We compare $\pi$-IW with previous width-based methods and with AlphaZero, a method that also interleaves planning and learning, in simple environments, and show that $\pi$-IW has superior performance. We also show that $\pi$-IW algorithm outperforms previous width-based methods in the pixel setting of Atari games suite.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07091](http://arxiv.org/abs/1904.07091)

##### PDF
[http://arxiv.org/pdf/1904.07091](http://arxiv.org/pdf/1904.07091)

