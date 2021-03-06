---
layout: post
title: "Specification Patterns for Robotic Missions"
date: 2019-01-07 21:34:33
categories: arXiv_RO
tags: arXiv_RO Relation
author: Claudio Menghi, Christos Tsigkanos, Patrizio Pelliccione, Carlo Ghezzi, Thorsten Berger
mathjax: true
---

* content
{:toc}

##### Abstract
Mobile and general-purpose robots increasingly support our everyday life, requiring dependable robotics control software. Creating such software mainly amounts to implementing their complex behaviors known as missions. Recognizing the need, a large number of domain-specific specification languages has been proposed. These, in addition to traditional logical languages, allow the use of formally specified missions for synthesis, verification, simulation, or guiding the implementation. For instance, the logical language LTL is commonly used by experts to specify missions, as an input for planners, which synthesize the behavior a robot should have. Unfortunately, domain-specific languages are usually tied to specific robot models, while logical languages such as LTL are difficult to use by non-experts. We present a catalog of 22 mission specification patterns for mobile robots, together with tooling for instantiating, composing, and compiling the patterns to create mission specifications. The patterns provide solutions for recurrent specification problems, each of which detailing the usage intent, known uses, relationships to other patterns, and---most importantly---a template mission specification in temporal logic. Our tooling produces specifications expressed in the LTL and CTL temporal logics to be used by planners, simulators, or model checkers. The patterns originate from 245 realistic textual mission requirements extracted from the robotics literature, and they are evaluated upon a total of 441 real-world mission requirements and 1251 mission specifications. Five of these reflect scenarios we defined with two well-known industrial partners developing human-size robots. We validated our patterns' correctness with simulators and two real robots.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.02077](http://arxiv.org/abs/1901.02077)

##### PDF
[http://arxiv.org/pdf/1901.02077](http://arxiv.org/pdf/1901.02077)

