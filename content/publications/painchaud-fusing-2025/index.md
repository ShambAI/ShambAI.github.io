---
title: Fusing Echocardiography Images and Medical Records for Continuous Patient Stratification

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Jérémie Stym-Popper
- Pierre-Yves Courand
- Nicolas Thome
- Pierre-Marc Jodoin
- Nicolas Duchateau
- Olivier Bernard

date: '2025-08-20'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Ultrasonics, Ferroelectrics, and Frequency Control*'
publication_short: '*IEEE TUFFC*'

abstract: 'Deep learning enables automatic and robust extraction of cardiac function
  descriptors from echocardiographic sequences, such as ejection fraction (EF) or
  strain. These descriptors provide fine-grained information that physicians consider,
  in conjunction with more global variables from the clinical record, to assess patients’
  condition. Drawing on novel Transformer models applied to tabular data, we propose
  a method that considers all descriptors extracted from medical records and echocardiograms
  to learn the representation of a cardiovascular pathology with a difficult-to-characterize
  continuum, namely hypertension. Our method first projects each variable into its
  own representation space using modality-specific approaches. These standardized
  representations of multimodal data are then fed to a Transformer encoder, which
  learns to merge them into a comprehensive representation of the patient through
  the task of predicting a clinical rating. This stratification task is formulated
  as an ordinal classification to enforce a pathological continuum in the representation
  space. We observe the major trends along this continuum on a cohort of 239 hypertensive
  patients, providing unprecedented details in the description of hypertension’s impact
  on various cardiac function descriptors. Our analysis shows that: 1) the XTab foundation
  model’s architecture allows to reach high performance (96.8% AUROC) even with limited
  data (less than 200 training samples); 2) stratification across the population is
  reproducible between trainings [within 5.7% of mean absolute error (MAE)]; and 3)
  patterns emerge in descriptors, some of which align with established physiological
  knowledge about hypertension, while others could pave the way for a more comprehensive
  understanding of this pathology. The code is available at https://github.com/creatis-myriad/didactic'

# Summary. An optional shortened abstract.
summary: Drawing on novel Transformer models applied to tabular data, we propose a method that considers all descriptors extracted from medical records and echocardiograms to learn the representation of a cardiovascular pathology with a difficult-to-characterize continuum.

tags:
- Multimodal  # 1st tag is displayed for featured publication, so override order from journal to display the most relevant tag
- Cardiac ultrasound
- Health records
- Pathology
- Medical services
- Hypertension
- Deep learning
- Representation learning
- Data models
- Transformers
- Adaptation models
- Feature extraction
- Stratification

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1109/TUFFC.2025.3600902
links:
- type: pdf
  url: https://arxiv.org/pdf/2401.07796v3
- type: code
  url: https://github.com/creatis-myriad/didactic
---
