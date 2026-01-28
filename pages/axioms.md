---
layout: default
title: Axioms
---

# Axioms of Gravitational Closure

This page states the axioms underlying the **Ananke Theorem**.  
They are not modelling assumptions or phenomenological hypotheses.  
They define the **admissibility conditions** for a classical gravitational field required to close with finite conserved energy.

Throughout, “closure” means exhaustion of admissible degrees of freedom under symmetry reduction.

---

## Axiom I — Classical covariance

**Statement.**  
The gravitational field admits a generally covariant variational formulation. All physically admissible structures are invariant under diffeomorphisms. No preferred coordinates, background geometries, or non-dynamical geometric data are permitted.

**Formal role.**  
All admissible contributions to the action must be constructed as scalar densities from the metric and covariant field variables. Any term that breaks covariance or introduces fixed background structure is inadmissible.

**Consequence.**  
Covariance restricts the action to a finite class of geometric and field-theoretic terms and ensures that any residual degrees of freedom are geometric in origin rather than coordinate artefacts.

---

## Axiom II — Quadratic closure with finite conserved energy

**Statement.**  
The gravitational field is required to close as a classical field. There exists a **finite conserved quadratic functional** on the space of admissible configurations, and no uncontrolled functional freedom may survive in regimes where the field is required to be rigid.

Abstractly, there exists a conserved bilinear form
$$
\mathcal{Q}[\Psi] = \langle \Psi, \Psi \rangle,
$$
finite on admissible configurations \(\Psi\) and invariant under the field evolution.

**Formal role.**  
Closure excludes any response structure whose energetic control:
- depends on arbitrary functions not fixed by symmetry,
- requires regime-dependent prescriptions to remain finite,
- or admits non-integrable energy densities in admissible regimes.

**Consequence.**  
Quadratic closure eliminates higher-order and non-quadratic response structures as fundamental terms (up to boundary equivalence) and enforces exhaustion of functional degrees of freedom under symmetry reduction.

---

## Axiom III — Orthogonality of response modes

**Statement.**  
The admissible gravitational response decomposes into **orthogonal modes** with respect to the conserved quadratic form. In the Ananke framework these are:
- a **longitudinal (constraint)** mode, and
- a **transverse (redistributive)** mode,

satisfying
$$
\langle \Psi_{\rm L}, \Psi_{\rm T} \rangle = 0.
$$

**Formal role.**  
The conserved quadratic functional decomposes additively,
$$
\mathcal{Q}[\Psi]
=
\mathcal{Q}_{\rm L}[\Psi_{\rm L}]
+
\mathcal{Q}_{\rm T}[\Psi_{\rm T}],
$$
with no mixed term. Orthogonality forbids hidden mode-mixing that would reintroduce uncontrolled degrees of freedom.

**Consequence.**  
Orthogonality permits rigid vacuum behaviour while allowing a controlled residual mode outside vacuum, without violating closure.

---

## Derived structural propositions

The axioms above imply the following structural results, which are proved in the theorem paper.

### Proposition 1 — Vacuum rigidity
In isolated, symmetry-reduced vacuum regimes, closure exhausts all admissible degrees of freedom. The redistributive mode is identically eliminated. The gravitational field admits **zero residual DOF**, yielding rigid exterior behaviour.

### Proposition 2 — Unique non-vacuum residual degree of freedom
In non-vacuum regimes under sufficient symmetry reduction, closure admits **exactly one** conserved residual degree of freedom. No additional independent degrees of freedom are admissible.

### Proposition 3 — Uniqueness of admissible action
The requirements of covariance, quadratic closure, and orthogonality fix the admissible covariant gravitational action **uniquely**, up to boundary terms and invertible local field redefinitions. Any modification introduces uncontrolled degrees of freedom or violates closure.

---

## Logical position in the programme

1. **Fundamental Fields Theorem**  
   Determines which classical interaction fields can satisfy closure under finite conserved energy.

2. **Ananke (Gravitational Closure) Theorem**  
   Classifies the unique admissible structure of closed classical gravity under the axioms above.

3. **Structural Diagnostics of Gravitational Closure**  
   Translates the classification into necessary and forbidden observational consequences under symmetry reduction.

4. **Phenomenological Consequences**  
   Applies those diagnostics to galactic and homogeneous cosmological regimes.

---

## Primary reference

- **Ananke (Gravitational Closure) Theorem** — Zenodo DOI:  
  [https://zenodo.org/records/18387510](https://zenodo.org/records/18387510)

