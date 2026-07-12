# Q11 — Temporal Casimir Rigidity and Closure of the Effective Metric

This repository contains the source of the **Q11 Cosmochrony paper**
*Temporal Casimir Rigidity and Closure of the Effective Metric: Identification of
$A_\tau = 2$*].

Paper Q5b leaves the temporal coefficient $A_\tau$ of the effective co-metric
$g^{\mu\nu} = \mathrm{diag}(-A_\tau, 2, 2, 2)$ as the **sole remaining free parameter**
of the spectral geometry programme (open problem Q5b-O3). This paper closes it.

## Core Result

$A_\tau = 2$, under the Q5a hypotheses and the spectral universality hypothesis [U] (U1),
in three steps:

1. **Cascade internalization lemma**: the temporal coordinate $\tau$ (BFS depth index $n$)
   has $\partial_\tau$ as the continuum limit of the cascade increment operator
   $T:\sigma_c(n)\mapsto\sigma_c(n+1)$, by the Carnot–Carathéodory convergence of Q5b (Pansu).
2. **[U]** (proved in U1) makes $T$ asymptotically $\mathrm{SU}(2)$-equivariant, so
   $\partial_\tau$ acts on $\operatorname{Sym}^2(V_\rho)$ without new irreducibles.
3. **Schur's lemma** forces the invariant form to be the Casimir $2\cdot\mathrm{Id}$; Q8 fixes
   the normalisation to unity.

The effective co-metric is therefore uniquely $g^{\mu\nu} = 2\,\eta^{\mu\nu}$ — **no free
parameter remains**. The temporal direction is the continuum image of the cascade depth, not
an additional geometric axis.

## Keywords

Temporal coordinate, Casimir rigidity, effective co-metric, Carnot–Carathéodory,
Schur's lemma, SU(2) equivariance, spectral universality.

## Repository Contents

```
q11/
├── tex/         # LaTeX sources (main + cosmochrony-bibliography.bib)
├── out/         # Compiled paper PDF (q11.pdf)
├── zenodo.json  # Zenodo deposition metadata
└── README.md
```

## Links

- 🔗 DOI: [10.5281/zenodo.20098387](https://doi.org/10.5281/zenodo.20098387)
- 🌐 Website: https://cosmochrony.org/science/emergent-geometry/q11/

## Citation

> J. Beau, *Temporal Casimir Rigidity and Closure of the Effective Metric: Identification
> of $A_\tau = 2$*, Zenodo, 2026. DOI: 10.5281/zenodo.20098387.

## Acknowledgements

Portions of the editorial refinement benefited from iterative interactions with large
language models, used as analytical assistants. All claims and final formulations remain
the sole responsibility of the author.
