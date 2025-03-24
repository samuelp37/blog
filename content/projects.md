---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: Personal projects
      text: These are my current personal projects.
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: true
      columns: 3
  - block: collection
    content:
      title: Inactive projects
      text: These are my past personal projects, currently not active anymore.
      filters:
        folders:
          - inactive-project
    design:
      view: article-grid
      fill_image: true
      columns: 3
---
