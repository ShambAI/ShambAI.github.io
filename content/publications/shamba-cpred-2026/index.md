---
title: "Learning Representations for Multivariate Time Series Classification via Context Prediction"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Kerstin Bach
- Gavin Taylor

date: '2026-07-20'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: 	Under review
publication_short: Under review

abstract: Time series classification is critical across domains such as healthcare, robotics, fitness, and industrial monitoring. Modern time series classification relies on learning informative representations, but obtaining sufficient labeled data to learn such representations remains costly and often impractical. Self‑supervised representation learning, especially contrastive learning and masked modelling, offers a promising path to learning useful representations directly from unlabelled data. However, existing methods rely on carefully designed augmentation strategies or complex masking and reconstruction objectives that introduce domain-specific biases and computational overhead. In this work, we show that a simple pretext task based on context prediction is sufficient to learn meaningful representations for multivariate time series classification. Given a reference patch from a time series instance, our method, C-Pred, trains the encoder to identify which of K candidate patches from the same instance is the immediate temporal neighbour, a K-way classification task that requires no data augmentation, no cross-instance negative sampling, and no reconstruction. The difficulty of the pretext task is controlled by K, providing a principled mechanism to balance upstream task tractability and downstream representation quality. C-Pred achieves competitive performance on 28 UEA multivariate benchmarks and six large-scale real-world datasets (>20k instances) while substantially reducing training time compared to contrastive and masked modelling baselines.

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
  url: https://arxiv.org/pdf/2606.xxxx
- name: arXiv
  url: https://arxiv.org/abs/2606.xxxx
- type: code
  url: https://github.com/sfi-norwai/C-Pred
---
