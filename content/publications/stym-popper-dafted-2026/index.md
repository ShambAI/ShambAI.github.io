---
title: "DAFTED: Decoupled Asymmetric Fusion of Tabular and Echocardiographic Data for Cardiac Hypertension Diagnosis"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Jérémie Stym-Popper
- admin
- Pierre-Yves Courand
- Clément Rambour
- Nicolas Thome
- Olivier Bernard

date: '2026-05-18'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: in proc. *Medical Imaging with Deep Learning (MIDL) 2025*
publication_short: in proc. *MIDL 2025*

abstract: Multimodal data fusion has emerged as a key approach in recent years for enhancing
  diagnosis and prognosis in many medical applications. With the advent of transformer-based
  methods, it is now possible to combine information from different modalities that provide
  complementary insights. However, most existing methods rely on symmetric fusion schemes, assuming
  equal importance for information carried by each modality—a strong assumption that may not always
  hold true. In this study, we propose an alternative fusion strategy based on an asymmetric scheme.
  Starting with a primary modality that offers the most critical information, we integrate secondary
  modality contributions by disentangling shared and modality-specific information. The proposed
  model was validated on a dataset of 239 patients for characterizing hypertension severity by
  fusing time series automatically extracted from echocardiographic image sequences and tabular
  data from patient records. Results show that our approach outperforms existing unimodal and
  multimodal approaches, achieving an AUC score over 90% - a crucial benchmark for clinical use.

# Summary. An optional shortened abstract.
summary: In this study, we propose a fusion strategy based on an asymmetric scheme.

tags:
- Multimodal fusion
- Transformers
- Tabular data
- Echocardiography
- Hypertension

# Standard identifiers for auto-linking
links:
- type: pdf
  url: https://raw.githubusercontent.com/mlresearch/v301/main/assets/stym-popper26a/stym-popper26a.pdf
- name: PMLR
  url: https://proceedings.mlr.press/v301/stym-popper26a.html
- name: OpenReview
  url: https://openreview.net/forum?id=ghhGImwv07
---
