---
title: Teaching
summary: My teaching experience
type: landing

cascade:
  - target:
      path: '{/teaching/*/**}'
    type: docs
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: schools
    content:
      title: Specialized Schools
      filters:
        tag: Schools
        kinds:
          - section
    design:
      view: article-grid
      show_read_time: false
      show_date: false
      show_read_more: false
      columns: 1

  - block: collection
    id: ta
    content:
      title: Teaching Assistant Positions
      filters:
        tag: TA
      count: 0
    design:
      view: citation
      show_read_time: false
      show_date: false
      show_read_more: false
---
