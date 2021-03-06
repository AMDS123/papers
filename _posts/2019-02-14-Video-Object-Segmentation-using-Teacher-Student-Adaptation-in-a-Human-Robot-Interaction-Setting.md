---
layout: post
title: "Video Object Segmentation using Teacher-Student Adaptation in a Human Robot Interaction Setting"
date: 2019-02-14 21:39:43
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Mennatullah Siam, Chen Jiang, Steven Lu, Laura Petrich, Mahmoud Gamal, Mohamed Elhoseiny, Martin Jagersand
mathjax: true
---

* content
{:toc}

##### Abstract
Video object segmentation is an essential task in robot manipulation to facilitate grasping and learning affordances. Incremental learning is important for robotics in unstructured environments, since the total number of objects and their variations can be intractable. Inspired by the children learning process, human robot interaction (HRI) can be utilized to teach robots about the world guided by humans similar to how children learn from a parent or a teacher. A human teacher can show potential objects of interest to the robot, which is able to self adapt to the teaching signal without providing manual segmentation labels. We propose a novel teacher-student learning paradigm to teach robots about their surrounding environment. A two-stream motion and appearance ``teacher`` network provides pseudo-labels to adapt an appearance ``student`` network. The student network is able to segment the newly learned objects in other scenes, whether they are static or in motion. We also introduce a carefully designed dataset that serves the proposed HRI setup, denoted as (I)nteractive (V)ideo (O)bject (S)egmentation. Our IVOS dataset contains teaching videos of different objects, and manipulation tasks. Unlike previous datasets, IVOS provides manipulation tasks sequences with segmentation annotation along with the waypoints for the robot trajectories. It also provides segmentation annotation for the different transformations such as translation, scale, planar rotation, and out-of-plane rotation. Our proposed adaptation method outperforms the state-of-the-art on DAVIS and FBMS with 6.8% and 1.2% in F-measure respectively. It improves over the baseline on IVOS dataset with 46.1% and 25.9% in mIoU.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.07733](http://arxiv.org/abs/1810.07733)

##### PDF
[http://arxiv.org/pdf/1810.07733](http://arxiv.org/pdf/1810.07733)

