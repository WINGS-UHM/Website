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
        folders:
          - teams       # 只看 content/teams 下的页面
        tag: "PI"       # 只要 tag=PI 的
        exclude_future: false
        exclude_past: false
      count: 0
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
        folders:
          - teams
        tag: "phd"      # 只要 tag=phd 的
        exclude_future: false
        exclude_past: false
      count: 0
    design:
      view: article-grid
      show_read_time: false
      show_date: false
      show_read_more: false
      columns: 3
---
