---
title: SLO-Aware Task Offloading within Collaborative Vehicle Platoons
featured: true
summary: Imagine you're a video processing service executed at an autonomous vehicle; in case you're struggling, which vehicle can best fulfill your requirements and what are the implications to co-located services?
share: false

authors:
- Boris Sedlak
- Andrea Morichetta
- Yuhao Wang
- Yang Fei
- Liang Wang
- Schahram Dustdar
- Xiaobo Qu
date: '2024-12-01'
publishDate: '2024-12-01T15:35:15.297481Z'
publication_types:
- paper-conference
publication: '*Service-Oriented Computing*'
doi: 10.1007/978-981-96-0808-9_6
abstract: In the context of autonomous vehicles (AVs), offloading is essential for
  guaranteeing the execution of perception tasks, e.g., mobile mapping or object detection.
  While existing work focused extensively on minimizing inter-vehicle networking latency
  through offloading, other objectives become relevant in the case of vehicle platoons,
  e.g., energy efficiency or data quality for heavy-duty or public transport. Therefore,
  we aim to enforce these Service Level Objectives (SLOs) through intelligent task
  offloading within AV platoons. We present a collaborative framework for handling
  and offloading services in a purely Vehicle-to-Vehicle approach (V2V) based on Bayesian
  Networks (BNs). Each service aggregates local observations into a platoon-wide understanding
  of how to ensure SLOs for heterogeneous vehicle types. With the resulting models,
  services can proactively decide to offload if this promises to improve global SLO
  fulfillment. We evaluate the approach in a real-case setting, where vehicles in
  a platoon continuously (i.e., every 500 ms) interpret the SLOs of three actual perception
  services. Our probabilistic, predictive method shows promising results in handling
  large AV platoons; within seconds, it detects and resolves SLO violations through
  offloading.
tags:
- Vehicular Edge Computing
- Service Level Objectives
- Distributed Systems
url_slides: 'uploads/slides_icsoc_slo_aware.pdf'
---
