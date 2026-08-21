---
title: ''
type: landing

sections:

  - block: collection
    id: conference
    content:
      title: Conference Presentations
      filters:
        folders:
          - talks
        tags:
          - conference
      count: 20
    design:
      view: article-grid
      columns: 2

  - block: collection
    id: invited-talks
    content:
      title: Invited Talks
      filters:
        folders:
          - talks
        tags:
          - invited-talk
      count: 20
    design:
      view: article-grid
      columns: 2
  - block: collection
    id: symposium
    content:
      title: Symposiums
      filters:
        folders:
          - talks
        tags:
          - symposium
      count: 20
    design:
      view: article-grid
      columns: 2

  - block: collection
    id: summer-school
    content:
      title: Summer Schools
      filters:
        folders:
          - talks
        tags:
          - summer-school
      count: 20
    design:
      view: article-grid
      columns: 2
---