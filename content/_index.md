---
title: ''
summary: ''
date: 2026-04-05
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: 下载简历
        url: /uploads/resume.pdf
      headings:
        about: ''
        education: 教育经历
        interests: 研究兴趣
    design:
      background:
        gradient_mesh:
          enable: false
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: 个人介绍
      text: |-
        我目前就读于中国科学技术大学，研究兴趣集中在人工智能与算法方向。

        在本科阶段，我系统学习了计算机科学核心课程，并参与算法竞赛、项目开发和实验室研究训练。

        我希望继续在 AI、算法设计与智能系统方向开展更深入的学习与研究。
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: 项目与论文
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: news
    content:
      title: 最新动态
      page_type: blog
      count: 5
      filters:
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
