---
layout: post
title: "Self-Stabilizing and Private Distributed Shared Atomic Memory in Seldomly Fair Message Passing Networks"
date: 2018-06-09 16:08:54
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Shlomi Dolev, Thomas Petig, Elad Michael Schiller
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of privately emulating shared memory in message-passing networks. The system includes clients that store and retrieve replicated information on N servers, out of which e are malicious. When a client access a malicious server, the data field of that server response might be different than the value it originally stored. However, all other control variables in the server reply and protocol actions are according to the server algorithm. For the coded atomic storage (CAS) algorithms by Cadambe et al., we present an enhancement that ensures no information leakage and malicious fault-tolerance. We also consider recovery after the occurrence of transient faults that violate the assumptions according to which the system is to behave. After their last occurrence, transient faults leave the system in an arbitrary state (while the program code stays intact). We present a self-stabilizing algorithm, which recovers after the occurrence of transient faults. This addition to Cadambe et al. considers asynchronous settings as long as no transient faults occur. The recovery from transient faults that bring the system counters (close) to their maximal values may include the use of a global reset procedure, which requires the system run to be controlled by a fair scheduler. After the recovery period, the safety properties are provided for asynchronous system runs that are not necessarily controlled by fair schedulers. Since the recovery period is bounded and the occurrence of transient faults is extremely rare, we call this design criteria self-stabilization in the presence of seldom fairness. Our self-stabilizing algorithm uses a bounded storage during asynchronous executions (that are not necessarily fair). To the best of our knowledge, we are the first to address privacy and self-stabilization in the context of emulating atomic shared memory in networked systems.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.03498](https://arxiv.org/abs/1806.03498)

##### PDF
[https://arxiv.org/pdf/1806.03498](https://arxiv.org/pdf/1806.03498)

