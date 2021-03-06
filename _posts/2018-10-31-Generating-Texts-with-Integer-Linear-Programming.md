---
layout: post
title: "Generating Texts with Integer Linear Programming"
date: 2018-10-31 18:24:32
categories: arXiv_CV
tags: arXiv_CV Text_Generation
author: Gerasimos Lampouras, Ion Androutsopoulos
mathjax: true
---

* content
{:toc}

##### Abstract
Concept-to-text generation typically employs a pipeline architecture, which often leads to suboptimal texts. Content selection, for example, may greedily select the most important facts, which may require, however, too many words to express, and this may be undesirable when space is limited or expensive. Selecting other facts, possibly only slightly less important, may allow the lexicalization stage to use much fewer words, or to report more facts in the same space. Decisions made during content selection and lexicalization may also lead to more or fewer sentence aggregation opportunities, affecting the length and readability of the resulting texts. Building upon on a publicly available state of the art natural language generator for Semantic Web ontologies, this article presents an Integer Linear Programming model that, unlike pipeline architectures, jointly considers choices available in content selection, lexicalization, and sentence aggregation to avoid greedy local decisions and produce more compact texts, i.e., texts that report more facts per word. Compact texts are desirable, for example, when generating advertisements to be included in Web search results, or when summarizing structured information in limited space. An extended version of the proposed model also considers a limited form of referring expression generation and avoids redundant sentences. An approximation of the two models can be used when longer texts need to be generated. Experiments with three ontologies confirm that the proposed models lead to more compact texts, compared to pipeline systems, with no deterioration or with improvements in the perceived quality of the generated texts.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.00051](https://arxiv.org/abs/1811.00051)

##### PDF
[https://arxiv.org/pdf/1811.00051](https://arxiv.org/pdf/1811.00051)

