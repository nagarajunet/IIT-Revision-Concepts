# IIT Thermal Physics: Revision Guide and Practice

Use SI units. In gas laws always use temperature in Kelvin.

## 1. Thermal Expansion

| Topic | Formula | Remember |
|---|---|---|
| Length | dL = alpha x L x dT | Rods and wires |
| Area | dA = 2 x alpha x A x dT | Isotropic solid |
| Volume | dV = gamma x V x dT | gamma is about 3 alpha |
| Prevented expansion | stress = Y x alpha x dT | Force = Y x A x alpha x dT |
| Liquid in vessel | apparent coefficient = liquid coefficient - vessel coefficient | |

- A hole in a plate expands when the plate is heated.
- Add the expansions of rods joined in series.
- Water has maximum density at 4 deg C. From 0 deg C to 4 deg C, it contracts on heating.

---

## 2. Calorimetry and Latent Heat

| Situation | Formula |
|---|---|
| Change in temperature | Q = m c dT |
| Change of state | Q = m L |
| Isolated calorimeter | Heat lost = heat gained |

### Reliable method

1. Write initial and final states.
2. Break the change into heating, cooling, melting, or boiling steps.
3. Apply heat lost = heat gained.
4. Check that enough heat exists for the phase change you assumed.

---

## 3. Ideal Gas Laws and Kinetic Theory

| Relation | Formula |
|---|---|
| Ideal gas | P V = n R T = N k T |
| Fixed mass | P V / T = constant |
| Density | rho = P M / R T |
| Kinetic-theory pressure | P = (1/3) rho c-rms-squared |
| RMS speed | c-rms = square-root(3 R T / M) |
| Average kinetic energy per molecule | 3 k T / 2 |

- Dalton law: total pressure is the sum of partial pressures.
- For an ideal gas, internal energy depends only on temperature.
- At the same temperature, all ideal gases have equal average kinetic energy per molecule.

---

## 4. Specific Heats

| Gas | Cv | Cp | Gamma = Cp/Cv |
|---|---:|---:|---:|
| Monoatomic | 3R/2 | 5R/2 | 5/3 |
| Diatomic at ordinary temperature | 5R/2 | 7R/2 | 7/5 |

- Cp - Cv = R for one mole of an ideal gas.
- Change in internal energy: dU = n Cv dT.
- Use the diatomic values above unless vibration is included in the question.

---

## 5. First Law and Thermodynamic Processes

In this guide, W means work done **by the gas**.

> Q = dU + W

| Process | Condition | Work by gas | Internal energy |
|---|---|---|---|
| Isochoric | V constant | W = 0 | dU = Q |
| Isobaric | P constant | W = P dV = n R dT | dU = n Cv dT |
| Isothermal ideal gas | T constant | W = n R T ln(V2/V1) | dU = 0, so Q = W |
| Reversible adiabatic | Q = 0 | W = -dU | dU = n Cv dT |

### Reversible adiabatic relations

- P V^Gamma = constant
- T V^(Gamma - 1) = constant
- T^Gamma P^(1 - Gamma) = constant

### Key observations

- Area under a P-V curve is work done by the gas.
- An adiabatic curve is steeper than an isothermal curve.
- In free expansion into vacuum: Q = 0 and W = 0. An ideal gas therefore has no temperature change.
- Do not use the adiabatic relations for free expansion because it is irreversible.

---

## 6. Bulk Modulus and Sound in Gases

| Compression type | Bulk modulus B |
|---|---|
| Isothermal | B = P |
| Adiabatic | B = Gamma P |

Speed of sound in an ideal gas:

> v = square-root(Gamma P / rho) = square-root(Gamma R T / M)

Sound compression is adiabatic because it happens too quickly for heat transfer.

---

## 7. Heat, Work, and Cycles

- Heat and work are modes of energy transfer.
- 1 calorie is approximately 4.186 joule.
- For a complete cycle, dU = 0. Therefore net heat supplied = net work by the gas.
- A clockwise P-V cycle gives positive net work by the gas.

---

## 8. Mean Free Path

Mean free path is the average distance a molecule travels between collisions.

> lambda = k T / [square-root(2) x pi x d-squared x P]

| Condition | Change in mean free path |
|---|---|
| Temperature constant | Inversely proportional to pressure |
| Pressure constant | Proportional to temperature |
| Molecular diameter doubles | Becomes one-fourth |

---

## Fast IIT Checklist

- Convert Celsius to Kelvin in all gas problems.
- Draw a P-V graph before calculating work.
- Check whether work is by the gas or on the gas.
- Use Cp at constant pressure and Cv at constant volume.
- Use adiabatic equations only for reversible adiabatic changes.
- In calorimetry, confirm the final phase before solving.

---

# Practice Questions

## Core practice

1. A steel wire has length 2.0 m and area 1.0 mm-squared. It is held between rigid walls. Y = 2.0 x 10^11 Pa and alpha = 1.2 x 10^-5 per K. Find the force for a 50 K temperature rise.
2. A liquid has volume-expansion coefficient 7.2 x 10^-4 per K. Its glass vessel has coefficient 2.7 x 10^-5 per K. Find apparent expansion coefficient.
3. 100 g ice at 0 deg C is added to 300 g water at 30 deg C. Take c-water = 1 cal per g per deg C and latent heat = 80 cal per g. Find the final state.
4. A 0.50 kg metal at 200 deg C is placed in 1.0 kg water at 20 deg C. Final temperature is 30 deg C. Find metal specific heat. Use c-water = 4186 J per kg per K.
5. A gas has density 1.25 kg per m-cubed at 1.0 x 10^5 Pa. Find RMS speed.
6. At what temperature is nitrogen RMS speed 600 m per s? Molar mass is 28 g per mol.
7. Find dU when 2 mol diatomic gas heats from 300 K to 500 K. Ignore vibration.
8. One mol monoatomic gas is heated at constant pressure by 100 K. Find Q, W, and dU.
9. Two mol gas expands reversibly and isothermally at 300 K from 10 L to 20 L. Find W.
10. Monoatomic gas expands reversibly and adiabatically from V to 8V. Find T2/T1.

## IIT-style questions

11. A vessel is full of water at 4 deg C and is heated slightly. Explain the initial level change.
12. A gas follows a straight line from (V0, P0) to (2V0, 2P0) on a P-V graph. Find W in terms of P0V0, and state whether temperature rises or falls.
13. One mol monoatomic gas goes from (P, V) to (P, 2V). Compare heat supplied for: (a) direct isobaric path, and (b) constant-volume heating to (2P, V), then isothermal expansion.
14. In reversible adiabatic compression, pressure becomes 32 times and volume becomes one-eighth. Find Gamma.
15. An ideal gas expands freely into an evacuated chamber of equal volume. Find final temperature and explain why the process is not reversible isothermal.
16. Compare heat needed to raise monoatomic and diatomic gas by dT at constant volume and constant pressure.
17. Air is diatomic. In adiabatic compression, pressure becomes four times. Find density ratio and temperature ratio.
18. Two gases have molecular diameters d and 2d at identical temperature and pressure. Find ratio of mean free paths.
19. A clockwise rectangular P-V cycle is bounded by P1, P2, V1, and V2. Find net work and net heat.
20. Assertion-reason: Cp is greater than Cv for ideal gas. Reason: At constant pressure, some heat is used for expansion work. Does the reason explain the assertion?

---

# Answer Key

| Question | Answer |
|---:|---|
| 1 | 120 N, compressive |
| 2 | 6.93 x 10^-4 per K |
| 3 | All ice melts; final temperature is 2.5 deg C |
| 4 | Approximately 492 J per kg per K |
| 5 | Approximately 490 m per s |
| 6 | Approximately 404 K |
| 7 | dU = 1000 R = 8.31 kJ |
| 8 | Q = 2.08 kJ; W = 0.831 kJ; dU = 1.25 kJ |
| 9 | W = 2RT ln(2) = 3.46 kJ |
| 10 | T2/T1 = 1/4 |
| 11 | Initially the level falls: water expansion coefficient is zero at 4 deg C but the vessel expands. |
| 12 | W = 3P0V0/2; temperature rises. |
| 13 | Direct: Q = 5PV/2. Two-step: Q = 3PV/2 + 2PV ln(2). |
| 14 | Gamma = 5/3 |
| 15 | Final temperature equals initial temperature; free expansion is irreversible. |
| 16 | Constant V: 3R dT/2 and 5R dT/2. Constant P: 5R dT/2 and 7R dT/2. |
| 17 | Density ratio = 4^(5/7); temperature ratio = 4^(2/7). |
| 18 | First gas mean free path / second gas mean free path = 4 |
| 19 | Net work = net heat = (P2 - P1)(V2 - V1) |
| 20 | Both statements are true, and the reason correctly explains the assertion. |
