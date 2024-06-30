---
title: Information Theoretically Optimal Sample Complexity of Learning Dynamical Directed
  Acyclic Graphs
software: https://github.com/mishfad/learningdynamical-dags
abstract: In this article, the optimal sample complexity of learning the underlying
  interactions or dependencies of a Linear Dynamical System (LDS) over a Directed
  Acyclic Graph (DAG) is studied. We call such a DAG underlying an LDS as dynamical
  DAG (DDAG). In particular, we consider a DDAG where the nodal dynamics are driven
  by unobserved exogenous noise sources that are wide-sense stationary (WSS) in time
  but are mutually uncorrelated, and have the same power spectral density (PSD). Inspired
  by the static DAG setting, a metric and an algorithm based on the PSD matrix of
  the observed time series are proposed to reconstruct the DDAG. It is shown that
  the optimal sample complexity (or length of state trajectory) needed to learn the
  DDAG is $n=\Theta(q\log(p/q))$, where $p$ is the number of nodes and $q$ is the
  maximum number of parents per node. To prove the sample complexity upper bound,
  a concentration bound for the PSD estimation is derived, under two different sampling
  strategies. A matching min-max lower bound using generalized Fano’s inequality also
  is provided, thus showing the order optimality of the proposed algorithm. The codes
  used in the paper are available at \url{https://github.com/Mishfad/Learning-Dynamical-DAGs}
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: shaikh-veedu24a
month: 0
tex_title: Information Theoretically Optimal Sample Complexity of Learning Dynamical
  Directed Acyclic Graphs
firstpage: 4636
lastpage: 4644
page: 4636-4644
order: 4636
cycles: false
bibtex_author: Shaikh Veedu, Mishfad and Deka, Deepjyoti and Salapaka, Murti
author:
- given: Mishfad
  family: Shaikh Veedu
- given: Deepjyoti
  family: Deka
- given: Murti
  family: Salapaka
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
pdf: https://proceedings.mlr.press/v238/shaikh-veedu24a/shaikh-veedu24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
