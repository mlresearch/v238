---
title: " Lexicographic Optimization: Algorithms and Stability "
abstract: " A lexicographic maximum of a set $X \\subseteq R^n$ is a vector in $X$
  whose smallest component is as large as possible, and subject to that requirement,
  whose second smallest component is as large as possible, and so on for the third
  smallest component, etc. Lexicographic maximization has numerous practical and theoretical
  applications, including fair resource allocation, analyzing the implicit regularization
  of learning algorithms, and characterizing refinements of game-theoretic equilibria.
  We prove that a minimizer in $X$ of the exponential loss function $L_c(x) = \\sum_i
  \\exp(-c x_i)$ converges to a lexicographic maximum of $X$ as $c \\to \\infty$,
  provided that $X$ is \\emph{stable} in the sense that a well-known iterative method
  for finding a lexicographic maximum of $X$ cannot be made to fail simply by reducing
  the required quality of each iterate by an arbitrarily tiny degree. Our result holds
  for both near and exact minimizers of the exponential loss, while earlier convergence
  results made much stronger assumptions about the set $X$ and only held for the exact
  minimizer. We are aware of no previous results showing a connection between the
  iterative method for computing a lexicographic maximum and exponential loss minimization.
  We show that every convex polytope is stable, but that there exist compact, convex
  sets that are not stable. We also provide the first analysis of the convergence
  rate of an exponential loss minimizer (near or exact) and discover a curious dichotomy:
  While the two smallest components of the vector converge to the lexicographically
  maximum values very quickly (at roughly the rate $\\frac{\\log n}{c}$), all other
  components can converge arbitrarily slowly. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: d-abernethy24a
month: 0
tex_title: " Lexicographic Optimization: Algorithms and Stability "
firstpage: 2503
lastpage: 2511
page: 2503-2511
order: 2503
cycles: false
bibtex_author: D Abernethy, Jacob and Schapire, Robert and Syed, Umar
author:
- given: Jacob
  family: D Abernethy
- given: Robert
  family: Schapire
- given: Umar
  family: Syed
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
pdf: https://proceedings.mlr.press/v238/d-abernethy24a/d-abernethy24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
