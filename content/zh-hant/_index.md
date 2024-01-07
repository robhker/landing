---
# Leave the homepage title empty to use the site title
title:
date: 2024-01-01
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 信賴有道
        content: 可靠的合作夥伴方可共創未來
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
          text: 瞭解更多
          url: ../zh-hant/intro/
      - title: 業務廣泛
        content: 多領域投資，引領行業發展，以卓越品質引領行業發展
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
          text: 瞭解更多
          url: ../zh-hant/intro/
      - title: 實現共贏
        content: 與您共同創造成功的故事
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
          text: 瞭解更多
          url: ../zh-hant/intro/
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
      title: 公司新聞
      subtitle: 最近一段時間的公司動態
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
      view: card
      columns: '1'
---