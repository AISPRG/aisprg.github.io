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
        <div style="font-size: 1.25rem;">
        <ul>

          <!-- NDSS'26 -->
          <li>
            <details>
              <summary><strong>[NDSS'26 x2]</strong> 2 paper accepted at NDSS 2026 (12/2025)</summary>
              <ul>
                <li>
                  <strong>Paper 1:</strong>
                  <a href="https://arxiv.org/abs/2509.09112" target="_blank">
                    Character-Level Perturbations Disrupt LLM Watermarks
                  </a>
                </li>
                <li>
                  <strong>Paper 2:</strong>
                  <a href="" target="_blank">
                    Unshaken by Weak Embedding: Robust Probabilistic Watermarking for Dataset Copyright Protection
                  </a>
                </li>
              </ul>
            </details>
          </li>

          <!-- USENIX Security'25 -->
          <li>
            <details>
              <summary><strong>[USENIX Security'25 x3]</strong> 3 papers accepted at USENIX Security 2025</summary>
              <ul>
                <li>
                  <strong>Paper 1:</strong>
                  <a href="https://www.usenix.org/conference/usenixsecurity25/presentation/ye-duplication" target="_blank">
                    Data Duplication: A Novel Multi-Purpose Attack Paradigm in Machine Unlearning
                  </a>
                </li>
                <li>
                  <strong>Paper 2:</strong>
                  <a href="https://www.usenix.org/conference/usenixsecurity25/presentation/ye-attacks" target="_blank">
                    Data-Free Model-Related Attacks: Unleashing the Potential of Generative AI
                  </a>
                </li>
                <li>
                  <strong>Paper 3:</strong>
                  <a href="https://www.usenix.org/conference/usenixsecurity25/presentation/ye-inversion" target="_blank">
                    Cross-Modal Prompt Inversion: Unifying Threats to Text and Image Generative AI Models
                  </a>
                </li>
              </ul>
            </details>
          </li>

        </ul>
        </div>
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
