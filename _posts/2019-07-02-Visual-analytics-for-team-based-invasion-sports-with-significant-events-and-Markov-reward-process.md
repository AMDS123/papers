---
layout: post
title: "Visual analytics for team-based invasion sports with significant events and Markov reward process"
date: 2019-07-02 08:11:16
categories: arXiv_AI
tags: arXiv_AI
author: Kun Zhao, Takayuki Osogami, Tetsuro Morimura
mathjax: true
---

* content
{:toc}

##### Abstract
In team-based invasion sports such as soccer and basketball, analytics is important for teams to understand their performance and for audiences to understand matches better. The present work focuses on performing visual analytics to evaluate the value of any kind of event occurring in a sports match with a continuous parameter space. Here, the continuous parameter space involves the time, location, score, and other parameters. Because the spatiotemporal data used in such analytics is a low-level representation and has a very large size, however, traditional analytics may need to discretize the continuous parameter space (e.g., subdivide the playing area) or use a local feature to limit the analysis to specific events (e.g., only shots). These approaches make evaluation impossible for any kind of event with a continuous parameter space. To solve this problem, we consider a whole match as a Markov chain of significant events, so that event values can be estimated with a continuous parameter space by solving the Markov chain with a machine learning model. The significant events are first extracted by considering the time-varying distribution of players to represent the whole match. Then, the extracted events are redefined as different states with the continuous parameter space and built as a Markov chain so that a Markov reward process can be applied. Finally, the Markov reward process is solved by a customized fitted-value iteration algorithm so that the event values with the continuous parameter space can be predicted by a regression model. As a result, the event values can be visually inspected over the whole playing field under arbitrary given conditions. Experimental results with real soccer data show the effectiveness of the proposed system.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01221](http://arxiv.org/abs/1907.01221)

##### PDF
[http://arxiv.org/pdf/1907.01221](http://arxiv.org/pdf/1907.01221)

