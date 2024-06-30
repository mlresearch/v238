---
title: Graph Pruning for Enumeration of Minimal Unsatisfiable Subsets
software: https://github.com/tufts-ml/GRAPE-MUST
abstract: Finding Minimal Unsatisfiable Subsets (MUSes) of boolean constraints is
  a common problem in infeasibility analysis of over-constrained systems. However,
  because of the exponential search space of the problem, enumerating MUSes is extremely
  time-consuming in real applications. In this work, we propose to prune formulas
  using a learned model to speed up MUS enumeration. We represent formulas as graphs
  and then develop a graph-based learning model to predict which part of the formula
  should be pruned. Importantly, the training of our model does not require labeled
  data. It does not even require training data from the target application because
  it extrapolates to data with different distributions. In our experiments we combine
  our model with existing MUS enumerators and validate its effectiveness in multiple
  benchmarks including a set of real-world problems outside our training distribution.
  The experiment results show that our method significantly accelerates MUS enumeration
  on average on these benchmark problems.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: lymperopoulos24a
month: 0
tex_title: Graph Pruning for Enumeration of Minimal Unsatisfiable Subsets
firstpage: 2647
lastpage: 2655
page: 2647-2655
order: 2647
cycles: false
bibtex_author: Lymperopoulos, Panagiotis and Liu, Liping
author:
- given: Panagiotis
  family: Lymperopoulos
- given: Liping
  family: Liu
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
pdf: https://proceedings.mlr.press/v238/lymperopoulos24a/lymperopoulos24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
