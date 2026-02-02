# Ananke (Gravitational Closure) Theorem

This repository contains the **Ananke (Gravitational Closure) Theorem**, a structural
classification result for **classical gravity**.

The theorem determines what gravitational field structures are admissible *in principle*
once gravity is required to **close as a classical field** with finite conserved energy
under covariance.

The result is **deductive and parameter-free**.  
It introduces no phenomenological modelling, no empirical tuning, and no additional matter
content. All conclusions follow by elimination from structural requirements alone.

---

## Scope and purpose

The purpose of the Ananke Theorem is **structural classification**, not modelling.

It answers the question:

> *Given that gravity closes as a classical field, what internal structure is admissible,
> and what follows necessarily from that structure?*

The theorem sits **downstream of the Fundamental Fields Theorem** and **upstream of all
phenomenological consequences**.

---

## Core result

Under the axioms of:

- classical covariance,
- quadratic closure with finite conserved energy,
- orthogonal modes of response,

the Ananke Theorem establishes that:

1. **Vacuum rigidity**  
   Isolated vacuum regimes admit **zero residual degrees of freedom**.  
   Closure is exact, exterior solutions are unique, and Newtonian gravity and General
   Relativity are recovered necessarily.

2. **Residual uniqueness**  
   In non-vacuum but symmetry-reduced regimes, closure admits **exactly one residual degree
   of freedom**.  
   This degree of freedom is redistributive rather than sourcing, introduces no independent
   vacuum modes or universal constants, and is uniquely constrained by conservation and
   orthogonality.

3. **Two-mode structure**  
   Gravity is a **polarised field** with orthogonal constraint and redistributive modes of
   response. No additional modes are admissible under closure.

4. **Action uniqueness**  
   The admissible covariant gravitational action is **unique up to equivalence**.  
   Field content, interaction structure, and matter coupling are fixed by structural
   necessity rather than modelling choice.

No phenomenological input or observational constraint is required at any stage.

---

## What this theorem does not do

This work does **not**:

- fit galaxy rotation curves or cosmological data;
- introduce dark matter or dark energy components;
- modify General Relativity by hand;
- assert empirical confirmation of closure.

Those questions are addressed strictly downstream.

---

## Repository structure

- [`paper/`](paper/)  
  Canonical paper artefacts.  
  The Zenodo record is the **version of record**; the PDF here is a mirror only.
  Editable source files are located in [`paper/source/`](paper/source/).

- [`pages/`](pages/)  
  Short technical pages that mirror the paper’s logical structure.
  These pages restate results for clarity and navigation and introduce no new claims.

---

## Pages overview

The `pages/` directory mirrors the paper’s section structure:

- [`pages/00-overview.md`](pages/00-overview.md) — overview  
- [`pages/01-problem-statement.md`](pages/01-problem-statement.md) — problem statement  
- [`pages/02-closure-principle.md`](pages/02-closure-principle.md) — closure principle  
- [`pages/03-scope.md`](pages/03-scope.md) — scope  
- [`pages/04-axioms.md`](pages/04-axioms.md) — axioms  
- [`pages/05-structural-consequences.md`](pages/05-structural-consequences.md) — structural consequences  
- [`pages/06-exhaustion-of-freedom.md`](pages/06-exhaustion-of-freedom.md) — exhaustion of freedom  
- [`pages/07-orthogonality-as-necessity.md`](pages/07-orthogonality-as-necessity.md) — orthogonality as necessity  
- [`pages/08-master-statement.md`](pages/08-master-statement.md) — consolidated theorem statement  
- [`pages/09-classification-of-admissible-response-structure.md`](pages/09-classification-of-admissible-response-structure.md) — classification result  
- [`pages/10-two-mode-structure-and-uniqueness.md`](pages/10-two-mode-structure-and-uniqueness.md) — two-mode structure and uniqueness  
- [`pages/11-vacuum-rigidity-and-zero-degree-of-freedom-closure.md`](pages/11-vacuum-rigidity-and-zero-degree-of-freedom-closure.md) — vacuum rigidity  
- [`pages/12-structural-consequences-of-vacuum-closure.md`](pages/12-structural-consequences-of-vacuum-closure.md) — vacuum consequences  
- [`pages/13-controlled-departure-from-vacuum-closure.md`](pages/13-controlled-departure-from-vacuum-closure.md) — controlled departure  
- [`pages/14-residual-degree-of-freedom-existence-uniqueness-and-character.md`](pages/14-residual-degree-of-freedom-existence-uniqueness-and-character.md) — residual degree of freedom  
- [`pages/15-slaving-conservation-and-non-vacuum-admissibility.md`](pages/15-slaving-conservation-and-non-vacuum-admissibility.md) — slaving and admissibility  
- [`pages/16-unique-admissible-covariant-action.md`](pages/16-unique-admissible-covariant-action.md) — unique action  
- [`pages/17-domain-of-validity-and-falsification-criteria.md`](pages/17-domain-of-validity-and-falsification-criteria.md) — falsification criteria  
- [`pages/18-conclusion.md`](pages/18-conclusion.md) — conclusion  
- [`pages/papers.md`](pages/papers.md) — Zenodo record, DOI, and PDF mirror  

---

## Relation to other repositories

This repository is part of a logically ordered framework:

- [`fundamental-fields-theorem`](https://github.com/ananke-research/fundamental-fields-theorem)  
  Establishes gravity as the unique classical field capable of closure.

- [`ananke-theorem`](https://github.com/ananke-research/ananke-theorem) *(this repository)*  
  Classifies the admissible closed gravitational field structure and unique action.

- [`phenomenological-consequences-of-ananke`](https://github.com/ananke-research/phenomenological-consequences-of-ananke)  
  Derives the observable galactic and cosmological scaling relations implied by that
  structure.

- [`structural-diagnostics-of-gravitational-closure`](https://github.com/ananke-research/structural-diagnostics-of-gravitational-closure)  
  Develops falsification criteria and diagnostic interpretation.

Each repository has a distinct logical role and should be cited independently.

---

## Citation

If you use or reference this work, cite the Zenodo record listed in
[`pages/papers.md`](pages/papers.md).

Machine-readable citation metadata is provided in
[`CITATION.cff`](CITATION.cff) at the repository root.

---

## License

This work is released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

See [`LICENSE`](LICENSE) for full terms.
