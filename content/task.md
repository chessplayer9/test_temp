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
    content:
      title: |
        <style> .no-wrap-center {white-space: nowrap; text-align: center;}</style><div class="no-wrap-center">OpenEarthSensing: Large-Scale Fine-Grained Open-World Remote Sensing Benchmark</div>

        <style>.center {text-align: center;}.link {font-size: 20px;text-decoration: none;}.link:hover {color: red; /* 改变链接颜色 */font-weight: bold; /* 改变链接文本的粗细 */cursor: pointer; /* 鼠标悬停时显示手型指示链接可点击 */}.separator {font-size: 20px;color: black;}</style><div class="center"><a href="https://arxiv.org/abs/2502.20668" class="link">[paper]</a> <span class="separator">|</span> <a href="https://www.kaggle.com/datasets/xiangexiang/openearthsensing-oes" class="link">[dataset]</a></div>

        <style>.text {font-size: 18px;line-height: 1.6;}strong {font-weight: bold;color: red;}</style><div class="text">Home page of the large-scale fine-grained open-world remote-sensing datasets and benchmark <strong>OpenEarthSensing (OES)</strong> for various open-world remote-sensing downstream tasks, mainly including evaluating the ability of models to detect semantic shifts, adapt to covariate shifts, and continuously update the parameters without forgetting learned knowledge. OES includes 189 scene and object categories, covering the vast majority of potential semantic shifts that may occur in the real world. To provide a more comprehensive testbed for evaluating the generalization performance, OES encompasses five data domains with significant covariate shifts, including two RGB satellite domains, one RGB aerial domain, one multi-spectral RGB domain, and one infrared domain.  </div>
      text: |-
      design:
        spacing:
          padding: ["0px", "0px", "0px", "0px"]  # 垂直30px/水平0.
---
