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
      title: '📚 研究介绍'
      subtitle: ''
      text: |-
        - 本课题组围绕高效可信人工智能系统开展研究，面向大模型与智能体时代人工智能系统在计算资源、数据共享、安全隐私和多主体协同等方面面临的挑战，重点研究高效大模型与智能体、分布式智能与联邦学习、人工智能安全与隐私保护等关键技术，探索大模型高效学习与推理、模型轻量化、分布式学习、联邦智能、隐私保护和智能体安全协同等理论与方法，构建面向复杂场景的高效、可扩展、安全可信人工智能系统。

        - 围绕智能审计这一特色应用领域，重点开展大数据审计、审计大模型、审计智能体和穿透式智能审计研究，探索大模型、智能体与分布式智能技术在复杂审计分析、风险识别和审计决策中的应用；同时面向金融风控、智慧医疗、政务智能等典型数据密集型和隐私敏感场景开展拓展研究，推动人工智能系统关键技术与行业应用深度融合。

        - 课题组注重理论与实践结合，鼓励学生结合自身兴趣与特长开展个性化、创新性研究。欢迎对科研训练感兴趣的研究生及本科生与我联系，探索可以落地应用的科学研究。
        
        - <u>已毕业学生就业与深造前景良好，众多赴政府、国企、事业单位、及IT企业等单位工作，优秀学子继续攻读博士学位，综合发展质量优异。具体见：</u> <a href="students" style="font-weight: bold;">学生培养情况</a>
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
