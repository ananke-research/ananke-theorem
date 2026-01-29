---
layout: default
title: Unique admissible action
permalink: /pages/action/
---

# Unique Admissible Action

This page presents the unique closed classical gravitational action in three layers:

1. each sector separately (to make the response structure explicit),  
2. a schematic block form,  
3. the full action in a compact two-line display.

Throughout, the organising requirement is closure under symmetry: finite conserved quadratic norm, classical covariance, and orthogonal response modes.

---

## Admissibility and exclusion of other response structures

Before presenting the admissible action, it is important to state what is ruled out by the axioms of gravitational closure.

Under classical covariance, finite conserved quadratic norm, and orthogonality of response modes, the gravitational field admits only a strictly limited set of response structures. Any additional scalar, vector, or tensor degrees of freedom beyond those listed below either introduce independent dynamical freedom, violate orthogonality, or fail to close under symmetry reduction.

In particular:

- additional scalar fields introduce unconstrained longitudinal freedom and spoil vacuum rigidity;  
- additional vector or tensor modes introduce propagating or long-range degrees of freedom incompatible with closure;  
- non-minimal couplings or functional freedoms require external bookkeeping and violate self-regulation;  
- independent vacuum-surviving charges or screening mechanisms are structurally forbidden.

As shown in the Ananke (Gravitational Closure) Theorem, once these possibilities are eliminated, exactly one constraint (longitudinal) response and exactly one conserved redistributive (transverse) response remain admissible. The action presented below is therefore not a model choice, but the unique closed structure permitted by the axioms.

---

### On fields, modes, and independence

The terms appearing in the admissible action do not represent independent gravitational fields. They are conjugate response modes of a single polarised gravitational field, introduced to enforce closure under the stated axioms.

The longitudinal (constraint) and transverse (redistributive) sectors are orthogonal components of the same field response, not additional sources or freely specifiable degrees of freedom. In particular, the transverse sector is not independently dynamical: its admissible contribution is fixed by conservation and symmetry, and in isolated vacuum regimes it vanishes identically.

Beyond vacuum, the transverse response appears only as a single conserved residual degree of freedom, slaved to the constraint sector through closure. No independent initial data or free functional freedom is associated with it.

---

## 1) Metric / geometric response (Einstein–Hilbert sector)

The metric sector is the unique covariant geometric response consistent with vacuum rigidity:

$$
S_{\rm EH}[g]
\;=\;
\frac{1}{16\pi G}\int d^4x\,\sqrt{-g}\,R .
$$

---

## 2) Longitudinal (constraint) sector

The constraint response is represented by a scalar constraint field. In the minimal closed form it appears with a quadratic kinetic term:

$$
S_{\rm L}[\phi;g]
\;=\;
\frac{1}{2}\int d^4x\,\sqrt{-g}\,g^{\mu\nu}\nabla_\mu\phi\,\nabla_\nu\phi .
$$

---

## 3) Transverse (redistributive) sector

The redistributive response is represented by a transverse vector potential with Maxwell-type quadratic form:

$$
S_{\rm T}[A;g]
\;=\;
-\frac{1}{4}\int d^4x\,\sqrt{-g}\,F_{\mu\nu}F^{\mu\nu},
\qquad
F_{\mu\nu}=\nabla_\mu A_\nu-\nabla_\nu A_\mu .
$$

This sector is orthogonal to the constraint response. In isolated vacuum regimes, closure forces this sector to vanish identically.

---

## 4) Closure / orthogonality constraint sector

Closure is enforced by a covariant constraint term. In the canonical form used in the theorem papers:

$$
S_{\rm c}[\lambda,\phi,u;g]
\;=\;
\int d^4x\,\sqrt{-g}\,\lambda\,\nabla_\mu(\phi\,u^\mu) .
$$

---

## 5) Matter coupling

Matter couples minimally through the metric:

$$
S_{\rm matter}[g,\psi] .
$$

No additional gravitational charges, screening terms, or free functional couplings are admissible under closure.

---

## 6) Schematic action (block form)

Collecting sectors:

$$
\begin{array}{l}
S
=\int d^4x\,\sqrt{-g}\,
\Big[
\underbrace{\mathcal{L}_{\rm EH}(g)}_{\text{metric / geometric response}}
\\
\qquad
+\underbrace{\mathcal{L}_{\rm L}(\phi)}_{\text{longitudinal (constraint)}}
+\underbrace{\mathcal{L}_{\rm T}(A_\mu)}_{\text{transverse (redistributive)}}
+\underbrace{\mathcal{L}_{\rm c}(\lambda,\phi,u^\mu)}_{\text{closure / orthogonality}}
\Big]
+\underbrace{S_{\rm matter}[g,\psi]}_{\text{matter coupling}} .
\end{array}
$$

Interpretation at the level of regimes:

- In isolated vacuum regimes, symmetry and conservation exhaust all freedom and force the redistributive sector to vanish, leaving pure constraint geometry (vacuum GR).  
- Beyond vacuum, under sufficient symmetry reduction, exactly one conserved redistributive degree of freedom is admissible and appears as a residual integration constant required by closure.

---

## 7) Full action (canonical closed form)

Up to boundary terms, invertible local field redefinitions, and normalisation conventions, the unique admissible closed classical gravitational action takes the form:

$$
\begin{array}{l}
S=\frac{1}{16\pi G}\int d^4x\,\sqrt{-g}\,R \\\\
\qquad+\frac{1}{2}\int d^4x\,\sqrt{-g}\,(\nabla\phi)^2
-\frac{1}{4}\int d^4x\,\sqrt{-g}\,F_{\mu\nu}F^{\mu\nu}
+\int d^4x\,\sqrt{-g}\,\lambda\,\nabla_\mu(\phi\,u^\mu)
+S_{\mathrm{matter}}[g,\psi].
\end{array}
$$

with

$$
(\nabla\phi)^2 \equiv g^{\mu\nu}\nabla_\mu\phi\,\nabla_\nu\phi,
\qquad
F_{\mu\nu}=\nabla_\mu A_\nu-\nabla_\nu A_\mu .
$$

---

## 8) What “unique” means here

“Unique” is meant in the strict structural sense: within the theorem’s scope, any addition introduces independent degrees of freedom or violates closure; any omission renders the response structure incomplete. Equivalence under boundary terms and invertible local field redefinitions is allowed.

---

## Links

- [Axioms of gravitational closure](/pages/axioms/)
- [Structural diagnostics](/pages/diagnostics/)
- [Papers and DOIs](/pages/papers/)
- [Physics FAQ](/pages/physics-faq/)
