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
        <!-- markdownlint-disable -->
        {{< test margin="625px" bg="#ffffff" >}}
        {{< center >}}
        ## Team Member
        {{< /center >}}

        {{ $flower := resources.Get "media/flower.jpg" }}
        <div class="team-grid" style="
          display: grid;
          grid-template-columns: repeat(2, 1fr);
          gap: 20px;
          margin-top: 30px;
        ">
      
          <!-- Member 1 -->
          <div class="member-card" style="
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
          ">
           <h3 style="margin: 0 0 10px 0">Xiang Xiang</h3>
           <p style="margin: 0; color: #555">Hust 1</p>
          </div>

          <!-- Member 2 -->
          <div class="member-card" style="
            background: white !important;
            padding: 20px !important;
            border-radius: 8px !important;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1) !important;
            display: flex !important;          /* 启用Flex布局 */
            align-items: center !important;    /* 垂直居中 */
            gap: 20px !important;             /* 图片和文字间距 */
          ">
           <img src="{{ $flower.RelPermalink }}" alt="Zhuo Xu" style="
            width: 120px !important;
            height: 120px !important;
            object-fit: cover !important;
            border-radius: 50% !important;
            border: 3px solid #4a89dc !important;
            flex-shrink: 0 !important;       /* 防止图片被压缩 */
            
           ">
           <div style="flex: 1 !important; display: flex !important; flex-direction: column !important; gap: 8px !important;">   <!-- 文字容器 -->
            <h3 style="margin: 0; font-size: 1.1em; white-space: nowrap;">Zhuo Xu</h3>
            <p style="margin: 0; color: #555; font-size: 0.9em; white-space: nowrap;">Huazhong University of Science and Technology</p>
            <p style="margin: 0; color: #555; font-size: 0.9em; white-space: nowrap;">Email:</p>
           </div>
          </div>
        </div>
      
        #  - **Xiang Xiang**, Huazhong University of Science and  Technology, China
        #  - <strong>Zhuo Xu</strong>, Huazhong University of Science and   Technology, China
        #  - <strong>Yao Deng</strong>, Huazhong University of Science and Technology, China
        #  - <strong>Qinhao Zhou</strong>, Huazhong University of Science and Technology, China
        #  - <strong>Yifan Liang</strong>, Huazhong University of Science and Technology, China
        {{< /test >}}
---
