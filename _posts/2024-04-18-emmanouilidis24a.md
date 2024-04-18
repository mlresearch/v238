---
title: " Stochastic Extragradient with Random Reshuffling: Improved Convergence for
  Variational Inequalities "
software: " https://github.com/emmanouilidisk/Stochastic-ExtraGradient-with-Random-Reshuffling "
abstract: " The Stochastic Extragradient (SEG) method is one of the most popular algorithms
  for solving finite-sum min-max optimization and variational inequality problems
  (VIPs) appearing in various machine learning tasks. However, existing convergence
  analyses of SEG focus on its with-replacement variants, while practical implementations
  of the method randomly reshuffle components and sequentially use them. Unlike the
  well-studied with-replacement variants, SEG with Random Reshuffling (SEG-RR) lacks
  established theoretical guarantees. In this work, we provide a convergence analysis
  of SEG-RR for three classes of VIPs: (i) strongly monotone, (ii) affine, and (iii)
  monotone. We derive conditions under which SEG-RR achieves a faster convergence
  rate than the uniform with-replacement sampling SEG. In the monotone setting, our
  analysis of SEG-RR guarantees convergence to an arbitrary accuracy without large
  batch sizes, a strong requirement needed in the classical with-replacement SEG.
  As a byproduct of our results, we provide convergence guarantees for Shuffle Once
  SEG (shuffles the data only at the beginning of the algorithm) and the Incremental
  Extragradient (does not shuffle the data). We supplement our analysis with experiments
  validating empirically the superior performance of SEG-RR over the classical with-replacement
  sampling SEG. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: emmanouilidis24a
month: 0
tex_title: " Stochastic Extragradient with Random Reshuffling: Improved Convergence
  for Variational Inequalities "
firstpage: 3682
lastpage: 3690
page: 3682-3690
order: 3682
cycles: false
bibtex_author: Emmanouilidis, Konstantinos and Vidal, Rene and Loizou, Nicolas
author:
- given: Konstantinos
  family: Emmanouilidis
- given: Rene
  family: Vidal
- given: Nicolas
  family: Loizou
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
pdf: https://proceedings.mlr.press/v238/emmanouilidis24a/emmanouilidis24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
