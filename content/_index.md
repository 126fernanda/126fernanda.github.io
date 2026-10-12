---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-10-12
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: '🔬 Research Focus'
      subtitle: ''
      text: |-
        My research focuses on the rational design of **artificial metalloenzymes** and **de novo metallopeptides** for biocatalysis and drug design through molecular dynamics, structure prediction, and mechanistic quantum modelling.

        I also develop open-source scientific Python tools to automate and deepen the analysis of simulations, integrating machine learning models into computational chemistry pipelines.
    design:
      columns: '1'

  - block: content-collection
    id: conferences
    content:
      title: Conferences & Presentations
      text: 'Selected conference talks and poster contributions'
      filters:
        folders:
          - publications
    design:
      view: article-grid
      columns: 2

  - block: content-collection
    id: projects
    content:
      title: Featured Projects & Software
      text: 'Open-source scientific tools and computational research projects'
      filters:
        folders:
          - projects
    design:
      view: card
      columns: 2

  - block: content-collection
    id: blog
    content:
      title: Recent Blog Posts
      subtitle: ''
      text: ''
      page_type: blog
      count: 3
      filters:
        folders:
          - blog
      offset: 0
      order: desc
    design:
      view: card
---
