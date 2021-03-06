---
layout: post
title: "Bonnet: An Open-Source Training and Deployment Framework for Semantic Segmentation in Robotics using CNNs"
date: 2019-02-01 17:08:34
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Face CNN Semantic_Segmentation Prediction
author: Andres Milioto, Cyrill Stachniss
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to interpret a scene is an important capability for a robot that is supposed to interact with its environment. The knowledge of what is in front of the robot is, for example, relevant for navigation, manipulation, or planning. Semantic segmentation labels each pixel of an image with a class label and thus provides a detailed semantic annotation of the surroundings to the robot. Convolutional neural networks (CNNs) are popular methods for addressing this type of problem. The available software for training and the integration of CNNs for real robots, however, is quite fragmented and often difficult to use for non-experts, despite the availability of several high-quality open-source frameworks for neural network implementation and training. In this paper, we propose a tool called Bonnet, which addresses this fragmentation problem by building a higher abstraction that is specific for the semantic segmentation task. It provides a modular approach to simplify the training of a semantic segmentation CNN independently of the used dataset and the intended task. Furthermore, we also address the deployment on a real robotic platform. Thus, we do not propose a new CNN approach in this paper. Instead, we provide a stable and easy-to-use tool to make this technology more approachable in the context of autonomous systems. In this sense, we aim at closing a gap between computer vision research and its use in robotics research. We provide an open-source codebase for training and deployment. The training interface is implemented in Python using TensorFlow and the deployment interface provides a C++ library that can be easily integrated in an existing robotics codebase, a ROS node, and two standalone applications for label prediction in images and videos.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.08960](http://arxiv.org/abs/1802.08960)

##### PDF
[http://arxiv.org/pdf/1802.08960](http://arxiv.org/pdf/1802.08960)

