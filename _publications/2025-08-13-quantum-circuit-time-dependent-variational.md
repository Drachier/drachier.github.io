---
title: "Quantum circuit simulation with a local time-dependent variational principle"
collection: publications
category: manuscripts
author: "Milbradt, R. M."
permalink: /publication/20250813-quantumcircuittimedependentvariational
date: 2025-08-13
venue: 'Preprint'

paperurl: 'https://doi.org/10.21203/rs.3.rs-8196476/v1'
arxivurl: 'https://arxiv.org/abs/2508.10096'
excerpt: ""
citation: 'Milbradt, R. M. et al. (2025). "Quantum circuit simulation with a local time-dependent variational principle." Preprint.'
---

Classical simulations of quantum circuits are vital for assessing potential quantum advantage and benchmarking devices, yet they require sophisticated methods to avoid the exponential growth of resources. Tensor network approaches, in particular matrix product states (MPS) combined with the time-evolving block decimation (TEBD) algorithm, currently dominate large-scale circuit simulations. These methods scale efficiently when entanglement is limited but suffer rapid bond dimension growth with increasing entanglement and handle long-range gates via costly SWAP insertions. Motivated by the success of the time-dependent variational principle (TDVP) in many-body physics, we reinterpret quantum circuits as a series of discrete time evolutions, using gate generators to construct an MPS-based circuit simulation via a local TDVP formulation. This addresses TEBD's key limitations by (1) naturally accommodating long-range gates and (2) optimally representing states on the MPS manifold. By diffusing entanglement more globally, the method suppresses local bond growth and reduces memory and runtime costs. We benchmark the approach on five 49-qubit circuits: three Hamiltonian circuits (1D open and periodic Heisenberg, 2D 7x7 Ising) and two algorithmic ones (quantum approximate optimization, hardware-efficient ansatz). Across all cases, our method yields substantial resource reductions over standard tools, establishing a new state-of-the-art for circuit simulation and enabling advances across quantum computing, condensed matter, and beyond.

[DOI: 10.21203/rs.3.rs-8196476/v1](https://doi.org/10.21203/rs.3.rs-8196476/v1)
