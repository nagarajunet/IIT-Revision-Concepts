# IIT JEE Mathematics — Area Under Curves & Definite Integral

> **JEE Main + JEE Advanced revision notes** covering graph interpretation, area under curves, area between curves, sign changes, parameter problems, minimum-area problems, translated curves, closed curves, parametric equations, and regions defined by inequalities.

---

## Topics Covered

- Drawing and interpreting graphs for area problems
- Area under a curve using definite integrals
- Area under linear curves and trapezoids
- Area bounded by a function that changes sign
- Area between two non-intersecting curves
- Area between two intersecting curves
- Multiple intersections and changing upper/lower curves
- Determination of parameters from area conditions
- Least/maximum area problems
- Shifting/translation of origin
- Area bounded by closed curves such as circles and ellipses
- Area of curves given by parametric equations
- Area of regions described by inequalities
- Choosing `dx` versus `dy`
- Symmetry shortcuts
- JEE Main and JEE Advanced corner cases

---

# 1. Fundamental Concept — Area as a Definite Integral

If `f(x) >= 0` on `[a,b]`, the geometrical area between the curve `y=f(x)` and the x-axis is

$$
\boxed{A=\int_a^b f(x)\,dx}
$$

The definite integral is fundamentally a **signed area**.

- Region above the x-axis contributes positively.
- Region below the x-axis contributes negatively.

Therefore, for geometrical area,

$$
\boxed{A=\int_a^b |f(x)|\,dx}
$$

when the curve crosses the x-axis.

### JEE Warning

Do not automatically call `∫f(x)dx` an area. First check whether the function changes sign.

---

# 2. Graph-First Strategy

Before integrating, sketch the important boundaries.

For an area problem, identify:

1. The curves.
2. The coordinate axes, if involved.
3. Vertical or horizontal boundaries.
4. Intersection points.
5. Roots/sign changes.
6. Which curve is upper/lower or right/left.
7. Symmetry.

### Universal JEE Workflow

$$
\boxed{\text{DRAW}\rightarrow\text{INTERSECT}\rightarrow\text{SIGN}\rightarrow\text{CHOOSE }dx/dy\rightarrow\text{SYMMETRY}\rightarrow\text{INTEGRATE}}
$$

Most errors in area questions come from incorrect limits or incorrect curve ordering rather than difficult integration.

---

# 3. Area Under a Curve

For `y=f(x)` between `x=a` and `x=b`, if `f(x)>=0`,

$$
\boxed{A=\int_a^b f(x)\,dx}
$$

If the curve is below the x-axis throughout,

$$
\boxed{A=-\int_a^b f(x)\,dx}
$$

More generally,

$$
\boxed{A=\int_a^b|f(x)|\,dx}
$$

---

# 4. Function Changes Sign — Split the Integral

Suppose `f(x)=0` at `x=c`, and the function changes sign there.

If

$$
f(x)<0\quad(a<x<c)
$$

and

$$
f(x)>0\quad(c<x<b),
$$

then

$$
\boxed{
A=-\int_a^c f(x)\,dx+\int_c^b f(x)\,dx
}
$$

### Example Pattern

For

$$
f(x)=(x-1)(x-3),
$$

roots are `1` and `3`.

Its sign changes across these roots, so an area integral over an interval containing them must be split at `x=1` and `x=3`.

### Corner Case

If a root has an **even multiplicity**, the function may touch the axis without changing sign. Splitting at such a point is not mathematically harmful, but the sign need not reverse.

---

# 5. Area Between Two Curves

For

$$
y=f(x),\qquad y=g(x),
$$

using vertical strips,

$$
\boxed{A=\int_a^b|f(x)-g(x)|\,dx}
$$

If `f(x)` is above `g(x)` throughout `[a,b]`,

$$
\boxed{A=\int_a^b[f(x)-g(x)]\,dx}
$$

### Rule

$$
\boxed{\text{Area}=\int(\text{upper curve}-\text{lower curve})\,dx}
$$

---

# 6. Two Non-Intersecting Curves

Suppose the curves do not intersect in the required interval and the boundaries are explicitly given as

$$
a\le x\le b.
$$

Then intersection is not necessary to determine the limits.

If `g(x)>f(x)`,

$$
\boxed{A=\int_a^b[g(x)-f(x)]\,dx}
$$

### JEE Trap

Do not unnecessarily solve `f(x)=g(x)` when the problem already gives vertical boundaries.

---

# 7. Two Intersecting Curves

For intersecting curves,

$$
y=f(x),\qquad y=g(x),
$$

first solve

$$
\boxed{f(x)=g(x)}
$$

to obtain candidate limits.

Then determine which curve is above the other.

Finally,

$$
\boxed{A=\int_a^b|f(x)-g(x)|\,dx}
$$

### Standard Example Pattern

For

$$
y=x^2,\qquad y=2x,
$$

intersections satisfy

$$
x^2=2x
$$

so

$$
x=0,2.
$$

Between these points,

$$
2x>x^2.
$$

Therefore,

$$
A=\int_0^2(2x-x^2)\,dx.
$$

---

# 8. Multiple Intersections

This is a common JEE Advanced corner case.

If two curves intersect at

$$
x=a,b,c,
$$

and the upper/lower curve changes between intervals, the total area must be split.

For example,

$$
A=\int_a^b|f-g|\,dx+\int_b^c|f-g|\,dx.
$$

### Important

Never assume that one curve remains above the other throughout the whole interval when there are multiple intersections.

---

# 9. Area Using `dy`

When horizontal strips are more convenient,

$$
\boxed{A=\int_c^d(x_{\text{right}}-x_{\text{left}})\,dy}
$$

For example, for

$$
x=y^2,\qquad x=4,
$$

use horizontal strips:

$$
A=\int_{-2}^{2}(4-y^2)\,dy.
$$

### JEE Strategy

Choose the direction that avoids unnecessary splitting or complicated inverses.

---

# 10. Area of Linear Curves — Triangle and Trapezoid

For a straight line

$$
y=mx+c,
$$

between `x=a` and `x=b`,

$$
A=\int_a^b(mx+c)\,dx.
$$

Hence,

$$
\boxed{A=\frac m2(b^2-a^2)+c(b-a)}
$$

However, if the region is visibly a triangle or trapezoid, geometry is usually faster.

### Triangle

$$
\boxed{A=\frac12bh}
$$

### Trapezoid

$$
\boxed{A=\frac12(a+b)h}
$$

### JEE Insight

Do not integrate a straight-line region automatically. Recognize standard geometry first.

---

# 11. Symmetry Properties

## Even Function

If

$$
f(-x)=f(x),
$$

then

$$
\boxed{\int_{-a}^{a}f(x)\,dx=2\int_0^a f(x)\,dx}
$$

## Odd Function

If

$$
f(-x)=-f(x),
$$

then

$$
\boxed{\int_{-a}^{a}f(x)\,dx=0}
$$

### Critical Corner Case

An odd function can have zero definite integral but non-zero geometrical area.

For example,

$$
\int_{-2}^{2}x\,dx=0,
$$

but total geometrical area is

$$
2\int_0^2x\,dx.
$$

---

# 12. Area Bounded by Coordinate Axes

For a region bounded by the curve `y=f(x)`, x-axis, and y-axis:

1. Set `x=0`.
2. Solve `f(x)=0` for the relevant x-intercept.
3. Confirm the sign of `f(x)`.
4. Integrate over the correct interval.

If the positive region runs from `0` to `a`,

$$
\boxed{A=\int_0^a f(x)\,dx}
$$

when `f(x)>=0`.

---

# 13. Area of a Parabola and Common Polynomial Regions

For

$$
y=ax^2+bx+c,
$$

first identify:

- roots
- vertex
- axis of symmetry
- sign in the required interval

Then determine whether the area is best evaluated directly, by symmetry, or by geometry.

### Useful Symmetry

For an even function,

$$
\boxed{\int_{-a}^{a}f(x)dx=2\int_0^af(x)dx}
$$

For translated symmetry about `x=h`, use a shift of variable (see Section 18).

---

# 14. Area of Circle

For

$$
x^2+y^2=r^2,
$$

the enclosed area is

$$
\boxed{A=\pi r^2}.
$$

Use the standard formula instead of integration whenever the entire circle is bounded.

---

# 15. Area of Ellipse

For

$$
\frac{x^2}{a^2}+\frac{y^2}{b^2}=1,
$$

the enclosed area is

$$
\boxed{A=\pi ab}.
$$

The semi-major and semi-minor axes are `a` and `b` (their geometric roles may be interchanged).

### Integral Derivation

Upper half:

$$
y=b\sqrt{1-\frac{x^2}{a^2}}.
$$

Therefore,

$$
A=2\int_{-a}^{a}b\sqrt{1-\frac{x^2}{a^2}}\,dx
$$

and symmetry gives

$$
A=4b\int_0^a\sqrt{1-\frac{x^2}{a^2}}\,dx.
$$

Using

$$
x=a\sin\theta,
$$

results in

$$
\boxed{A=\pi ab}.
$$

---

# 16. Standard Closed Curves

For a closed region, first check whether it matches a standard figure:

| Region | Area |
|---|---:|
| Circle | `\pi r^2` |
| Ellipse | `\pi ab` |
| Triangle | `\frac12bh` |
| Trapezoid | `\frac12(a+b)h` |
| Rectangle | `bh` |

For non-standard closed curves, use integration or a suitable parametric/line-integral method.

---

# 17. Determination of Parameters From Area

A parameter may occur in the function and therefore affect:

- roots
- intersection points
- the sign of the function
- the limits of integration
- the final area

### Standard Procedure

1. Write the function containing the parameter.
2. Find intersections or roots.
3. Determine the ordering of roots.
4. Determine the sign of the function.
5. Write the geometrical area.
6. Equate it to the given area.
7. Solve for the parameter.
8. Check whether the parameter satisfies all restrictions.

### Example Pattern

For

$$
y=x^2+\lambda x=x(x+\lambda),
$$

roots are

$$
x=0,\qquad x=-\lambda.
$$

The limits depend on `\lambda`, so the area equation must also reflect the parameter-dependent interval.

### Corner Case

A parameter can change the number of real intersections. In that situation, the problem must be solved in separate parameter ranges.

---

# 18. Shifting the Origin / Translation of Curves

For a translated curve, use

$$
\boxed{X=x-h,\qquad Y=y-k}
$$

or equivalently

$$
\boxed{x=X+h,\qquad y=Y+k}.
$$

Example:

$$
y=(x-2)^2+3.
$$

Put

$$
X=x-2,\qquad Y=y-3.
$$

Then

$$
Y=X^2.
$$

The translated parabola becomes the standard parabola.

### Key Fact

Translation does not change area:

$$
\boxed{A_{\text{original}}=A_{\text{translated}}}
$$

### JEE Use

Shifting is especially effective when the curve has symmetry about

$$
x=h
$$

or

$$
y=k.
$$

---

# 19. Symmetry About a Shifted Axis

If a curve is symmetric about `x=h`, set

$$
X=x-h.
$$

Then a symmetric interval

$$
h-a\le x\le h+a
$$

becomes

$$
-a\le X\le a.
$$

If the transformed function is even,

$$
\boxed{A=2\int_0^a f(X)\,dX}.
$$

This is a powerful JEE Advanced simplification.

---

# 20. Least / Minimum Area Problems

Suppose area depends on a variable parameter:

$$
A=A(t).
$$

Candidate extrema satisfy

$$
\boxed{\frac{dA}{dt}=0}.
$$

For a local minimum,

$$
\boxed{\frac{d^2A}{dt^2}>0}
$$

is a sufficient second-derivative test.

But for JEE problems, also inspect the allowed boundary values.

### Correct Optimization Checklist

1. Determine the domain of the parameter.
2. Obtain `A(t)`.
3. Find stationary points.
4. Check whether they lie in the allowed domain.
5. Compare stationary and boundary values.

### Important Corner Case

A stationary point is not automatically the global minimum.

---

# 21. Intercept-Form Minimum/Maximum Area Models

A line with positive intercepts can be written as

$$
\frac{x}{a}+\frac{y}{b}=1.
$$

The coordinate-axis triangle has area

$$
\boxed{A=\frac12ab}.
$$

If an additional constraint gives a relation between `a` and `b`, substitute that relation into `A` and optimize.

### AM-GM Warning

If

$$
a+b=k,
$$

AM-GM gives

$$
ab\le\frac{(a+b)^2}{4}.
$$

Hence it gives an **upper bound** on `ab`, so in this particular constraint it leads to a maximum triangle area, not automatically a minimum.

Always identify what quantity is being minimized/maximized and whether the feasible set is bounded.

---

# 22. Parametric Equations — Basic Area Formula

If

$$
x=x(t),\qquad y=y(t),
$$

then

$$
dx=\frac{dx}{dt}\,dt.
$$

Therefore,

$$
\boxed{
A=\int y\,dx
=\int_{t_1}^{t_2}y(t)\frac{dx}{dt}\,dt
}
$$

provided the region and orientation are interpreted correctly.

### Essential Steps

1. Find the parameter interval.
2. Determine `x(t)` and `y(t)`.
3. Calculate `dx/dt`.
4. Substitute into `∫y dx`.
5. Check orientation/sign.
6. Convert signed result to geometrical area when required.

---

# 23. Closed Parametric Curves

For a closed parametric curve, area can be expressed as a line integral.

A useful form is

$$
\boxed{A=\left|\oint y\,dx\right|}
$$

with the absolute value accounting for orientation/sign.

Another standard form is

$$
\boxed{
A=\frac12\left|\oint(x\,dy-y\,dx)\right|
}
$$

For a positively oriented simple closed curve, the latter equals the enclosed geometrical area.

### Orientation Corner Case

Reversing the parameter direction changes the sign of the line integral but not the geometrical area.

---

# 24. Parametric Ellipse

For

$$
x=a\cos t,\qquad y=b\sin t,
$$

we have

$$
\frac{dx}{dt}=-a\sin t.
$$

Thus

$$
A=\left|\int_0^{2\pi}y\frac{dx}{dt}\,dt\right|
$$

which gives

$$
\boxed{A=\pi ab}.
$$

This is an important example connecting parametric integration with the standard ellipse formula.

---

# 25. Regions Given by Inequalities

Inequalities often define a region directly.

### Vertical-Strip Form

If

$$
f(x)\le y\le g(x),
$$

then the region exists where

$$
f(x)\le g(x).
$$

Its area is

$$
\boxed{A=\int[g(x)-f(x)]\,dx}.
$$

### Example Pattern

For

$$
x^2\le y\le4,
$$

we need

$$
x^2\le4
$$

so

$$
-2\le x\le2.
$$

Then

$$
\boxed{A=\int_{-2}^{2}(4-x^2)\,dx}.
$$

---

# 26. Inequalities in `x` — Horizontal Strips

If

$$
f(y)\le x\le g(y),
$$

then the region area is

$$
\boxed{A=\int[g(y)-f(y)]\,dy}.
$$

Interpretation:

$$
\boxed{\text{Area}=\int(\text{right boundary}-\text{left boundary})\,dy}
$$

This is particularly useful for sideways parabolas and inequalities involving `x`.

---

# 27. Absolute-Value Area Problems

For

$$
A=\int_a^b|f(x)-g(x)|\,dx,
$$

first solve

$$
f(x)-g(x)=0.
$$

Create a sign chart across the roots, then remove the modulus interval by interval.

### General Pattern

If the sign is `+,-,+`, then

$$
\boxed{
A=\int_{a}^{c_1}(f-g)dx
-\int_{c_1}^{c_2}(f-g)dx
+\int_{c_2}^{b}(f-g)dx
}
$$

### Corner Case

Do not assume every root causes a sign reversal. Check the multiplicity/sign chart.

---

# 28. Three or More Curves

Suppose the region involves

$$
y=f(x),\quad y=g(x),\quad y=h(x).
$$

The upper and lower boundaries may change from one interval to another.

### Procedure

1. Find all relevant pairwise intersections.
2. Sort the x-values.
3. Test one point in each interval.
4. Determine the top and bottom boundary in each interval.
5. Split the integral accordingly.

### JEE Advanced Trap

The phrase “bounded by three curves” does not imply that a single pair of curves bounds the region everywhere.

---

# 29. Area Ratios

JEE problems frequently ask for ratios rather than absolute areas.

If two regions share a common strip and differ only in height, compare the integrands directly before performing complete calculations.

Useful idea:

$$
\boxed{\frac{A_1}{A_2}=\frac{\int f_1(x)dx}{\int f_2(x)dx}}
$$

when the same limits and setup apply.

Symmetry can make the ratio immediate.

---

# 30. Common JEE Corner Cases

## Corner Case 1 — Integral is zero

`∫f(x)dx=0` does not imply geometrical area is zero.

Typical reason: positive and negative areas cancel.

---

## Corner Case 2 — Curve crosses the axis

Split at every relevant sign-change point.

---

## Corner Case 3 — Curves intersect more than twice

Split wherever the upper/lower relation changes.

---

## Corner Case 4 — Parameter changes the limits

Do not treat the limits as constants when they depend on the parameter.

---

## Corner Case 5 — Parameter changes the number of intersections

Use separate cases for different parameter ranges.

---

## Corner Case 6 — `dx` is complicated

Try `dy`.

---

## Corner Case 7 — `dy` is complicated

Return to `dx`.

---

## Corner Case 8 — Entire closed standard curve

Look for circle/ellipse/triangle/trapezoid formulas before integrating.

---

## Corner Case 9 — Stationary area

Check stationary points **and** boundary values.

---

## Corner Case 10 — Modulus

Never remove `| |` without a sign analysis.

---

## Corner Case 11 — Tangency

Two curves may touch at an intersection without crossing. A touching point does not necessarily reverse which curve is larger.

---

## Corner Case 12 — Repeated roots

An even-multiplicity root often corresponds to touching rather than crossing. Check the sign instead of assuming alternation.

---

# 31. Choosing `dx` or `dy` — Decision Rule

## Use `dx` when

- curves are naturally written as `y=f(x)`
- vertical boundaries are simple
- upper/lower comparison is easy
- inverse functions would be messy

## Use `dy` when

- curves are naturally written as `x=f(y)`
- horizontal boundaries are simpler
- one x-value corresponds to multiple y-branches that would force splitting in `dx`
- the region is naturally described by left/right boundaries

### Master Formulas

$$
\boxed{dx:\quad A=\int(\text{upper}-\text{lower})dx}
$$

$$
\boxed{dy:\quad A=\int(\text{right}-\text{left})dy}
$$

---

# 32. Quick Formula Sheet

| Situation | Formula |
|---|---|
| Area under non-negative curve | `\int_a^b f(x)dx` |
| Geometrical area | `\int_a^b |f(x)|dx` |
| Between two curves | `\int_a^b |f-g|dx` |
| Upper minus lower | `\int_a^b(f-g)dx` |
| Horizontal-strip area | `\int_c^d(x_{right}-x_{left})dy` |
| Parametric area | `\int y\,dx=\int y(t)x'(t)dt` |
| Closed parametric curve | `|\oint y\,dx|` |
| Green-type form | `\frac12|\oint(xdy-ydx)|` |
| Circle | `\pi r^2` |
| Ellipse | `\pi ab` |
| Triangle | `\frac12bh` |
| Trapezoid | `\frac12(a+b)h` |
| Even function | `\int_{-a}^{a}f=2\int_0^a f` |
| Odd function | `\int_{-a}^{a}f=0` |

---

# 33. JEE Question Models to Practice

### JEE Main Level

1. Direct area under a polynomial.
2. Area under a curve and coordinate axes.
3. Area using symmetry.
4. Area involving modulus.
5. Area between two curves.
6. Circle/ellipse recognition.
7. Area represented by simple inequalities.
8. Choosing correct limits.

### JEE Advanced Level

9. Multiple curve intersections.
10. Parameter-dependent area.
11. Parameter-dependent limits.
12. Parameter changing the number of intersections.
13. Minimum/maximum area.
14. Translation of curves.
15. Area using horizontal strips.
16. Parametric area.
17. Closed parametric curves.
18. Regions defined by multiple inequalities.
19. Area ratios.
20. Piecewise upper/lower boundaries.

---

# 34. Final JEE Checklist

Before submitting an answer, verify:

- [ ] Have I drawn/sketched the region?
- [ ] Have I found all relevant intersections?
- [ ] Did I check whether the function/curve changes sign?
- [ ] Did I identify the correct upper and lower curves?
- [ ] Should I use `dx` or `dy`?
- [ ] Is there symmetry I can exploit?
- [ ] Is the region a standard geometric figure?
- [ ] Does a parameter affect the limits or sign?
- [ ] Did I check endpoints in an optimization problem?
- [ ] If the answer is zero, is it really area or only signed integral?

---

# 35. One-Line Master Rule

$$
\boxed{
\textbf{DRAW}\;\rightarrow\;\textbf{FIND\ BOUNDARIES}\;\rightarrow\;\textbf{CHECK\ SIGN}\;\rightarrow\;\textbf{CHOOSE\ }dx/dy\;\rightarrow\;\textbf{USE\ SYMMETRY}\;\rightarrow\;\textbf{INTEGRATE}
}
$$

> **JEE Golden Rule:** The hardest part of most area problems is not integration. It is correctly identifying the region, its boundaries, its sign, and the most efficient direction of integration.
