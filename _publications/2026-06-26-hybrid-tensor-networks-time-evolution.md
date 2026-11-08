---
title: "Time Evolution on Hybrid Tensor Networks -- A Novel and Parallelizable Algorithm"
collection: publications
category: manuscripts
author: "Milbradt, R. M."
permalink: /publication/20260626-hybridtensornetworkstimeevolution
date: 2026-06-26
venue: 'Preprint'
arxivurl: 'https://arxiv.org/abs/2606.28169'
excerpt: ""
citation: 'Milbradt, R. M. et al. (2026). "Time Evolution on Hybrid Tensor Networks -- A Novel and Parallelizable Algorithm." Preprint.'
---

We develop a novel time-evolution algorithm for matrix product states based on the recently introduced hybrid tensor network (hTN) framework. We retain the tensors close to the boundary on the classical computer and offload the highly entangled inner ones to the quantum computer. In our variant, we employ the Basis Update and Galerkin (BUG) integrator to time-evolve the classical tensors, and we develop a coupling scheme between the classical and quantum parts. Our framework admits modular combination with any quantum time-evolution method, such as (classically pre-optimized) Trotterization. The ratio of classical and quantum tensor degrees of freedom can be dynamically adjusted during the time evolution, which can be advantageous when the classical memory requirements become prohibitive. The quantum and classical components can run in parallel during a single time step and are not constrained by synchronization barriers or mid-circuit measurements. We describe the detailed steps and pseudocode for our algorithm specialized for tensor networks originating from the matrix product state Ansatz.

[arXiv: 2606.28169](https://arxiv.org/abs/2606.28169)
