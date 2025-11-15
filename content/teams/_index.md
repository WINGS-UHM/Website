---
title: Team
summary: All main contributors to this group
type: landing

sections:
  - block: collection
    id: team-pi
    content:
      title: Principal Investigator
      filters:
        # 只从 content/teams/ 下面取内容
        folders:
          - teams
        # 只要 tag 为 PI 的页面
        tag: "PI"
        exclude_future: false
        exclude_past: false
      # 0 = 不限制数量
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
