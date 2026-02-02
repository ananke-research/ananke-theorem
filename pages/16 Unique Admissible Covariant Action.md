## 16 — Unique admissible covariant action

> **PDF correspondence:** Section 25 of the Ananke (Gravitational Closure) Theorem (Zenodo v1.0)

At this stage, no structural freedom remains. Closure, orthogonality, vacuum rigidity, and admissible non-vacuum structure together fix the covariant gravitational action **uniquely up to equivalence**. The action is not postulated or selected by modelling preference; it is obtained by elimination of all structurally inadmissible alternatives.

Equivalence is understood up to boundary terms, invertible local field redefinitions, and overall normalisation conventions.

---

### Metric sector

Vacuum rigidity requires that isolated vacuum regimes admit zero residual degrees of freedom and exhibit unique exterior behaviour. In four spacetime dimensions, the only generally covariant, second-order metric action satisfying this requirement is the Einstein–Hilbert action, up to boundary terms.

Accordingly, the metric sector is fixed as,

 $$ 
S_g = \frac{1}{16\pi G}\int d^4x\,\sqrt{-g}\,R .
 $$

No primitive cosmological term is permitted, as such a term would survive in vacuum and introduce an independent universal constant, contradicting vacuum rigidity. Curvature-like contributions may arise only as integration constants in non-vacuum or homogeneous regimes.

---

### Constraint sector

The constraint mode governs local gravitational balance and must close exactly under symmetry reduction. Quadratic closure requires that its contribution enter solely through a quadratic norm.

The admissible scalar contribution is therefore,

 $$ 
S_c = \int d^4x\,\sqrt{-g}\,\frac{1}{2}(\nabla\phi)^2 .
 $$

No potential term is allowed, as this would introduce an additional universal constant and modify vacuum behaviour.

---

### Redistributive sector

The redistributive mode cannot exist as an independent field. It must be slaved to the constraint sector and constructed as a composite object fixed by symmetry and admissibility.

The redistributive potential therefore takes the form,

 $$ 
A_\mu = \phi\,u_\mu ,
 $$

where $$u_\mu $$ is a direction field whose freedom is fixed by symmetry rather than by independent dynamics.

Quadratic closure and orthogonality permit only a Maxwell-type norm built from this composite field. The redistributive contribution is therefore,

 $$ 
S_r = -\frac{1}{4}\int d^4x\,\sqrt{-g}\,F_{\mu\nu}F^{\mu\nu} ,
 $$

with

 $$ 
F_{\mu\nu} = \nabla_\mu A_\nu - \nabla_\nu A_\mu .
 $$

No cross-terms with the constraint sector are permitted, as these would violate orthogonality and reintroduce hidden degrees of freedom.

---

### Conservation constraint

Redistribution must occur without creation or destruction of the scalar content it transports. Global conservation therefore imposes a continuity constraint, enforced by a Lagrange multiplier field \( \lambda \),

 $$ 
S_\lambda = \int d^4x\,\sqrt{-g}\,\lambda\,\nabla_\mu(\phi\,u^\mu) .
 $$

The form of this constraint is fixed uniquely by covariance and closure.

---

### Matter coupling

Universality and closure forbid direct coupling of matter to either the constraint or redistributive sectors. Matter therefore couples minimally to the metric alone,

 $$ 
S_{\text{matter}} = S_{\text{matter}}[g,\psi] .
 $$

No additional couplings are admissible.

---

### The unique closed action

Collecting the metric, constraint, redistributive, conservation, and matter sectors, the admissible closed classical gravitational action necessarily decomposes as,

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
 $$ 
S = S_g + S_c + S_r + S_\lambda + S_{\text{matter}} .
 $$

A representative of this unique equivalence class is therefore,

 $$ 
\begin{aligned}
S = {} & \frac{1}{16\pi G}\int d^4x\,\sqrt{-g}\,R
+ \int d^4x\,\sqrt{-g}\,\frac{1}{2}(\nabla\phi)^2 \\
& - \frac{1}{4}\int d^4x\,\sqrt{-g}\,F_{\mu\nu}F^{\mu\nu}
+ \int d^4x\,\sqrt{-g}\,\lambda\,\nabla_\mu(\phi\,u^\mu)
+ S_{\text{matter}}[g,\psi] .
\end{aligned}
 $$

Under the requirements of closure, orthogonality, and vacuum rigidity, this action is fixed uniquely up to equivalence. Any modification introduces independent degrees of freedom or violates closure; any omission renders the admissible structure incomplete.
