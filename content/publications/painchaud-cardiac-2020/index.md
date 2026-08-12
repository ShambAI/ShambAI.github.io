---
title: Cardiac Segmentation With Strong Anatomical Guarantees

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

date: '2020-06-17'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Medical Imaging*'
publication_short: '*IEEE TMI*'

abstract: Convolutional neural networks (CNN) have had unprecedented success in medical
  imaging and, in particular, in medical image segmentation. However, despite the
  fact that segmentation results are closer than ever to the inter-expert variability,
  CNNs are not immune to producing anatomically inaccurate segmentations, even when
  built upon a shape prior. In this paper, we present a framework for producing cardiac
  image segmentation maps that are guaranteed to respect pre-defined anatomical criteria,
  while remaining within the inter-expert variability. The idea behind our method
  is to use a well-trained CNN, have it process cardiac images, identify the anatomically
  implausible results and warp these results toward the closest anatomically valid
  cardiac shape. This warping procedure is carried out with a constrained variational
  autoencoder (cVAE) trained to learn a representation of valid cardiac shapes through
  a smooth, yet constrained, latent space. With this cVAE, we can project any implausible
  shape into the cardiac latent space and steer it toward the closest correct shape.
  We tested our framework on short-axis MRI as well as apical two and four-chamber
  view ultrasound images, two modalities for which cardiac shapes are drastically
  different. With our method, CNNs can now produce results that are both within the
  inter-expert variability and always anatomically plausible without having to rely
  on a shape prior.

# Summary. An optional shortened abstract.
summary: In this paper, we present a framework for producing cardiac image segmentation maps that are guaranteed to respect pre-defined anatomical criteria, while remaining within the inter-expert variability.

tags:
- Cardiac segmentation  # 1st tag is displayed for featured publication, so override order from journal to display the most relevant tag
- Neural networks
- CNN
- Variational autoencoder
- Image segmentation
- MRI
- Magnetic resonance imaging
- Ultrasound
- Ultrasonic imaging
- Shape
- Three-dimensional displays

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1109/TMI.2020.3003240
links:
- type: pdf
  url: https://arxiv.org/pdf/2006.08825v1

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  preview_only: true
---
