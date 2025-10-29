---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '🧬 "My Research Goals'
      subtitle: ''
      text: |-
        I am an aspiring research scientist exploring the molecular intersections of basic biology and translational medicine, with a passion for turning discoveries into therapies. I am particularly interested in entering the pharmaceutical and biotech realms to continue bridging mechanistic studies with applied research. Beyond the bench, I am committed to making science accessible through mentorship, teaching, and communication, fostering curiosity, innovation, and inclusion in the scientific community.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: 'Some of My Work' # This could be called Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: ''
  #     filters:
  #       folders:
  #         - publications
  #       exclude_featured: false
  #   design:
  #     view: citation
#   - block: collection
#     id: talks
#     content:
#       title: Recent & Upcoming Talks
#       filters:
#         folders:
#           - events
#     design:
#       view: card
#   - block: collection
#     id: news
#     content:
#       title: Recent News
#       subtitle: ''
#       text: ''
#       # Page type to display. E.g. post, talk, publication...
#       page_type: blog
#       # Choose how many pages you would like to display (0 = all pages)
#       count: 5
#       # Filter on criteria
#       filters:
#         author: ''
#         category: ''
#         tag: ''
#         exclude_featured: false
#         exclude_future: false
#         exclude_past: false
#         publication_type: ''
#       # Choose how many pages you would like to offset by
#       offset: 0
#       # Page order: descending (desc) or ascending (asc) date.
#       order: desc
#     design:
#       # Choose a layout view
#       view: card
#       # Reduce spacing
#       spacing:
#         padding: [0, 0, 0, 0]
---
