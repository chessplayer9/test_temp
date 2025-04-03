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
        padding: ["0px", "0px","600px","0px"]  # 垂直30px/水平0
      css_class: dark
      background:
        color: white
        image:
          # Add your image background to `assets/media/`.
          filename: people.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false


  - block: markdown
    content:
      #title: '<span style="font-size: 24px;">Team Member</span>'
      text: |
        {{< test margin="625px" bg="#ffffff" >}}
        {{< center >}}
        # Team Member
        {{< /center >}}
        {{< center >}}
        ## Team Representatives
        {{< /center >}}

         - **Xiang Xiang**, Huazhong University of Science and  Technology, China

        {{< center >}}
        ## Core Members
        {{< /center >}}

        ### Dataset

           - <strong>Zhuo Xu</strong>, Huazhong University of Science and   Technology, China
           - <strong>Yao Deng</strong>, Huazhong University of Science and Technology, China
           - <strong>Qinhao Zhou</strong>, Huazhong University of Science and Technology, China
           - <strong>Yifan Liang</strong>, Huazhong University of Science and Technology, China
  
        ### Framework

           - <strong>Zhuo Xu</strong>, Huazhong University of Science and Technology, China
           - <strong>Yao Deng</strong>, Huazhong University of Science and Technology, China
           - <strong>Qinhao Zhou</strong>, Huazhong University of Science and Technology, China
           - <strong>Yifan Liang</strong>, Huazhong University of Science and Technology, China
        {{< /test >}}
---
