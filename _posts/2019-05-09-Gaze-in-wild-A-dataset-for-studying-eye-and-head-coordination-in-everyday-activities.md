---
layout: post
title: "Gaze-in-wild: A dataset for studying eye and head coordination in everyday activities"
date: 2019-05-09 16:33:03
categories: arXiv_CV
tags: arXiv_CV Tracking Classification
author: Rakshit Kothari, Zhizhuo Yang, Christopher Kanan, Reynold Bailey, Jeff Pelz, Gabriel Diaz
mathjax: true
---

* content
{:toc}

##### Abstract
The interaction between the vestibular and ocular system has primarily been studied in controlled environments. Consequently, off-the shelf tools for categorization of gaze events (e.g. fixations, pursuits, saccade) fail when head movements are allowed. Our approach was to collect a novel, naturalistic, and multimodal dataset of eye+head movements when subjects performed everyday tasks while wearing a mobile eye tracker equipped with an inertial measurement unit and a 3D stereo camera. This Gaze-in-the-Wild dataset (GW) includes eye+head rotational velocities (deg/s), infrared eye images and scene imagery (RGB+D). A portion was labelled by coders into gaze motion events with a mutual agreement of 0.72 sample based Cohen's $\kappa$. This labelled data was used to train and evaluate two machine learning algorithms, Random Forest and a Recurrent Neural Network model, for gaze event classification. Assessment involved the application of established and novel event based performance metrics. Classifiers achieve $\sim$90$\%$ human performance in detecting fixations and saccades but fall short (60$\%$) on detecting pursuit movements. Moreover, pursuit classification is far worse in the absence of head movement information. A subsequent analysis of feature significance in our best-performing model revealed a reliance upon absolute eye and head velocity, indicating that classification does not require spatial alignment of the head and eye tracking coordinate systems. The GW dataset, trained classifiers and evaluation metrics will be made publicly available with the intention of facilitating growth in the emerging area of head-free gaze event classification.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13146](http://arxiv.org/abs/1905.13146)

##### PDF
[http://arxiv.org/pdf/1905.13146](http://arxiv.org/pdf/1905.13146)

