---
layout: post
title: "Considerations for the Interpretation of Bias Measures of Word Embeddings"
date: 2019-06-19 21:56:25
categories: arXiv_CL
tags: arXiv_CL Embedding Relation
author: Inom Mirzaev, Anthony Schulte, Michael Conover, Sam Shah
mathjax: true
---

* content
{:toc}

##### Abstract
Word embedding spaces are powerful tools for capturing latent semantic relationships between terms in corpora, and have become widely popular for building state-of-the-art natural language processing algorithms. However, studies have shown that societal biases present in text corpora may be incorporated into the word embedding spaces learned from them. Thus, there is an ethical concern that human-like biases contained in the corpora and their derived embedding spaces might be propagated, or even amplified with the usage of the biased embedding spaces in downstream applications. In an attempt to quantify these biases so that they may be better understood and studied, several bias metrics have been proposed. We explore the statistical properties of these proposed measures in the context of their cited applications as well as their supposed utilities. We find that there are caveats to the simple interpretation of these metrics as proposed. We find that the bias metric proposed by Bolukbasi et al. 2016 is highly sensitive to embedding hyper-parameter selection, and that in many cases, the variance due to the selection of some hyper-parameters is greater than the variance in the metric due to corpus selection, while in fewer cases the bias rankings of corpora vary with hyper-parameter selection. In light of these observations, it may be the case that bias estimates should not be thought to directly measure the properties of the underlying corpus, but rather the properties of the specific embedding spaces in question, particularly in the context of hyper-parameter selections used to generate them. Hence, bias metrics of spaces generated with differing hyper-parameters should be compared only with explicit consideration of the embedding-learning algorithms particular configurations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08379](http://arxiv.org/abs/1906.08379)

##### PDF
[http://arxiv.org/pdf/1906.08379](http://arxiv.org/pdf/1906.08379)

