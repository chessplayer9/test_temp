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
        padding: ["165px", "0px","170px","0px"]  # 垂直30px/水平0
      css_class: dark
      background:
        color: white
        image:
          # Add your image background to `assets/media/`.
          filename: people.jpg
          filters:
            brightness: 1.0
          size: 1100px 500px
          position: center
          parallax: false


  - block: markdown
    content:
      #title: '<span style="font-size: 24px;">Team Member</span>'
      text: |
        {{< test margin="625px" bg="#ffffff" >}}
        {{< center >}}
        ## Team Member
        {{< /center >}}
  
        <!-- 在Markdown文件中直接使用HTML -->
        <div class="two-columns" style="
           display: grid;
           grid-template-columns: 1fr 1fr;
           gap: 2rem;
        ">
          <!-- 左列 -->
          <div>
            {{< team_member name="张三" img="flower.jpg" >}}
          </div>
  
          <!-- 右列 -->
          <div>
            {{< team_member name="李四" img="member2.jpg" >}}
          </div>
        </div>
        {{< /test >}}
---
