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
      button:
        text: Download CV
        url: uploads/resume.pdf
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
      title: '📚 研究简介'
      subtitle: ''
      text: |-
        Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

        I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
        Please reach out to collaborate 😃
    design:
      columns: '1' 

  - block: collection
      id: news
      content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - news
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
      title: Selected Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
       view: citation

 
  - block: collection
    id: students
    content:
      title: students
      filters:
        folders:
          - students
    design:
      columns: '2'
      view: compact

  - block: contact
    id: contact
    content:
      title: 如果您对边缘智能和人工智能研究感兴趣，欢迎随时与我联系！快捷发送邮件的方式如下：
      subtitle: ''
      text: ''
      # Contact details - edit or remove options as needed
      email: 邮箱：ffshen AT nau DOT edu DOT cn （将AT替换为“@”，将DOT替换为点“.”） 
      address:
        street: 地址：江苏省
        city: 南京市
        region: 浦口区江浦街道雨山西路86号致明楼222办公室
      office_hours:
        - '工作时间：周一至周五 09:00 to 17:00'
      contact_links:
        - icon: weixin
          icon_pack: fab
          name: 微信：WeChat Me
          link: 'authors/admin/weixin.jpg'
        # Automatically link email and phone or display them just as text?
      autolink: true
      # Choose an email form provider (netlify/formspree)
      form:
        provider: formspree
        formspree:
          # If using Formspree, enter your Formspree form ID
          id: 'xleyzoew'
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
---
