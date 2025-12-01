---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        AI Security & Privacy Lab
      image:
        filename: Logo-300.png  # Hugo finds this in assets/media/
      text: 
        <br>
        The AI Security & Privacy Lab is a core lab at the Australian Artificial Intelligence Institute (AAII) at University of Technology Sydney (UTS). It has been a center of excellence for AI/Data security and privacy research, teaching, and practice since its founding in 2019. 
    design:
      columns: '1'


  - block: markdown
    content:
      title: Latest News
      subtitle:
      text: |
        <details open>
          <summary><strong>Recent News (2025)</strong></summary>
          <ul>
            <li><strong>[NDSS'26 x1]</strong> 1 paper accepted at ICML-25 (CORE A*/CCF A) (05/2025).</li>
            <li><strong>[Usenix Security'25 x3]</strong> Three papers accepted at Usenix Security'25 (CORE A*/CCF A).</li>
          </ul>
        </details>
    design:
      columns: '1'


  
  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
