---
layout: post
title: "Structure-Invariant Testing for Machine Translation"
date: 2019-07-19 22:20:01
categories: arXiv_CL
tags: arXiv_CL NMT
author: Pinjia He, Clara Meister, Zhendong Su
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, machine translation software has increasingly been integrated into our daily lives. People routinely use machine translation for various applications, such as describing symptoms to a foreign doctor and reading political news in a foreign language. However, due to the complexity and intractability of neural machine translation (NMT) models that power modern machine translation systems, these systems are far from being robust. They can return inferior results that lead to misunderstanding, medical misdiagnoses, or threats to personal safety. Despite its apparent importance, validating the robustness of machine translation is very difficult and has, therefore, been much under-explored. 
 To tackle this challenge, we introduce structure-invariant testing (SIT), a novel, widely applicable metamorphic testing methodology for validating machine translation software. Our key insight is that the translation results of similar source sentences should typically exhibit a similar sentence structure. SIT is designed to leverage this insight to test any machine translation system with unlabeled sentences; it specifically targets mistranslations that are difficult-to-find using state-of-the-art translation quality metrics such as BLEU. We have realized a practical implementation of SIT by (1) substituting one word in a given sentence with semantically similar, syntactically equivalent words to generate similar sentences, and (2) using syntax parse trees (obtained via constituency/dependency parsing) to represent sentence structure. To evaluate SIT, we have used it to test Google Translate and Bing Microsoft Translator with 200 unlabeled sentences as input, which led to 56 and 61 buggy translations with 60% and 61% top-1 accuracy, respectively. The bugs are diverse, including under-translation, over-translation, incorrect modification, word/phrase mistranslation, and unclear logic.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.08710](http://arxiv.org/abs/1907.08710)

##### PDF
[http://arxiv.org/pdf/1907.08710](http://arxiv.org/pdf/1907.08710)

