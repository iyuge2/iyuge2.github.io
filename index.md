---
layout: splash
title: "iyuge2"
excerpt: "算法工程师，关注推荐系统、机器学习工程和多模态理解。这里会展示既往工作，也沉淀一些阶段性思考。"
header:
  overlay_color: "#334155"
  overlay_filter: "0.45"
  actions:
    - label: "查看工作"
      url: "/work/"
    - label: "阅读文章"
      url: "/blog/"
intro:
  - excerpt: "把工程里的问题讲清楚，把研究里的方法落到实处。"
feature_row:
  - title: "推荐与排序"
    excerpt: "关注模型、数据、指标和线上体验之间的闭环。"
  - title: "机器学习工程"
    excerpt: "记录训练、评估、排障和复现实验中的可迁移经验。"
  - title: "多模态理解"
    excerpt: "从研究经历出发，持续关注文本、视觉和语音信号的协同建模。"
feature_row_work:
  - title: "既往工作"
    excerpt: "算法工程师，清华大学计算机系硕士，华中科技大学计算机科学与技术本科。"
    url: "/work/"
    btn_label: "了解更多"
    btn_class: "btn--primary"
feature_row_blog:
  - title: "博客沉淀"
    excerpt: "后续会写推荐系统、机器学习工程、多模态学习和工具使用相关内容。"
    url: "/blog/"
    btn_label: "查看文章"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row_work" type="left" %}

{% include feature_row id="feature_row_blog" type="right" %}
