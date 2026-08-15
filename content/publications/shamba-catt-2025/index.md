---
title: "Contrast All the Time: Learning Time Series Representation from Temporal Consistency"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Kerstin Bach
- Gavin Taylor

date: '2026-07-15'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: 	Published in the 28th European Conference on AI (ECAI), October 2025
publication_short: Accepted at ECAI 2025

abstract: Representation learning for time series using contrastive learning has emerged as a critical technique for improving the performance of downstream tasks. To advance this effective approach, we introduce CaTT (Contrast All The Time), a new approach to unsupervised contrastive learning for time series, which takes advantage of dynamics between temporally similar moments more efficiently and effectively than existing methods. CaTT departs from conventional time-series contrastive approaches that rely on data augmentations or selected views. Instead, it uses the full temporal dimension by contrasting all time steps in parallel. This is made possible by a scalable NT-pair formulation, which extends the classic N-pair loss across both batch and temporal dimensions, making the learning process end-to-end and more efficient. CaTT learns directly from the natural structure of temporal data, using repeated or adjacent time steps as implicit supervision, without the need for pair selection heuristics. We demonstrate that this approach produces superior embeddings which allow better performance in downstream tasks. Additionally, training is faster than other contrastive learning approaches, making it suitable for large-scale and real-world time series applications. The source code is publicly available at https://github.com/sfi-norwai/CaTT.

# Summary. An optional shortened abstract.
summary: We introduce CaTT (Contrast All The Time), a new approach to unsupervised contrastive learning for time series, which takes advantage of dynamics between temporally similar moments more efficiently and effectively than existing methods

tags:
- Time Series # 1st tag is displayed for featured publication, so override alphabetical order to display the most relevant tag
- Self-supervised learning
- Representation learning
- Contrastive learning


# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
# hugoblox:
#   ids:
#     doi: 
links:

- type: pdf
  url: https://arxiv.org/pdf/2410.15416
- name: arXiv
  url: https://arxiv.org/abs/2410.15416
- name: IOS Press
  url: https://ebooks.iospress.nl/volumearticle/76073
- type: code
  url: https://github.com/sfi-norwai/CaTT
---
