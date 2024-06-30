---
title: Efficient Graph Laplacian Estimation by Proximal Newton
software: https://github.com/BGUCompSci/GraphLaplacianEstimationProxNewton
abstract: The Laplacian-constrained Gaussian Markov Random Field (LGMRF) is a common
  multivariate statistical model for learning a weighted sparse dependency graph from
  given data. This graph learning problem can be formulated as a maximum likelihood
  estimation (MLE) of the precision matrix, subject to Laplacian structural constraints,
  with a sparsity-inducing penalty term. This paper aims to solve this learning problem
  accurately and efficiently. First, since the commonly used $\ell_1$-norm penalty
  is inappropriate in this setting and may lead to a complete graph, we employ the
  nonconvex minimax concave penalty (MCP), which promotes sparse solutions with lower
  estimation bias. Second, as opposed to existing first-order methods for this problem,
  we develop a second-order proximal Newton approach to obtain an efficient solver,
  utilizing several algorithmic features, such as using conjugate gradients, preconditioning,
  and splitting to active/free sets. Numerical experiments demonstrate the advantages
  of the proposed method in terms of both computational complexity and graph learning
  accuracy compared to existing methods.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: medvedovsky24a
month: 0
tex_title: Efficient Graph {L}aplacian Estimation by Proximal {N}ewton
firstpage: 1171
lastpage: 1179
page: 1171-1179
order: 1171
cycles: false
bibtex_author: Medvedovsky, Yakov and Treister, Eran and S Routtenberg, Tirza
author:
- given: Yakov
  family: Medvedovsky
- given: Eran
  family: Treister
- given: Tirza
  family: S Routtenberg
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
pdf: https://proceedings.mlr.press/v238/medvedovsky24a/medvedovsky24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
