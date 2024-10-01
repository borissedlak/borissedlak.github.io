---
title: Adaptive Stream Processing on Edge Devices through Active Inference
authors:
- Boris Sedlak
- Victor Casamayor Pujol
- Andrea Morichetta
- Praveen Kumar Donta
- Schahram Dustdar
date: '2024-09-01'
publishDate: '2024-10-01T15:35:15.286946Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2409.17937
abstract: The current scenario of IoT is witnessing a constant increase on the volume
  of data, which is generated in constant stream, calling for novel architectural
  and logical solutions for processing it. Moving the data handling towards the edge
  of the computing spectrum guarantees better distribution of load and, in principle,
  lower latency and better privacy. However, managing such a structure is complex,
  especially when requirements, also referred to Service Level Objectives (SLOs),
  specified by applications' owners and infrastructure managers need to be ensured.
  Despite the rich number of proposals of Machine Learning (ML) based management solutions,
  researchers and practitioners yet struggle to guarantee long-term prediction and
  control, and accurate troubleshooting. Therefore, we present a novel ML paradigm
  based on Active Inference (AIF) -- a concept from neuroscience that describes how
  the brain constantly predicts and evaluates sensory information to decrease long-term
  surprise. We implement it and evaluate it in a heterogeneous real stream processing
  use case, where an AIF-based agent continuously optimizes the fulfillment of three
  SLOs for three autonomous driving services running on multiple devices. The agent
  used causal knowledge to gradually develop an understanding of how its actions are
  related to requirements fulfillment, and which configurations to favor. Through
  this approach, our agent requires up to thirty iterations to converge to the optimal
  solution, showing the capability of offering accurate results in a short amount
  of time. Furthermore, thanks to AIF and its causal structures, our method guarantees
  full transparency on the decision making, making the interpretation of the results
  and the troubleshooting effortless.
tags:
- Computer Science - Distributed
- Parallel
- and Cluster Computing
- Computer Science - Machine Learning
---
