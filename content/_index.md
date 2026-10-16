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
        about: 'Profile'
        education: 'Academic Formation'
        interests: 'Core Research Areas'
    design:
      spacing:
        padding: ["1.5rem", "0", "3rem", "0"]
      background:
        gradient_mesh:
          enable: false
      name:
        size: md
      avatar:
        size: large
        shape: circle

  - block: resume-skills
    content:
      title: Core Competencies & Technical Expertise
      username: me
    design:
      show_skill_percentage: false

  - block: content-collection
    id: conferences
    content:
      title: Conferences & Presentations
      text: 'Selected oral communications and poster contributions at international and national scientific meetings.'
      filters:
        folders:
          - publications
    design:
      view: citation

  - block: content-collection
    id: projects
    content:
      title: Featured Projects & Research Software
      text: 'Open-source Python packages, UCSF Chimera scripts, and computational research workflows.'
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
