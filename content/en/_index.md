---
# Leave the homepage title empty to use the site title
title:
date: 2024-01-01
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: Reliable partners for the future
        content: A reliable partner for the future
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
          text: Learn more
          url: ../en/intro/
      - title: Wide-ranging business
        content: Multi-disciplinary investment, leading the industry with superior quality
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
          text: Learn more
          url: ../en/intro/
      - title: Achieve a win-win situation
        content: Creating success stories with you
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
          text: Learn more
          url: ../en/intro/
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
      title: Company News
      subtitle: Company news in recent times
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