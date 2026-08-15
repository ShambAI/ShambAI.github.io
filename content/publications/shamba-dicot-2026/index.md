---
title: "Divide and Contrast: Learning Robust Temporal Features without Augmentation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Kerstin Bach
- Gavin Taylor

date: '2026-05-20'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: 	Published in the 43rd International Conference on Machine Learning (ICML 2026)
publication_short: accepted at *ICML*

abstract: Self-supervised learning for time-series representation aims to reduce reliance on labeled data while maintaining strong downstream performance, yet many existing approaches incur high computational costs or rely on assumptions that do not hold across diverse temporal dynamics. In this work, we introduce Divide and Contrast (Di-COT), an unsupervised framework that avoids data augmentation and multiple encoder passes by contrasting informative substructures within a window rather than individual timesteps. Di-COT stochastically partitions each window into a small number of overlapping sub-blocks per iteration, enabling efficient and meaningful contrast while mitigating false positives during temporal transitions. To further improve scalability, we adopt a contrastive objective whose computation depends on the batch size and the number of sub-blocks, making loss computation independent of sequence length. Extensive experiments on six large-scale real-world datasets, as well as the UCR and UEA benchmarks, demonstrate that Di-COT learns semantically structured and transferable representations, achieving state-of-the-art performance on classification, clustering, kNN, and cross-dataset transfer, while substantially reducing training time. The source code is publicly available at this https URL. The source code is publicly available at https://github.com/sfi-norwai/Di-COT.

# Summary. An optional shortened abstract.
summary: We propose Di-COT, a simple framework for learning from time-series data without labels or data augmentation.

tags:
- Time Series # 1st tag is displayed for featured publication, so override alphabetical order to display the most relevant tag
- Self-supervised learning
- Representation learning
- Deep learning


# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
# hugoblox:
#   ids:
#     doi: 
links:
# - type: poster
#   url: https://icml.cc/media/PosterPDFs/ICML%202026/66203.png
- type: pdf
  url: https://openreview.net/pdf?id=5ooFLqHTo4
- name: arXiv
  url: https://arxiv.org/abs/2605.21241
- name: openreview
  url: https://openreview.net/forum?id=5ooFLqHTo4
- name: ICML
  url: https://icml.cc/virtual/2026/poster/66203
- type: code
  url: https://github.com/sfi-norwai/Di-COT
---
