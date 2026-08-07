# Chapter 2 — Introduction to Analytical Chemistry

> Notes distilled from our learning conversation. The goal is **mastery and intuition**, not just definitions.

## 1. What analytical chemistry is for

Analytical chemistry asks two fundamental questions about a sample:

- **Qualitative analysis:** *What is present?*
- **Quantitative analysis:** *How much is present?*

The broader workflow is to **separate, identify, and quantify** the matter under study.

A chemist normally analyzes a **small representative sample**, not the entire bulk material. When only a few grams of sample are used, the textbook refers to this as **semi-microanalysis**.

### Classical methods introduced

Qualitative methods include:

- precipitation,
- extraction,
- distillation.

Identification may use observable properties such as colour, odour, melting point, boiling point, and chemical reactivity.

Quantitative methods include:

- **gravimetric analysis** — quantity inferred from **mass**,
- **titrimetric / volumetric analysis** — quantity inferred from **volume** of a reacting solution.

### Important clarification

The textbook emphasizes percentage elemental analysis under organic compounds and gravimetric/titrimetric methods under inorganic compounds. This should **not** be interpreted as meaning percentage composition is inapplicable to inorganic compounds. Percentage composition can be determined for inorganic compounds as well; the textbook itself uses such calculations in exercises.

---

## 2. Qualitative analysis: dry and wet methods

### Dry method

The sample is **not dissolved**. Dry tests are commonly preliminary clues obtained from colour, heating behaviour, odour, etc.

### Wet method

The sample is first **dissolved**, then subjected to chemical tests.

### Organic compounds

Elementary qualitative analysis commonly checks for elements such as:

- C, H, O, N, S, halogens, P.

Further identification may involve:

- functional-group tests,
- melting point,
- boiling point.

### Inorganic compounds

The main aim is detecting and confirming:

- **cations** (positive ions),
- **anions** (negative ions).

---

## 3. Quantitative analysis

### Organic compounds

Two typical quantitative goals are:

1. Determine the **percentage of constituent elements**.
2. Determine the **concentration of a known compound** in a sample.

### Inorganic compounds

Two major methods emphasized are:

- **gravimetric analysis**,
- **titrimetric (volumetric) analysis**.

The key distinction is simply:

| Method | Main measured quantity |
|---|---:|
| Gravimetric | Mass |
| Volumetric / titrimetric | Volume |

---

## 4. Measurement, error, accuracy, and precision

No physical measurement is perfectly exact. Every instrument and procedure introduces some uncertainty.

### Accuracy

**Accuracy** is the closeness of a measured value to the true or accepted value.

A useful intuition:

- high accuracy → small error,
- poor accuracy → systematic offset from the true value.

### Precision

**Precision** is the reproducibility of repeated measurements — how tightly they cluster together.

A result can be:

- precise and accurate,
- precise but inaccurate,
- inaccurate and imprecise.

A classic example:

- true value: `1.000 M`
- readings around `0.850 M` with tiny spread → **high precision, low accuracy**.

Calibration typically improves **accuracy** by reducing systematic error, while precision may remain similar.

### Absolute error

\[
\text{Absolute error} = \text{Observed value} - \text{True value}
\]

The sign indicates whether the observation is above or below the true value.

### Relative error

\[
\text{Relative error} = \frac{\text{Absolute error}}{\text{True value}}\times 100\%
\]

Relative error is usually more informative because the seriousness of an error depends on the scale of what is being measured.

### Absolute deviation

For repeated measurements:

\[
\text{Absolute deviation} = |\text{Observed value} - \text{Mean}|
\]

### Mean absolute deviation

The arithmetic mean of all absolute deviations.

### Relative deviation

\[
\text{Relative deviation} = \frac{\text{Mean absolute deviation}}{\text{Mean}}\times 100\%
\]

---

## 5. Scientific notation

Scientific notation is written as:

\[
N\times 10^n
\]

where `1 ≤ N < 10`.

Examples:

- `123.546 = 1.23546 × 10^2`
- `0.00015 = 1.5 × 10^-4`

### Addition / subtraction

Make the exponents equal first, then operate on the coefficients.

Example:

\[
5.55\times10^4 + 6.95\times10^3
= 5.55\times10^4 + 0.695\times10^4
= 6.245\times10^4
\]

### Multiplication

Multiply the coefficients and add exponents.

Example:

\[
(5.6\times10^5)(6.9\times10^8)
=38.64\times10^{13}
=3.864\times10^{14}
\]

---

## 6. Significant figures — the real intuition

The central principle is:

> **Significant figures communicate the precision of a measurement.**

A significant figure is a digit known with certainty plus one estimated digit.

### Why `400` is usually treated as one significant figure

The number `400` is ambiguous. It does not tell us whether the quantity was measured to the nearest:

- hundred,
- ten,
- one,
- tenth.

By convention, trailing zeros in an integer without an indicated decimal are not assumed significant.

Scientific notation removes the ambiguity:

- `4 × 10^2` → 1 significant figure,
- `4.0 × 10^2` → 2 significant figures,
- `4.00 × 10^2` → 3 significant figures.

The key idea is that a significant digit is a digit you have **earned by measurement**, not a placeholder required by decimal notation.

### Counting rules

- All non-zero digits are significant.
- Zeros between non-zero digits are significant.
- Leading zeros are not significant.
- Trailing zeros after a decimal point are significant.
- In scientific notation, all written digits in the coefficient are significant.

### Rounding

- If the first discarded digit is `< 5`, leave the previous digit unchanged.
- If it is `≥ 5`, increase the previous digit by 1.

The deeper reason for rounding is not convenience. It is to avoid **claiming precision that was never measured**.

---

## 7. Empirical formula and molecular formula

### Empirical formula

The **simplest whole-number ratio** of atoms in a compound.

### Molecular formula

The **actual number of atoms** of each element in one molecule.

Example:

- empirical formula: `CH2`
- possible molecular formulas: `CH2`, `C2H4`, `C3H6`, ...

### Why assume a 100 g sample?

If a compound is 24.27% carbon, then in a 100 g sample it contains exactly 24.27 g carbon. Percentages become grams directly.

### Why convert grams to moles?

Chemical formulas represent **ratios of atoms**, not ratios of masses. Since equal masses of different elements contain different numbers of atoms, masses must be converted to moles before finding atomic ratios.

### Algorithm

1. Assume 100 g of compound.
2. Convert each percentage to grams.
3. Convert grams to moles.
4. Divide all mole values by the smallest.
5. Adjust to the nearest simple whole-number ratio.
6. Write the empirical formula.
7. Calculate empirical formula mass.
8. Find:

\[
n = \frac{\text{Molar mass}}{\text{Empirical formula mass}}
\]

9. Multiply all empirical subscripts by `n`.

### Worked example

Composition:

- C = 40.0%
- H = 6.7%
- O = 53.3%

For 100 g:

- C: `40/12 ≈ 3.33 mol`
- H: `6.7/1 = 6.7 mol`
- O: `53.3/16 ≈ 3.33 mol`

Ratio:

\[
3.33:6.7:3.33 \approx 1:2:1
\]

Empirical formula:

\[
\boxed{CH_2O}
\]

If molar mass = `180 g mol^-1`:

- empirical formula mass = `30`
- `n = 180/30 = 6`

Molecular formula:

\[
\boxed{C_6H_{12}O_6}
\]

---

## 8. How could chemists measure molar mass of an unknown compound?

Composition alone gives the empirical formula, not the full molecular formula. A second, independent measurement is needed: **molar mass**.

Historically and experimentally, molar mass can be obtained in several ways depending on the substance:

- gas density / vapour density,
- ideal-gas measurements,
- colligative properties,
- modern mass spectrometry.

For a gas, if mass `m` and number of moles `n` are determined:

\[
M = \frac{m}{n}
\]

Using the ideal gas law:

\[
PV=nRT
\]

one can infer `n`, then obtain molar mass.

### Pending historical detour

After Chapter 2, we planned a special session:

> **How Chemists Weighed Invisible Molecules**

Topics to connect:

- Proust and fixed composition,
- Dalton,
- Gay-Lussac,
- Avogadro,
- vapour density,
- molecular mass,
- the emergence of molecular formulas.

---

## 9. Stoichiometry

A balanced chemical equation is fundamentally a **ratio statement in moles**.

Example:

\[
2H_2 + O_2 \rightarrow 2H_2O
\]

means the ratio:

\[
2:1:2
\]

This ratio can be scaled freely:

- 2 mol : 1 mol : 2 mol
- 4 mol : 2 mol : 4 mol
- 0.5 mol : 0.25 mol : 0.5 mol

### Core pipeline

\[
\text{Mass} \rightarrow \text{Moles} \rightarrow \text{Mole ratio} \rightarrow \text{Moles} \rightarrow \text{Mass/Volume/Particles}
\]

### Example: 16 g O2 with excess H2

- `16 g O2 = 0.5 mol O2`
- reaction ratio gives `1 mol H2O`
- `1 mol H2O = 18 g`

Answer: `18 g H2O`.

### Example: 8 g H2 with excess O2

- `8 g H2 = 4 mol H2`
- ratio gives `4 mol H2O`
- mass = `4 × 18 = 72 g`

Answer: `72 g H2O`.

### Conservation-of-mass sanity check

For:

\[
CaCO_3 \rightarrow CaO + CO_2
\]

25 g CaCO3 = 0.25 mol.

Products:

- CaO: `0.25 × 56 = 14 g`
- CO2: `0.25 × 44 = 11 g`

Check:

\[
14+11=25\text{ g}
\]

This is a useful final check.

---

## 10. Discovering stoichiometric ratios experimentally

A chemist does **not** need to test infinitely many combinations.

If reactants are mixed in a non-stoichiometric ratio, one reactant is consumed completely and the other remains in excess. By systematically varying the starting ratio and observing when neither reactant is left over, the stoichiometric ratio can be inferred.

For gases, historical chemists often measured **volumes**, which led to simple combining-volume ratios and eventually helped motivate Avogadro's hypothesis.

---

## 11. Limiting reagent

The **limiting reagent** is the reactant consumed first. It determines the maximum amount of product that can form.

### Textbook method

For each reactant separately:

1. Assume it reacts completely.
2. Calculate how much product it could produce.
3. The reactant that gives the smaller product amount is limiting.

Example:

\[
N_2 + 3H_2 \rightarrow 2NH_3
\]

Given:

- 5 mol N2,
- 12 mol H2.

If all N2 reacts → 10 mol NH3 possible.

If all H2 reacts → 8 mol NH3 possible.

Therefore:

- H2 is limiting,
- 8 mol NH3 forms,
- only 4 mol N2 reacts,
- 1 mol N2 remains.

### Exact stoichiometric amounts

If reactants are present in the exact stoichiometric ratio, **both are exhausted together** and there is no excess reagent.

Example:

- 56 g N2 = 2 mol,
- 12 g H2 = 6 mol,

which exactly matches the 1:3 ratio. Therefore 4 mol NH3 = 68 g forms, with no excess reactant.

---

## 12. Concentration of solutions

Four concentration units were introduced.

### 12.1 Mass percent

\[
\text{Mass percent} = \frac{\text{Mass of solute}}{\text{Mass of solution}}\times100
\]

Remember:

\[
\text{Mass of solution} = \text{Mass of solute} + \text{Mass of solvent}
\]

Example:

2 g solute + 18 g water → 20 g solution.

\[
\frac{2}{20}\times100 = 10\%
\]

### 12.2 Mole fraction

\[
X_A=\frac{n_A}{n_A+n_B}
\]

For a binary solution:

\[
X_A+X_B=1
\]

Mole fraction is unitless.

### 12.3 Molarity

\[
M = \frac{\text{Moles of solute}}{\text{Volume of solution in L}}
\]

Important: denominator is **solution volume**, not solvent volume.

Example:

4 g NaOH in 250 mL solution:

- moles = `4/40 = 0.1`
- volume = `0.250 L`

\[
M=0.1/0.250=0.4\,M
\]

### Why molarity changes with temperature

The number of moles stays constant, but solution volume changes with thermal expansion.

Heating generally increases volume, so molarity generally decreases.

### 12.4 Molality

\[
m = \frac{\text{Moles of solute}}{\text{Mass of solvent in kg}}
\]

Important: denominator is **mass of solvent only**.

Molality is temperature-independent because mass does not change with temperature.

### Molarity vs molality

| Quantity | Denominator | Temperature dependent? |
|---|---|---|
| Molarity | L of solution | Yes |
| Molality | kg of solvent | No |

### Temperature thought experiment

If a solution is heated without losing material:

- mass percent → unchanged,
- mole fraction → unchanged,
- molarity → changes (usually decreases),
- molality → unchanged.

### Example used in mastery practice

9.8 g H2SO4 = 0.1 mol.

If final solution volume = 500 mL:

\[
M=0.1/0.5=0.2\,M
\]

If instead dissolved in 250 g water:

\[
m=0.1/0.25=0.4\,m
\]

---

## 13. Use of graphs in analysis

Experimental data usually contain scatter because measurements are imperfect.

Instead of joining every measured point with straight line segments, chemists draw a **smooth best-fit line or curve** representing the underlying trend.

The purpose is to distinguish the real relationship from random measurement noise.

In the textbook's gas example, the best-fit trend shows a direct relationship between gas volume and temperature under the stated conditions.

The larger lesson is:

> A graph is an analytical tool for extracting an underlying relationship from imperfect data.

---

## 14. Mastery observations from our practice

### Concepts handled well

- qualitative vs quantitative analysis,
- accuracy vs precision,
- empirical vs molecular formula,
- stoichiometric mole ratios,
- limiting reagent reasoning,
- molarity vs molality.

### Arithmetic / bookkeeping slips to guard against

Two mistakes during practice were conceptual **non-issues** but useful reminders:

1. When converting mass to moles, use:

\[
\boxed{n=\frac{m}{M}}
\]

not its reciprocal.

2. For molality, divide by **kg of solvent**, not solution mass and not an accidentally converted quantity.

### Final-answer checklist

Before boxing an answer, ask:

1. Did I use the correct definition / equation?
2. Did I use the correct denominator?
3. Are the units correct?
4. Does the answer pass a rough sanity check?
5. For reaction-mass questions, does conservation of mass provide a useful check?

---

## 15. Chapter 2 status

Covered:

- 2.1 Introduction
- 2.2 Analysis
- 2.3 Mathematical operation and error analysis
- 2.4 Determination of molecular formula
- 2.5 Chemical reactions and stoichiometric calculations
- 2.6 Limiting reagent
- 2.7 Concentration of solution
- 2.8 Use of graph in analysis
- representative mastery problems

**Chapter 2: complete.**

Next planned session:

> **Historical Detour — How Chemists Weighed Invisible Molecules**

