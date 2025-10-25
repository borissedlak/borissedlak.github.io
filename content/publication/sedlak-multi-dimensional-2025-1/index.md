---
title: 'Multi-dimensional Autoscaling of Processing Services: A Comparison of Agent-based
  Methods'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Boris Sedlak
- Alireza Furutanpey
- Zihang Wang
- Víctor Casamayor Pujol
- Schahram Dustdar

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-06-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-10-25T13:29:06.967200Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- manuscript

# Publication name and optional abbreviated publication name.
publication: '*arXiv*'
publication_short: ''

doi: 10.48550/arXiv.2506.10420

abstract: 'Edge computing breaks with traditional autoscaling due to strict resource
  constraints, thus, motivating more flexible scaling behaviors using multiple elasticity
  dimensions. This work introduces an agent-based autoscaling framework that dynamically
  adjusts both hardware resources and internal service configurations to maximize
  requirements fulfillment in constrained environments. We compare four types of scaling
  agents: Active Inference, Deep Q Network, Analysis of Structural Knowledge, and
  Deep Active Inference, using two real-world processing services running in parallel:
  YOLOv8 for visual recognition and OpenCV for QR code detection. Results show all
  agents achieve acceptable SLO performance with varying convergence patterns. While
  the Deep Q Network benefits from pre-training, the structural analysis converges
  quickly, and the deep active inference agent combines theoretical foundations with
  practical scalability advantages. Our findings provide evidence for the viability
  of multi-dimensional agent-based autoscaling for edge environments and encourage
  future work in this research direction.'

# Summary. An optional shortened abstract.
summary: ''

tags:
- Computer Science - Distributed
- Parallel
- and Cluster Computing
- Computer Science - Machine Learning
- Computer Science - Artificial Intelligence
- Computer Science - Emerging Technologies

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'uploads/slides_multi_dim_comparison.pdf'
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
