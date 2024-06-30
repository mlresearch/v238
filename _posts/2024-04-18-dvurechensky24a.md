---
title: Analysis of Kernel Mirror Prox for Measure Optimization
abstract: By choosing a suitable function space as the dual to the non-negative measure
  cone, we study in a unified framework a class of functional saddle-point optimization
  problems, which we term the Mixed Functional Nash Equilibrium (MFNE), that underlies
  several existing machine learning algorithms, such as implicit generative models,
  distributionally robust optimization (DRO), and Wasserstein barycenters. We model
  the saddle-point optimization dynamics as an interacting Fisher-Rao-RKHS gradient
  flow when the function space is chosen as a reproducing kernel Hilbert space (RKHS).
  As a discrete time counterpart, we propose a primal-dual kernel mirror prox (KMP)
  algorithm, which uses a dual step in the RKHS, and a primal entropic mirror prox
  step. We then provide a unified convergence analysis of KMP in an infinite-dimensional
  setting for this class of MFNE problems, which establishes a convergence rate of
  $O(1/N)$ in the deterministic case and $O(1/\sqrt{N})$ in the stochastic case, where
  $N$ is the iteration counter. As a case study, we apply our analysis to DRO, providing
  algorithmic guarantees for DRO robustness and convergence.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: dvurechensky24a
month: 0
tex_title: Analysis of Kernel Mirror Prox for Measure Optimization
firstpage: 2350
lastpage: 2358
page: 2350-2358
order: 2350
cycles: false
bibtex_author: Dvurechensky, Pavel and Zhu, Jia-Jie
author:
- given: Pavel
  family: Dvurechensky
- given: Jia-Jie
  family: Zhu
date: 2024-04-18
address:
container-title: Proceedings of The 27th International Conference on Artificial Intelligence
  and Statistics
volume: '238'
genre: inproceedings
issued:
  date-parts:
  - 2024
  - 4
  - 18
pdf: https://proceedings.mlr.press/v238/dvurechensky24a/dvurechensky24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
