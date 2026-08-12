---
title: Cardiac MRI Segmentation with Strong Anatomical Guarantees

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Youssef Skandarani
- Thierry Judge
- Olivier Bernard
- Alain Lalande
- Pierre-Marc Jodoin

date: '2019-10-10'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: in proc. *Medical Image Computing and Computer Assisted Intervention (MICCAI)*
publication_short: in proc. *MICCAI*

abstract: Recent publications have shown that the segmentation accuracy of modern-day
  convolutional neural networks (CNN) applied on cardiac MRI can reach the inter-expert
  variability, a great achievement in this area of research. However, despite these
  successes, CNNs still produce anatomically inaccurate segmentations as they provide
  no guarantee on the anatomical plausibility of their outcome, even when using a
  shape prior. In this paper, we propose a cardiac MRI segmentation method which always
  produces anatomically plausible results. At the core of the method is an adversarial
  variational autoencoder (aVAE) whose latent space encodes a smooth manifold on which
  lies a large spectrum of valid cardiac shapes. This aVAE is used to automatically
  warp anatomically inaccurate cardiac shapes towards a close but correct shape. Our
  method can accommodate any cardiac segmentation method and convert its anatomically
  implausible results to plausible ones without affecting its overall geometric and
  clinical metrics. With our method, CNNs can now produce results that are both within
  the inter-expert variability and always anatomically plausible.

# Summary. An optional shortened abstract.
summary: In this paper, we propose a cardiac MRI segmentation method which always produces anatomically plausible results.

tags:
- Cardiac MRI segmentation
- CNN
- Variational autoencoder

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1007/978-3-030-32245-8_70
links:
- type: pdf
  url: https://arxiv.org/pdf/1907.02865v2
---
