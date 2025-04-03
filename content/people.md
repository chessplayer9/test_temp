---
title: 'People'
date: 2025-04-03
type: landing

design:
  # Section spacing
  spacing: '0rem'

# Page sections
sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      # username: admin
      text: ""
    design:
      spacing:
        padding: ["920px", "0px", "920px", "0px"]  # 垂直30px/水平0
      css_class: dark
      background:
        color: white
        image:
          # Add your image background to `assets/media/`.
          filename: 24gf-ellipsiws.png
          filters:
            brightness: 1.0
          size: actual
          position: center
          parallax: false


  - block: markdown
    content:
      title: '<span style="font-size: 24px;">Team Member</span>'
      text: |
        {{< test margin="625px" bg="#ffffff" >}}
        {{< center >}}
        ## Team Representatives
        - **xx**
        {{< /center >}}
        {{< center >}}
        ## Core Members
        {{< /center >}}
        ### Dataset
        ### Framework
        {{< /test >}}
---
