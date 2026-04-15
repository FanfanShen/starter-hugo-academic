---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      #button:
      #  text: Download CV
      #  url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 研究方向'
      subtitle: ''
      text: |-
        - 本课题组以人工智能系统为核心研究方向，聚焦多模态数据处理中的性能优化、安全可信、隐私保护及知识缓存等关键问题，涉及联邦学习、深度学习、模型压缩、知识蒸馏、边缘智能、机器视觉等技术，构建安全高效、轻量化可部署的分布式智能系统，研究成果广泛应用于智能审计、智慧医疗、智慧金融等实际场景。

        - 课题组注重理论与实践结合，鼓励学生结合自身兴趣与特长开展个性化、创新性研究。欢迎对科研训练感兴趣的研究生及本科生与我联系，探索可以落地应用的科学研究。<u>已指导学生情况请点击：</u> <a href="students" style="font-weight: bold;">学生成果</a>
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
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      view: article-grid
      columns: 2
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
  - block: markdown
    content:
      title: '📚 学术服务'
      subtitle: ''
      text: |-
        - IEEE Transactions on Neural Networks and Learning Systems，审稿服务
        - ACM International Conference on Multimedia (CCF A)，审稿服务
        - International Conference on Machine Learning (CCF A)，审稿服务
        - Computer Networks (CCF B)，优秀审稿人
        - Information Processing and Management (CCF B)审稿服务
        - The journal of supercomputing (CCF C)审稿服务
        - 国际标准化组织ISO/TC295“审计数据采集标准”中国专家组成员     
    design:
      columns: '1'
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
  - block: contact-info
    id: contact
    content:
      title: 联系方式
      subtitle: "Let's build something amazing together"
      text: |-
        如果您对我们的工作内容感兴趣或想加入我们，欢迎随时与我取得联系！办公地点：江苏省南京市浦口区南京审计大学致明楼222办公室，工作时间：周一到周五 09:00 至 17:00。
      email: ffshen@nau.edu.cn
      autolink: true
    design:
      columns: '1'
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
---
