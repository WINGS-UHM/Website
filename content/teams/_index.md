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
        # 只从 teams 这个 section 里取内容
        folders:
          - teams
        # 只要 tag 为 "PI" 的页面
        tag: "PI"
        exclude_future: false
        exclude_past: false
      count: 0   # 0 表示不限制数量
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
        tag: "phd"
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
