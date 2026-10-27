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
      text: |-
        Open-source Python packages, UCSF Chimera scripts, and computational research workflows.
        * **Software Automation:** Building open-source Python packages like [Gephyra](https://github.com/insilichem/Gephyra) to analyze [water-bridge networks](https://github.com/insilichem/Gephyra).
      filters:
        folders:
          - projects
    design:
      view: card
      columns: 2

  - block: markdown
    id: visualizations
    content:
      title: Molecular & Trajectory Visualizations
      subtitle: 'Structural & Solvent Network Analysis in Artificial Metalloenzymes'
      text: |-
        <div class="viz-showcase-grid">
          <div class="viz-card">
            <div class="viz-card-header">
              <span class="viz-badge">Water-Bridge Network Analysis</span>
              <h3><a href="https://github.com/insilichem/Gephyra" target="_blank" rel="noopener">Gephyra — Hydration Pathway Discovery &amp; Clustering</a></h3>
              <p>Building open-source Python packages like <a href="https://github.com/insilichem/Gephyra" target="_blank" rel="noopener">Gephyra</a> to analyze <a href="https://github.com/insilichem/Gephyra" target="_blank" rel="noopener">water-bridge networks</a>. Combines NetworkX graph path search across MD frames (<strong>Panel A</strong>, Frame 3900: 77 paths) with Fréchet-distance hierarchical clustering into ranked hydration channels (<strong>Panel B</strong>, Clusters 1–10).</p>
            </div>
            <a href="/media/visualizations/gephyra-water-network.png" target="_blank" rel="noopener" class="viz-img-link">
              <img src="/media/visualizations/gephyra-water-network.png" alt="Gephyra Water-Bridge Network Discovery and Pathway Clustering" loading="lazy" />
            </a>
          </div>

          <div class="viz-card">
            <div class="viz-card-header">
              <span class="viz-badge">Geometric Solvent Partitioning</span>
              <h3><a href="https://github.com/insilichem/Water-count-per-plane" target="_blank" rel="noopener">Water Counting per Plane — Active-Site Hydration Quantification</a></h3>
              <p>Automated UCSF Chimera workflow defining a least-squares reference plane across coordinated metal cofactor atoms (<strong>Panel A</strong>, <code>water-plane-noW</code>) to identify and count explicit water molecules within radial and plane-distance cutoffs such as <code>3.7 Å</code> and <code>4.7 Å</code> (<strong>Panel B</strong>, <code>water-plane-noW2</code>).</p>
            </div>
            <a href="/media/visualizations/water-counting-per-plane.png" target="_blank" rel="noopener" class="viz-img-link">
              <img src="/media/visualizations/water-counting-per-plane.png" alt="Water Counting per Plane Geometric Solvent Partitioning" loading="lazy" />
            </a>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ["2.5rem", "0", "3rem", "0"]

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
