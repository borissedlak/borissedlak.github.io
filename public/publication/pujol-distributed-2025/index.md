---
title: Distributed Intelligence in the Computing Continuum with Active Inference

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Victor Casamayor Pujol
- Boris Sedlak
- Tommaso Salvatori
- Karl Friston
- Schahram Dustdar

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-05-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-10-25T13:23:12.952104Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- manuscript

# Publication name and optional abbreviated publication name.
publication: '*arXiv*'
publication_short: ''

doi: 10.48550/arXiv.2505.24618

abstract: The Computing Continuum (CC) is an emerging Internet-based computing paradigm
  that spans from local Internet of Things sensors and constrained edge devices to
  large-scale cloud data centers. Its goal is to orchestrate a vast array of diverse
  and distributed computing resources to support the next generation of Internet-based
  applications. However, the distributed, heterogeneous, and dynamic nature of CC
  platforms demands distributed intelligence for adaptive and resilient service management.
  This article introduces a distributed stream processing pipeline as a CC use case,
  where each service is managed by an Active Inference (AIF) agent. These agents collaborate
  to fulfill service needs specified by SLOiDs, a term we introduce to denote Service
  Level Objectives that are aware of its deployed devices, meaning that non-functional
  requirements must consider the characteristics of the hosting device. We demonstrate
  how AIF agents can be modeled and deployed alongside distributed services to manage
  them autonomously. Our experiments show that AIF agents achieve over 90% SLOiD fulfillment
  when using tested transition models, and around 80% when learning the models during
  deployment. We compare their performance to a multi-agent reinforcement learning
  algorithm, finding that while both approaches yield similar results, MARL requires
  extensive training, whereas AIF agents can operate effectively from the start. Additionally,
  we evaluate the behavior of AIF agents in offloading scenarios, observing a strong
  capacity for adaptation. Finally, we outline key research directions to advance
  AIF integration in CC platforms.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Computer Science - Distributed
- Parallel
- and Cluster Computing
- Computer Science - Multiagent Systems
- Electrical Engineering and Systems Science - Systems and Control
- Computer Science - Systems and Control

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
