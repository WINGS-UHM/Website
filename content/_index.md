---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  # - block: resume-biography-3
  #   content:
  #     # Choose a user profile to display (a folder name within `content/authors/`)
  #     username: admin
  #     text: ''
  #     # Show a call-to-action button under your biography? (optional)
  #     button:
  #       text: Download CV
  #       url: uploads/resume.pdf
  #     headings:
  #       about: ''
  #       education: ''
  #       interests: ''
  #   design:
  #     # Apply a gradient background
  #     css_class: hbx-bg-gradient
  #     # Avatar customization
  #     avatar:
  #       size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
  #       shape: circle # Options: circle (default), square, rounded
  - block: hero
    content:
      title: WINGS Lab
      text: Wireless Intelligent Networks for FutureG with Security
      primary_action:
        text: Github
        url: https://github.com/WINGS-UHM
        # icon: rocket-launch
        icon: brands/github
      secondary_action:
        text: Read the docs
        url: https://docs.hugoblox.com
      # announcement:
      #   text: "Announcing the release of version 1."
      #   link:
      #     text: "Read more"
      #     url: "/blog/"
    design:
      # spacing:
      #   padding: [0, 0, 0, 0]
      #   margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: ""
      background:
        color: ""
        image:
          # Add your image background to `assets/media/`.
          filename: ""
          filters:
            brightness: 0.5
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
        # margin: [0, 0, 0, 0]

  - block: markdown
    content:
      title: '📚 Research Interests
      subtitle: ''
      text: |-
          - Wireless Communication & FutureG
          - Integrated Sensing and Communcation (ISAC)
          - AI-Native RAN / O-RAN
          - Privacy & Security for FutureG, AI for Security
          - Intelligent IoT and Cyber Physical Systems
    design:
      columns: 2
      spacing:
        padding: [0, 0, 0, 0]
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publications
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      # Choose a layout view
      view: article-grid
      fill_image: false
      columns: 2
      show_date: false
      show_read_time: false
      show_read_more: false
            # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: article-grid
      fill_image: false
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: false
            # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: cta-card
    demo: false # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Connect With Us?
      text: |-
        Please contact with us if you have any iterested cooperation!
      button:
        text: Connect
        url: xxue@hawaii.edu
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
