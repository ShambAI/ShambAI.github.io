---
title: 'Extraction of Volumetric Indices from Echocardiography: Which Deep Learning Solution for Clinical Use?'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Hang Jung Ling
- admin
- Pierre-Yves Courand
- Pierre-Marc Jodoin
- Damien Garcia
- Olivier Bernard

date: '2023-06-16'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: in proc. *Functional Imaging and Modeling of the Heart*
publication_short: in proc. *FIMH*

abstract: Deep learning-based methods have spearheaded the automatic analysis of echocardiographic
  images, taking advantage of the publication of multiple open access datasets annotated
  by experts (CAMUS being one of the largest public databases). However, these models
  are still considered unreliable by clinicians due to unresolved issues concerning
  i) the temporal consistency of their predictions, and ii) their ability to generalize
  across datasets. In this context, we propose a comprehensive comparison between
  the current best performing methods in medical/echocardiographic image segmentation,
  with a particular focus on temporal consistency and cross-dataset aspects. We introduce
  a new private dataset, named CARDINAL, of apical two-chamber and apical four-chamber
  sequences, with reference segmentation over the full cardiac cycle. We show that
  the proposed 3D nnU-Net outperforms alternative 2D and recurrent segmentation methods.
  We also report that the best models trained on CARDINAL, when tested on CAMUS without
  any fine-tuning, still manage to perform competitively with respect to prior methods.
  Overall, the experimental results suggest that with sufficient training data, 3D
  nnU-Net could become the first automated tool to finally meet the standards of an
  everyday clinical device.

# Summary. An optional shortened abstract.
summary: We propose a comprehensive comparison between the current best performing methods in medical/echocardiographic image segmentation, with a particular focus on temporal consistency and cross-dataset aspects.

tags:
- CNN
- Deep learning
- Ultrasound
- Cardiac segmentation
- Temporal segmentation

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1007/978-3-031-35302-4_25
links:
- type: pdf
  url: https://arxiv.org/pdf/2305.01997v2
- type: code
  url: https://github.com/creatis-myriad/ASCENT
---
