---
layout: post
title: "Modeling Social Group Communication with Multi-Agent Imitation Learning"
date: 2019-03-04 21:04:22
categories: arXiv_AI
tags: arXiv_AI Attention
author: Navyata Sanghvi, Ryo Yonetani, Kris Kitani
mathjax: true
---

* content
{:toc}

##### Abstract
In crowded social scenarios with a myriad of external stimuli, human brains exhibit a natural ability to filter out irrelevant information and narrowly focus their attention. In the midst of multiple groups of people, humans use such sensory gating to effectively further their own group's interactional goals. In this work, we consider the design of a policy network to model multi-group multi-person communication. Our policy takes as input the state of the world such as an agent's gaze direction, body pose of other agents or history of past actions, and outputs an optimal action such as speaking, listening or responding (communication modes). Inspired by humans' natural neurobiological filtering process, a central component of our policy network design is an information gating function, termed the Kinesic-Proxemic-Message Gate (KPM-Gate), that models the ability of an agent to selectively gather information from specific neighboring agents. The degree of influence of a neighbor is based on dynamic non-verbal cues such as body motion, head pose (kinesics) and interpersonal space (proxemics). We further show that the KPM-Gate can be used to discover social groups using its natural interpretation as a social attention mechanism. We pose the communication policy learning problem as a multi-agent imitation learning problem. We learn a single policy shared by all agents under the assumption of a decentralized Markov decision process. We term our policy network as the Multi-Agent Group Discovery and Communication Mode Network (MAGDAM network), as it learns social group structure in addition to the dynamics of group communication. Our experimental validation on both synthetic and real world data shows that our model is able to both discover social group structure and learn an accurate multi-agent communication policy.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.01537](https://arxiv.org/abs/1903.01537)

##### PDF
[https://arxiv.org/pdf/1903.01537](https://arxiv.org/pdf/1903.01537)

