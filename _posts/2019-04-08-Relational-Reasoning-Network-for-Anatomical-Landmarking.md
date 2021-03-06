---
layout: post
title: "Relational Reasoning Network for Anatomical Landmarking"
date: 2019-04-08 20:58:47
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Deep_Learning Relation
author: Neslisah Torosdagli, Mary McIntosh, Denise K. Liberton, Payal Verma, Murat Sincan, Wade W. Han, Janice S. Lee, Ulas Bagci
mathjax: true
---

* content
{:toc}

##### Abstract
Accurately identifying anatomical landmarks is a crucial step in deformation analysis and surgical planning for craniomaxillofacial (CMF) bones. Available methods require segmentation of the object of interest for precise landmarking. Unlike those, our purpose in this study is to perform anatomical landmarking using the inherent relation of CMF bones without explicitly segmenting them. We propose a new deep network architecture, called relational reasoning network (RRN), to accurately learn the local and the global relations of the landmarks. Specifically, we are interested in learning landmarks in CMF region: mandible, maxilla, and nasal bones. The proposed RRN works in an end-to-end manner, utilizing learned relations of the landmarks based on dense-block units and without the need for segmentation. For a given a few landmarks as input, the proposed system accurately and efficiently localizes the remaining landmarks on the aforementioned bones. For a comprehensive evaluation of RRN, we used cone-beam computed tomography (CBCT) scans of 250 patients. The proposed system identifies the landmark locations very accurately even when there are severe pathologies or deformations in the bones. The proposed RRN has also revealed unique relationships among the landmarks that help us infer several reasoning about informativeness of the landmark points. RRN is invariant to order of landmarks and it allowed us to discover the optimal configurations (number and location) for landmarks to be localized within the object of interest (mandible) or nearby objects (maxilla and nasal). To the best of our knowledge, this is the first of its kind algorithm finding anatomical relations of the objects using deep learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.04354](http://arxiv.org/abs/1904.04354)

##### PDF
[http://arxiv.org/pdf/1904.04354](http://arxiv.org/pdf/1904.04354)

