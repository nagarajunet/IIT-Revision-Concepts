# IIT JEE Physics — Cooling Curve & Specific Heat Practicals

> High-yield IIT JEE concepts, formulas, experimental reasoning, graph interpretation, and question patterns for cooling curves, calorimetry, and specific heat capacity by the method of mixtures.

## Topics Covered

- Cooling curve: temperature vs time
- Newton's law of cooling
- Interpretation of cooling-curve slope
- Specific heat capacity of a solid by method of mixtures
- Specific heat capacity of a liquid by method of mixtures
- Calorimeter heat capacity and water equivalent
- Experimental precautions and sources of error
- Cooling correction
- IIT JEE conceptual and numerical question patterns

---

# 1. Cooling Curve — Temperature vs Time

A hot body is allowed to cool in surroundings maintained approximately at constant temperature.

The cooling curve is a plot of:

$$
\boxed{T\text{ vs }t}
$$

The curve is generally **non-linear** and approaches the surrounding temperature asymptotically.

## Newton's Law of Cooling

For a sufficiently small temperature difference between the body and surroundings:

$$
\boxed{-\frac{dT}{dt}\propto(T-T_s)}
$$

or

$$
\boxed{\frac{dT}{dt}=-k(T-T_s)}
$$

where:

- `T` = temperature of the body
- `T_s` = surrounding temperature
- `k` = cooling constant under the given conditions

Therefore:

$$
\boxed{\text{Rate of cooling}\propto\text{temperature difference from surroundings}}
$$

## Integrated Form

$$
\boxed{T-T_s=(T_0-T_s)e^{-kt}}
$$

where `T₀` is the initial temperature.

### Graph Interpretation

- Initially, `T − T_s` is large → cooling is fast.
- Later, `T − T_s` becomes small → cooling becomes slow.
- The magnitude of the slope decreases with time.
- As `T → T_s`, the cooling rate tends to zero.

The slope of a `T-t` graph is:

$$
\boxed{\text{slope}=\frac{dT}{dt}}
$$

So:

$$
\boxed{|dT/dt|\text{ larger}\Rightarrow\text{faster cooling}}
$$

---

# 2. Important Cooling-Curve Concepts

### When is cooling fastest?

When:

$$
\boxed{T-T_s\text{ is maximum}}
$$

For a body initially much hotter than the surroundings, this occurs near the beginning of cooling.

### What happens near room temperature?

As the body approaches room temperature:

$$
T-T_s\rightarrow0
$$

Therefore:

$$
\boxed{\frac{dT}{dt}\rightarrow0}
$$

### Is the cooling curve a straight line?

No. The complete Newton-law cooling curve is exponential.

For a **small temperature interval**, a short portion of the curve may be treated as approximately linear.

---

# 3. Connection Between Cooling Rate and Specific Heat

From:

$$
Q=mc\,dT
$$

and Newton's law of cooling, the cooling rate can be related to heat capacity.

For otherwise identical conditions:

$$
\boxed{\left|\frac{dT}{dt}\right|\propto\frac{T-T_s}{mc}}
$$

Therefore, for equal masses and the same temperature difference:

$$
\boxed{\text{Rate of cooling}\propto\frac1c}
$$

Hence:

- Higher specific heat → slower temperature change.
- Lower specific heat → faster temperature change.

### JEE Comparison Trap

Do **not** say that a body with larger specific heat always cools more slowly without checking the other factors. Cooling also depends on mass, surface area, emissivity, temperature difference, and surrounding conditions.

---

# 4. Specific Heat Capacity

The specific heat capacity `c` is defined by:

$$
\boxed{Q=mc\Delta T}
$$

Therefore:

$$
\boxed{c=\frac{Q}{m\Delta T}}
$$

SI unit:

$$
\boxed{J\,kg^{-1}K^{-1}}
$$

It is the heat required to raise the temperature of unit mass of a substance by one kelvin.

## Heat Capacity

For a body of mass `m`:

$$
\boxed{C=mc}
$$

and

$$
\boxed{Q=C\Delta T}
$$

### Difference

| Quantity | Meaning | Formula | SI unit |
|---|---|---|---|
| Specific heat `c` | Heat capacity per unit mass | `Q = mcΔT` | `J kg⁻¹ K⁻¹` |
| Heat capacity `C` | Heat required per kelvin for the whole body | `Q = CΔT` | `J K⁻¹` |

---

# 5. Method of Mixtures — Core Principle

The method of mixtures is based on conservation of energy.

For an approximately isolated calorimeter:

$$
\boxed{\text{Heat lost} = \text{Heat gained}}
$$

or:

$$
\boxed{\sum Q=0}
$$

### Always identify first

1. Which object is initially hotter?
2. Which object loses heat?
3. Which objects gain heat?
4. Does the calorimeter absorb heat?
5. Is there a phase change?

Only then write the heat-balance equation.

---

# 6. Specific Heat of a Solid by Method of Mixtures

A solid of known mass is heated to a known temperature and then transferred quickly into a calorimeter containing water.

The hot solid loses heat and the water + calorimeter gain heat.

Let:

- `m_s` = mass of solid
- `c_s` = specific heat of solid
- `T_s` = initial temperature of solid
- `m_w` = mass of water
- `c_w` = specific heat of water
- `T_w` = initial temperature of water
- `T_f` = final equilibrium temperature
- `C_cal` = heat capacity of calorimeter

Then:

$$
\boxed{
 m_sc_s(T_s-T_f)
=(m_wc_w+C_{cal})(T_f-T_w)
}
$$

Therefore:

$$
\boxed{
 c_s=
\frac{(m_wc_w+C_{cal})(T_f-T_w)}
{m_s(T_s-T_f)}
}
$$

## If calorimeter heat capacity is negligible

$$
\boxed{
 c_s=
\frac{m_wc_w(T_f-T_w)}
{m_s(T_s-T_f)}
}
$$

---

# 7. Water Equivalent of a Calorimeter

The calorimeter itself absorbs heat and must often be included.

If its heat capacity is `C_cal`, its water equivalent is:

$$
\boxed{W=\frac{C_{cal}}{c_w}}
$$

If `W` is expressed as an equivalent mass of water, then:

$$
\boxed{C_{cal}=Wc_w}
$$

The heat gained by water + calorimeter is then:

$$
\boxed{Q=(m_w+W)c_w\Delta T}
$$

Thus the solid formula becomes:

$$
\boxed{
 c_s=
\frac{(m_w+W)c_w(T_f-T_w)}
{m_s(T_s-T_f)}
}
$$

### JEE Trap

Do not confuse:

- actual mass of the calorimeter
- heat capacity of the calorimeter
- water equivalent of the calorimeter

They are different quantities.

---

# 8. Specific Heat of a Liquid by Method of Mixtures

A known mass of hot liquid is mixed with water in a calorimeter.

Let:

- `m_l` = mass of liquid
- `c_l` = specific heat of liquid
- `T_l` = initial temperature of liquid
- `m_w` = mass of water
- `c_w` = specific heat of water
- `T_w` = initial temperature of water
- `T_f` = final temperature
- `C_cal` = heat capacity of calorimeter

Heat lost by hot liquid:

$$
Q_l=m_lc_l(T_l-T_f)
$$

Heat gained by water + calorimeter:

$$
Q_w+Q_{cal}=(m_wc_w+C_{cal})(T_f-T_w)
$$

Hence:

$$
\boxed{
 m_lc_l(T_l-T_f)
=(m_wc_w+C_{cal})(T_f-T_w)
}
$$

Therefore:

$$
\boxed{
 c_l=
\frac{(m_wc_w+C_{cal})(T_f-T_w)}
{m_l(T_l-T_f)}
}
$$

If water equivalent `W` is given:

$$
\boxed{
 c_l=
\frac{(m_w+W)c_w(T_f-T_w)}
{m_l(T_l-T_f)}
}
$$

---

# 9. Why Is Stirring Done?

The mixture is stirred to:

- distribute heat uniformly
- reduce temperature gradients
- bring the contents close to thermal equilibrium
- ensure the thermometer reads a representative temperature

### Important

Stirring does **not** supply the heat being measured. It helps establish uniform temperature.

---

# 10. Why Is a Calorimeter Used?

A calorimeter provides an approximately insulated environment so that heat exchange with the surroundings is minimized.

Typical design aims are:

- minimize heat loss
- obtain thermal equilibrium quickly
- maintain nearly uniform temperature
- allow accurate temperature measurement

A lid reduces heat exchange and evaporation.

---

# 11. Experimental Procedure — Solid by Method of Mixtures

1. Measure the mass of the solid.
2. Heat the solid to a known temperature.
3. Measure a known mass of water in the calorimeter.
4. Record the initial temperature of water.
5. Transfer the hot solid quickly into the calorimeter.
6. Cover the calorimeter.
7. Stir gently and continuously.
8. Record the equilibrium/final temperature.
9. Apply heat balance.
10. Calculate the specific heat of the solid.

### Key Experimental Requirement

The hot solid should be transferred **quickly** to reduce heat loss to the surroundings before mixing.

---

# 12. Experimental Procedure — Liquid by Method of Mixtures

1. Measure the mass of the liquid.
2. Heat the liquid to a known temperature.
3. Measure water and its initial temperature.
4. Transfer the hot liquid rapidly to the calorimeter.
5. Cover the calorimeter.
6. Stir to obtain uniform temperature.
7. Record the final equilibrium temperature.
8. Include calorimeter heat capacity/water equivalent.
9. Apply conservation of energy.
10. Calculate the specific heat of the liquid.

---

# 13. Cooling Correction ⭐⭐⭐⭐⭐

In a real experiment, the mixture may continue to exchange heat with the surroundings while its temperature is being measured.

Therefore the observed maximum temperature may not be the ideal equilibrium temperature for a perfectly insulated system.

A **cooling curve** can be used to estimate the corrected temperature.

### Concept

1. Record temperature against time before/around the experiment.
2. Plot the cooling curve.
3. Extend/extrapolate the appropriate cooling curve to the effective mixing time.
4. Obtain a corrected final temperature.
5. Use the corrected temperature in the heat-balance equation.

### JEE Advanced Insight

If a problem gives a cooling curve and asks for a corrected temperature, do not automatically use the thermometer's maximum observed temperature. Interpret the graph first.

---

# 14. Major Sources of Experimental Error

### Heat loss to surroundings

Causes the observed result to differ from the ideal heat-balance calculation.

### Heat absorbed by calorimeter

Ignoring it when it is significant gives an incorrect specific heat.

### Heat loss during transfer

Especially important for a hot solid or hot liquid transferred from another vessel.

### Non-uniform temperature

Solved approximately by proper stirring.

### Thermometer error

Affects the measured initial and final temperatures.

### Evaporation

Can cause both mass and heat-transfer errors, especially with hot liquids.

---

# 15. IIT JEE Question Patterns — Cooling Curve

## Q1. Cooling rate

A body cools according to Newton's law. What happens to the rate of cooling as its temperature approaches room temperature?

### Answer

It decreases because:

$$
\boxed{\left|\frac{dT}{dt}\right|\propto(T-T_s)}
$$

and `T − T_s` decreases.

---

## Q2. Compare two bodies

Two bodies of equal mass and equal surface area are at the same temperature above the surroundings. Body A has larger specific heat than body B. Which has the greater magnitude of cooling rate under otherwise identical conditions?

### Answer

Body B, because:

$$
\boxed{\left|\frac{dT}{dt}\right|\propto\frac1c}
$$

for equal mass under identical cooling conditions.

---

## Q3. Cooling curve slope

What physical quantity is represented by the slope of a temperature-time graph?

### Answer

$$
\boxed{\frac{dT}{dt}}
$$

Its magnitude gives the instantaneous rate of temperature change.

---

## Q4. Same final temperature

A body cools from `90°C` toward surroundings at `30°C`. Is the rate of cooling the same at `90°C` and `40°C`?

### Answer

No.

At `90°C`:

$$
T-T_s=60^\circ C
$$

At `40°C`:

$$
T-T_s=10^\circ C
$$

Therefore the initial cooling rate is much greater.

---

# 16. IIT JEE Question Patterns — Method of Mixtures

## Q5. Basic solid problem

A hot metal of mass `m_s` at `T_s` is placed in water of mass `m_w` at `T_w`. Final temperature is `T_f`. Neglect calorimeter heat capacity. Find `c_s`.

### Key equation

$$
\boxed{
 m_sc_s(T_s-T_f)=m_wc_w(T_f-T_w)
}
$$

---

## Q6. Calorimeter correction

If the calorimeter has water equivalent `W`, what changes?

### Answer

Replace the water mass in the heat-gain term by:

$$
\boxed{m_w+W}
$$

Thus:

$$
\boxed{
 m_sc_s(T_s-T_f)=(m_w+W)c_w(T_f-T_w)
}
$$

---

## Q7. Final temperature range

A hot substance and a colder substance are mixed in an isolated calorimeter without a phase change. Where must the final temperature lie?

### Answer

Between the two initial temperatures:

$$
\boxed{T_{cold}<T_f<T_{hot}}
$$

---

## Q8. Liquid specific heat

A hot liquid is mixed with cooler water in a calorimeter. Which equation should be used?

### Answer

$$
\boxed{
 m_lc_l(T_l-T_f)
=(m_wc_w+C_{cal})(T_f-T_w)
}
$$

---

## Q9. Negligible calorimeter

If the problem explicitly states that the calorimeter has negligible heat capacity, what happens?

### Answer

Set:

$$
\boxed{C_{cal}=0}
$$

and remove its heat-gain term.

---

## Q10. Phase change added to calorimetry

If the solid melts during the experiment, is `Q=mcΔT` alone sufficient?

### Answer

No. Include latent heat:

$$
\boxed{Q=mL}
$$

in addition to sensible heat terms.

---

# 17. IIT JEE Advanced-Level Thinking

### Problem Pattern 1 — Cooling curve + mixture

A hot solid is transferred into a calorimeter, and the temperature-time data are supplied. Determine the corrected final temperature before calculating its specific heat.

**Key idea:** The thermometer reading may need a cooling correction.

### Problem Pattern 2 — Two bodies with different specific heats

Bodies have different masses, surface areas, and specific heats. Compare their cooling rates.

**Key idea:** Do not compare `c` alone. Consider the full heat-capacity and heat-transfer relation.

### Problem Pattern 3 — Calorimeter included

The calorimeter has known heat capacity. Find the unknown specific heat.

**Key idea:** Include:

$$
Q_{cal}=C_{cal}\Delta T
$$

### Problem Pattern 4 — Heat loss during transfer

A hot body loses some heat before entering the calorimeter.

**Key idea:** The actual heat available to the mixture is less than the initial heat calculated from its original temperature.

### Problem Pattern 5 — Mixture + phase change

A hot body transfers enough energy to melt ice or cause vaporisation.

**Key idea:** Break the process into stages and include both:

$$
Q=mc\Delta T
$$

and

$$
Q=mL
$$

---

# 18. 15 Must-Remember JEE Traps

1. **Specific heat `c` is not heat capacity `C`.**
2. `C = mc`.
3. Cooling rate is not determined by temperature alone.
4. Newton's cooling law is valid in its usual simple form for relatively small temperature differences.
5. A complete cooling curve is generally exponential.
6. The slope of a `T-t` graph is `dT/dt`.
7. Larger `|dT/dt|` means faster cooling.
8. As `T → T_s`, the cooling rate approaches zero.
9. Calorimeter can absorb heat.
10. Water equivalent is not the actual mass of the calorimeter.
11. Stirring produces uniform temperature; it does not create heat.
12. A lid reduces heat exchange and evaporation.
13. Hot objects should be transferred quickly.
14. In an ideal mixture, heat lost = heat gained.
15. If a cooling curve is supplied, check whether a **cooling correction** is required before using the final temperature.

---

# 19. Master Formula Sheet

| Concept | Formula |
|---|---|
| Sensible heat | `Q = mcΔT` |
| Heat capacity | `C = mc` |
| Calorimetry | `ΣQ = 0` |
| Heat balance | `Heat lost = Heat gained` |
| Newton cooling | `−dT/dt = k(T − T_s)` |
| Integrated cooling | `T − T_s = (T₀ − T_s)e^(−kt)` |
| Solid method of mixtures | `m_s c_s(T_s−T_f) = (m_w c_w+C_cal)(T_f−T_w)` |
| Liquid method of mixtures | `m_l c_l(T_l−T_f) = (m_w c_w+C_cal)(T_f−T_w)` |
| Water equivalent | `W = C_cal/c_w` |
| Calorimeter heat | `Q_cal = C_cal ΔT` |
| With water equivalent | `Q_water+cal = (m_w+W)c_wΔT` |
| Latent heat | `Q = mL` |

---

# 20. One-Minute Revision

### Cooling Curve

$$
\boxed{\text{Cooling rate}\propto(T-T_s)}
$$

### Specific Heat

$$
\boxed{Q=mc\Delta T}
$$

### Method of Mixtures

$$
\boxed{\text{Heat lost} = \text{Heat gained}}
$$

### Calorimeter

$$
\boxed{Q_{cal}=C_{cal}\Delta T}
$$

### Water Equivalent

$$
\boxed{W=C_{cal}/c_w}
$$

### Cooling Correction

**Observed maximum temperature may need correction because the calorimeter is not perfectly isolated.**

---

# Final IIT JEE Memory Map

**Cooling curve → slope = `dT/dt` → Newton cooling → heat capacity → `Q=mcΔT` → heat balance → calorimeter correction → water equivalent → specific heat of solid/liquid → cooling correction → graph-based Advanced questions.**
