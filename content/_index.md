---
title: "Michael Nguyen-Mason"
date: 2025-07-21
type: landing

design:
  spacing: "5rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: uploads/mnguyenmason_cv_2025.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: .75
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
        <div style="text-align: center; margin-top: -3rem;">
        <a href="https://www.dropbox.com/scl/fi/czotoc62f11dp9klrgfi2/JMP_nguyenmason.pdf?rlkey=0oft7shnmbgqxv66vc85rt2vj&st=i47g8t6c&dl=0" style="display: inline-block; padding: 0.5rem 1.5rem; background-color: #1565c0; color: white; text-decoration: none; border-radius: 0.375rem; font-size: 0.875rem; font-weight: 500;" target="_blank" rel="noopener">Job Market Paper</a>
        </div>
    design:
      spacing:
        padding: [0, 0, 0, 0]

  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-

        My research asks how the microeconomic incentives created by scientific uncertainty and public policy shape the direction of medical innovation: who innovates, what is innovated, and who benefits. My work uses econometric methods to analyze large, granular datasets and focuses on (i) the barriers and boons to scientific entrepreneurship and (ii) the incentives that shape the geographic and demographic distribution of medical innovation.

        More broadly, I am interested in questions at the intersection of innovation, policy, and medicine.

        Please reach out to collaborate!

    design:
      columns: '1'

  - block: resume-awards
    content:
      title: Awards & Honors
      username: admin

  - block: collection
    id: research
    content:
      title: Dissertation Research
      text: "Distributional Causes and Consequences of Medical Innovation"
      filters:
        folders:
          - research
        featured_only: true
      count: 3
    design:
      view: citation
      columns: 1

  - block: collection
    id: talks
    content:
      title: Recent Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1

  - block: collection
    id: news
    content:
      title: Written Op-Eds
      filters:
        folders:
          - news
    design:
      view: article-grid
      columns: 1

  - block: collection
    id: teaching
    content:
      title: Courses Taught
      filters:
        folders:
          - teaching
        featured_only: true
      count: 2
    design:
      view: article-grid
      columns: 2
---