---
title: Multi-Dimensional Autoscaling of Stream Processing Services on Edge Devices

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Boris Sedlak
- Philipp Raith
- Andrea Morichetta
- Víctor Casamayor Pujol
- Schahram Dustdar

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-10-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-10-25T13:23:12.971380Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- manuscript

# Publication name and optional abbreviated publication name.
publication: '*arXiv*'
publication_short: ''

doi: 10.48550/arXiv.2510.06882

abstract: Edge devices have limited resources, which inevitably leads to situations
  where stream processing services cannot satisfy their needs. While existing autoscaling
  mechanisms focus entirely on resource scaling, Edge devices require alternative
  ways to sustain the Service Level Objectives (SLOs) of competing services. To address
  these issues, we introduce a Multi-dimensional Autoscaling Platform (MUDAP) that
  supports fine-grained vertical scaling across both service- and resource-level dimensions.
  MUDAP supports service-specific scaling tailored to available parameters, e.g.,
  scale data quality or model size for a particular service. To optimize the execution
  across services, we present a scaling agent based on Regression Analysis of Structural
  Knowledge (RASK). The RASK agent efficiently explores the solution space and learns
  a continuous regression model of the processing environment for inferring optimal
  scaling actions. We compared our approach with two autoscalers, the Kubernetes VPA
  and a reinforcement learning agent, for scaling up to 9 services on a single Edge
  device. Our results showed that RASK can infer an accurate regression model in merely
  20 iterations (i.e., observe 200s of processing). By increasingly adding elasticity
  dimensions, RASK sustained the highest request load with 28% less SLO violations,
  compared to baselines.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Computer Science - Distributed
- Parallel
- and Cluster Computing
- Computer Science - Machine Learning
- Computer Science - Artificial Intelligence
- Computer Science - Performance

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
