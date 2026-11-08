---
title: "Tree Tensor Networks Methods for Efficient Calculation of Molecular Vibrational Spectra"
collection: publications
category: manuscripts
author: "Milbradt, R. M."
permalink: /publication/20260721-treetensornetworksvibrationalspectra
date: 2026-07-21
venue: 'The Journal of Chemical Physics'

paperurl: 'https://doi.org/10.1063/5.0323779'
arxivurl: 'https://arxiv.org/abs/2512.15875'
excerpt: ""
citation: 'Milbradt, R. M. et al. (2026). "Tree Tensor Networks Methods for Efficient Calculation of Molecular Vibrational Spectra." The Journal of Chemical Physics.'
---

We develop and employ general Tree Tensor Networks (TTNs) to compute the vibrational spectra for two model systems: a set of 64-dimensional coupled oscillators and acetonitrile. We explore various tree architectures, ranging from the simple linear structure of Matrix Product States (MPS), to trees where only the leaf nodes carry a physical leg -- as commonly seen in the underlying ansatz of the Multilayer Multiconfiguration Time-Dependent Hartree (ML-MCTDH) method -- and further to more general trees in which all nodes are allowed to possess a physical leg. In addition, we implement Locally Optimal Block Preconditioned Conjugate Gradient (LOBPCG) methods and Inverse Iteration methods as eigensolvers. Benchmarking runtime and accuracy shows that all tested topologies can reach high accuracy. For acetonitrile, inverse-iteration refinement brings all 84 computed states below 1~cm$^{-1}$ error, while the fork-4 tree, a comb-like tree with four backbone nodes, provides the best overall balance between accuracy and cost. MPS remains computationally attractive, whereas more connected trees generally improve accuracy at fixed bond dimension. All numerical simulations were performed using PyTreeNet, a Python package designed for flexible tensor network computations.

[DOI: 10.1063/5.0323779](https://doi.org/10.1063/5.0323779)
