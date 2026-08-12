---
title: On the effectiveness of GAN generated cardiac MRIs for segmentation

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Youssef Skandarani
- admin
- Pierre-Marc Jodoin
- Alain Lalande

date: '2020-04-18'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: presented at *Medical Imaging with Deep Learning (MIDL)*
publication_short: presented at *MIDL*

abstract: In this work, we propose a Variational Autoencoder (VAE) - Generative Adversarial
  Networks (GAN) model that can produce highly realistic MRI together with its pixel accurate
  groundtruth for the application of cine-MR image cardiac segmentation.  On one side of our model
  is a Variational Autoencoder (VAE) trained to learn the latent representations of cardiac shapes.
  On the other side is a GAN that uses  ”SPatially-Adaptive (DE)Normalization” (SPADE) modules to
  generate realistic MR images tailored to a given anatomical map.  At test time, the sampling of
  the VAE latent space allows to generate an arbitrary large number of cardiac shapes, which are
  fed to the GAN that subsequently generates MR images whose cardiac structure fits that of the
  cardiac shapes.  In other words, our system can generate a large volume of realistic yet labeled
  cardiac MR images.  We show that segmentation with CNNs trained with our synthetic annotated
  images gets competitive results compared to traditional techniques.
  We also show that combining data augmentation with our GAN-generated images lead to an
  improvement in the Dice score of up to 12 percent while allowing for better generalization
  capabilities on  other datasets.

# Summary. An optional shortened abstract.
summary: In this work, we propose a Variational Autoencoder (VAE) - Generative Adversarial Networks (GAN) model that can produce highly realistic MRI together with its pixel accurate groundtruth for the application of cine-MR image cardiac segmentation.

tags:
- GAN
- CNN
- Deep learning
- Cine-MRI
- Heart

# Standard identifiers for auto-linking
links:
- type: pdf
  url: https://openreview.net/pdf?id=f9Pl3Qj3_Q
- name: OpenReview
  url: https://openreview.net/forum?id=f9Pl3Qj3_Q
---
