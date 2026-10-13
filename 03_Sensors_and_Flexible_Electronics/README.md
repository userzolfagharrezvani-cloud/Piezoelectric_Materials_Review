# 03 — Sensors and Flexible Electronics

## What piezoelectric sensors measure
Piezoelectric sensors suit dynamic signals such as vibration, impact, acoustic pressure, transient force, and changing deformation. Pure piezoelectric sensing is generally less suitable for indefinitely measuring static force because charge can leak through finite input resistance and material/circuit leakage.

## Material choices
- Ceramics: high response and stiffness, but brittle and less conformable.
- PVDF and copolymers: flexible, light, suitable for films and wearables.
- Ceramic–polymer composites: balance flexibility and response.
- Nanostructured and thin-film materials: useful for miniaturized devices.
- Textile and porous structures: conformable but may introduce variability and humidity dependence.

## Sensor metrics
Sensitivity; linear range and nonlinearity; detection limit and signal-to-noise ratio; hysteresis; repeatability; response time and bandwidth; temperature/humidity dependence; cross-sensitivity; fatigue and drift. High voltage response alone does not establish a low detection limit.

## Wearable and AI-enabled uses
Potential applications include gait/posture monitoring, respiration-related motion, joint movement, touch interfaces, electronic skin, human–machine interaction, and event recognition. Machine-learning studies should use participant-independent or device-independent splits when the intended use requires generalization; randomly splitting adjacent time-series samples can overestimate performance.

## Experimental checklist
1. Define the input quantity and calibrate against a reference.
2. State active area, film thickness, electrode pattern, and mounting.
3. Report measurement impedance and acquisition bandwidth.
4. Test repeatability across devices and cycles.
5. Evaluate humidity, temperature, motion artifacts, and drift.
6. For human studies, describe protocol, sample size, and ethics/consent as applicable.
7. For AI, report data splits, baseline model, class balance, and external validation if available.

## Reviews
- Chen, Zhang & Lu, “Flexible piezoelectric materials and strain sensors for wearable electronics and artificial intelligence applications,” Chemical Science (2024). https://doi.org/10.1039/D4SC05166A
- “Piezoelectric materials for flexible and wearable electronics: A review,” Materials & Design. https://doi.org/10.1016/j.matdes.2021.110164
- Mahapatra et al., Advanced Science (2021). https://doi.org/10.1002/advs.202100864