---
layout: post
title: "Longitudinal Trajectory Prediction of Human-driven Vehicles Near Traffic Lights"
date: 2019-06-02 21:06:25
categories: arXiv_RO
tags: arXiv_RO Prediction
author: Geunseob Oh, Huei Peng
mathjax: true
---

* content
{:toc}

##### Abstract
Predicting future trajectories of human-driven vehicles is a crucial problem in autonomous driving. While the trajectory prediction problem in highway has been well addressed, the problem in city driving where the motions of vehicles are governed by traffic lights has barely been discussed. Despite its importance, no comprehensive model which predicts longitudinal trajectories of vehicles near traffic signals is available. Our idea is to simply utilize information from vehicle-to-infrastructure communications to model how human drivers drive near traffic signals and use the model for the longitudinal trajectory prediction. We propose a "human policy model" which maps a state of a human vehicle and a traffic signal to a longitudinal acceleration of the vehicle. The proposed model is trained on 471,273 data points sampled from 3,398 real-world historical trips conducted by 583 distinct vehicles near a signalized intersection. We used a neural network for learning deterministic (most-likelihood) human policy and a mixture density network for learning probabilistic human policy. Our most-likelihood predictions were as accurate as 0.9-2.3m for the position and 0.3-0.9m/s for the speed (the median error between the predicted and the actual value at 5 seconds into the future) depending on scenarios. This result is far superior to the results obtained from other available models. Our probabilistic policy model provides probabilistic contexts for the predicted trajectories. It is also capable of learning multi-modal distributions which allows the model to capture competing policies, for example, 'pass' or 'stop' in the yellow-light dilemma zone. Finally, we conducted an ablation study to identify the influence of the state features on the deterministic policy model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00486](http://arxiv.org/abs/1906.00486)

##### PDF
[http://arxiv.org/pdf/1906.00486](http://arxiv.org/pdf/1906.00486)

