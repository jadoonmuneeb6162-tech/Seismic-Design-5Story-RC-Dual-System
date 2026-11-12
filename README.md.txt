# Seismic Design of a 5-Story Reinforced Concrete Dual-System Building

Structural design of a 5-story reinforced concrete office building in San Francisco, CA, using a dual lateral system (special RC shear walls plus special moment frames), designed to ASCE 7-22 and ACI 318-19.

## Project Overview
- Building: 5-story cast-in-place RC office; 96 x 72 ft; 5 stories at 12 ft (hn = 60 ft)
- Gravity system: 8 in. two-way slab on 18x30 beams, 30x30 columns
- Lateral system: dual system (special RC shear walls + special moment frames)
- Site: San Francisco, CA; Site Class D; Seismic Design Category D
- Codes: ASCE 7-22 (loads and seismic demand), ACI 318-19 (concrete design and detailing)
- Analysis: ETABS, Equivalent Lateral Force procedure

## Key Design Parameters
- System factors: R = 7, Omega-0 = 2.5, Cd = 5.5, Ie = 1.0, rho = 1.3
- Spectral: SDS = 1.16 g, SD1 = 1.17 g
- Seismic weight: W = 10,098 kip
- Seismic coefficient: Cs = 0.166
- Base shear: V = 1,676 kip

## Results and Checks
- Fundamental period: T1 = 0.19 s (translational); torsion at Mode 3
- Mass participation: 99.7% (X), 100% (Y)
- Base shear, hand vs ETABS: 1,673 vs 1,676 kip (0.17%)
- Story drift: 0.001 < 0.020 allowable
- Torsional irregularity: 1.03 / 1.04 < 1.2 (none)
- P-Delta: theta = 0.001 < 0.10
- Dual-system 25% rule: frames resist 29% (X) and 39% (Y), both >= 25%
- All member checks (beam, column, joint, wall) pass; capacity design per ACI 318-19 Chapter 18

## Repository Contents
- `ETABS-model/` : ETABS structural model
- `Calculations/` : Excel design workbook (loads, ELF, drift and torsion, member design)
- `Drawings/` : AutoCAD drawing set (framing plan, sections, elevations, seismic details) and DXF
- `Presentation/` : project presentation

## Tools
ETABS, Microsoft Excel, AutoCAD.

## Author
Muneeb Jadoon