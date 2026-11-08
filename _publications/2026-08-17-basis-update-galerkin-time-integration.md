---
title: "Basis-update and Galerkin time integration in canonical matrix-product-state form"
collection: publications
category: manuscripts
author: "Milbradt, R. M."
permalink: /publication/20260817-basisupdategalerkintimeintegration
date: 2026-08-17
venue: 'Preprint'
arxivurl: 'https://arxiv.org/abs/2608.16994'
excerpt: ""
citation: 'Milbradt, R. M. et al. (2026). "Basis-update and Galerkin time integration in canonical matrix-product-state form." Preprint.'
---

Matrix product state algorithms must enlarge their bond spaces as entanglement grows and compress them to control cost. We formulate basis-update and Galerkin (BUG) time integration as a sequence of canonical MPS sweeps for Hamiltonians represented as matrix product operators. We show when two natural basis updates produce the same trial space and when transporting coefficients between successive bases preserves the represented state. Under these conditions, the existing first-order error bound for uncompressed tree-tensor-network BUG also applies to the alternating-endpoint MPS schedule. We verify the uncompressed implementation against an independent six-site calculation. We then compare BUG with two-site TDVP for 16-site transverse-field Ising and Haldane-Shastry dynamics. At matched timestep and truncation settings, BUG performs fewer local exponential actions and has lower runtime. These settings do not produce equal accuracy. The runtime versus accuracy curves cross for the Ising model and are close for the Haldane-Shastry model. The comparison therefore identifies model-dependent trade-offs rather than a general advantage for either method.

[arXiv: 2608.16994](https://arxiv.org/abs/2608.16994)
