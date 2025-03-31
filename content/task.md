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
        padding: ["310px", "0px", "310px", "0px"]  # 垂直30px/水平0
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
        <!DOCTYPE html><html lang="en"><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><title>Research Topics</title><style>body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }
        .topic-list {
            list-style-type: none;
            padding: 0;
        }
        .topic-item {
            background-color: #f8f9fa;
            margin: 10px 0;
            padding: 15px;
            border-left: 5px solid #3498db;
            font-size: 18px;
            font-weight: bold;
        }</style></head><body><h1>Research Topics</h1><ul class="topic-list">
        <li class="topic-item">Semantic Shift OOD Detection & OSR</li>
        <li class="topic-item">Covariate Shift OOD Detection & Generalization</li>
        <li class="topic-item">Class Incremental Learning</li>
        <li class="topic-item">Domain-Incremental Learning</li>
        <li class="topic-item">Coarse-to-Fine Few-shot Class-Incremental Learning</li></ul></body></html>
      design:
        spacing:
          padding: ["0px", "0px", "0px", "0px"]  # 垂直30px/水平0.
---
