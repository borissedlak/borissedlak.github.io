---
title: Markov Blanket Composition of SLOs
share: false
authors:
- Boris Sedlak
- Victor Casamayor Pujol
- Praveen Kumar Donta
- Schahram Dustdar
date: '2024-06-01'
publishDate: '2024-10-01T15:35:15.191582Z'
publication_types:
- paper-conference
publication: '*2024 IEEE International Conference on Edge Computing and Communications
  (EDGE)*'
doi: 10.1109/EDGE62653.2024.00025
abstract: Smart environments use composable microservices pipelines to process Internet
  of Things (IoT) data, where each service is dependent on the outcome of its predecessor.
  To ensure Quality of Service (QoS), individual services must fulfill Service Level
  Objectives (SLOs); however, SLO fulfillment is dependent on resources (e.g., processing
  or storage), which are scarcely available within the Edge. Hence, when distributing
  services over heterogeneous devices, this raises the question of where to deploy
  each service to best fulfill both its own SLOs as well as those imposed by dependent
  services. In this paper, we maximize SLO fulfillment of a pipeline-based application
  by analyzing these dependencies. To achieve this, services and hosting devices alike
  are extended with a Markov blanket (MB) – a probabilistic view into their internal
  processes – which are composed into one overarching model. Given a mutable set of
  services, hosts, and SLOs, the composed MB allows inferring the optimal assignment
  between services and edge devices. We evaluated our method for a smart city scenario,
  which assigned pipelined services (e.g., video processing) under constraints from
  subsequent services (e.g., consumer latency). The results showed how our method
  can support infrastructure providers by optimizing SLO fulfillment for arbitrary
  devices currently available.
url_slides: 'uploads/slides_services_composition.pdf'
---
