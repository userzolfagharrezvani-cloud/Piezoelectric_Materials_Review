# 02 — Piezoelectric Energy Harvesting

## Concept
A piezoelectric harvester converts mechanical excitation—vibration, bending, impacts, flow-induced motion, or human movement—into electrical energy. The practical target is often to power or extend the life of low-power sensors and wireless nodes, rather than to replace grid-scale generation.

## Architectures
- Cantilever beam: useful for vibration, often requiring resonance tuning.
- Unimorph/bimorph: active layer(s) coupled to a substrate or each other.
- Stack: compact and force-capable; requires appropriate mechanical loading.
- Membrane/diaphragm: useful in pressure, acoustic, and fluid-driven systems.
- Flexible patch/textile: conformable but mechanically harder to standardize.
- Impact/footstep devices: intermittent high-force excitation; assess durability and comfort.

## Power is not voltage
Open-circuit voltage can be high while deliverable power remains small. State the electrical load and measurement method. For a resistive load:

Pavg = (1/T) ∫[v(t)²/R] dt

For approximately sinusoidal voltage across a resistor, Pavg = VRMS²/R.

Report excitation amplitude, frequency, acceleration or force, displacement, device dimensions, load resistance, rectifier/power-management circuit, and whether power is measured before or after that circuit.

## Performance factors
1. Material coefficient and electromechanical coupling.
2. Resonance and bandwidth relative to actual excitation.
3. Stress distribution and boundary conditions.
4. Active volume, electrode arrangement, and capacitance.
5. Dielectric and mechanical losses.
6. Rectification, impedance matching, storage, and circuit consumption.
7. Fatigue and environmental exposure.

A narrow resonant peak may perform poorly when real-world frequency varies. Broadband designs and frequency tuning can be important.

## Applications
Wireless sensor networks; structural health monitoring; wearable/implantable low-power electronics; industrial machinery; transportation and infrastructure; flow-driven or acoustic microsystems; self-powered event sensors.

## Experimental protocol
- Calibrate the excitation source.
- Measure at multiple frequencies and amplitudes.
- Show waveforms and load-dependence.
- Calculate average power with a clear RMS or integration method.
- Include controls and report device-to-device variation.
- Test cycling durability and a realistic energy budget.
- Distinguish generated energy from net energy after electronics losses.

## Reviews
- Sezer & Koç, “A comprehensive review on the state-of-the-art of piezoelectric energy harvesting,” Nano Energy (2021). https://doi.org/10.1016/j.nanoen.2020.105567
- Li et al., “Piezoelectric Energy Harvesting Technology: From Materials, Structures, to Applications,” Small Structures (2022). https://doi.org/10.1002/sstr.202100128
- Brusa et al., “A Review of Piezoelectric Energy Harvesting: Materials, Design, and Readout Circuits,” Actuators (2023). https://doi.org/10.3390/act12120457