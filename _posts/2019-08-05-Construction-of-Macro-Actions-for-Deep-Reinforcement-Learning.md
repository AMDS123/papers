---
layout: post
title: "Construction of Macro Actions for Deep Reinforcement Learning"
date: 2019-08-05 05:59:40
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Yi-Hsiang Chang, Kuan-Yu Chang, Henry Kuo, Chun-Yi Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional deep reinforcement learning typically determines an appropriate primitive action at each timestep, which requires enormous amount of time and effort for learning an effective policy, especially in large and complex environments. To deal with the issue fundamentally, we incorporate macro actions, defined as sequences of primitive actions, into the primitive action space to form an augmented action space. The problem lies in how to find an appropriate macro action to augment the primitive action space. The agent using a proper augmented action space is able to jump to a farther state and thus speed up the exploration process as well as facilitate the learning procedure. In previous researches, macro actions are developed by mining the most frequently used action sequences or repeating previous actions. However, the most frequently used action sequences are extracted from a past policy, which may only reinforce the original behavior of that policy. On the other hand, repeating actions may limit the diversity of behaviors of the agent. Instead, we propose to construct macro actions by a genetic algorithm, which eliminates the dependency of the macro action derivation procedure from the past policies of the agent. Our approach appends a macro action to the primitive action space once at a time and evaluates whether the augmented action space leads to promising performance or not. We perform extensive experiments and show that the constructed macro actions are able to speed up the learning process for a variety of deep reinforcement learning methods. Our experimental results also demonstrate that the macro actions suggested by our approach are transferable among deep reinforcement learning methods and similar environments. We further provide a comprehensive set of ablation analysis to validate the proposed methodology.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01478](http://arxiv.org/abs/1908.01478)

##### PDF
[http://arxiv.org/pdf/1908.01478](http://arxiv.org/pdf/1908.01478)

