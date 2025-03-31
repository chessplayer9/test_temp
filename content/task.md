---
title: 'Task'
date: 2023-10-24
type: landing

design:
  spacing: '3rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      # username: admin
      text: ""
    design:
      spacing:
        padding: ["265px", "0px", "270px", "0px"]  # 垂直30px/水平0
      css_class: dark
      background:
        color: white
        image:
          # Add your image background to `assets/media/`.
          filename: ICCV.png
          filters:
            brightness: 1.0
          size: actual
          position: center
          parallax: false  

  - block: markdown
    id: overview
    content:
      title: |
      text: |-

      design:
        spacing:
          padding: ["0px", "0px", "0px", "0px"]  # 垂直30px/水平0.
---
