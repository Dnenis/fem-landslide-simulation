# Landslide FEM Simulation

Finite Element simulation of a slow-moving landslide using a viscoplastic 
material model (Perzyna). Developed as part of my M.Sc. in Geosciences 
(Computational Geomechanics) at Johannes Gutenberg-Universität Mainz.

---

## Overview

This project models slope deformation and failure behavior under two 
scenarios using the Finite Element Method (FEM):

- **Task 8 – Stable slope:** Creep deformation under gravity loading,
  resulting in ~1.0 m total displacement. Classified as "Extremely Slow"
  per Hungr et al. (2014).
- **Task 12 – Progressive failure:** Strain-softening behavior leading to
  accelerating displacement and slope collapse. Classified as "Rapid".

The simulations use a **Perzyna viscoplastic model** with a 
Drucker-Prager yield criterion, implemented in VP2D.

---

## Workflow
Geometry (Inkscape) → Mesh generation (MeshTools2D) →
FEM Simulation (VP2D) → Post-processing & Visualization (ParaView)

---

## Key Results

| Scenario | Max. Displacement | Velocity Class |
|---|---|---|
| Task 8 – Stable | ~1.0 m | Extremely Slow |
| Task 12 – Progressive failure | >> 1.0 m | Rapid |

---

## Tools & Technologies

| Tool | Purpose |
|---|---|
| VP2D | FEM solver (viscoplastic, 2D) |
| MeshTools2D | Mesh generation |
| Inkscape | Geometry definition |
| ParaView | Result visualization |
| LaTeX | Report writing |

---

## Skills Demonstrated

- Finite Element Method (FEM) for nonlinear geomechanical problems
- Viscoplastic constitutive modeling (Perzyna, Drucker-Prager)
- Mesh generation and model setup
- Interpretation of displacement, strain and stress fields
- Scientific visualization with ParaView
- Technical report writing (LaTeX)

---

## Background

Developed as part of the **Computational Geomechanics** course at JGU
