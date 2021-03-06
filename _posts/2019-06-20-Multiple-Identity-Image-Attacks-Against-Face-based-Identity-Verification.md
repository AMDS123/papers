---
layout: post
title: "Multiple-Identity Image Attacks Against Face-based Identity Verification"
date: 2019-06-20 08:58:22
categories: arXiv_CV
tags: arXiv_CV Face Quantitative Detection
author: Jerone T. A. Andrews, Thomas Tanay, Lewis D. Griffin
mathjax: true
---

* content
{:toc}

##### Abstract
Facial verification systems are vulnerable to poisoning attacks that make use of multiple-identity images (MIIs)---face images stored in a database that resemble multiple persons, such that novel images of any of the constituent persons are verified as matching the identity of the MII. Research on this mode of attack has focused on defence by detection, with no explanation as to why the vulnerability exists. New quantitative results are presented that support an explanation in terms of the geometry of the representations spaces used by the verification systems. In the spherical geometry of those spaces, the angular distance distributions of matching and non-matching pairs of face representations are only modestly separated, approximately centred at 90 and 40-60 degrees, respectively. This is sufficient for open-set verification on normal data but provides an opportunity for MII attacks. Our analysis considers ideal MII algorithms, demonstrating that, if realisable, they would deliver faces roughly 45 degrees from their constituent faces, thus classed as matching them. We study the performance of three methods for MII generation---gallery search, image space morphing, and representation space inversion---and show that the latter two realise the ideal well enough to produce effective attacks, while the former could succeed but only with an implausibly large gallery to search. Gallery search and inversion MIIs depend on having access to a facial comparator, for optimisation, but our results show that these attacks can still be effective when attacking disparate comparators, thus securing a deployed comparator is an insufficient defence.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08507](http://arxiv.org/abs/1906.08507)

##### PDF
[http://arxiv.org/pdf/1906.08507](http://arxiv.org/pdf/1906.08507)

