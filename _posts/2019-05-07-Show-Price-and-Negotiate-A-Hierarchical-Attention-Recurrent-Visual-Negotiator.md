---
layout: post
title: "Show, Price and Negotiate: A Hierarchical Attention Recurrent Visual Negotiator"
date: 2019-05-07 06:20:59
categories: arXiv_CV
tags: arXiv_CV Attention Embedding Deep_Learning
author: Amin Parvaneh, Ehsan Abbasnejad, Qi Wu, Javen Shi
mathjax: true
---

* content
{:toc}

##### Abstract
Negotiation, as a seller or buyer, is an essential and complicated aspect of online shopping. It is challenging for an intelligent agent because it requires (1) extracting and utilising information from multiple sources (e.g. photos, texts, and numerals), (2) predicting a suitable price for the products to reach the best possible agreement, (3) expressing the intention conditioned on the price in a natural language and (4) consistent pricing. Conventional dialog systems do not address these problems well. For example, we believe that the price should be the driving factor for the negotiation and understood by the agent. But conventionally, the price was simply treated as a word token i.e. being part of a sentence and sharing the same word embedding space with other words. To that end, we propose our Visual Negotiator that comprises of an end-to-end deep learning model that anticipates an initial agreement price and updates it while generating compelling supporting dialog. For (1), our visual negotiator utilises attention mechanism to extract relevant information from the images and textual description, and feeds the price (and later refined price) as separate important input to several stages of the system, instead of simply being part of a sentence; For (2), we use the attention to learn a price embedding to estimate an initial value; Subsequently, for (3) we generate the supporting dialog in an encoder-decoder fashion that utilises the price embedding. Further, we use a hierarchical recurrent model that learns to refine the price at one level while generating the supporting dialog in another; For (4), this hierarchical model provides consistent pricing. Empirically, we show that our model significantly improves negotiation on the CraigslistBargain dataset, in terms of the agreement price, price consistency, and the language quality.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03721](http://arxiv.org/abs/1905.03721)

##### PDF
[http://arxiv.org/pdf/1905.03721](http://arxiv.org/pdf/1905.03721)

