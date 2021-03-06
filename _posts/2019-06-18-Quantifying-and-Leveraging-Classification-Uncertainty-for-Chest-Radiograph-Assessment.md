---
layout: post
title: "Quantifying and Leveraging Classification Uncertainty for Chest Radiograph Assessment"
date: 2019-06-18 19:21:44
categories: arXiv_CV
tags: arXiv_CV Classification Deep_Learning Prediction Detection
author: Florin C. Ghesu, Bogdan Georgescu, Eli Gibson, Sebastian Guendel, Mannudeep K. Kalra, Ramandeep Singh, Subba R. Digumarthy, Sasa Grbic, Dorin Comaniciu
mathjax: true
---

* content
{:toc}

##### Abstract
The interpretation of chest radiographs is an essential task for the detection of thoracic diseases and abnormalities. However, it is a challenging problem with high inter-rater variability and inherent ambiguity due to inconclusive evidence in the data, limited data quality or subjective definitions of disease appearance. Current deep learning solutions for chest radiograph abnormality classification are typically limited to providing probabilistic predictions, relying on the capacity of learning models to adapt to the high degree of label noise and become robust to the enumerated causal factors. In practice, however, this leads to overconfident systems with poor generalization on unseen data. To account for this, we propose an automatic system that learns not only the probabilistic estimate on the presence of an abnormality, but also an explicit uncertainty measure which captures the confidence of the system in the predicted output. We argue that explicitly learning the classification uncertainty as an orthogonal measure to the predicted output, is essential to account for the inherent variability characteristic of this data. Experiments were conducted on two datasets of chest radiographs of over 85,000 patients. Sample rejection based on the predicted uncertainty can significantly improve the ROC-AUC, e.g., by 8% to 0.91 with an expected rejection rate of under 25%. Eliminating training samples using uncertainty-driven bootstrapping, enables a significant increase in robustness and accuracy. In addition, we present a multi-reader study showing that the predictive uncertainty is indicative of reader errors.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07775](http://arxiv.org/abs/1906.07775)

##### PDF
[http://arxiv.org/pdf/1906.07775](http://arxiv.org/pdf/1906.07775)

