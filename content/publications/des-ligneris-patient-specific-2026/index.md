---
title: A Patient-Specific Pulmonary Arterial Tree Digital Twin to Extract Pulmonary Embolism Biomarkers

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Morgane des Ligneris
- admin
- Allan Serva
- Laurent Bertoletti
- Pierre Croisille
- Carole Frindel
- Odyssée Merveille

date: '2026-04-20'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: under review
publication_short: under review

abstract: Pulmonary embolism, the obstruction of a pulmonary artery by a blood clot, is one of the
  leading causes of acute cardiovascular syndrome. In clinical practice, therapeutic decisions
  after diagnosis via computed tomography pulmonary angiography rely on risk stratification, which
  categorizes 30-day mortality risk into three categories. This stratification depends on the
  right-to-left ventricular diameter ratio and blood levels of two cardiac enzymes. However, blood
  biomarkers are not always available in emergency settings, and manual calculation of established
  severity scores – such as Qanadli and Mastora – is time-consuming and rarely performed in
  clinical routine practice. This study introduces an automated pipeline that models a directed
  graph representation of the pulmonary arterial tree, labeling its hierarchical structure and
  characterizing pulmonary embolism. The pipeline derives image-based biomarkers, including local
  artery-level features (morphological information, hierarchical position, clot volume, and
  resulting obstruction) and global patient-level biomarkers such as automatically calculated
  severity scores (Qanadli and Mastora) and the total embolic volume distribution by lobes and
  hierarchical levels. Using artificial-intelligence-generated binary masks of arteries, emboli,
  lungs, and lobes, it creates a patient digital twin of the arterial structure. Validation of the
  pipeline through comparison to an existing pipeline, anatomical expectations, and manual severity
  score calculations demonstrates the pipeline’s ability to automatically generate anatomically
  accurate digital twins and severity scores with strong agreement. This supports the potential of
  these image-derived biomarkers to automatically provide rapid, precise information on thrombotic
  burden and spatial clot distribution.

# Summary. An optional shortened abstract.
summary: This study introduces an automated pipeline that models a directed graph representation of the pulmonary arterial tree, labeling its hierarchical structure and characterizing pulmonary embolism.

tags:
- Biomarkers
- Graph
- Pipeline
- Pulmonary embolism
- Pulmonary vascular tree
- Segmentations

# Standard identifiers for auto-linking
links:
- type: pdf
  url: https://arxiv.org/pdf/2605.28217
- name: arXiv
  url: https://arxiv.org/abs/2605.28217
- type: code
  url: https://github.com/creatis-myriad/PulmonaryTreeGraph
---
