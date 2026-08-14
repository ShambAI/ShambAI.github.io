---
title: 'Resume'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  # - block: resume-skills
  #   content:
  #     title: Skills & Hobbies
  #     username: admin
  #   design:
  #     show_skill_percentage: false
  - block: resume-awards
    content:
      title: Awards
      username: admin
  - block: markdown
    content:
      title: 'Reviews'
      subtitle: ''
      text: |-
        I have reviewed for top-tier conferences in artificial intelligence and machine learning, such as:
        * [Conference on Neural Information Processing Systems (NeurIPS)](https://neurips.cc/)
        * [European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (ECML PKDD)](https://ecmlpkdd.org/)

  - block: resume-languages
    content:
      title: Languages
      username: admin
---
