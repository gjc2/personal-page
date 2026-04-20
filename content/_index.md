---
title: ''
summary: ''
date: 2026-04-20
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
        interests: 研究方向
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
        我目前就读于中国科学技术大学，研究方向为 ECSP 框架下判定问题、优化问题和计数问题的研究。

        我关注相关理论模型中的复杂性分析、算法设计以及不同问题形式之间的联系，希望在理论计算机科学方向继续深入探索。

        除理论研究外，我也有算法竞赛、系统开发和实验室项目训练经历。
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
