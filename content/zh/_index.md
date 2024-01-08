---
# Leave the homepage title empty to use the site title
title:
date: 2024-01-01
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 信赖有道
        content: 可靠的合作伙伴方可共创未来
        align: center
        background:
          image:
            filename: 1.webp
            filters:
              brightness: 0.7
          position: right
          color: '#666'
        link:
          icon: circle-info
          icon_pack: fas
          text: 了解更多
          url: ../intro/
      - title: 业务广泛
        content: 多领域投资，引领行业发展，以卓越品质引领行业发展
        align: left
        background:
          image:
            filename: 2.webp
            filters:
              brightness: 0.7
          position: center
          color: '#555'
        link:
          icon: circle-info
          icon_pack: fas
          text: 了解更多
          url: ../intro/
      - title: 实现共赢
        content: 与您共同创造成功的故事
        align: right
        background:
          image:
            filename: 3.webp
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: circle-info
          icon_pack: fas
          text: 了解更多
          url: ../intro/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '400px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000

  - block: collection
    content:
      title: 公司新闻
      subtitle: 最近一段时间的公司动态
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: true
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: compact
      columns: '1'
---