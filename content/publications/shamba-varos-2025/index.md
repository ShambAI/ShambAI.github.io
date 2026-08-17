---
title: Towards Generating Realistic Underwater Images

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

date: '2025-05-20'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: Preprint Arxiv*
publication_short: Preprint Arxiv

abstract: This paper explores the use of contrastive learning and generative adversarial networks for generating realistic underwater images from synthetic images with uniform lighting. We investigate the performance of image translation models for generating realistic underwater images using the VAROS dataset. Two key evaluation metrics, Fréchet Inception Distance (FID) and Structural Similarity Index Measure (SSIM), provide insights into the trade-offs between perceptual quality and structural preservation. For paired image translation, pix2pix achieves the best FID scores due to its paired supervision and PatchGAN discriminator, while the autoencoder model attains the highest SSIM, suggesting better structural fidelity despite producing blurrier outputs. Among unpaired methods, CycleGAN achieves a competitive FID score by leveraging cycle-consistency loss, whereas CUT, which replaces cycle-consistency with contrastive learning, attains higher SSIM, indicating improved spatial similarity retention. Notably, incorporating depth information into CUT results in the lowest overall FID score, demonstrating that depth cues enhance realism. However, the slight decrease in SSIM suggests that depth-aware learning may introduce structural variations.

# Summary. An optional shortened abstract.
summary: In this paper, explores the use of contrastive learning and generative adversarial networks for generating realistic underwater images from synthetic images.

tags:
- Underwater Images
- Image Translation
- GANs

# Standard identifiers for auto-linking
# hugoblox:
#   ids:
#     doi: 10.1007/978-3-030-32245-8_70
links:
- type: pdf
  url: https://arxiv.org/pdf/2505.14296
- name: arXiv
  url: https://arxiv.org/abs/2505.14296
---
