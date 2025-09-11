---
name: New Glossary Term
about: 新的术语词
title: "[新术语词]"
labels: ''
assignees: ''
body:
  - type: textarea
    id: original
    attributes:
      label: 原文
      description: 术语的原名
      placeholder: 术语的原文，如entity
    validations:
      required: true
  - type: textarea
    id: translation
    attributes:
      label: 译文
      description: 术语的译文
    validations:
      required: true
  - type: dropdown
    id: state
    attributes:
      label: 状态
      description: 状态
      options:
        - 推荐
        - 草稿
        - 弃置 
      default: 0
    validations:
      required: true
---


