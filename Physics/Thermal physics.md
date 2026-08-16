# IIT JEE Physics — Thermal Physics, Thermodynamics & Kinetic Theory

> High-yield concept revision notes, formulas, JEE traps, and frequently asked question patterns.

## Syllabus Covered

- Thermal expansion of solids, liquids and gases
- Calorimetry
- Latent heat
- Ideal gas laws
- Specific heats: `C_v` and `C_p`
- Monoatomic and diatomic gases
- Isothermal and adiabatic processes
- Bulk modulus of gases
- Equivalence of heat and work
- First law of thermodynamics and its applications to ideal gases
- Mean free path

---

# 1. Thermal Expansion of Solids

## Linear Expansion

$$
\Delta L=L_0\alpha\Delta T
$$

$$
L=L_0(1+\alpha\Delta T)
$$

where `α` is the coefficient of linear expansion.

## Area Expansion

$$
\Delta A=A_0\beta\Delta T
$$

For an isotropic solid:

$$
\boxed{\beta=2\alpha}
$$

## Volume Expansion

$$
\Delta V=V_0\gamma\Delta T
$$

For an isotropic solid:

$$
\boxed{\gamma=3\alpha}
$$

Therefore:

$$
\boxed{\alpha:\beta:\gamma=1:2:3}
$$

## Important JEE Concept — Expansion of a Hole

When a metal plate containing a hole is heated, **the hole also expands**.

Treat the hole as though it were made of the same material as the plate.

## Thermal Stress

If a rod is completely prevented from expanding:

$$
\boxed{\text{Stress}=Y\alpha\Delta T}
$$

and the force developed is

$$
\boxed{F=YA\alpha\Delta T}
$$

where `Y` is Young's modulus.

### Common Question Pattern

A rod is fixed between two rigid walls and heated. Typical questions ask for:

- thermal stress
- compressive force
- force exerted on the walls
- change in temperature required for a specified stress

---

# 2. Thermal Expansion of Liquids

Liquids do not have a fixed shape, so ordinary thermal expansion is considered in terms of **volume expansion**.

## Apparent Expansion

When a liquid is heated inside a container, both the liquid and the container expand.

$$
\boxed{\gamma_{\text{app}}=\gamma_l-\gamma_c}
$$

Hence:

$$
\boxed{\Delta V_{\text{app}}=V_0(\gamma_l-\gamma_c)\Delta T}
$$

### JEE Trap

Actual expansion of the liquid is greater than its apparent expansion when the container also expands.

---

# 3. Anomalous Expansion of Water

Water behaves unusually between `0°C` and `4°C`.

- From `0°C → 4°C`, water **contracts on heating**.
- At `4°C`, water has **maximum density**.

$$
\boxed{\rho_{\max}=\rho(4^\circ C)}
$$

### Winter-Lake Concept

During winter:

1. Surface water cools.
2. Water reaching `4°C` becomes denser and sinks.
3. Water below `4°C` becomes less dense and remains near the surface.
4. Ice forms at the surface.
5. The lower water remains comparatively warmer, allowing aquatic life to survive.

---

# 4. Calorimetry

## Heat Required to Change Temperature

$$
\boxed{Q=mc\Delta T}
$$

where `c` is the specific heat capacity.

## Heat Capacity

$$
\boxed{C=mc}
$$

Therefore:

$$
\boxed{Q=C\Delta T}
$$

## Principle of Calorimetry

For an isolated system:

$$
\boxed{\text{Heat lost}=\text{Heat gained}}
$$

or

$$
\boxed{\sum Q=0}
$$

## Mixing Problems

If a hot body at `T₁` is mixed with a colder body at `T₂`:

$$
\boxed{m_1c_1(T_1-T_f)=m_2c_2(T_f-T_2)}
$$

assuming `T₁ > T_f > T₂` and no heat is lost to the surroundings.

### JEE Strategy

Before writing an equation, identify:

- Who loses heat?
- Who gains heat?
- Is there a phase change?
- Does the calorimeter absorb heat?

---

# 5. Latent Heat

During a phase change, temperature remains constant while heat is supplied or removed.

$$
\boxed{Q=mL}
$$

## Latent Heat of Fusion

$$
\boxed{Q=mL_f}
$$

## Latent Heat of Vaporisation

$$
\boxed{Q=mL_v}
$$

## Multi-stage Heating Problems

For a process such as ice below `0°C → water → steam`, calculate heat stage-by-stage:

$$
Q=mc_{ice}\Delta T+mL_f+mc_{water}\Delta T+mL_v+mc_{steam}\Delta T
$$

Only include stages that actually occur.

### Common JEE Pattern

Ice at a negative temperature is mixed with water or steam. Determine the final state by checking sequentially whether enough heat is available to:

1. Bring ice to `0°C`.
2. Melt the ice.
3. Heat the resulting water.
4. Vaporise water if enough heat remains.

---

# 6. Ideal Gas Law

The ideal gas equation is:

$$
\boxed{PV=nRT}
$$

Alternative molecular form:

$$
\boxed{PV=Nk_BT}
$$

and

$$
\boxed{R=N_Ak_B}
$$

where:

- `P` = pressure
- `V` = volume
- `n` = number of moles
- `R` = universal gas constant
- `T` = absolute temperature
- `N` = number of molecules
- `k_B` = Boltzmann constant

## Combined Gas Equation

For fixed number of moles:

$$
\boxed{\frac{P_1V_1}{T_1}=\frac{P_2V_2}{T_2}}
$$

### Critical Reminder

Always use **Kelvin** in gas-law equations:

$$
\boxed{T(K)=T(^\circ C)+273.15}
$$

Never substitute Celsius directly into `PV=nRT`.

---

# 7. Gas Laws

## Boyle's Law

At constant temperature:

$$
\boxed{PV=\text{constant}}
$$

## Charles' Law

At constant pressure:

$$
\boxed{\frac{V}{T}=\text{constant}}
$$

## Pressure Law

At constant volume:

$$
\boxed{\frac{P}{T}=\text{constant}}
$$

---

# 8. Specific Heat Capacities — `C_v` and `C_p`

For an ideal gas:

$$
\boxed{C_p-C_v=R}
$$

This is **Mayer's relation**.

The ratio of specific heats is:

$$
\boxed{\gamma=\frac{C_p}{C_v}}
$$

Hence:

$$
\boxed{C_v=\frac{R}{\gamma-1}}
$$

$$
\boxed{C_p=\frac{\gamma R}{\gamma-1}}
$$

---

# 9. Monoatomic Ideal Gas

For a monoatomic gas, the number of active degrees of freedom at ordinary JEE temperatures is:

$$
\boxed{f=3}
$$

Therefore:

$$
\boxed{C_v=\frac{3}{2}R}
$$

$$
\boxed{C_p=\frac{5}{2}R}
$$

$$
\boxed{\gamma=\frac{5}{3}}
$$

Internal energy:

$$
\boxed{U=\frac{3}{2}nRT}
$$

---

# 10. Diatomic Ideal Gas

At ordinary temperatures, a diatomic gas has approximately:

$$
\boxed{f=5}
$$

Therefore:

$$
\boxed{C_v=\frac{5}{2}R}
$$

$$
\boxed{C_p=\frac{7}{2}R}
$$

$$
\boxed{\gamma=\frac{7}{5}}
$$

Internal energy:

$$
\boxed{U=\frac{5}{2}nRT}
$$

### JEE Note

At sufficiently high temperatures, vibrational degrees of freedom can become active. Unless a problem specifically indicates otherwise, standard JEE problems generally use `f = 5` for a diatomic gas.

---

# 11. Internal Energy of an Ideal Gas

For an ideal gas:

$$
\boxed{\Delta U=nC_v\Delta T}
$$

The internal energy of an ideal gas depends **only on temperature**.

### Isothermal Process

$$
\Delta T=0
$$

so

$$
\boxed{\Delta U=0}
$$

### Important Concept

For an ideal gas, internal energy does not directly depend on pressure or volume. If the temperature is unchanged, the internal energy is unchanged.

---

# 12. First Law of Thermodynamics

Using the JEE convention where `W` is work done **by the gas**:

$$
\boxed{Q=\Delta U+W}
$$

or

$$
\boxed{\Delta U=Q-W}
$$

## Work Done by a Gas

$$
\boxed{W=\int_{V_1}^{V_2}P\,dV}
$$

On a `P-V` diagram:

$$
\boxed{W=\text{area under the process curve}}
$$

### Sign Convention

- Expansion: `W > 0`
- Compression: `W < 0`
- Heat supplied to gas: `Q > 0`
- Heat rejected by gas: `Q < 0`

---

# 13. First Law — Special Processes

## Isochoric Process

Volume is constant:

$$
\Delta V=0
$$

Therefore:

$$
\boxed{W=0}
$$

and

$$
\boxed{Q=\Delta U=nC_v\Delta T}
$$

---

## Isobaric Process

Pressure is constant.

Work:

$$
\boxed{W=P(V_2-V_1)}
$$

Using `PV=nRT`:

$$
\boxed{W=nR\Delta T}
$$

Heat supplied:

$$
\boxed{Q=nC_p\Delta T}
$$

Internal-energy change:

$$
\boxed{\Delta U=nC_v\Delta T}
$$

---

# 14. Isothermal Process

For an ideal gas:

$$
T=\text{constant}
$$

Therefore:

$$
\boxed{\Delta U=0}
$$

From the first law:

$$
\boxed{Q=W}
$$

Since `PV = constant`:

$$
\boxed{W=nRT\ln\left(\frac{V_2}{V_1}\right)}
$$

or

$$
\boxed{W=nRT\ln\left(\frac{P_1}{P_2}\right)}
$$

### Expansion

If `V₂ > V₁`:

$$
W>0
$$

### Compression

If `V₂ < V₁`:

$$
W<0
$$

---

# 15. Adiabatic Process

No heat is exchanged:

$$
\boxed{Q=0}
$$

First law gives:

$$
0=\Delta U+W
$$

Therefore:

$$
\boxed{W=-\Delta U}
$$

For an ideal gas:

$$
\boxed{PV^\gamma=\text{constant}}
$$

Other useful forms:

$$
\boxed{TV^{\gamma-1}=\text{constant}}
$$

$$
\boxed{T^\gamma P^{1-\gamma}=\text{constant}}
$$

## Work Done

$$
\boxed{W=\frac{P_1V_1-P_2V_2}{\gamma-1}}
$$

or

$$
\boxed{W=nC_v(T_1-T_2)}
$$

### Important Concept

During adiabatic expansion, the gas does work using its internal energy, so its temperature decreases.

---

# 16. Isothermal vs Adiabatic

| Property | Isothermal | Adiabatic |
|---|---|---|
| Temperature | Constant | Changes |
| Heat exchange | Usually non-zero | `Q = 0` |
| `ΔU` for ideal gas | `0` | Non-zero if `T` changes |
| Equation | `PV = constant` | `PV^γ = constant` |
| Work | `W = Q` | `W = -ΔU` |
| `P-V` curve | Less steep | More steep |

## Important JEE Comparison

For the same initial state and expansion:

$$
\boxed{P_{adiabatic}<P_{isothermal}}
$$

The adiabatic curve is steeper than the isothermal curve.

---

# 17. Bulk Modulus of a Gas

Definition:

$$
\boxed{B=-V\frac{dP}{dV}}
$$

## Isothermal Bulk Modulus

For an isothermal process:

$$
PV=\text{constant}
$$

Therefore:

$$
\boxed{B_T=P}
$$

## Adiabatic Bulk Modulus

For an adiabatic process:

$$
PV^\gamma=\text{constant}
$$

Therefore:

$$
\boxed{B_S=\gamma P}
$$

Hence:

$$
\boxed{B_S>B_T}
$$

and

$$
\boxed{\frac{B_S}{B_T}=\gamma}
$$

---

# 18. Equivalence of Heat and Work

Mechanical work can be converted into thermal energy.

The mechanical equivalent of heat is denoted by `J`:

$$
\boxed{W=JQ}
$$

In SI units:

$$
\boxed{1\text{ cal}\approx4.186\text{ J}}
$$

and

$$
\boxed{1\text{ J}\approx0.239\text{ cal}}
$$

### Concept

Heat is not a material substance. It is energy transferred between systems because of a temperature difference.

---

# 19. Mean Free Path

The **mean free path** is the average distance travelled by a gas molecule between two successive collisions.

$$
\boxed{\lambda=\frac{1}{\sqrt{2}\pi d^2n}}
$$

where:

- `λ` = mean free path
- `d` = molecular diameter
- `n = N/V` = number density

Since

$$
 n=\frac{P}{k_BT}
$$

we obtain:

$$
\boxed{\lambda=\frac{k_BT}{\sqrt{2}\pi d^2P}}
$$

Therefore, for fixed molecular diameter:

$$
\boxed{\lambda\propto\frac{T}{P}}
$$

### Dependence

- Temperature ↑ → mean free path ↑
- Pressure ↑ → mean free path ↓
- Number density ↑ → mean free path ↓
- Molecular diameter ↑ → mean free path decreases as `1/d²`

---

# 20. Master Formula Sheet

| Topic | Formula |
|---|---|
| Linear expansion | `ΔL = L₀αΔT` |
| Area expansion | `ΔA = A₀βΔT` |
| Volume expansion | `ΔV = V₀γΔT` |
| Isotropic solid | `β = 2α`, `γ = 3α` |
| Thermal stress | `Stress = YαΔT` |
| Thermal force | `F = YAαΔT` |
| Apparent liquid expansion | `γ_app = γ_l − γ_c` |
| Calorimetry | `ΣQ = 0` |
| Sensible heat | `Q = mcΔT` |
| Latent heat | `Q = mL` |
| Ideal gas | `PV = nRT` |
| Combined gas law | `P₁V₁/T₁ = P₂V₂/T₂` |
| Mayer relation | `C_p − C_v = R` |
| Ratio of specific heats | `γ = C_p/C_v` |
| Monoatomic `C_v` | `3R/2` |
| Monoatomic `C_p` | `5R/2` |
| Monoatomic `γ` | `5/3` |
| Diatomic `C_v` | `5R/2` |
| Diatomic `C_p` | `7R/2` |
| Diatomic `γ` | `7/5` |
| Internal energy change | `ΔU = nC_vΔT` |
| First law | `Q = ΔU + W` |
| Work | `W = ∫P dV` |
| Isobaric work | `W = nRΔT` |
| Isothermal | `PV = constant` |
| Isothermal work | `W = nRT ln(V₂/V₁)` |
| Adiabatic | `PV^γ = constant` |
| Adiabatic relation | `TV^(γ−1) = constant` |
| Adiabatic work | `W = nC_v(T₁−T₂)` |
| Isothermal bulk modulus | `B_T = P` |
| Adiabatic bulk modulus | `B_S = γP` |
| Mean free path | `λ = 1/(√2πd²n)` |
| Mean free path | `λ = k_BT/(√2πd²P)` |

---

# 21. IIT JEE High-Yield Question Patterns

> The following are **frequently tested question patterns**, not a claim that each item is a verbatim previous-year question.

## Level 1 — Must Be Instant

1. Rod heated → increase in length.
2. Convert linear expansion coefficient into area/volume expansion coefficient.
3. Hole in a heated metal plate.
4. Apparent expansion of liquid in a container.
5. Ice + water calorimetry.
6. Ice + steam calorimetry.
7. Ideal-gas equation using changes in `P`, `V`, and `T`.
8. Find `C_p`, `C_v`, and `γ` for monoatomic/diatomic gases.
9. Calculate internal-energy change.
10. Calculate work in an isobaric process.

## Level 2 — Common JEE Main/Advanced Patterns

11. Isothermal expansion → calculate `Q`, `W`, and `ΔU`.
12. Adiabatic expansion → calculate `T₂`, `P₂`, and `W`.
13. Compare work in isothermal and adiabatic processes.
14. Calculate work from a `P-V` graph.
15. Multi-step thermodynamic cycle → calculate net `W`, `Q`, and `ΔU`.
16. Compare `C_p`, `C_v`, and bulk moduli.
17. Determine `γ` from a thermodynamic process.
18. Adiabatic compression → determine temperature rise.
19. Mean free path after changes in pressure or temperature.
20. Calorimetry combined with phase change.

## Level 3 — IIT JEE Advanced-Style Patterns

21. Two gases separated by a partition and subsequently allowed to interact.
22. Gas undergoes multiple processes on a `P-V` diagram.
23. Compare different paths connecting the same initial and final states.
24. Find `Q`, `W`, and `ΔU` for each path.
25. Thermodynamic cycle with unknown `C_v`, `C_p`, or `γ`.
26. Combination of isothermal and adiabatic processes.
27. Gas mixed with a calorimeter where a phase change occurs.
28. Thermal expansion with mechanical constraints and thermal stress.
29. Apparent liquid expansion with a nontrivial container.
30. Mean free path combined with pressure, temperature, and density changes.

---

# 22. Ten JEE Traps to Never Forget

1. **Use Kelvin**, not Celsius, in gas equations.
2. Heat `Q` is **path dependent**.
3. Work `W` is **path dependent**.
4. Internal energy `U` is a **state function**.
5. For an ideal gas in an isothermal process: `ΔU = 0`.
6. Adiabatic means `Q = 0`, **not** `ΔU = 0`.
7. Adiabatic expansion causes the gas to **cool**.
8. A hole in a heated plate **expands**.
9. Water has **maximum density at 4°C**.
10. The adiabatic `P-V` curve is **steeper** than the isothermal curve.

---

# 23. Six-Step Thermodynamics Problem Strategy

Whenever you see a JEE thermodynamics problem, ask these questions in order:

1. **What process is occurring?**
2. **Is `Q = 0`?**
3. **Is `W = 0`?**
4. **Is temperature constant?**
5. **What happens to `ΔU`?**
6. **Which equation or process relation applies?**

This process-identification approach is often more useful than memorising isolated formulas.

---

# 24. Quick Revision Checklist

- [ ] `β = 2α`, `γ = 3α`
- [ ] Hole expands when plate is heated
- [ ] Thermal stress: `YαΔT`
- [ ] Apparent liquid expansion
- [ ] Water has maximum density at `4°C`
- [ ] `Q = mcΔT`
- [ ] `Q = mL`
- [ ] Principle of calorimetry: `ΣQ = 0`
- [ ] `PV = nRT`
- [ ] Always convert temperature to Kelvin for gas laws
- [ ] `C_p − C_v = R`
- [ ] Monoatomic: `C_v = 3R/2`, `C_p = 5R/2`, `γ = 5/3`
- [ ] Diatomic: `C_v = 5R/2`, `C_p = 7R/2`, `γ = 7/5`
- [ ] `ΔU = nC_vΔT`
- [ ] First law: `Q = ΔU + W`
- [ ] Isothermal: `ΔU = 0`
- [ ] Adiabatic: `Q = 0`
- [ ] Adiabatic: `PV^γ = constant`
- [ ] `B_T = P`
- [ ] `B_S = γP`
- [ ] Mean free path: `λ ∝ T/P`
- [ ] Adiabatic curve is steeper than isothermal

---

## Final One-Line Memory Map

**Expansion → Calorimetry → Phase Change → Gas Law → `C_p/C_v` → First Law → Process Identification → `P-V` Work → Isothermal/Adiabatic → Bulk Modulus → Mean Free Path.**
