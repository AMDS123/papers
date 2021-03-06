---
layout: post
title: "LeagueAI: Improving object detector performance and flexibility through automatically generated training data and domain randomization"
date: 2019-05-28 21:07:22
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Detection
author: Oliver Struckmeier
mathjax: true
---

* content
{:toc}

##### Abstract
In this technical report I present my method for automatic synthetic dataset generation for object detection and demonstrate it on the video game League of Legends. This report furthermore serves as a handbook on how to automatically generate datasets and as an introduction on the dataset generation part of the LeagueAI framework. The LeagueAI framework is a software framework that provides detailed information about the game League of Legends based on the same input a human player would have, namely vision. The framework allows researchers and enthusiasts to develop their own intelligent agents or to extract detailed information about the state of the game. A big problem of machine vision applications usually is the laborious work of gathering large amounts of hand labeled data. Thus, a crucial part of the vision pipeline of the LeagueAI framework, the dataset generation, is presented in this report. The method involves extracting image raw data from the game's 3D models and combining them with the game background to create game-like synthetic images and to generate the corresponding labels automatically. In an experiment I compared a model trained on synthetic data to a model trained on hand labeled data and a model trained on a combined dataset. The model trained on the synthetic data showed higher detection precision on more classes and more reliable tracking performance of the player character. The model trained on the combined dataset did not perform better because of the different formats of the older hand labeled dataset and the synthetic data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13546](http://arxiv.org/abs/1905.13546)

##### PDF
[http://arxiv.org/pdf/1905.13546](http://arxiv.org/pdf/1905.13546)

