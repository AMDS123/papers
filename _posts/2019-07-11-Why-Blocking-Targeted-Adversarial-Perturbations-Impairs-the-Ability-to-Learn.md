---
layout: post
title: "Why Blocking Targeted Adversarial Perturbations Impairs the Ability to Learn"
date: 2019-07-11 06:28:25
categories: arXiv_AI
tags: arXiv_AI Adversarial Knowledge
author: Ziv Katzir, Yuval Elovici
mathjax: true
---

* content
{:toc}

##### Abstract
Despite their accuracy, neural network-based classifiers are still prone to manipulation through adversarial perturbations. Those perturbations are designed to be misclassified by the neural network, while being perceptually identical to some valid input. The vast majority of attack methods rely on white-box conditions, where the attacker has full knowledge of the attacked network's parameters. This allows the attacker to calculate the network's loss gradient with respect to some valid input and use this gradient in order to create an adversarial example. The task of blocking white-box attacks has proven difficult to solve. While a large number of defense methods have been suggested, they have had limited success. In this work we examine this difficulty and try to understand it. We systematically explore the abilities and limitations of defensive distillation, one of the most promising defense mechanisms against adversarial perturbations suggested so far in order to understand the defense challenge. We show that contrary to commonly held belief, the ability to bypass defensive distillation is not dependent on an attack's level of sophistication. In fact, simple approaches, such as the Targeted Gradient Sign Method, are capable of effectively bypassing defensive distillation. We prove that defensive distillation is highly effective against non-targeted attacks but is unsuitable for targeted attacks. This discovery leads us to realize that targeted attacks leverage the same input gradient that allows a network to be trained. This implies that blocking them will require losing the network's ability to learn, presenting an impossible tradeoff to the research community.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05718](http://arxiv.org/abs/1907.05718)

##### PDF
[http://arxiv.org/pdf/1907.05718](http://arxiv.org/pdf/1907.05718)

