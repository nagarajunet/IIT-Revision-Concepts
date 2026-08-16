# IIT Thermal Physics — Key Concepts & Practice

Use SI units throughout. Take \(R=8.314\ \mathrm{J\,mol^{-1}K^{-1}}\), \(k_B=1.38\times10^{-23}\ \mathrm{J\,K^{-1}}\), unless stated otherwise.

## 1. Thermal expansion

For an isotropic solid:

\[
\Delta L=\alpha L\Delta T,\qquad \Delta A=2\alpha A\Delta T,\qquad
\Delta V=\gamma V\Delta T\quad(\gamma\simeq3\alpha)
\]

- A hole expands exactly as if it were made of the removed material.
- For a composite rod with parts in series, total expansion is \(\sum \alpha_iL_i\Delta T\).
- If expansion is prevented, thermal stress is \(Y\alpha\Delta T\); force is \(YA\alpha\Delta T\).
- Apparent expansion of a liquid in a vessel: \(\gamma_{app}=\gamma_{liquid}-\gamma_{vessel}\).
- Water has maximum density at \(4^\circ\mathrm C\); between \(0\) and \(4^\circ\mathrm C\), it contracts when heated.

## 2. Calorimetry and phase change

\[
Q=mc\Delta T,\qquad Q=mL
\]

- In an isolated calorimeter, \(\sum Q=0\): heat lost = heat gained. Include calorimeter water equivalent if supplied.
- During a phase change at constant pressure, temperature remains constant; supplied heat changes internal/potential molecular energy.
- Always track the state sequence (ice → water → steam) before using a single formula.
- Mixing problems can have a final mixture at the melting/boiling point with some phase left over.

## 3. Ideal gas and kinetic theory

\[
PV=nRT=Nk_BT,\qquad \rho=\frac{PM}{RT}
\]

\[
P=\frac13\rho c_{rms}^2,\qquad c_{rms}=\sqrt{\frac{3RT}{M}},
\qquad \overline K=\frac32k_BT
\]

- For a fixed mass: \(PV/T=\text{constant}\). Use kelvin, never Celsius.
- Dalton’s law: \(P=\sum P_i\); each gas obeys \(P_iV=n_iRT\).
- Internal energy of an ideal gas depends only on temperature.

## 4. Specific heats and degrees of freedom

\[
C_V=\frac f2R,\qquad C_P=C_V+R,\qquad \Gamma=\frac{C_P}{C_V}=1+\frac2f
\]

| Gas (ordinary temperature) | \(f\) | \(C_V\) | \(C_P\) | \(\Gamma\) |
|---|---:|---:|---:|---:|
| Monoatomic | 3 | \(3R/2\) | \(5R/2\) | \(5/3\) |
| Diatomic (vibration neglected) | 5 | \(5R/2\) | \(7R/2\) | \(7/5\) |

For \(n\) moles, \(\Delta U=nC_V\Delta T\). At high temperature, vibrational modes may add degrees of freedom; use the value stipulated in the question.

## 5. Work, heat, and the first law

Sign convention used here: \(W\) is work done **by** the gas.

\[
Q=\Delta U+W
\]

| Process | Key relation | \(W\) | \(\Delta U\) for ideal gas |
|---|---|---|---|
| Isochoric | \(V=\) constant | 0 | \(Q=nC_V\Delta T\) |
| Isobaric | \(P=\) constant | \(P\Delta V=nR\Delta T\) | \(nC_V\Delta T\) |
| Isothermal | \(T=\) constant | \(nRT\ln(V_2/V_1)\) | 0, so \(Q=W\) |
| Adiabatic (reversible) | \(Q=0\) | \(-\Delta U\) | \(nC_V\Delta T\) |

For a reversible adiabatic process:

\[
PV^\Gamma=\text{constant},\qquad TV^{\Gamma-1}=\text{constant},\qquad
T^\Gamma P^{1-\Gamma}=\text{constant}
\]

- Area under a \(P\)-\(V\) curve is work done by the gas.
- An adiabatic curve is steeper than an isotherm through the same point.
- Free expansion into vacuum: \(W=Q=0\), hence \(\Delta U=0\); an ideal gas has unchanged temperature. It is irreversible, so do not apply \(PV^\Gamma\)=constant.

## 6. Bulk modulus and speed of sound in gases

\[
B=-V\frac{dP}{dV}
\]

- Isothermal compression of an ideal gas: \(B=P\).
- Adiabatic compression: \(B=\Gamma P\).
- Hence Newton–Laplace speed of sound: \(v=\sqrt{\Gamma P/\rho}=\sqrt{\Gamma RT/M}\).

## 7. Equivalence of heat and work

Heat and mechanical work are two modes of energy transfer. Mechanical equivalent:

\[
1\ \mathrm{cal}\approx4.186\ \mathrm J
\]

For a complete cyclic process, \(\Delta U=0\), therefore net heat supplied equals net work done by the gas: \(Q_{net}=W_{net}\).

## 8. Mean free path

\[
\lambda=\frac{1}{\sqrt2\pi d^2n}=\frac{k_BT}{\sqrt2\pi d^2P}
\]

Here \(d\) is molecular diameter and \(n=N/V\) is number density.

- At fixed \(T\), \(\lambda\propto1/P\). At fixed \(P\), \(\lambda\propto T\).
- Collision frequency per molecule \(z\sim \bar c/\lambda\); mean time between collisions \(\tau=\lambda/\bar c\).

## IIT problem habits / common traps

1. Draw the process on a \(P\)-\(V\) diagram before calculating work.
2. State the system and sign convention. For “work done on gas”, change the sign.
3. Expansion coefficients are small-change relations unless integration/data is given.
4. In calorimetry, test the assumed final state; an assumed all-melted state may be impossible.
5. \(C_P-C_V=R\) is for one mole of an ideal gas; for \(n\) moles use \(nR\).
6. \(PV^\Gamma\) is only for reversible adiabatic changes of an ideal gas.

---

# Practice Questions

## A. Core drills

1. A steel wire of length \(2.0\ \mathrm m\) and area \(1.0\ \mathrm{mm^2}\) is held rigidly between two walls. Given \(Y=2.0\times10^{11}\ \mathrm{Pa}\), \(\alpha=1.2\times10^{-5}\ \mathrm{K^{-1}}\), find the force developed for a rise of \(50\ \mathrm K\).

2. A liquid has real cubical expansion coefficient \(7.2\times10^{-4}\ \mathrm{K^{-1}}\). Its glass vessel has \(\gamma=2.7\times10^{-5}\ \mathrm{K^{-1}}\). Find its apparent coefficient.

3. \(100\ \mathrm g\) ice at \(0^\circ\mathrm C\) is added to \(300\ \mathrm g\) water at \(30^\circ\mathrm C\). Take \(c_w=1\ \mathrm{cal\,g^{-1}\,^\circ C^{-1}}\), \(L_f=80\ \mathrm{cal\,g^{-1}}\). Find the final state.

4. A \(0.50\ \mathrm{kg}\) metal at \(200^\circ\mathrm C\) is dropped into \(1.0\ \mathrm{kg}\) water at \(20^\circ\mathrm C\). Final temperature is \(30^\circ\mathrm C\). Neglect calorimeter heat capacity. Find the metal’s specific heat in \(\mathrm{J\,kg^{-1}K^{-1}}\).

5. A gas has density \(1.25\ \mathrm{kg\,m^{-3}}\) at pressure \(1.0\times10^5\ \mathrm{Pa}\). Find \(c_{rms}\).

6. At what temperature is the rms speed of nitrogen \((M=28\ \mathrm{g\,mol^{-1}})\) equal to \(600\ \mathrm{m\,s^{-1}}\)?

7. Find \(\Delta U\) when 2 mol of a diatomic ideal gas is heated from 300 K to 500 K, with vibrational modes inactive.

8. One mole of monoatomic ideal gas is heated at constant pressure by 100 K. Find \(Q\), \(W\), and \(\Delta U\).

9. Two moles of ideal gas expand isothermally and reversibly at 300 K from 10 L to 20 L. Find work done by the gas.

10. One mole of a monoatomic gas expands adiabatically and reversibly from \(V\) to \(8V\). Find \(T_2/T_1\).

## B. IIT-style conceptual / multi-step

11. A vessel is completely filled with water at \(4^\circ\mathrm C\). It is heated slightly. Will water overflow? Explain using the anomalous expansion of water and expansion of the vessel.

12. An ideal gas follows a straight-line path from \((V_0,P_0)\) to \((2V_0,2P_0)\) on a \(P\)-\(V\) plot. Find the work in terms of \(P_0V_0\), and state whether its temperature rises or falls.

13. One mole of monoatomic gas goes from \((P,V)\) to \((P,2V)\). Compare the heat supplied for (i) the direct isobaric path and (ii) an isochoric heating to \((2P,V)\), followed by isothermal expansion to \((P,2V)\).

14. A gas is compressed adiabatically until its pressure becomes 32 times and its volume becomes \(1/8\) times. Determine \(\Gamma\).

15. A gas is expanded freely into an evacuated chamber of equal volume. For an ideal gas, find the final temperature and explain why the process is not isothermal in the thermodynamic-process sense.

16. At the same \(P,V,T\), compare the energy needed to raise the temperature of 1 mol monoatomic gas and 1 mol diatomic gas by \(\Delta T\) at (i) constant volume and (ii) constant pressure.

17. Air is treated as a diatomic ideal gas. If pressure is quadrupled in an adiabatic compression, find \(\rho_2/\rho_1\) and \(T_2/T_1\).

18. Two gases at the same temperature have molecular diameters \(d\) and \(2d\), and equal pressure. Find \(\lambda_1/\lambda_2\).

19. A gas goes through a clockwise rectangular cycle on a \(P\)-\(V\) diagram, bounded by \(P_1,P_2\) and \(V_1,V_2\). Find net work and net heat.

20. Assertion–Reason: Assertion: \(C_P>C_V\) for an ideal gas. Reason: at constant pressure, some supplied heat performs expansion work. Decide whether each statement is true and whether the reason correctly explains the assertion.

## Answer key

1. \(120\ \mathrm N\) (compressive).
2. \(6.93\times10^{-4}\ \mathrm{K^{-1}}\).
3. Water can give only 9000 cal on cooling to \(0^\circ\mathrm C\); it melts \(112.5\ \mathrm g\) ice, so all ice melts and final temperature is \(2.5^\circ\mathrm C\).
4. \(c_m\approx492\ \mathrm{J\,kg^{-1}K^{-1}}\).
5. \(c_{rms}=490\ \mathrm{m\,s^{-1}}\).
6. \(T\approx404\ \mathrm K\).
7. \(\Delta U=10^3R\approx8.31\ \mathrm{kJ}\).
8. \(Q=\frac52R(100)=2.08\ \mathrm{kJ}\), \(W=0.831\ \mathrm{kJ}\), \(\Delta U=1.25\ \mathrm{kJ}\).
9. \(W=2RT\ln2\approx3.46\ \mathrm{kJ}\).
10. \(T_2/T_1=(1/8)^{2/3}=1/4\).
11. For an infinitesimal rise from \(4^\circ\mathrm C\), the level initially falls: water’s expansion coefficient is zero at \(4^\circ\mathrm C\), while the vessel expands. At a larger rise, overflow depends on the relative volume expansions; numerical coefficients are needed.
12. \(W=\frac32P_0V_0\); \(PV\) increases fourfold, so temperature rises.
13. Direct isobaric: \(Q=5PV/2\). Two-step: \(Q=3PV/2+2PV\ln2\). The two-step path requires more heat; the difference is the larger work done during its isothermal leg.
14. \(32(1/8)^\Gamma=1\Rightarrow\Gamma=5/3\).
15. \(T_f=T_i\); it is irreversible and has no well-defined intermediate equilibrium states.
16. At \(V\): \(3R\Delta T/2\) vs \(5R\Delta T/2\). At \(P\): \(5R\Delta T/2\) vs \(7R\Delta T/2\).
17. \(\rho_2/\rho_1=4^{1/\Gamma}=4^{5/7}\); \(T_2/T_1=4^{(\Gamma-1)/\Gamma}=4^{2/7}\).
18. \(\lambda_1/\lambda_2=4\).
19. \(W_{net}=Q_{net}=(P_2-P_1)(V_2-V_1)\).
20. Both true, and the reason correctly explains the assertion.
