---
title: SLO-Aware Task Offloading within Collaborative Vehicle Platoons
featured: true
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

authors:
- Boris Sedlak
- Andrea Morichetta
- Yuhao Wang
- Yang Fei
- Liang Wang
- Schahram Dustdar
- Xiaobo Qu
date: '2024-09-01'
publishDate: '2024-10-01T15:35:15.297481Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2409.17667
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
---
