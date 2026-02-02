# Ananke (Gravitational Closure) Theorem

This repository contains the **Ananke (Gravitational Closure) Theorem**, a structural classification result for classical gravity. The theorem determines what gravitational field structures are admissible *in principle* once gravity is required to close as a classical field with finite conserved energy under covariance.

The result is deductive and parameter-free. It introduces no phenomenological modelling, no empirical tuning, and no additional matter content. Its conclusions follow by elimination from structural requirements alone.

---

## Core result

Under the axioms of classical covariance, quadratic closure with finite conserved energy, and orthogonal modes of response:

1. **Vacuum rigidity:** isolated vacuum regimes admit zero residual degrees of freedom. Closure is exact, exterior solutions are unique, and Newtonian gravity and General Relativity are recovered necessarily.

2. **Residual uniqueness:** in non-vacuum but symmetry-reduced regimes, closure admits exactly one residual degree of freedom. This degree of freedom is redistributive rather than sourcing, introduces no independent vacuum modes or universal constants, and is uniquely constrained by conservation and orthogonality.

3. **Action uniqueness:** the admissible covariant gravitational action is unique up to equivalence. Field content, interaction structure, and matter coupling are fixed by structural necessity rather than modelling choice.

No phenomenological input or observational constraint is required at any stage.

---

## Repository structure

- `paper/` — canonical paper artefacts (PDF mirror and editable source). The Zenodo record is the version of record for citation purposes.
- `pages/` — short technical pages following the paper’s logical development; no new claims appear here.

---

## How to read

- Start with `pages/00-overview.md`.
- See `pages/08-master-statement.md` for the consolidated theorem.
- See `pages/16-unique-admissible-action.md` for the unique action statement.
- See `pages/papers.md` for the Zenodo record, DOI, and PDF mirror.

---

## Relation to other repositories

This repository sits within a larger logically ordered framework:

- `fundamental-fields-theorem` — establishes gravity as the unique classical field capable of closure.
- `phenomenological-consequences-of-ananke` — derives regime-dependent scaling laws from the classified structure.
- `structural-diagnostics-of-gravitational-closure` — develops diagnostic and falsification criteria implied by closure.

Each paper is housed in a separate repository and should be cited independently.

---

## Citation

If you use or reference this work, cite the Zenodo record listed in `pages/papers.md`. Machine-readable citation metadata is provided in `CITATION.cff` at the repository root.

While the Ananke Theorem itself is complete at the level of structural classification, its results imply that gravitational scaling laws across vacuum, galactic, and cosmological regimes arise as consequences of the same closed-field structure under different symmetry conditions; the explicit derivation of these laws is presented separately in the `phenomenological-consequences-of-ananke` repository and is not required for completion of the theorem.
