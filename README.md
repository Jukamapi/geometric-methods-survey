# Analiza metod geometrycznych wspomagania modelowania 3D
*(Geometric Methods in 3D Modeling)*

Individual academic project (*Projekt Indywidualny*) written at the Faculty of Electrical Engineering, Warsaw University of Technology (Politechnika Warszawska), 2026.

**Note:** The paper is written in **Polish**. 

The compiled document is available directly in this repository: **[paper.pdf](paper.pdf)**.

---

## Overview

A literature review on 3D geometry representations, procedural generation methods, and related spatial algorithms based on SIGGRAPH papers and standard computer graphics literature.

### Topics covered:
* **Representations:** Triangle meshes (Indexed Face Sets vs. Half-Edge and Winged-Edge structures, topological 2-manifolds), NURBS (B-splines, knot vectors, projective weights), and Signed Distance Functions (SDFs, voxel grids, octrees, CSG operations).
* **Procedural generation:** Subdivision surfaces (Catmull-Clark for quads, Loop for triangles, limit surface continuity) and gradient noise (Perlin, Improved Perlin, Simplex, Worley).
* **Algorithms:** Marching Cubes (isosurface extraction from scalar fields, 15 canonical patterns, Transvoxel transitions) and SDF-based collision detection (broad-phase vs. narrow-phase, surface normal estimation via gradients).

---

## Building from source

The LaTeX source code and figures are in the `src/` directory.

To compile:
```bash
cd src
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
