---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      # button:
      #  text: Download CV
      #  url: /             # uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 研究方向'
      subtitle: ''
      text: |-
        - 本课题组研究包括深度学习、联邦学习、机器学习、模型压缩、隐私保护、知识蒸馏、边缘智能、机器视觉、智能审计等领域，解决图像处理、大模型中模型的效率、安全、存储等问题，在智慧交通，智慧医疗等场景中应用。同时鼓励学生结合自身兴趣及特长，进行新方向探索。

        - 欢迎对科研训练感兴趣的研究生及本科生与我联系，探索可以落地应用的科学研究。<u>已指导学生情况请点击：</u> [**学生成果**]({{< relref "../students/index.md" >}})
    design:
      columns: '1'
  - block: collection
    id: news
    content:
      title: 最新动态
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: news
      # Choose how many pages you would like to display (0 = all pages)
      count: 2
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
#  - block: collection
#    id: students
#    content:
#      title: 指导学生情况
#      filters:
#        folders:
#          - students
#    design:
#      view: article-grid
#      columns: 1
  - block: markdown
    id: contact 
    content:
      title: '联系方式'
      subtitle: ''
      text: |-
        如果您对我们的工作内容感兴趣或想加入我们，欢迎随时与我取得联系！ 具体信息如下：
        - **邮箱：** ffshen AT nau DOT edu DOT cn （将AT替换为“@”，将DOT替换为点“.”）
        - **微信号：** WaldenLakewood
        - **地址：** 江苏省南京市浦口区南京审计大学致明楼222办公室
        - **工作时间：** 周一至周五 09:00 至 17:00
    design:
      columns: '1'
---
