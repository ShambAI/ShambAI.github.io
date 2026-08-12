---
title: Echocardiography Segmentation With Enforced Temporal Consistency

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Nicolas Duchateau
- Olivier Bernard
- Pierre-Marc Jodoin

date: '2022-05-09'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Medical Imaging*'
publication_short: '*IEEE TMI*'

abstract: Convolutional neural networks (CNN) have demonstrated their ability to segment
  2D cardiac ultrasound images. However, despite recent successes according to which
  the intra-observer variability on end-diastole and end-systole images has been reached,
  CNNs still struggle to leverage temporal information to provide accurate and temporally
  consistent segmentation maps across the whole cycle. Such consistency is required
  to accurately describe the cardiac function, a necessary step in diagnosing many
  cardiovascular diseases. In this paper, we propose a framework to learn the 2D+time
  apical long-axis cardiac shape such that the segmented sequences can benefit from
  temporal and anatomical consistency constraints. Our method is a post-processing
  that takes as input segmented echocardiographic sequences produced by any state-of-the-art
  method and processes it in two steps to (i) identify spatio-temporal inconsistencies
  according to the overall dynamics of the cardiac sequence and (ii) correct the inconsistencies.
  The identification and correction of cardiac inconsistencies relies on a constrained
  autoencoder trained to learn a physiologically interpretable embedding of cardiac
  shapes, where we can both detect and fix anomalies. We tested our framework on 98
  full-cycle sequences from the CAMUS dataset, which are available alongside this
  paper. Our temporal regularization method not only improves the accuracy of the
  segmentation across the whole sequences, but also enforces temporal and anatomical
  consistency.

# Summary. An optional shortened abstract.
summary: In this paper, we propose a framework to learn the 2D+time apical long-axis cardiac shape such that the segmented sequences can benefit from temporal and anatomical consistency constraints.

tags:
- Cardiac segmentation  # 1st tag is displayed for featured publication, so override order from journal to display the most relevant tag
- Deep learning
- CNN
- Encoding
- Variational autoencoder
- Annotations
- Image segmentation
- Ultrasound
- Echocardiography
- Cardiac function
- Left ventricle
- Myocardium
- Shape

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1109/TMI.2022.3173669
links:
- type: pdf
  url: https://arxiv.org/pdf/2112.02102v2
- type: code
  url: https://github.com/vitalab/castor
---
