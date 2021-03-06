---
layout: post
title: "Adaptive Symmetric Reward Noising for Reinforcement Learning"
date: 2019-05-24 10:54:33
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Refael Vivanti, Talya D. Sohlberg-Baris, Shlomo Cohen, Orna Cohen
mathjax: true
---

* content
{:toc}

##### Abstract
Recent reinforcement learning algorithms, though achieving impressive results in various fields, suffer from brittle training effects such as regression in results and high sensitivity to initialization and parameters. We claim that some of the brittleness stems from variance differences, i.e. when different environment areas - states and/or actions - have different rewards variance. This causes two problems: First, the "Boring Areas Trap" in algorithms such as Q-learning, where moving between areas depends on the current area variance, and getting out of a boring area is hard due to its low variance. Second, the "Manipulative Consultant" problem, when value-estimation functions used in DQN and Actor-Critic algorithms influence the agent to prefer boring areas, regardless of the mean rewards return, as they maximize estimation precision rather than rewards. This sheds a new light on how exploration contribute to training, as it helps with both challenges. Cognitive experiments in humans showed that noised reward signals may paradoxically improve performance. We explain this using the two mentioned problems, claiming that both humans and algorithms may share similar challenges. Inspired by this result, we propose the Adaptive Symmetric Reward Noising (ASRN), by which we mean adding Gaussian noise to rewards according to their states' estimated variance, thus avoiding the two problems while not affecting the environment's mean rewards behavior. We conduct our experiments in a Multi Armed Bandit problem with variance differences. We demonstrate that a Q-learning algorithm shows the brittleness effect in this problem, and that the ASRN scheme can dramatically improve the results. We show that ASRN helps a DQN algorithm training process reach better results in an end to end autonomous driving task using the AirSim driving simulator.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10144](http://arxiv.org/abs/1905.10144)

##### PDF
[http://arxiv.org/pdf/1905.10144](http://arxiv.org/pdf/1905.10144)

