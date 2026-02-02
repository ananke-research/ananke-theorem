## 00 — Overview

The **Ananke (Gravitational Closure) Theorem** establishes a foundational structural result for classical gravity.  
It determines what gravitational field structures are admissible *in principle* once gravity is required to close as a classical field with finite conserved energy under covariance.

The theorem does not introduce new dynamics, phenomenological fits, or empirical parameters.  
Instead, it classifies the internal structure of gravity by eliminating all field constructions that fail to satisfy closure.

The central result is that closure imposes strict and exhaustive constraints on gravitational response. Under these constraints, gravity is neither geometry alone nor an arbitrary collection of fields, but a **polarised field** admitting exactly two orthogonal modes of response whose structure is fixed by necessity.

---

### Logical status

The Ananke Theorem is a **classification theorem**, not a model proposal.  
Its conclusions follow deductively from structural requirements placed on classical gravitational fields.

No observational inputs are used.  
No phenomenological tuning is performed.  
No regime-dependent assumptions are introduced.

The theorem answers a single question:

> *What gravitational field structures remain admissible once closure is required?*

---

### Closure as the organising principle

Closure is defined as the requirement that the gravitational field account fully for its own conserved energy within the field description itself, without auxiliary bookkeeping, hidden regulators, or unconstrained functional freedom.

When closure is imposed, many formally covariant constructions are excluded. The remaining admissible structures are fixed not by choice, but by exhaustion of alternatives.

Closure therefore acts as a **selection principle**, determining the internal architecture of gravity independently of empirical detail.

---

### From structure to action

Imposing classical covariance, quadratic closure with finite conserved energy, exhaustion of functional freedom under symmetry, and forced orthogonality uniquely fixes the admissible response structure of gravity.

At the level of the action, this structure is most transparently displayed in **schematic form**.

---

### Schematic form of the closed action

Any admissible closed classical gravitational action must decompose as

 $$
\begin{array}{l}
S
=\int d^4x\,\sqrt{-g}\,
\Big[
\underbrace{\mathcal{L}_{\rm EH}(g)}_{\text{metric (geometric / vacuum-rigid) response}}
\\
\qquad
+\underbrace{\mathcal{L}_{\rm L}(\phi)}_{\text{longitudinal (constraint) sector}}
+\underbrace{\mathcal{L}_{\rm T}(A_\mu)}_{\text{transverse (redistributive) sector}}
+\underbrace{\mathcal{L}_{\rm cl}(\lambda,\phi,u^\mu)}_{\text{closure enforcement (conservation \ orthogonality)}}
\Big]
+\underbrace{S_{\rm matter}[g,\psi]}_{\text{universal matter coupling}} .
\end{array}
 $$

This decomposition is not assumed. Each sector is required by closure:

- the metric sector enforces vacuum rigidity and unique exterior geometry,
- the longitudinal sector enforces local gravitational balance,
- the transverse sector realises the single admissible redistributive degree of freedom,
- the closure enforcement sector imposes conservation and orthogonality without introducing independent degrees of freedom,
- matter couples universally through the metric alone.

No additional sectors are admissible, and no sector may be omitted without violating closure.

---

### Explicit realisation

Up to boundary terms, invertible local field redefinitions, and normalisation conventions, the unique admissible closed classical gravitational action takes the explicit form

$$ \begin{array}{l} S=\frac{1}{16\pi G}\int d^4x\,\sqrt{-g}\,R \\\\ \qquad+\frac{1}{2}\int d^4x\,\sqrt{-g}\,(\nabla\phi)^2 -\frac{1}{4}\int d^4x\,\sqrt{-g}\,F_{\mu\nu}F^{\mu\nu} +\int d^4x\,\sqrt{-g}\,\lambda\,\nabla_\mu(\phi\,u^\mu) +S_{\mathrm{matter}}[g,\psi]. \end{array} $$ with $$ (\nabla\phi)^2 \equiv g^{\mu\nu}\nabla_\mu\phi\,\nabla_\nu\phi, \qquad F_{\mu\nu}=\nabla_\mu A_\nu-\nabla_\nu A_\mu . $$

The redistributive potential is slaved to the constraint sector via

 $$
A_\mu = \phi\,u_\mu ,
 $$

and does not constitute an independent field.

---

### Uniqueness

Under the requirements of closure, orthogonality, and vacuum rigidity, this action is fixed uniquely up to equivalence. Any modification introduces independent degrees of freedom or violates closure; any omission renders the admissible structure incomplete.

---

### Scope of what follows

The pages in this repository unpack the structural reasoning leading to this result. Phenomenological consequences, regime-specific behaviour, and observational diagnostics are treated downstream and do not enter the theorem itself.

Within its stated domain, the Ananke Theorem provides a complete and exact classification of admissible classical gravitational structure.
