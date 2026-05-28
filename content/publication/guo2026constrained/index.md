---
title: 'Constrained Bayesian Experimental Design via Online Planning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - "Yujia Guo"
  - "Daolang Huang"
  - "Xinyu Zhang"
  - "Sammie Katt"
  - "Samuel Kaski"
  - ayush

date: '2026-05-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-05-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Machine Learning*
publication_short: In *ICML*

abstract: 'Bayesian experimental design (BED) is a principled framework for data-efficient design of sequential experiments.
           However, existing BED methods are unable to adapt to dynamic constraints inherent in real-world tasks due to budget
           limitations, varying costs, or physical constraints
           that restrict how designs evolve over time. In
           this paper, we introduce a novel approach to BED
           that enables constrained optimization of experimental designs by combining offline pre-training
           of an amortized policy and a posterior network
           with online multi-step lookahead planning using
           scenario trees. We empirically demonstrate that
           our method yields substantially more informative
           design sequences than existing methods across a
           range of constrained BED tasks, while incurring
           only a modest additional computational overhead'


# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
  - icon:
    icon_pack: fas
    name: 'arXiv'
    url: https://arxiv.org/pdf/2605.26990

url_pdf: ''
url_code: 'https://github.com/yujiag21/COPEx'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false
---