---
layout: post
title: "Unsupervised and Unregistered Hyperspectral Image Super-Resolution with Mutual Dirichlet-Net"
date: 2019-04-27 16:38:35
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Relation
author: Ying Qu, Hairong Qi, Chiman Kwan
mathjax: true
---

* content
{:toc}

##### Abstract
Hyperspectral images (HSI) provide rich spectral information that contributed to the successful performance improvement of numerous computer vision tasks. However, it can only be achieved at the expense of images' spatial resolution. Hyperspectral image super-resolution (HSI-SR) addresses this problem by fusing low resolution (LR) HSI with multispectral image (MSI) carrying much higher spatial resolution (HR). All existing HSI-SR approaches require the LR HSI and HR MSI to be well registered and the reconstruction accuracy of the HR HSI relies heavily on the registration accuracy of different modalities. This paper exploits the uncharted problem domain of HSI-SR without the requirement of multi-modality registration. Given the unregistered LR HSI and HR MSI with overlapped regions, we design a unique unsupervised learning structure linking the two unregistered modalities by projecting them into the same statistical space through the same encoder. The mutual information (MI) is further adopted to capture the non-linear statistical dependencies between the representations from two modalities (carrying spatial information) and their raw inputs. By maximizing the MI, spatial correlations between different modalities can be well characterized to further reduce the spectral distortion. A collaborative $l_{2,1}$ norm is employed as the reconstruction error instead of the more common $l_2$ norm, so that individual pixels can be recovered as accurately as possible. With this design, the network allows to extract correlated spectral and spatial information from unregistered images that better preserves the spectral information. The proposed method is referred to as unregistered and unsupervised mutual Dirichlet Net ($u^2$-MDN). Extensive experimental results using benchmark HSI datasets demonstrate the superior performance of $u^2$-MDN as compared to the state-of-the-art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12175](http://arxiv.org/abs/1904.12175)

##### PDF
[http://arxiv.org/pdf/1904.12175](http://arxiv.org/pdf/1904.12175)

