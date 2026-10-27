---
title: "Gephyra"
summary: "Open-source Python package & GUI to discover, track, and cluster water-bridge networks in molecular dynamics trajectories."
date: 2026-01-01
tags:
  - Python
  - Molecular Dynamics
  - Bioinformatics
  - Network Analysis
links:
  - type: site
    url: https://github.com/insilichem/Gephyra
    name: GitHub Repository
    icon: brands/github
---

**Gephyra** is a pip-installable Python package with both a command-line interface (CLI) and graphical user interface (GUI) designed to discover, track, and statistically analyze [water-bridge networks](https://github.com/insilichem/Gephyra) in molecular dynamics trajectories.

### Key Capabilities
* **Probabilistic Hydrogen-Bond Scoring:** Robust identification of explicit water-bridge interactions connecting catalytic cofactors, ligands, and protein residues.
* **Weighted Graph Path Search:** Powered by NetworkX to trace water-mediated chains from root ligand atoms across MD trajectory frames (**Panel A**).
* **Fréchet-Distance Hierarchical Clustering:** Groups recurring 3D water pathways into ranked spatial hydration channels and representative medoid paths (**Panel B**).
* **Automated 3D Scene Generation:** Exports ready-to-run visualization scripts (`.cxc`, `.bild`, `.pml`, `.vmd`) for UCSF ChimeraX, UCSF Chimera, PyMOL, and VMD.

**Authors:** Peralta-Morales, M. F., Sciortino, G. & Maréchal, J.-D. (2026) — [GitHub Repository (`insilichem/Gephyra`)](https://github.com/insilichem/Gephyra)
