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
      text: |
        {{< test >}}
            Home page of the large-scale fine-grained open-world remote-sensing datasets and benchmark OpenEarthSensing (OES) for various open-world remote-sensing downstream tasks, mainly including evaluating the ability of models to detect semantic shifts, adapt to covariate shifts, and continuously update the parameters without forgetting learned knowledge. OES includes 189 scene and object categories, covering the vast majority of potential semantic shifts that may occur in the real world. To provide a more comprehensive testbed for evaluating the generalization performance, OES encompasses five data domains with significant covariate shifts, including two RGB satellite domains, one RGB aerial domain, one multi-spectral RGB domain, and one infrared domain.
        {{< /test >}}

      design:
        spacing:
          padding: ["0px", "0px", "0px", "0px"]  # 垂直30px/水平0.
        design:
            width: full

  
      

#   - block: markdown
#     content:
#       title: |
#         <style> .no-wrap-center {white-space: nowrap; text-align: center;}</style><div class="no-wrap-center">Semantic Shift OOD Detection & OSR</div>

#         <style>.text {font-size: 18px;line-height: 1.6;font-weight: normal;}strong {font-weight: bold;color: red;}</style><div class="text">Home page of the large-scale fine-grained open-world remote-sensing datasets and benchmark <strong>OpenEarthSensing (OES)</strong> for various open-world remote-sensing downstream tasks, mainly including evaluating the ability of models to detect semantic shifts, adapt to covariate shifts, and continuously update the parameters without forgetting learned knowledge. OES includes 189 scene and object categories, covering the vast majority of potential semantic shifts that may occur in the real world. To provide a more comprehensive testbed for evaluating the generalization performance, OES encompasses five data domains with significant covariate shifts, including two RGB satellite domains, one RGB aerial domain, one multi-spectral RGB domain, and one infrared domain.  </div>

#         <style> .no-wrap-center {white-space: nowrap; text-align: center;}</style><div class="no-wrap-center">Covariate Shift OOD Detection & Generalization</div>

#         <style>.text {font-size: 18px;line-height: 1.6;font-weight: normal;}strong {font-weight: bold;color: red;}</style><div class="text">Home page of the large-scale fine-grained open-world remote-sensing datasets and benchmark <strong>OpenEarthSensing (OES)</strong> for various open-world remote-sensing downstream tasks, mainly including evaluating the ability of models to detect semantic shifts, adapt to covariate shifts, and continuously update the parameters without forgetting learned knowledge. OES includes 189 scene and object categories, covering the vast majority of potential semantic shifts that may occur in the real world. To provide a more comprehensive testbed for evaluating the generalization performance, OES encompasses five data domains with significant covariate shifts, including two RGB satellite domains, one RGB aerial domain, one multi-spectral RGB domain, and one infrared domain.  </div>

#         <style> .no-wrap-center {white-space: nowrap; text-align: center;}</style><div class="no-wrap-center">Class Incremental Learning</div>

#         <style>.text {font-size: 18px;line-height: 1.6;font-weight: normal;}strong {font-weight: bold;color: red;}</style><div class="text">Home page of the large-scale fine-grained open-world remote-sensing datasets and benchmark <strong>OpenEarthSensing (OES)</strong> for various open-world remote-sensing downstream tasks, mainly including evaluating the ability of models to detect semantic shifts, adapt to covariate shifts, and continuously update the parameters without forgetting learned knowledge. OES includes 189 scene and object categories, covering the vast majority of potential semantic shifts that may occur in the real world. To provide a more comprehensive testbed for evaluating the generalization performance, OES encompasses five data domains with significant covariate shifts, including two RGB satellite domains, one RGB aerial domain, one multi-spectral RGB domain, and one infrared domain.  </div>

#         <style> .no-wrap-center {white-space: nowrap; text-align: center;}</style><div class="no-wrap-center">Domain-Incremental Learning</div>

#         <style>.text {font-size: 18px;line-height: 1.6;font-weight: normal;}strong {font-weight: bold;color: red;}</style><div class="text">Home page of the large-scale fine-grained open-world remote-sensing datasets and benchmark <strong>OpenEarthSensing (OES)</strong> for various open-world remote-sensing downstream tasks, mainly including evaluating the ability of models to detect semantic shifts, adapt to covariate shifts, and continuously update the parameters without forgetting learned knowledge. OES includes 189 scene and object categories, covering the vast majority of potential semantic shifts that may occur in the real world. To provide a more comprehensive testbed for evaluating the generalization performance, OES encompasses five data domains with significant covariate shifts, including two RGB satellite domains, one RGB aerial domain, one multi-spectral RGB domain, and one infrared domain.  </div>

#         <style> .no-wrap-center {white-space: nowrap; text-align: center;}</style><div class="no-wrap-center">Coarse-to-Fine Few-shot Class-Incremental Learning</div>

#         <style>.text {font-size: 18px;line-height: 1.6;font-weight: normal;}strong {font-weight: bold;color: red;}</style><div class="text">Home page of the large-scale fine-grained open-world remote-sensing datasets and benchmark <strong>OpenEarthSensing (OES)</strong> for various open-world remote-sensing downstream tasks, mainly including evaluating the ability of models to detect semantic shifts, adapt to covariate shifts, and continuously update the parameters without forgetting learned knowledge. OES includes 189 scene and object categories, covering the vast majority of potential semantic shifts that may occur in the real world. To provide a more comprehensive testbed for evaluating the generalization performance, OES encompasses five data domains with significant covariate shifts, including two RGB satellite domains, one RGB aerial domain, one multi-spectral RGB domain, and one infrared domain.  </div>
#       text: |-
#       design:
#         spacing:
#           padding: ["0px", "0px", "0px", "0px"]  # 垂直30px/水平0.

#   - block: markdown
#     content:
#       text: |
#         <!DOCTYPE html><html lang="en"><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><title>调整文字与网页左侧的间距</title><style>body {font-family: Arial, sans-serif;line-height: 1.6;margin: 0;padding-left: 20px; /* 设置左侧间距为20px */}.content {max-width: 800px;margin: 0 auto;padding: 20px;background-color: #f9f9f9;}</style></head><body><div class="content"><h1>这是标题</h1><p>这是一段文字，通过设置CSS中的padding属性，您可以调整文字与网页左侧的间距。</p></div></body></html>
#       design:
#         spacing:
#           padding: ["0px", "0px", "0px", "0px"]  # 垂直30px/水平0.

---
