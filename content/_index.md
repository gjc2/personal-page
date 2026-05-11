---
title: ''
summary: ''
date: 2026-04-20
type: landing

design:
  spacing: '5rem'

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
        size: large
        shape: circle
  - block: markdown
    id: research
    content:
      title: 研究兴趣
      text: |-
        我目前关注 ECSP 框架下判定问题、优化问题和计数问题的研究。这个方向强调从统一的约束框架出发，理解不同问题形式的表达能力、复杂性边界与算法结构。

        ### 判定问题

        研究给定实例是否满足某类约束条件，关注可判定性、复杂性分类以及结构化实例上的有效算法。

        ### 优化问题

        研究在约束系统中寻找最优解的问题，关注目标函数、近似算法、参数化结构以及复杂性下界。

        ### 计数问题

        研究满足解的数量及其计算复杂性，关注计数版本与判定、优化版本之间的联系。
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
