---
title: Learning Extensive-Form Perfect Equilibria in Two-Player Zero-Sum Sequential
  Games
abstract: Designing efficient algorithms for computing refinements of the Nash equilibrium
  (NE) in two-player zero-sum sequential games is of paramount importance, since the
  NE may prescribe sub-optimal actions off the equilibrium path. The extensive-form
  perfect equilibrium (EFPE) amends such a weakness by accounting for the possibility
  that players may make mistakes. This is crucial in the real world, which involves
  humans with bounded rationality, and it is also key in boosting superhuman agents
  for games like Poker. Nevertheless, there are only few algorithms for computing
  NE refinements, which either lack convergence guarantees to exact equilibria or
  do not scale to large games. We provide the first efficient iterative algorithm
  that provably converges to an EFPE in two-player zero-sum sequential games. Our
  algorithm works by tracking a sequence of equilibria of regularized-perturbed games,
  by using a procedure that is specifically tailored to converge last iterate to such
  equilibria. The procedure can be implemented efficiently by visiting the game tree,
  making our method computationally appealing. We also empirically evaluate our algorithm,
  showing that its strategies are much more robust to players’ mistakes than those
  of state-of-the-art algorithms.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bernasconi24a
month: 0
tex_title: Learning Extensive-Form Perfect Equilibria in Two-Player Zero-Sum Sequential
  Games
firstpage: 2152
lastpage: 2160
page: 2152-2160
order: 2152
cycles: false
bibtex_author: Bernasconi, Martino and Marchesi, Alberto and Trov\`{o}, Francesco
author:
- given: Martino
  family: Bernasconi
- given: Alberto
  family: Marchesi
- given: Francesco
  family: Trovò
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
pdf: https://proceedings.mlr.press/v238/bernasconi24a/bernasconi24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
