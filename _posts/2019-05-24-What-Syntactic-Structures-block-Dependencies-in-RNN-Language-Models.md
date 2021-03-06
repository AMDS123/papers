---
layout: post
title: "What Syntactic Structures block Dependencies in RNN Language Models?"
date: 2019-05-24 20:06:04
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Language_Model Relation
author: Ethan Wilcox, Roger Levy, Richard Futrell
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent Neural Networks (RNNs) trained on a language modeling task have been shown to acquire a number of non-local grammatical dependencies with some success. Here, we provide new evidence that RNN language models are sensitive to hierarchical syntactic structure by investigating the filler--gap dependency and constraints on it, known as syntactic islands. Previous work is inconclusive about whether RNNs learn to attenuate their expectations for gaps in island constructions in particular or in any sufficiently complex syntactic environment. This paper gives new evidence for the former by providing control studies that have been lacking so far. We demonstrate that two state-of-the-art RNN models are are able to maintain the filler--gap dependency through unbounded sentential embeddings and are also sensitive to the hierarchical relationship between the filler and the gap. Next, we demonstrate that the models are able to maintain possessive pronoun gender expectations through island constructions---this control case rules out the possibility that island constructions block all information flow in these networks. We also evaluate three untested islands constraints: coordination islands, left branch islands, and sentential subject islands. Models are able to learn left branch islands and learn coordination islands gradiently, but fail to learn sentential subject islands. Through these controls and new tests, we provide evidence that model behavior is due to finer-grained expectations than gross syntactic complexity, but also that the models are conspicuously un-humanlike in some of their performance characteristics.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10431](http://arxiv.org/abs/1905.10431)

##### PDF
[http://arxiv.org/pdf/1905.10431](http://arxiv.org/pdf/1905.10431)

