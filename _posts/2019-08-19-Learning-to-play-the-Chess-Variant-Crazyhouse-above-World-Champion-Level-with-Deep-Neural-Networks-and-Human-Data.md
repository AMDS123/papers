---
layout: post
title: "Learning to play the Chess Variant Crazyhouse above World Champion Level with Deep Neural Networks and Human Data"
date: 2019-08-19 09:31:47
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning Prediction
author: Johannes Czech, Moritz Willig, Alena Beyer, Kristian Kersting, Johannes F&#xfc;rnkranz
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have been successfully applied in learning the board games Go, chess and shogi without prior knowledge by making use of reinforcement learning. Although starting from zero knowledge has been shown to yield impressive results, it is associated with high computationally costs especially for complex games. With this paper, we present CrazyAra which is a neural network based engine solely trained in supervised manner for the chess variant crazyhouse. Crazyhouse is a game with a higher branching factor than chess and there is only limited data of lower quality available compared to AlphaGo. Therefore, we focus on improving efficiency in multiple aspects while relying on low computational resources. These improvements include modifications in the neural network design and training configuration, the introduction of a data normalization step and a more sample efficient Monte-Carlo tree search which has a lower chance to blunder. After training on 569,537 human games for 1.5 days we achieve a move prediction accuracy of 60.4%. During development, versions of CrazyAra played professional human players. Most notably, CrazyAra achieved a four to one win over 2017 crazyhouse world champion Justin Tan (aka LM Jann Lee) who is more than 400 Elo higher rated compared to the average player in our training set. Furthermore, we test the playing strength of CrazyAra on CPU against all participants of the second Crazyhouse Computer Championships 2017, winning against twelve of the thirteen participants. Finally, for CrazyAraFish we continue training our model on generated engine games. In ten long-time control matches playing Stockfish 10, CrazyAraFish wins three games and draws one out of ten matches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06660](http://arxiv.org/abs/1908.06660)

##### PDF
[http://arxiv.org/pdf/1908.06660](http://arxiv.org/pdf/1908.06660)

