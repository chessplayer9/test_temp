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
        <div class="team-container" style="
          display: grid;
          grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
          gap: 30px;
          margin-top: 40px;
      
          <!-- Member 1 -->
          <div class="team-member" style="text-align: center">
            <img src="cutegirl.jpg" alt="Xiang Xiang" style="
              width: 150px;
              height: 150px;
              object-fit: cover;
              border-radius: 50%;
              border: 3px solid #1976d2;
              margin-bottom: 15px;
            ">
            <h3 style="margin: 10px 0 5px 0">Xiang Xiang</h3>
            <p style="color: #666; margin: 0">Huazhong University of Science and Technology</p>
          </div>

          <!-- Member 2 -->
          <div class="team-member" style="text-align: center">
            <img src="zhuoxu.jpg" alt="Zhuo Xu" style="
              width: 150px;
              height: 150px;
              object-fit: cover;
              border-radius: 50%;
              border: 3px solid #1976d2;
              margin-bottom: 15px;
            ">
            <h3 style="margin: 10px 0 5px 0">Zhuo Xu</h3>
            <p style="color: #666; margin: 0">Huazhong University of Science and Technology</p>
          </div>
        </div>
      
        #  - **Xiang Xiang**, Huazhong University of Science and  Technology, China
        #  - <strong>Zhuo Xu</strong>, Huazhong University of Science and   Technology, China
        #  - <strong>Yao Deng</strong>, Huazhong University of Science and Technology, China
        #  - <strong>Qinhao Zhou</strong>, Huazhong University of Science and Technology, China
        #  - <strong>Yifan Liang</strong>, Huazhong University of Science and Technology, China
        {{< /test >}}
---
