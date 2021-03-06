---
layout: post
title: "Collaborative Large-Scale Dense 3D Reconstruction with Online Inter-Agent Pose Optimisation"
date: 2019-07-02 15:00:40
categories: arXiv_CV
tags: arXiv_CV Knowledge Face Tracking
author: Stuart Golodetz, Tommaso Cavallari, Nicholas A Lord, Victor A Prisacariu, David W Murray, Philip H S Torr
mathjax: true
---

* content
{:toc}

##### Abstract
Reconstructing dense, volumetric models of real-world 3D scenes is important for many tasks, but capturing large scenes can take significant time, and the risk of transient changes to the scene goes up as the capture time increases. These are good reasons to want instead to capture several smaller sub-scenes that can be joined to make the whole scene. Achieving this has traditionally been difficult: joining sub-scenes that may never have been viewed from the same angle requires a high-quality camera relocaliser that can cope with novel poses, and tracking drift in each sub-scene can prevent them from being joined to make a consistent overall scene. Recent advances, however, have significantly improved our ability to capture medium-sized sub-scenes with little to no tracking drift: real-time globally consistent reconstruction systems can close loops and re-integrate the scene surface on the fly, whilst new visual-inertial odometry approaches can significantly reduce tracking drift during live reconstruction. Moreover, high-quality regression forest-based relocalisers have recently been made more practical by the introduction of a method to allow them to be trained and used online. In this paper, we leverage these advances to present what to our knowledge is the first system to allow multiple users to collaborate interactively to reconstruct dense, voxel-based models of whole buildings using only consumer-grade hardware, a task that has traditionally been both time-consuming and dependent on the availability of specialised hardware. Using our system, an entire house or lab can be reconstructed in under half an hour and at a far lower cost than was previously possible.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1801.08361](http://arxiv.org/abs/1801.08361)

##### PDF
[http://arxiv.org/pdf/1801.08361](http://arxiv.org/pdf/1801.08361)

