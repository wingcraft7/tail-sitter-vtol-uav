# Tail-Sitter VTOL UAV – Conceptual Design & Aerodynamic Analysis

The conceptual design and aerodynamic analysis of a flying-wing tail-sitter vertical takeoff and landing (VTOL) unmanned aerial vehicle (UAV) are presented in this repository. Aerodynamic efficiency and geometric simplicitymare the main goals of the project.

---

## Project Overview

The aircraft uses twin tractor propulsion, a blended center body, and a tailless flying-wing configuration. OpenVSP was used to develop the geometry parametrically. The VSPAERO panel-method solver was then used to estimate parasite drag and perform aerodynamic analysis.

---

## Key Design Features

- Tail-sitter VTOL configuration
- Flying-wing planform with blended center body
- Aspect ratio = 9, wingspan = 1.4 m
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

This work is limited to conceptual level inviscid aerodynamic analysis. Future research would focus on flight dynamics and control analysis, propulsion sizing, CFD simulations with viscous effects, and structural finite element analysis.

**Note** - An RC transmitter is not included in the BOM, as it will be sourced from my college equipment for testing.

---

## Author

Pushkal Garg  
B.Tech Mechanical Engineering  
IIT Ropar

