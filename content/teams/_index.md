---
title: Team
summary: All main contribution to this group
type: landing

cascade:
  - target:
      path: '{/teams/*/**}'
    type: docs
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: teams
    content:
      title: Priciple
      filters:
        tag: PI
        kinds:
          - section
    design:
      view: article-grid
      show_read_time: false
      show_date: false
      show_read_more: false
      columns: 3
  - block: collection
    id: teams
    content:
      title: PhD
      filters:
        tag: phd
        kinds:
          - section
    design:
      view: article-grid
      show_read_time: false
      show_date: false
      show_read_more: false
      columns: 3
---
