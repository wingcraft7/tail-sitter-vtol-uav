# Tail-Sitter VTOL UAV – Conceptual Design & Aerodynamic Analysis

This repository presents the conceptual design and preliminary aerodynamic analysis of a tail-sitter vertical takeoff and landing (VTOL) unmanned aerial vehicle (UAV) based on a flying-wing configuration. The project focuses on aerodynamic efficiency, geometric simplicity, and suitability for conceptual-level analysis.

---

## Project Overview

The aircraft employs a tailless flying-wing layout with a blended center body and twin tractor propulsion. Geometry was developed parametrically using OpenVSP, followed by parasite drag estimation and aerodynamic analysis using the VSPAERO panel-method solver.

---

## Key Design Features

- Tail-sitter VTOL configuration
- Flying-wing planform with blended center body
- Aspect ratio ≈ 9, wingspan ≈ 1.4 m
- NACA 4415 root airfoil, NACA 0012 tip airfoil
- −2° linear washout from root to tip
- Elevons for combined pitch and roll control
- Twin wing-mounted tractor propulsion

---

## Aerodynamic Analysis Summary

- Parasite drag build-up performed at 100 km/h, sea level
- Zero-lift drag coefficient: **CD₀ ≈ 0.018** (including 7% excrescence)
- VSPAERO angle-of-attack sweep: −4° to +14°
- Lift coefficient: **CL ≈ 0.85 at 10° AoA**
- Smooth drag rise and stable pitching moment behavior
- Peak lift-to-drag ratio at moderate angles of attack

---

## Tools Used

- OpenVSP (geometry modeling and parasite drag estimation)
- VSPAERO (panel-method aerodynamic analysis)
- LaTeX (technical documentation)

---

## Repository Contents

- `report/` – Final research-style technical report (PDF)
- `geometry/` – OpenVSP (.vsp3) aircraft geometry file
- `figures/` – Key geometry and aerodynamic result figures
- `analysis_notes/` – Analysis assumptions and solver settings

---

## Limitations and Future Work

This study is limited to conceptual-level aerodynamic analysis using inviscid methods. Future work may include structural finite element analysis, high-fidelity CFD simulations including viscous effects, propulsion sizing, and flight dynamics and control analysis.

---

## Author

Pushkal Garg  
B.Tech Mechanical Engineering  
IIT Ropar

