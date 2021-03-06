---
layout: post
title: "Automated Driving Maneuvers under Interactive Environment based on Deep Reinforcement Learning"
date: 2019-01-09 05:36:47
categories: arXiv_RO
tags: arXiv_RO Adversarial Knowledge Tracking Reinforcement_Learning
author: Pin Wang, Ching-Yao Chan
mathjax: true
---

* content
{:toc}

##### Abstract
Safe and efficient autonomous driving maneuvers in an interactive and complex environment can be considerably challenging due to the unpredictable actions of other surrounding agents that may be cooperative or adversarial in their interactions with the ego vehicle. One of the state-of-the-art approaches is to apply Reinforcement Learning (RL) to learn a time-sequential driving policy, to execute proper control strategy or tracking trajectory in dynamic situations. However, direct application of RL algorithms is not satisfactorily enough to deal with the cases in the autonomous driving domain, mainly due to the complex driving environment and continuous action space. In this paper, we adopt Q-learning as our basic learning framework and design a unique format of the Q-function approximator that consists of neural networks to handle the continuous action space challenge. The learning model is present in a closed form of continuous control variables and trained in a simulation platform that we have developed with embedded properties of real-time vehicle interactions. The proposed algorithm avoids invoking an additional actor network that learns to take actions, as in actor-critic algorithms. At the same time, some prior knowledge of vehicle dynamics is also fed into the model to assist learning. We test our algorithm with a challenging use case - lane change maneuver, to verify the practicability and feasibility of the proposed approach. Results from accumulated rewards and vehicle performance show that RL vehicle agents successfully learn a safe, comfort and efficient driving policy as defined in the reward function.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.09200](http://arxiv.org/abs/1803.09200)

##### PDF
[http://arxiv.org/pdf/1803.09200](http://arxiv.org/pdf/1803.09200)

