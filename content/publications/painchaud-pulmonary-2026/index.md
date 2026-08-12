---
title: "Pulmonary Embolism Risk Stratification from CTPA and Medical Records: Vascular Graphs Are Not All You Need"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Tristan Habémont
- Morgane des Ligneris
- Allan Serva
- Pierre Croisille
- Laurent Bertoletti
- Thomas Lampert
- Johannes F. Lutzeyer
- Odyssée Merveille

date: '2026-06-12'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: accepted for *Medical Image Computing and Computer Assisted Intervention (MICCAI)*
publication_short: accepted for *MICCAI*

abstract: Risk stratification for pulmonary embolism (PE) is critical for
  clinical decision-making. Stratification guidelines are based on patient
  medical records, parameters measured from computed tomography pulmonary
  angiography (CTPA), and blood tests. However, blood tests are often missing
  in routine practice. This work studies whether state-of-the-art models can
  accurately classify risk stratification from only medical records and
  biomarkers extracted from CTPA images. We benchmark different approaches to
  combine medical records and cardiac biomarkers with rich pulmonary vascular
  information; we add vascular biomarkers to tabular models and apply graph
  neural networks (GNNs) on the vascular tree's intrinsic graph representation.
  We use a private dataset (n=353) with uniquely complete data for PE risk
  stratification. Our results show that, among global features, medical records
  and cardiac biomarkers are the most significant predictors, while vascular
  biomarkers do not further improve stratification. Even more surprising, even
  GNNs on vascular graphs fail to outperform strong tabular baseline on global
  features. We consider hypotheses, on both models and data, that could explain
  this suboptimal performance. Our investigation suggests that, counter-intuitively,
  vascular graphs may not help predict PE guidelines risk better than simpler
  clinical biomarkers. Code is available from https://github.com/creatis-myriad/GENESIS.

# Summary. An optional shortened abstract.
summary: We benchmark different approaches to combine medical records and cardiac biomarkers with rich pulmonary vascular information.

tags:
- Multimodal fusion # 1st tag is displayed for featured publication, so override alphabetical order to display the most relevant tag
- Foundation model
- Graph classification
- Graph neural networks
- Tabular data

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
# hugoblox:
#   ids:
#     doi: 
links:
- type: pdf
  url: uploads/painchaud_pulmonary_2026.pdf
- name: arXiv
  url: https://arxiv.org/abs/2606.25956
- type: code
  url: https://github.com/creatis-myriad/genesis
---
