---
layout: post
title: "DaiMoN: A Decentralized Artificial Intelligence Model Network"
date: 2019-07-19 06:02:41
categories: arXiv_AI
tags: arXiv_AI Embedding Classification
author: Surat Teerapittayanon, H. T. Kung
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce DaiMoN, a decentralized artificial intelligence model network, which incentivizes peer collaboration in improving the accuracy of machine learning models for a given classification problem. It is an autonomous network where peers may submit models with improved accuracy and other peers may verify the accuracy improvement. The system maintains an append-only decentralized ledger to keep the log of critical information, including who has trained the model and improved its accuracy, when it has been improved, by how much it has improved, and where to find the newly updated model. DaiMoN rewards these contributing peers with cryptographic tokens. A main feature of DaiMoN is that it allows peers to verify the accuracy improvement of submitted models without knowing the test labels. This is an essential component in order to mitigate intentional model overfitting by model-improving peers. To enable this model accuracy evaluation with hidden test labels, DaiMoN uses a novel learnable Distance Embedding for Labels (DEL) function proposed in this paper. Specific to each test dataset, DEL scrambles the test label vector by embedding it in a low-dimension space while approximately preserving the distance between the dataset's test label vector and a label vector inferred by the classifier. It therefore allows proof-of-improvement (PoI) by peers without providing them access to true test labels. We provide analysis and empirical evidence that under DEL, peers can accurately assess model accuracy. We also argue that it is hard to invert the embedding function and thus, DEL is resilient against attacks aiming to recover test labels in order to cheat. Our prototype implementation of DaiMoN is available at https://github.com/steerapi/daimon.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.08377](http://arxiv.org/abs/1907.08377)

##### PDF
[http://arxiv.org/pdf/1907.08377](http://arxiv.org/pdf/1907.08377)

