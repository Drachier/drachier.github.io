---
title: "Large-scale stochastic simulation of open quantum systems"
collection: publications
category: manuscripts
author: "Milbradt, R. M."
permalink: /publication/20251210-largescalestochasticsimulation
date: 2025-12-10
venue: 'Nature Communications'

paperurl: 'https://doi.org/10.1038/s41467-025-66846-x'
arxivurl: 'https://arxiv.org/abs/2501.17913'
excerpt: ""
citation: 'Milbradt, R. M. et al. (2025). "Large-scale stochastic simulation of open quantum systems." Nature Communications.'
---

Understanding the precise interaction mechanisms between quantum systems and their environment is crucial for advancing stable quantum technologies, designing reliable experimental frameworks, and building accurate models of real-world phenomena. However, simulating open quantum systems, which feature complex non-unitary dynamics, poses significant computational challenges that require innovative methods to overcome. In this work, we introduce the tensor jump method (TJM), a scalable, embarrassingly parallel algorithm for stochastically simulating large-scale open quantum systems, specifically Markovian dynamics captured by Lindbladians. This method is built on three core principles where, in particular, we extend the Monte Carlo wave function (MCWF) method to matrix product states, use a dynamic time-dependent variational principle (TDVP) to significantly reduce errors during time evolution, and introduce what we call a sampling MPS to drastically reduce the dependence on the simulation's time step size. We demonstrate that this method scales more effectively than previous methods and ensures convergence to the Lindbladian solution independent of system size, which we show both rigorously and numerically. Finally, we provide evidence of its utility by simulating Lindbladian dynamics of XXX Heisenberg models up to a thousand spins using a consumer-grade CPU. This work represents a significant step forward in the simulation of large-scale open quantum systems, with the potential to enable discoveries across various domains of quantum physics, particularly those where the environment plays a fundamental role, and to both dequantize and facilitate the development of more stable quantum hardware.

[DOI: 10.1038/s41467-025-66846-x](https://doi.org/10.1038/s41467-025-66846-x)
