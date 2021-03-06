---
layout: post
title: "Image Evolution Trajectory Prediction and Classification from Baseline using Learning-based Patch Atlas Selection for Early Diagnosis"
date: 2019-07-13 12:17:00
categories: arXiv_CV
tags: arXiv_CV Classification Prediction
author: Can Gafuroglu, Islem Rekik
mathjax: true
---

* content
{:toc}

##### Abstract
Patients initially diagnosed with early mild cognitive impairment (eMCI) are known to be a clinically heterogeneous group with very subtle patterns of brain atrophy. To examine the boarders between normal controls (NC) and eMCI, Magnetic Resonance Imaging (MRI) was extensively used as a non-invasive imaging modality to pin-down subtle changes in brain images of MCI patients. However, eMCI research remains limited by the number of available MRI acquisition timepoints. Ideally, one would learn how to diagnose MCI patients in an early stage from MRI data acquired at a single timepoint, while leveraging 'non-existing' follow-up observations. To this aim, we propose novel supervised and unsupervised frameworks that learn how to jointly predict and label the evolution trajectory of intensity patches, each seeded at a specific brain landmark, from a baseline intensity patch. Specifically, both strategies aim to identify the best training atlas patches at baseline timepoint to predict and classify the evolution trajectory of a given testing baseline patch. The supervised technique learns how to select the best atlas patches by training bidirectional mappings from the space of pairwise patch similarities to their corresponding prediction errors -when one patch was used to predict the other. On the other hand, the unsupervised technique learns a manifold of baseline atlas and testing patches using multiple kernels to well capture patch distributions at multiple scales. Once the best baseline atlas patches are selected, we retrieve their evolution trajectories and average them to predict the evolution trajectory of the testing baseline patch. Next, we input the predicted trajectories to an ensemble of linear classifiers, each trained at a specific landmark. Our classification accuracy increased by up to 10% points in comparison to single timepoint-based classification methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06064](http://arxiv.org/abs/1907.06064)

##### PDF
[http://arxiv.org/pdf/1907.06064](http://arxiv.org/pdf/1907.06064)

