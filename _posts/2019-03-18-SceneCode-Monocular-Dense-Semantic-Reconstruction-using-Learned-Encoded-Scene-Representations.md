---
layout: post
title: "SceneCode: Monocular Dense Semantic Reconstruction using Learned Encoded Scene Representations"
date: 2019-03-18 16:55:47
categories: arXiv_CV
tags: arXiv_CV Face Relation
author: Shuaifeng Zhi, Michael Bloesch, Stefan Leutenegger, Andrew J. Davison
mathjax: true
---

* content
{:toc}

##### Abstract
Systems which incrementally create 3D semantic maps from image sequences must store and update representations of both geometry and semantic entities. However, while there has been much work on the correct formulation for geometrical estimation, state-of-the-art systems usually rely on simple semantic representations which store and update independent label estimates for each surface element (depth pixels, surfels, or voxels). Spatial correlation is discarded, and fused label maps are incoherent and noisy. We introduce a new compact and optimisable semantic representation by training a variational auto-encoder that is conditioned on a colour image. Using this learned latent space, we can tackle semantic label fusion by jointly optimising the low-dimenional codes associated with each of a set of overlapping images, producing consistent fused label maps which preserve spatial correlation. We also show how this approach can be used within a monocular keyframe based semantic mapping system where a similar code approach is used for geometry. The probabilistic formulation allows a flexible formulation where we can jointly estimate motion, geometry and semantics in a unified optimisation.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.06482](https://arxiv.org/abs/1903.06482)

##### PDF
[https://arxiv.org/pdf/1903.06482](https://arxiv.org/pdf/1903.06482)

