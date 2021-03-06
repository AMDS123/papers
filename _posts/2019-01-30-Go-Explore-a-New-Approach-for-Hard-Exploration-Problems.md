---
layout: post
title: "Go-Explore: a New Approach for Hard-Exploration Problems"
date: 2019-01-30 18:40:37
categories: arXiv_AI
tags: arXiv_AI Sparse Knowledge Reinforcement_Learning
author: Adrien Ecoffet, Joost Huizinga, Joel Lehman, Kenneth O. Stanley, Jeff Clune
mathjax: true
---

* content
{:toc}

##### Abstract
A grand challenge in reinforcement learning is intelligent exploration, especially when rewards are sparse or deceptive. Two Atari games serve as benchmarks for such hard-exploration domains: Montezuma's Revenge and Pitfall. On both games, current RL algorithms perform poorly, even those with intrinsic motivation, which is the dominant method to improve performance on hard-exploration domains. To address this shortfall, we introduce a new algorithm called Go-Explore. It exploits the following principles: (1) remember previously visited states, (2) first return to a promising state (without exploration), then explore from it, and (3) solve simulated environments through any available means (including by introducing determinism), then robustify via imitation learning. The combined effect of these principles is a dramatic performance improvement on hard-exploration problems. On Montezuma's Revenge, Go-Explore scores a mean of over 43k points, almost 4 times the previous state of the art. Go-Explore can also harness human-provided domain knowledge and, when augmented with it, scores a mean of over 650k points on Montezuma's Revenge. Its max performance of nearly 18 million surpasses the human world record, meeting even the strictest definition of "superhuman" performance. On Pitfall, Go-Explore with domain knowledge is the first algorithm to score above zero. Its mean score of almost 60k points exceeds expert human performance. Because Go-Explore produces high-performing demonstrations automatically and cheaply, it also outperforms imitation learning work where humans provide solution demonstrations. Go-Explore opens up many new research directions into improving it and weaving its insights into current RL algorithms. It may also enable progress on previously unsolvable hard-exploration problems in many domains, especially those that harness a simulator during training (e.g. robotics).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.10995](http://arxiv.org/abs/1901.10995)

##### PDF
[http://arxiv.org/pdf/1901.10995](http://arxiv.org/pdf/1901.10995)

