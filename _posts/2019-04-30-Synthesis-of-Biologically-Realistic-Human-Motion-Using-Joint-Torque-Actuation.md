---
layout: post
title: "Synthesis of Biologically Realistic Human Motion Using Joint Torque Actuation"
date: 2019-04-30 03:55:30
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning Optimization
author: Yifeng Jiang, Tom Van Wouwe, Friedl De Groote, C. Karen Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Using joint actuators to drive the skeletal movements is a common practice in character animation, but the resultant torque patterns are often unnatural or infeasible for real humans to achieve. On the other hand, physiologically-based models explicitly simulate muscles and tendons and thus produce more human-like movements and torque patterns. This paper introduces a technique to transform an optimal control problem formulated in the muscle-actuation space to an equivalent problem in the joint-actuation space, such that the solutions to both problems have the same optimal value. By solving the equivalent problem in the joint-actuation space, we can generate human-like motions comparable to those generated by musculotendon models, while retaining the benefit of simple modeling and fast computation offered by joint-actuation models. Our method transforms constant bounds on muscle activations to nonlinear, state-dependent torque limits in the joint-actuation space. In addition, the metabolic energy function on muscle activations is transformed to a nonlinear function of joint torques, joint configuration and joint velocity. Our technique can also benefit policy optimization using deep reinforcement learning approach, by providing a more anatomically realistic action space for the agent to explore during the learning process. We take the advantage of the physiologically-based simulator, OpenSim, to provide training data for learning the torque limits and the metabolic energy function. Once trained, the same torque limits and the energy function can be applied to drastically different motor tasks formulated as either trajectory optimization or policy learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.13041](http://arxiv.org/abs/1904.13041)

##### PDF
[http://arxiv.org/pdf/1904.13041](http://arxiv.org/pdf/1904.13041)

