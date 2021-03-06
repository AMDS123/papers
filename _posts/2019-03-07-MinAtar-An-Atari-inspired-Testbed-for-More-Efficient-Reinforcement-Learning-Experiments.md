---
layout: post
title: "MinAtar: An Atari-inspired Testbed for More Efficient Reinforcement Learning Experiments"
date: 2019-03-07 20:34:36
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Represenation_Learning
author: Kenny Young, Tian Tian
mathjax: true
---

* content
{:toc}

##### Abstract
The Arcade Learning Environment (ALE) is a popular platform for evaluating reinforcement learning agents. Much of the appeal comes from the fact that Atari games are varied, showcase aspects of competency we expect from an intelligent agent, and are not biased towards any particular solution approach. The challenge of the ALE includes 1) the representation learning problem of extracting pertinent information from the raw pixels, and 2) the behavioural learning problem of leveraging complex, delayed associations between actions and rewards. Often, in reinforcement learning research, we care more about the latter, but the representation learning problem adds significant computational expense. In response, we introduce MinAtar, short for miniature Atari, a new evaluation platform that captures the general mechanics of specific Atari games, while simplifying certain aspects. In particular, we reduce the representational complexity to focus more on behavioural challenges. MinAtar consists of analogues to five Atari games which play out on a 10x10 grid. MinAtar provides a 10x10xn state representation. The n channels correspond to game-specific objects, such as ball, paddle and brick in the game Breakout. While significantly simplified, these domains are still rich enough to allow for interesting behaviours. To demonstrate the challenges posed by these domains, we evaluated a smaller version of the DQN architecture. We also tried variants of DQN without experience replay, and without a target network, to assess the impact of those two prominent components in the MinAtar environments. In addition, we evaluated a simpler agent that used actor-critic with eligibility traces, online updating, and no experience replay. We hope that by introducing a set of simplified, Atari-like games we can allow researchers to more efficiently investigate the unique behavioural challenges provided by the ALE.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.03176](http://arxiv.org/abs/1903.03176)

##### PDF
[http://arxiv.org/pdf/1903.03176](http://arxiv.org/pdf/1903.03176)

