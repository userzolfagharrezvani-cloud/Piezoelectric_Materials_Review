# 01 — Fundamentals of Piezoelectric Materials

## Physical meaning
Piezoelectricity is electromechanical coupling: mechanical stress can generate electrical displacement (direct effect), and an applied electric field can generate mechanical strain (converse effect). In the classical crystal description, a piezoelectric response requires a non-centrosymmetric crystal structure. Ferroelectric ceramics commonly require poling to establish useful macroscopic polarization.

## Linear constitutive equations
One common stress-charge form is:

S = sᴱT + dᵀE

D = dT + εᵀE

Here S is strain, T stress, E electric field, D electric displacement, sᴱ compliance at constant field, d the piezoelectric coefficient matrix, and εᵀ permittivity at constant stress. Alternative strain-charge forms are also used, so conventions should be stated.

For a simplified one-dimensional approximation:
D₃ ≈ d₃₃T₃ and S₃ ≈ d₃₃E₃.

These relations are teaching approximations; clamping, lateral coupling, nonlinear ferroelectric behavior, and electrical boundary conditions can change device response.

## Common metrics
- d33 and d31: piezoelectric coefficients, often reported in pC N⁻¹ or pm V⁻¹ depending on measurement and convention.
- g coefficient: relates electric field to stress under specified conditions.
- Electromechanical coupling factor k: conversion efficiency for a defined mode.
- Permittivity and dielectric loss: affect charge storage and circuit behavior.
- Mechanical quality factor Qm: important for resonant devices.
- Curie temperature, fatigue, aging, coercive field, and depolarization: critical for reliability.

A large isolated coefficient does not guarantee a better device. The relevant mode, frequency, geometry, dielectric loss, mechanical strength, and circuitry must be considered together.

## Material families
| Family | Strengths | Constraints |
|---|---|---|
| PZT and related lead-based ceramics | High response; mature processing | Lead toxicity and end-of-life concerns |
| BaTiO3 and other lead-free ceramics | Reduced lead concerns; tunable composition | Performance depends on composition and microstructure |
| KNN-based ceramics | Lead-free potential | Phase control, densification, reproducibility |
| PVDF / P(VDF-TrFE) | Flexible, lightweight, processable | Phase content and poling matter; response often below high-performance ceramics |
| ZnO, AlN, thin films | Integration with microelectronics and MEMS | Texture, residual stress, interfaces |
| Ceramic–polymer composites | Balance flexibility and response | Filler dispersion and interface quality |
| Bio-derived materials | Potential biocompatibility and sustainability | Variable properties; hydration and processing matter |

## Measurement checklist
Report composition and phase; synthesis and poling; dimensions; density/porosity; electrode geometry; measurement method and calibration; loading direction; frequency; temperature; electrical boundary condition; uncertainty and replicates. For thin films, include thickness, substrate, texture/orientation, and residual stress when known.

## Suggested review
Mahapatra et al., “Piezoelectric Materials for Energy Harvesting and Sensing Applications: Roadmap for Future Smart Materials,” Advanced Science (2021). https://doi.org/10.1002/advs.202100864