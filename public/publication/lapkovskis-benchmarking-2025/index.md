---
title: Benchmarking Dynamic SLO Compliance in Distributed Computing Continuum Systems

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Alfreds Lapkovskis
- Boris Sedlak
- Sindri Magnússon
- Schahram Dustdar
- Praveen Kumar Donta

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-03-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-10-25T13:23:12.934360Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- manuscript

# Publication name and optional abbreviated publication name.
publication: '*arXiv*'
publication_short: ''

doi: 10.48550/arXiv.2503.03274

abstract: "Ensuring Service Level Objectives (SLOs) in large-scale architectures,
  such as Distributed Computing Continuum Systems (DCCS), is challenging due to their
  heterogeneous nature and varying service requirements across different devices and
  applications. Additionally, unpredictable workloads and resource limitations lead
  to fluctuating performance and violated SLOs. To improve SLO compliance in DCCS,
  one possibility is to apply machine learning; however, the design choices are often
  left to the developer. To that extent, we provide a benchmark of Active Inference
  -- an emerging method from neuroscience -- against three established reinforcement
  learning algorithms (Deep Q-Network, Advantage Actor-Critic, and Proximal Policy
  Optimization). We consider a realistic DCCS use case: an edge device running a video
  conferencing application alongside a WebSocket server streaming videos. Using one
  of the respective algorithms, we continuously monitor key performance metrics, such
  as latency and bandwidth usage, to dynamically adjust parameters -- including the
  number of streams, frame rate, and resolution -- to optimize service quality and
  user experience. To test algorithms' adaptability to constant system changes, we
  simulate dynamically changing SLOs and both instant and gradual data-shift scenarios,
  such as network bandwidth limitations and fluctuating device thermal states. Although
  the evaluated algorithms all showed advantages and limitations, our findings demonstrate
  that Active Inference is a promising approach for ensuring SLO compliance in DCCS,
  offering lower memory usage, stable CPU utilization, and fast convergence."

# Summary. An optional shortened abstract.
summary: ''

tags:
- Computer Science - Distributed
- Parallel
- and Cluster Computing
- Computer Science - Machine Learning
- Computer Science - Artificial Intelligence
- Computer Science - Networking and Internet Architecture
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
