---
layout: post
title: "LORAKI: Autocalibrated Recurrent Neural Networks for Autoregressive MRI Reconstruction in k-Space"
date: 2019-04-20 03:02:34
categories: arXiv_CV
tags: arXiv_CV CNN RNN Deep_Learning Relation
author: Tae Hyung Kim, Pratyush Garg, Jusin P. Haldar
mathjax: true
---

* content
{:toc}

##### Abstract
We propose and evaluate a new MRI reconstruction method named LORAKI that trains an autocalibrated scan-specific recurrent neural network (RNN) to recover missing k-space data. Methods like GRAPPA, SPIRiT, and AC-LORAKS assume that k-space data has shift-invariant autoregressive structure, and that the scan-specific autoregression relationships needed to recover missing samples can be learned from fully-sampled autocalibration (ACS) data. Recently, the structure of the linear GRAPPA method has been translated into a nonlinear deep learning method named RAKI. RAKI uses ACS data to train an artificial neural network to interpolate missing k-space samples, and often outperforms GRAPPA. In this work, we apply a similar principle to translate the linear AC-LORAKS method (simultaneously incorporating support, phase, and parallel imaging constraints) into a nonlinear deep learning method named LORAKI. Since AC-LORAKS is iterative and convolutional, LORAKI takes the form of a convolutional RNN. This new architecture admits a wide range of sampling patterns, and even calibrationless patterns are possible if synthetic ACS data is generated. The performance of LORAKI was evaluated with retrospectively undersampled brain datasets, with comparisons against other related reconstruction methods. Results suggest that LORAKI can provide improved reconstruction compared to other scan-specific autocalibrated reconstruction methods like GRAPPA, RAKI, and AC-LORAKS. LORAKI offers a new deep-learning approach to MRI reconstruction based on RNNs in k-space, and enables improved image quality and enhanced sampling flexibility.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09390](http://arxiv.org/abs/1904.09390)

##### PDF
[http://arxiv.org/pdf/1904.09390](http://arxiv.org/pdf/1904.09390)

