---
title: "eMargin: Revisiting Contrastive Learning with Margin-Based Separation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Kerstin Bach
- Gavin Taylor

date: '2025-07-15'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: 	LDD'25 Learning from Difficult Data Workshop (ECAI 2025)
publication_short: Accepted at LDD'25 Workshop (ECAI 2025)

abstract: We revisit previous contrastive learning frameworks to investigate the effect of introducing an adaptive margin into the contrastive loss function for time series representation learning. Specifically, we explore whether an adaptive margin (eMargin), adjusted based on a predefined similarity threshold, can improve the separation between adjacent but dissimilar time steps and subsequently lead to better performance in downstream tasks. Our study evaluates the impact of this modification on clustering performance and classification in three benchmark datasets. Our findings, however, indicate that achieving high scores on unsupervised clustering metrics does not necessarily imply that the learned embeddings are meaningful or effective in downstream tasks. To be specific, eMargin added to InfoNCE consistently outperforms state-of-the-art baselines in unsupervised clustering metrics, but struggles to achieve competitive results in downstream classification with linear probing. The source code is publicly available at https://github.com/sfi-norwai/eMargin.

# Summary. An optional shortened abstract.
summary: We explore whether an adaptive margin (eMargin), adjusted based on a predefined similarity threshold, can improve the separation between adjacent but dissimilar time steps and subsequently lead to better performance in downstream tasks.
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
  url: https://arxiv.org/pdf/2507.14828
- name: arXiv
  url: https://arxiv.org/abs/2507.14828
- type: code
  url: https://github.com/sfi-norwai/eMargin
---
