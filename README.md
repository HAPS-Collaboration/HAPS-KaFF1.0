# HAPS-KaFF1.0
Modern Determination of Charged-Pion and Charged-Kaon Fragmentation Functions from SIA and High-Precision COMPASS SIDIS Multiplicities


<p align="left">
  <img src="https://img.shields.io/badge/HAPS--KaFF1.0-Charged--Kaon%20FF%20Set-F57C00?style=for-the-badge" alt="HAPS-KaFF1.0">
</p>

# HAPS-KaFF1.0

**HAPS-KaFF1.0** is a charged-kaon fragmentation-function set developed within the **HAPS Collaboration**.

The grids accompany the analysis:

> **Modern Determination of Pion and Kaon Fragmentation Functions from SIA and High-Precision COMPASS SIDIS Multiplicities**
> Maryam Soleymaninia, Hamzeh Khanpour, Hubert Spiesberger, Majid Azizi, Michael Klasen, and Hadi Hashamipour

## Paper

* **Title:** Modern Determination of Pion and Kaon Fragmentation Functions from SIA and High-Precision COMPASS SIDIS Multiplicities
* **Authors:** Maryam Soleymaninia, Hamzeh Khanpour, Hubert Spiesberger, Majid Azizi, Michael Klasen, and Hadi Hashamipour
* **Collaboration:** HAPS Collaboration
* **arXiv:** https://arxiv.org/abs/2606.16754
* **INSPIRE:** https://inspirehep.net/literature/3168717
* **DOI:**
* **LHAPDF grids:** https://github.com/HAPS-Collaboration/HAPS-KaFF1.0

## Physics scope

HAPS-KaFF1.0 provides charged-kaon fragmentation functions extracted from a global QCD analysis combining single-inclusive electron-positron annihilation data with charge-separated semi-inclusive deep-inelastic-scattering multiplicities from HERMES and COMPASS.

The analysis incorporates modern COMPASS SIDIS measurements, including the 2025 proton-target multiplicities and the 2026 revised isoscalar-target multiplicities. The revised isoscalar measurements supersede the earlier COMPASS datasets used in previous global fragmentation-function analyses.

The charge-separated kaon measurements enhance the sensitivity to light-quark, unfavored, and strange-to-kaon fragmentation channels. In particular, they provide important information on the flavor structure of charged-kaon production, including the favored (u \to K^+) and (\bar{s} \to K^+) fragmentation channels.

The extraction is performed at next-to-leading order and within a next-to-next-to-leading-order perturbative-QCD setup. The resulting Monte Carlo replica sets are provided in standard LHAPDF format.

## Available LHAPDF grids

This repository contains six charged-kaon fragmentation-function sets:

| Grid directory            | Hadron combination | Perturbative order |
| ------------------------- | -----------------: | -----------------: |
| `HAPS-KaFF1.0-plus-NLO`   |                 K⁺ |                NLO |
| `HAPS-KaFF1.0-plus-NNLO`  |                 K⁺ |               NNLO |
| `HAPS-KaFF1.0-minus-NLO`  |                 K⁻ |                NLO |
| `HAPS-KaFF1.0-minus-NNLO` |                 K⁻ |               NNLO |
| `HAPS-KaFF1.0-sum-NLO`    |            K⁺ + K⁻ |                NLO |
| `HAPS-KaFF1.0-sum-NNLO`   |            K⁺ + K⁻ |               NNLO |

## Repository structure

```text
HAPS-KaFF1.0/
├── HAPS-KaFF1.0-minus-NLO/
├── HAPS-KaFF1.0-minus-NNLO/
├── HAPS-KaFF1.0-plus-NLO/
├── HAPS-KaFF1.0-plus-NNLO/
├── HAPS-KaFF1.0-sum-NLO/
├── HAPS-KaFF1.0-sum-NNLO/
└── README.md
```

## Companion charged-pion grids

The corresponding **HAPS-PiFF1.0** charged-pion fragmentation-function grids are available at:

https://github.com/HAPS-Collaboration/HAPS-PiFF1.0

## Citation

When using these grids, please cite:

```bibtex
%\cite{Soleymaninia:2026edd}
\bibitem{Soleymaninia:2026edd}
M.~Soleymaninia \textit{et al.} [HAPS],
%``Modern Determination of Pion and Kaon Fragmentation Functions from SIA and High-Precision COMPASS SIDIS Multiplicities,''
[arXiv:2606.16754 [hep-ph]].
%0 citations counted in INSPIRE as of 24 Jun 2026
```

## Related resources

* HAPS Collaboration: https://github.com/HAPS-Collaboration
* HAPS-PiFF1.0: https://github.com/HAPS-Collaboration/HAPS-PiFF1.0
* arXiv: https://arxiv.org/abs/2606.16754
* INSPIRE: https://inspirehep.net/literature/3168717
