---
title: Team
summary: All main contributors to this group
type: landing

cascade:
  - target:
      path: '{/teams/*/**}'
    type: docs
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: team-pi
    content:
      title: Principal Investigator
      filters:
        tags: ["PI"]
        kinds:
          - page
    design:
      view: article-grid
      show_read_time: false
      show_date: false
      show_read_more: false
      columns: 3

  - block: collection
    id: team-phd
    content:
      title: PhD Students
      filters:
        tags: ["phd"]
        kinds:
          - page
    design:
      view: article-grid
      show_read_time: false
      show_date: false
      show_read_more: false
      columns: 3
---
