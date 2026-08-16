# IIT JEE Organic Chemistry — Structure, Stereochemistry, Isomerism & Nomenclature

> High-yield IIT JEE concepts, formulas, traps, and question patterns for structural chemistry, hybridisation, stereochemistry, IUPAC nomenclature, and conformations.

## Topics Covered

- Hybridisation of carbon
- Sigma and pi bonding
- Shapes of simple organic molecules
- Structural/constitutional isomerism
- Geometrical isomerism
- Optical isomerism with up to two asymmetric centres
- Enantiomers, diastereomers, meso compounds and racemic mixtures
- Basic IUPAC nomenclature of hydrocarbons and mono-/bi-functional compounds
- Newman projections
- Ethane conformations
- Butane conformations

---

# 1. Hybridisation of Carbon ⭐⭐⭐⭐⭐

| Hybridisation | Orbitals mixed | Geometry | Bond angle | Example |
|---|---|---|---|---|
| `sp3` | 1s + 3p | Tetrahedral | 109.5° | CH4 |
| `sp2` | 1s + 2p | Trigonal planar | 120° | C2H4 |
| `sp` | 1s + 1p | Linear | 180° | C2H2 |

### Quick identification

- Carbon involved only in single bonds → generally `sp3`.
- Carbon of a C=C double bond → `sp2`.
- Carbon of a C≡C triple bond → `sp`.

### JEE Trap

Determine hybridisation from the orbital arrangement/electron domains around the atom, not merely by counting the number of drawn bond lines.

---

# 2. Sigma and Pi Bonds ⭐⭐⭐⭐⭐

### Single bond

$$
\boxed{1\sigma}
$$

### Double bond

$$
\boxed{1\sigma+1\pi}
$$

### Triple bond

$$
\boxed{1\sigma+2\pi}
$$

A σ bond is formed mainly by head-on overlap. A π bond is formed by sideways overlap of parallel unhybridised p orbitals.

### Examples

**Ethane:** `CH3–CH3`

$$
\boxed{7\sigma,\ 0\pi}
$$

**Ethene:** `CH2=CH2`

$$
\boxed{5\sigma,\ 1\pi}
$$

**Ethyne:** `HC≡CH`

$$
\boxed{3\sigma,\ 2\pi}
$$

---

# 3. Shapes of Simple Organic Molecules ⭐⭐⭐⭐⭐

| Species/centre | Hybridisation | Shape | Approx. angle |
|---|---|---|---:|
| CH4 carbon | `sp3` | Tetrahedral | 109.5° |
| C=C carbon | `sp2` | Trigonal planar | 120° |
| C≡C carbon | `sp` | Linear | 180° |

For ethene, the atoms directly involved in the C=C framework are approximately coplanar. Ethyne is linear around the triple-bonded carbons.

---

# 4. Structural (Constitutional) Isomerism ⭐⭐⭐⭐⭐

Structural isomers have:

> **The same molecular formula but different connectivity of atoms.**

Example for `C4H10`:

1. n-butane: `CH3CH2CH2CH3`
2. 2-methylpropane: `(CH3)3CH`

Therefore:

$$
\boxed{C_4H_{10}\text{ has 2 constitutional isomers}}
$$

## Main Types

### Chain isomerism

Different carbon skeletons.

Example: n-butane and 2-methylpropane.

### Position isomerism

Same skeleton, different position of a substituent, multiple bond, or functional group.

Example:

`CH3CH2CH2OH` and `CH3CHOHCH3`.

### Functional isomerism

Same molecular formula but different functional groups.

Example for `C2H6O`:

- ethanol: `CH3CH2OH`
- methoxymethane: `CH3OCH3`

### Metamerism

Different alkyl groups on either side of a polyvalent functional group; commonly encountered with ethers.

---

# 5. Geometrical Isomerism ⭐⭐⭐⭐⭐

Geometrical isomerism results from **restricted rotation**, especially around a C=C bond.

## Condition for an Alkene to Show GI

Each carbon of the double bond must have two different groups attached.

For:

$$
R^1R^2C=CR^3R^4
$$

GI is possible when:

$$
\boxed{R^1\ne R^2\quad\text{and}\quad R^3\ne R^4}
$$

### Example

`CH3CH=CHCH3` has cis/trans forms.

### No GI

**Ethene:** `CH2=CH2` — each carbon has two H atoms.

**Propene:** `CH3CH=CH2` — terminal carbon has two H atoms.

**2-methylpropene:** `(CH3)2C=CH2` — one alkene carbon has two identical CH3 groups.

### JEE Shortcut

For a C=C bond, inspect **both alkene carbons separately**. If either carbon has two identical groups, ordinary geometrical isomerism is absent.

> Note: R/S and E/Z nomenclature are excluded from this revision scope, but the structural condition for geometrical isomerism remains important.

---

# 6. Optical Isomerism ⭐⭐⭐⭐⭐

A molecule is chiral when it is not superimposable on its mirror image.

For the basic JEE cases in this syllabus, the most important source is a tetrahedral carbon attached to **four different groups**.

Such a carbon is commonly called an asymmetric/chiral centre.

Example:

`CH3–CH(OH)–COOH`

The central carbon is attached to:

- H
- OH
- CH3
- COOH

so it is an asymmetric centre.

---

# 7. Enantiomers ⭐⭐⭐⭐⭐

Enantiomers are **non-superimposable mirror images**.

They generally have identical physical properties in an achiral environment but differ in their interaction with plane-polarised light and chiral environments.

For a pair of enantiomers:

$$
\boxed{\alpha_1=-\alpha_2}
$$

for equal experimental conditions.

---

# 8. Diastereomers ⭐⭐⭐⭐

Diastereomers are stereoisomers that are **not mirror images** of each other.

They generally have different physical properties such as melting point, boiling point, solubility, etc.

### JEE distinction

- Mirror-image, non-superimposable pair → **enantiomers**.
- Stereoisomers that are not mirror images → **diastereomers**.

---

# 9. Number of Stereoisomers with Asymmetric Centres ⭐⭐⭐⭐⭐

For `n` independent asymmetric centres, the maximum number is:

$$
\boxed{2^n}
$$

Therefore for two asymmetric centres:

$$
\boxed{2^2=4\text{ maximum stereoisomers}}
$$

### Important

`2^n` is a **maximum**, not a guaranteed number. Symmetry can make some configurations identical.

---

# 10. Meso Compounds ⭐⭐⭐⭐⭐

A meso compound:

- contains stereogenic/asymmetric centres,
- has an internal symmetry element such as a plane of symmetry,
- is achiral,
- is optically inactive.

### Classic JEE example

2,3-dichlorobutane:

`CH3–CHCl–CHCl–CH3`

It has two stereogenic centres, but because of symmetry the actual number of stereoisomers is:

$$
\boxed{3}
$$

rather than 4:

- one enantiomeric pair
- one meso form

### JEE Trap

Never apply `2^n` blindly. Always check for internal symmetry.

---

# 11. Racemic Mixture ⭐⭐⭐⭐

A racemic mixture contains equal amounts of two enantiomers:

$$
\boxed{50:50}
$$

Their optical rotations cancel:

$$
+\alpha+(-\alpha)=0
$$

Therefore the mixture is optically inactive.

### Racemic vs Meso

| Racemic mixture | Meso compound |
|---|---|
| Mixture of two enantiomers | Single achiral molecular species |
| External compensation | Internal compensation/symmetry |
| Each molecule can be chiral | Molecule itself is achiral |
| Net rotation is zero | Rotation is zero |

---

# 12. IUPAC Nomenclature — Basic Workflow ⭐⭐⭐⭐⭐

Use the following order:

1. Identify the principal functional group.
2. Select the longest suitable parent chain containing it.
3. Number the chain to give the principal functional group the lowest possible locant.
4. Identify substituents.
5. Assign substituent locants.
6. Arrange prefixes alphabetically where applicable.
7. Write the complete systematic name.

### Key idea

The principal functional group normally determines the **suffix** and strongly influences numbering.

---

# 13. Hydrocarbon Nomenclature

### Alkanes

Suffix:

$$
\boxed{-ane}
$$

Example: `CH3CH2CH3` → propane.

### Alkenes

Suffix:

$$
\boxed{-ene}
$$

Example: `CH2=CHCH3` → propene.

### Alkynes

Suffix:

$$
\boxed{-yne}
$$

Example: `CH≡CCH3` → prop-1-yne.

---

# 14. Functional-Group Priority — Basic JEE Scope ⭐⭐⭐⭐⭐

For the functional groups relevant to this syllabus, a useful simplified priority order is:

$$
\boxed{COOH>CHO>C=O>OH>NH_2>C=C>C\equiv C}
$$

Use the principal group as the suffix and treat lower-priority groups as prefixes when required.

> Always apply the exact IUPAC rules specified by the question; the table is a JEE revision shortcut, not a replacement for complete nomenclature rules.

---

# 15. Bifunctional Compounds ⭐⭐⭐⭐⭐

Examples:

### Dicarboxylic acid

`HOOC–CH2–COOH`

→ **propanedioic acid**

### Diol

`HO–CH2–CH2–OH`

→ **ethane-1,2-diol**

### Dialdehyde

`OHC–CHO`

→ **ethane-1,2-dial**

### JEE approach

For bifunctional compounds, identify the parent chain and determine whether both identical functional groups are represented by a multiplicative suffix such as `-diol`, `-dioic acid`, `-dial`, etc.

---

# 16. Conformations ⭐⭐⭐⭐⭐

Conformations are different spatial arrangements produced by rotation about a single σ bond.

They are **not constitutional isomers**.

The standard tool for analysing ethane and butane is the **Newman projection**.

---

# 17. Ethane Conformations

Look down the C–C bond using a Newman projection.

## Staggered

The C–H bonds on the front and rear carbons are maximally separated.

$$
\boxed{\text{Staggered = more stable}}
$$

## Eclipsed

Bonds on the front and rear carbons line up.

$$
\boxed{\text{Eclipsed = less stable}}
$$

Main reason: eclipsing introduces torsional strain.

Therefore:

$$
\boxed{E_{staggered}<E_{eclipsed}}
$$

---

# 18. Butane Conformations ⭐⭐⭐⭐⭐

Analyse rotation around the central `C2–C3` bond using a Newman projection.

Important conformations:

1. Anti
2. Gauche
3. Eclipsed
4. Fully eclipsed

## Stability order

$$
\boxed{Anti>Gauche>Eclipsed>Fully\ eclipsed}
$$

## Energy order

$$
\boxed{Anti<Gauche<Eclipsed<Fully\ eclipsed}
$$

---

# 19. Anti Butane ⭐⭐⭐⭐⭐

The two methyl groups have a dihedral angle of:

$$
\boxed{180^\circ}
$$

This is the **most stable** butane conformation because the methyl groups are maximally separated.

---

# 20. Gauche Butane ⭐⭐⭐⭐

The two methyl groups have a dihedral angle of:

$$
\boxed{60^\circ}
$$

It is less stable than anti because the methyl groups experience greater steric interaction.

---

# 21. Fully Eclipsed Butane ⭐⭐⭐⭐⭐

The two methyl groups eclipse each other at a dihedral angle of:

$$
\boxed{0^\circ}
$$

It has maximum torsional and steric strain and is therefore the **highest-energy** conformation.

---

# 22. Butane Newman Projection Summary

| Conformation | CH3–CH3 dihedral angle | Relative stability | Relative energy |
|---|---:|---|---|
| Anti | 180° | Highest | Lowest |
| Gauche | 60° | High | Low |
| Eclipsed | 120° | Lower | Higher |
| Fully eclipsed | 0° | Lowest | Highest |

---

# 23. IIT JEE High-Yield Question Patterns

## Hybridisation and bonding

1. Find hybridisation of every carbon in a molecule.
2. Count total σ and π bonds.
3. Identify bond angles from hybridisation.
4. Identify planar, trigonal-planar, tetrahedral and linear centres.
5. Determine the number of unhybridised p orbitals involved in π bonding.

## Structural isomerism

6. Count chain isomers.
7. Count position isomers.
8. Identify functional isomers.
9. Determine whether two displayed structures are actually identical.
10. Count constitutional isomers for a molecular formula.

## Geometrical isomerism

11. Decide whether a given alkene can show GI.
12. Count geometrical isomers.
13. Identify cis/trans arrangements where applicable.
14. Identify why a substituted alkene does or does not show GI.
15. Handle restricted rotation in cyclic systems where relevant.

## Optical isomerism

16. Identify asymmetric/chiral centres.
17. Count stereogenic centres.
18. Calculate maximum stereoisomers using `2^n`.
19. Check for meso forms and symmetry.
20. Count enantiomeric pairs.
21. Distinguish enantiomers and diastereomers.
22. Identify racemic mixtures.
23. Decide whether a molecule or sample is optically active/inactive.

## IUPAC nomenclature

24. Select the correct parent chain.
25. Choose the correct numbering direction.
26. Identify the principal functional group.
27. Assign substituent positions.
28. Apply alphabetical ordering of prefixes.
29. Name mono-functional compounds.
30. Name bi-functional compounds.
31. Convert IUPAC name → structure.
32. Convert structure → IUPAC name.
33. Identify incorrect IUPAC names.

## Conformations

34. Draw Newman projection of ethane.
35. Identify staggered and eclipsed forms.
36. Draw important butane conformations.
37. Rank conformations by stability.
38. Rank conformations by energy.
39. Identify anti and gauche forms.
40. Explain why anti-butane is more stable than gauche-butane.

---

# 24. JEE Traps — Must Remember ⚠️

1. Hybridisation is based on orbital arrangement, not simply the number of lines in a structural formula.
2. Double bond = `1σ + 1π`.
3. Triple bond = `1σ + 2π`.
4. Rotation around C=C is restricted.
5. Rotation around an ordinary C–C single bond produces conformations.
6. Conformations are not constitutional isomers.
7. GI in a simple alkene requires two different groups on **each** alkene carbon.
8. `2^n` gives the **maximum** number of stereoisomers, not always the actual number.
9. Always check for symmetry before counting stereoisomers.
10. A racemic mixture is inactive due to cancellation of rotations of opposite enantiomers.
11. A meso compound is inactive because the molecule is achiral.
12. Enantiomers are mirror-image, non-superimposable stereoisomers.
13. Diastereomers are stereoisomers that are not mirror images.
14. Anti-butane is more stable than gauche-butane.
15. Fully eclipsed butane has the highest energy.
16. Principal functional group controls the suffix and numbering priority.

---

# 25. One-Minute Revision Sheet

### Hybridisation

$$
\boxed{sp\rightarrow180^\circ,\quad sp^2\rightarrow120^\circ,\quad sp^3\rightarrow109.5^\circ}
$$

### Bonds

$$
\boxed{Single=1\sigma}
$$

$$
\boxed{Double=1\sigma+1\pi}
$$

$$
\boxed{Triple=1\sigma+2\pi}
$$

### Structural isomerism

$$
\boxed{Same\ molecular\ formula+different\ connectivity}
$$

### Geometrical isomerism

$$
\boxed{Restricted\ rotation+two\ different\ groups\ on\ each\ alkene\ carbon}
$$

### Optical isomerism

$$
\boxed{Four\ different\ groups\ on\ a\ tetrahedral\ carbon\rightarrow possible\ chiral\ centre}
$$

### Maximum stereoisomers

$$
\boxed{2^n}
$$

For two asymmetric centres:

$$
\boxed{Maximum=4}
$$

but symmetry may reduce this to 3 or fewer.

### Ethane

$$
\boxed{Staggered>Eclipsed\ (stability)}
$$

### Butane

$$
\boxed{Anti>Gauche>Eclipsed>Fully\ eclipsed}
$$

### Energy

$$
\boxed{Anti<Gauche<Eclipsed<Fully\ eclipsed}
$$

---

# 26. Master IIT JEE Concept Chain

$$
\boxed{Structure\rightarrow Hybridisation\rightarrow Geometry\rightarrow Bonding\rightarrow Isomerism\rightarrow Stereochemistry\rightarrow Conformation\rightarrow Nomenclature}
$$

Mastering this sequence makes later GOC, hydrocarbons, haloalkanes, alcohols, carbonyl compounds, and amines substantially easier.
