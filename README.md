# Ananke (Gravitational Closure) Theorem

This repository contains the **Ananke (Gravitational Closure) Theorem**, a structural
classification result for classical gravity.

The theorem determines what gravitational field structures are **admissible in principle**
once gravity is required to close as a classical field with finite conserved energy under
covariance. Its results are deductive, parameter-free, and independent of phenomenological
modelling.

---

## Scope and purpose

The purpose of the Ananke Theorem is **classification**, not model building.

It answers a single question:

> *What internal structure must gravity possess if it is to close as a classical field?*

The theorem introduces no empirical inputs, no fitting procedures, and no additional matter
content. All results follow by elimination from structural requirements alone.

---

## Core result

Under the axioms of:

- classical covariance,
- quadratic closure with finite conserved energy,
- orthogonal modes of response,

the Ananke Theorem establishes that gravity is a **polarised field** whose admissible
structure is uniquely constrained.

In particular:

1. **Vacuum rigidity**  
   In isolated vacuum regimes, all degrees of freedom are exhausted. Exterior solutions
   are rigid and unique, and Newtonian gravity and General Relativity are recovered
   necessarily.

2. **Residual uniqueness**  
   In non-vacuum but symmetry-reduced regimes, closure admits **exactly one** residual
   degree of freedom. This degree of freedom is redistributive rather than sourcing,
   introduces no independent vacuum modes, and is fixed structurally by conservation and
   orthogonality.

3. **Two-mode structure**  
   Gravity admits exactly two orthogonal modes of response: a constraint mode and a
   redistributive mode. No additional modes or charges are admissible.

4. **Action uniqueness**  
   The admissible covariant gravitational action is unique up to equivalence. Field
   content, coupling structure, and interaction terms are fixed by structural necessity
   rather than modelling choice.

No phenomenological input or observational constraint is required at any stage.

---

## What this theorem does not do

This work does **not**:

- propose a modified theory of gravity;
- introduce dark matter or dark energy;
- derive scaling laws or phenomenology;
- fit observational data;
- assert empirical confirmation of closure.

Those tasks are addressed in logically downstream repositories.

---

## Repository structure

- `paper/`  
  Canonical paper artefacts.  
  The Zenodo record is the **version of record**; the PDF here is a mirror only.
  Editable source files are located in `paper/source/`.

- `pages/`  
  Short technical pages that follow the paper’s logical development section by section.
  These pages restate results for clarity and navigation and introduce no new claims.

---

## Pages overview

The `pages/` directory mirrors the paper’s section structure:

- `pages/00-overview.md` — overview
- `pages/01-problem-statement.md` — problem statement
- `pages/02-closure-principle.md` — closure principle
- `pages/03-scope.md` — scope
- `pages/04-axioms.md` — axioms
- `pages/05-structural-consequences.md` — structural consequences
- `pages/06-exhaustion-of-freedom.md` — exhaustion of freedom
- `pages/07-orthogonality-as-necessity.md` — orthogonality as necessity
- `pages/08-master-statement.md` — consolidated theorem statement
- `pages/09-classification-of-admissible-response-structure.md` — classification result
- `pages/10-two-mode-structure-and-uniqueness.md` — two-mode structure and uniqueness
- `pages/11-vacuum-rigidity-and-zero-degree-of-freedom-closure.md` — vacuum rigidity
- `pages/12-structural-consequences-of-vacuum-closure.md` — vacuum consequences
- `pages/13-controlled-departure-from-vacuum-closure.md` — controlled departure
- `pages/14-residual-degree-of-freedom-existence-uniqueness-and-character.md` — residual DOF
- `pages/15-slaving-conservation-and-non-vacuum-admissibility.md` — slaving and admissibility
- `pages/16-unique-admissible-covariant-action.md` — unique action
- `pages/17-domain-of-validity-and-falsification-criteria.md` — falsification criteria
- `pages/18-conclusion.md` — conclusion
- `pages/papers.md` — Zenodo record, DOI, and PDF mirror

---

## Relation to other repositories

This repository occupies a central position in a logically ordered framework:

- `fundamental-fields-theorem`  
  Establishes gravity as the unique classical field capable of closure.

- `ananke-theorem` *(this repository)*  
  Classifies the admissible closed gravitational field structure and unique action.

- `phenomenological-consequences-of-ananke`  
  Derives the observable galactic and cosmological scaling relations implied by that
  structure.

- `structural-diagnostics-of-gravitational-closure`  
  Develops falsification criteria and diagnostic interpretation.

Each repository has a distinct logical role and should be cited independently.

---

## Citation

If you use or reference this work, cite the Zenodo record listed in `pages/papers.md`.
Machine-readable citation metadata is provided in `CITATION.cff` at the repository root.

---

## License

This work is released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)**
license. See `LICENSE` for details.
