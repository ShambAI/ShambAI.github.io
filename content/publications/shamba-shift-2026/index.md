---
title: "Learning by Shifting: Temporal View Construction for Time Series Contrastive Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Kerstin Bach
- Gavin Taylor

date: '2026-06-20'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: 	Published in the European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (ECML PKDD)
publication_short: accepted at *ECML PKDD*

abstract: Supervised learning demands large quantities of labeled data, a bottleneck that is expensive and reliant on domain-specific expertise. Self-supervised learning, particularly contrastive learning, has emerged as a compelling alternative, enabling rich representation learning directly from unlabeled data. Yet its success hinges critically on the design of positive and negative sample pairs. Existing approaches for time series rely on hand-crafted augmentations and masking heuristics that embed strong domain assumptions, often limiting generalization across diverse temporal patterns and potentially introducing spurious correlations. In this work, we challenge this paradigm by demonstrating that explicitly encoding temporal shift invariance through a simple, deterministic view construction is sufficient to learn strong representations for time series classification. By exploiting temporal structure, our method, Shift Invariant Feature Training (ShiFT), achieves state-of-the-art performance on six diverse real-world time series benchmark datasets, as well as the UCR and UEA archives, while reducing training time. Beyond empirical performance, we present a systematic analysis of contrastive learning dynamics in time series settings, examining the effects of batch size and the number of negatives on downstream performance. Our findings provide practical insights for designing efficient contrastive learning frameworks for time series representation learning. The source code is publicly available at https://github.com/sfi-norwai/ShiFT.

# Summary. An optional shortened abstract.
summary: We demonstrated that explicitly encoding temporal shift invariance through a simple, deterministic view construction is sufficient to learn strong representations for time series classification.

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
  url: https://arxiv.org/pdf/2606.21957
- name: arXiv
  url: https://arxiv.org/abs/2606.21957
- type: code
  url: https://github.com/sfi-norwai/ShiFT
---
