---
title: Fusing Echocardiography Images and Medical Records for Continuous Patient Stratification

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Pierre-Yves Courand
- Pierre-marc Jodoin
- Nicolas Duchateau
- Olivier Bernard

date: '2024-04-27'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: presented at *Medical Imaging with Deep Learning (MIDL)*
publication_short: presented at *MIDL*

abstract: Deep learning now enables automatic and robust extraction of cardiac function
  descriptors from echocardiographic sequences, such as ejection fraction or strain.
  These descriptors provide fine-grained information that physicians consider, in
  conjunction with global variables from the clinical record, to assess patients'
  condition. Drawing on novel transformer models applied to tabular data (e.g. variables
  from electronic health records), we propose a method that considers descriptors
  extracted from medical records and echocardiograms to learn a representation of
  hypertension, a difficult-to-characterize and highly prevalent cardiovascular pathology.
  Our method first embeds each descriptor separately using modality-specific approaches.
  These embeddings are fed as tokens to a transformer encoder, which combines them
  into a unified representation of the patient to predict a clinical rating. This
  task is formulated as an ordinal classification to enforce a pathological continuum
  in the representation space. We observe trends along this continuum for a cohort
  of 239 hypertensive patients to describe the gradual effects of hypertension on
  cardiac function descriptors. Our analysis shows that i) pretrained weights from
  a foundation model allow to reach good performance (83% accuracy) even with limited
  data ($textless$ 200 training samples), ii) trends across the population are reproducible
  between trainings, and iii) for descriptors known to interact with hypertension,
  patterns are consistent with prior physiological knowledge.

# Summary. An optional shortened abstract.
summary: Drawing on novel transformer models applied to tabular data (e.g. variables from electronic health records), we propose a method that considers descriptors extracted from medical records and echocardiograms to learn a representation of hypertension.

tags:
- Multimodal
- Contrastive learning
- Transformer
- Foundation model
- Cardiac ultrasound
- Health records
- Hypertension

# Standard identifiers for auto-linking
links:
- type: pdf
  url: https://openreview.net/pdf?id=atsESsgxPa
- name: OpenReview
  url: https://openreview.net/forum?id=atsESsgxPa
- type: code
  url: https://github.com/creatis-myriad/didactic
---
