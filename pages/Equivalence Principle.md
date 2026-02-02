---
layout: default
title: Equivalence principle
permalink: /old-pages/equivalence-principle/
---

# Deriving the equivalence principle (structurally)

This page explains why the **equivalence principle** (EP) is structurally required by gravitational closure, rather than postulated as an independent axiom.

Within the Ananke (Gravitational Closure) framework, the EP is not an additional assumption. It is a consequence of three facts:

1. gravity is required to **close** with finite conserved quadratic norm,  
2. gravitational response admits **orthogonal modes** and exhausts freedom under symmetry,  
3. in vacuum, residual degrees of freedom are **forbidden** (vacuum rigidity).

---

## 1) Which equivalence principle is meant

The term “equivalence principle” is used in several strengths. Here we separate:

- **Universality of free fall (UFF / weak EP):** test bodies fall identically in a given gravitational environment.
- **Einstein equivalence principle (EEP):** local non-gravitational physics is Lorentz invariant and locally special-relativistic; gravity can be represented by a metric and minimal coupling.
- **Strong EP (SEP):** extends the principle to self-gravitating bodies (with caveats).

The closure framework targets the structural origin of UFF/EEP, and clarifies what is required (and what is not) for SEP.

---

## 2) Core claim

If classical gravity closes as a field, then **there can be no independent gravitational “charge”** beyond the conserved extensive content already present in matter.

Equivalently: once closure and vacuum rigidity are imposed, gravity cannot couple selectively.

That statement is the equivalence principle in structural form.

---

## 3) Why “gravitational charge” must be universal under closure

Consider what would be required to violate the equivalence principle in a classical field theory:

- different materials would carry different gravitational charges, or  
- different species would couple to different gravitational response channels, or  
- gravity would distinguish internal composition via extra couplings.

Any such violation requires **additional independent degrees of freedom** in the gravitational response (new long-range charges, extra fields, or composition-dependent coupling functions).

Closure forbids this for two reasons:

### (i) Vacuum rigidity forbids extra long-range charges

In isolated vacuum exteriors, closure forces **zero residual DOF**. A composition-dependent gravitational charge would generically imprint distinct exterior fields even in vacuum. That would introduce residual freedom in the vacuum sector and destroy rigidity.

Therefore, in the closure regime, gravity must have a single universal source content.

### (ii) Finite conserved quadratic norm forbids uncontrolled coupling freedom

If coupling depended on arbitrary internal structure, the field’s conserved quadratic norm would depend on uncontrolled functional freedom (material-dependent couplings). That contradicts closure: conserved quantities must not require external bookkeeping or ad hoc prescriptions.

Therefore, the coupling must reduce to the unique extensive conserved content available.

---

## 4) The action-level expression of universality

The closure-admissible structure couples matter minimally through the metric:

$$
S_{\mathrm{matter}}[g,\psi],
$$

so that the stress-energy tensor is defined by

$$
T_{\mu\nu} \equiv -\frac{2}{\sqrt{-g}}\frac{\delta S_{\mathrm{matter}}}{\delta g^{\mu\nu}}.
$$

General covariance then yields the Noether identity (on-shell)

$$
\nabla_\mu T^{\mu\nu} = 0.
$$

This is the structural bridge from “universal coupling” to “universal motion”.

---

## 5) From covariant conservation to universal free fall

For localized matter, covariant conservation implies that the center-of-mass worldline follows a metric geodesic to leading order (and follows well-defined multipole-corrected motion when structure is included).

At the test-body level, one may view the motion as extremizing proper time:

$$
S_{\mathrm{pp}} = -m \int ds,
\qquad
ds^2 = g_{\mu\nu}dx^\mu dx^\nu,
$$

which yields the geodesic equation

$$
\frac{d^2x^\mu}{d\tau^2}+\Gamma^\mu_{\alpha\beta}
\frac{dx^\alpha}{d\tau}\frac{dx^\beta}{d\tau}=0.
$$

Key point: the mass parameter cancels from the acceleration, so the trajectory is independent of composition in the test limit. This is UFF.

In closure language: if there is only one admissible coupling channel in vacuum-rigid gravity, then there is only one admissible notion of “gravitational charge”, and it is universal.

---

## 6) Interpreting inertial vs gravitational mass

Operationally:

- **inertial mass** quantifies resistance to acceleration under non-gravitational forces,
- **gravitational mass** quantifies coupling to gravitational response.

A violation of equality would mean gravity couples to something other than the conserved extensive content that also governs inertia. Under closure, there is no additional admissible “something”.

Thus, within this framework, the equality is not mysterious:

- inertia is the universal conserved content carried by matter,
- gravity couples to that same content because no other charge is admissible in a closed field.

This is the equivalence principle as a closure theorem corollary.

---

## 7) What the theorem does and does not guarantee

### Guaranteed in-scope (structural)
- a single universal coupling channel in vacuum-rigid regimes,
- no additional long-range gravitational charges,
- UFF/EEP in the test-body limit as a consequence of minimal coupling and covariance.

### Not automatically guaranteed (requires careful qualification)
- full SEP for strongly self-gravitating bodies in arbitrary environments,
- absence of all possible effective EP violations arising from symmetry breaking, non-stationarity, or non-minimal matter sectors not covered by the closure assumptions.

The closure framework explains why EP is structurally enforced where the regime conditions hold, and also clarifies how apparent violations, if observed, would signal either symmetry breaking or failure of closure.

---

## 8) Falsification modes (equivalence-specific)

Within the regime conditions where closure is sharp, the EP would be structurally challenged by any confirmed evidence of:

- composition-dependent free fall in controlled gravitational fields,
- additional long-range gravitational charges (“fifth-force” charges) persisting in vacuum exteriors,
- environment-dependent coupling that cannot be reduced to symmetry breaking or matter distribution inputs.

Such observations would indicate additional admissible degrees of freedom beyond the closure classification.

---

## Summary

The equivalence principle is structurally enforced by gravitational closure:

- vacuum rigidity forbids extra long-range charges,
- closure forbids uncontrolled coupling freedom,
- covariance forces universal coupling via the metric,
- and universal coupling yields universal motion (geodesic free fall).

In a closed classical gravitational field, gravity cannot couple selectively.  

Consequentially, ***it can be no other way.***

---

## Next

[Next: Falsifiability](/old-pages/falsifiability/)

<small>See also: [Unique admissible action](/old-pages/action/)</small>
