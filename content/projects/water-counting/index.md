---
title: "Water Counting per Plane"
summary: "Python workflow for UCSF Chimera to define cofactor reference planes and quantify water molecules across catalytic pockets."
date: 2026-01-01
tags:
  - Python
  - UCSF Chimera
  - Molecular Dynamics
links:
  - type: site
    url: https://github.com/insilichem/Water-count-per-plane
    name: GitHub Repository
    icon: brands/github
---

**Water Counting per Plane** is a Python tool for UCSF Chimera that defines a least-squares geometric reference plane across selected cofactor or ligand atoms and quantifies solvent molecules partitioned across the plane along molecular dynamics trajectories.

### Workflow Highlights
* **Cofactor Reference Plane Definition (`water-plane-noW`):** Anchors an exact geometric plane across the coordinated metal cofactor ring prior to solvent filtering (**Panel A**).
* **Distance-Resolved Solvent Partitioning (`water-plane-noW2`):** Identifies and counts explicit water molecules within user-defined radial and signed plane-distance cutoffs (e.g., `3.7 Å` and `4.7 Å`, **Panel B**).

**Authors:** Peralta-Morales, M. F., Sciortino, G. & Maréchal, J.-D. (2026) — [GitHub Repository (`insilichem/Water-count-per-plane`)](https://github.com/insilichem/Water-count-per-plane)
