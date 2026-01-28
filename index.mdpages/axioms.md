---
layout: default
title: Axioms
---

# Axioms of Gravitational Closure

This page states the three axioms used by the **Ananke (Gravitational Closure) Theorem**.  
They are intended to be minimal structural requirements for a classical gravitational field: covariant, energetically closed, and with response structure exhausted under symmetry reduction.

---

## Axiom I — Classical covariance

**Statement.** The gravitational field admits a generally covariant variational formulation. No preferred coordinates, fixed background structures, or non-dynamical geometric data are permitted.

**Operational content.**
- Physical statements are diffeomorphism-invariant.
- Field equations arise from a covariant action principle.
- Conserved quantities (where they exist) are defined in a coordinate-independent manner.

**Role in the theorem.** Covariance restricts admissible terms in the action to scalar densities constructed from the metric and covariant derivatives of the gravitational field variables.

---

## Axiom II — Quadratic closure with finite conserved energy

**Statement.** The gravitational field is required to **close** as a classical field: it admits a **finite conserved quadratic norm** (energy functional) on the space of admissible configurations, and it does not require external bookkeeping, regime-dependent supplements, or uncontrolled functional freedom to remain finite.

A convenient abstract statement is: there exists a conserved bilinear form (quadratic functional)
$$
\mathcal{Q}[\Psi] \;=\; \langle \Psi,\Psi\rangle,
$$
finite for admissible configurations \(\Psi\), and conserved under the field evolution.

**Operational content.**
- The fundamental energetic measure is **quadratic** in the field response variables.
- Closure excludes actions whose energetic control depends on:
  - arbitrary functions not fixed by symmetry/constraints,
  - non-compact “free data” that survives reduction,
  - non-integrable energy densities in admissible regimes.

**Role in the theorem.**
- Quadratic closure excludes higher-derivative and non-quadratic response structures as fundamental terms (except as boundary-equivalent forms).
- Under symmetry reduction, closure forces **exhaustion of functional freedom**: if free functions survive in a regime where the field is required to be rigid, closure fails.

---

## Axiom III — Orthogonality of response modes

**Statement.** The gravitational field admits **orthogonal modes of response** with respect to the conserved quadratic form. In the Ananke framework these are:
- a **constraint (longitudinal)** mode, and
- a **redistributive (transverse)** mode,

with vanishing cross-term in the conserved bilinear norm:
$$
\langle \Psi_{\rm L}, \Psi_{\rm T} \rangle \;=\; 0.
$$

**Operational content.**
- The total conserved quadratic measure decomposes into a sum of independent sector norms:
$$
\mathcal{Q}[\Psi] \;=\; \mathcal{Q}_{\rm L}[\Psi_{\rm L}] \;+\; \mathcal{Q}_{\rm T}[\Psi_{\rm T}],
$$
with no mixed term.
- Orthogonality enforces **sector decoupling** under appropriate symmetry conditions and prevents hidden mode-mixing from reintroducing functional freedom.

**Role in the theorem.**
- Orthogonality is what allows the classification of admissible response structure into a rigid vacuum sector and a controlled non-vacuum residual sector.
- It is the structural mechanism by which “GR as equilibrium” and “one residual DOF outside vacuum” can coexist without contradiction.

---

## Immediate structural consequences (used downstream)

The axioms above are sufficient to establish the following qualitative consequences (precise statements and proofs are in the theorem paper):

1. **Vacuum rigidity (zero residual DOF).**  
   In isolated symmetry-reduced vacuum regimes, closure exhausts functional freedom. No residual redistributive mode is admissible, yielding rigid exterior behaviour.

2. **Exactly one admissible non-vacuum residual DOF.**  
   In non-vacuum symmetry-reduced regimes, closure permits exactly one conserved residual degree of freedom associated with redistribution, with no further freedoms permitted.

3. **Uniqueness of admissible action (up to equivalence).**  
   Covariance + quadratic closure + orthogonality fix the admissible covariant action to a unique class, up to boundary terms and invertible local field redefinitions.

---

## Where this fits in the paper sequence

- **Fundamental Fields Theorem:** identifies which classical interaction fields can satisfy closure.  
- **Ananke (Gravitational Closure) Theorem:** classifies the unique admissible structure of closed classical gravity from the axioms above.  
- **Structural Diagnostics:** translates the classification into falsifiable observational criteria under symmetry reduction.  
- **Phenomenology:** applies those diagnostics to galactic and cosmological regimes.

---

## References (primary)

- Ananke (Gravitational Closure) Theorem — Zenodo DOI:  
  [https://zenodo.org/records/18387510](https://zenodo.org/records/18387510)
