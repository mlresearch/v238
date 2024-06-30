---
title: First Passage Percolation with Queried Hints
software: https://drive.google.com/drive/folders/1I4EMQNk2PRXUWlulgkDaWw2VpBc40Uw4?usp=sharing
abstract: Solving optimization problems leads to elegant and practical solutions in
  a wide variety of real-world applications. In many of those real-world applications,
  some of the information required to specify the relevant optimization problem is
  noisy, uncertain, and expensive to obtain. In this work, we study how much of that
  information needs to be queried in order to obtain an approximately optimal solution
  to the relevant problem. In particular, we focus on the shortest path problem in
  graphs with dynamic edge costs. We adopt the {\em first passage percolation} model
  from probability theory wherein a graph $G’$ is derived from a weighted base graph
  $G$ by multiplying each edge weight by an independently chosen, random number in
  $[1, \rho]$. Mathematicians have studied this model extensively when $G$ is a $d$-dimensional
  grid graph, but the behavior of shortest paths in this model is still poorly understood
  in general graphs. We make progress in this direction for a class of graphs that
  resemble real-world road networks. Specifically, we prove that if $G$ has a constant
  continuous doubling dimension, then for a given $s-t$ pair, we only need to probe
  the weights on $((\rho \log n )/ \epsilon)^{O(1)}$ edges in $G’$ in order to obtain
  a $(1 + \epsilon)$-approximation to the $s-t$ distance in $G’$. We also generalize
  the result to a correlated setting and demonstrate experimentally that probing improves
  accuracy in estimating $s-t$ distances.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: karntikoon24a
month: 0
tex_title: First Passage Percolation with Queried Hints
firstpage: 4231
lastpage: 4239
page: 4231-4239
order: 4231
cycles: false
bibtex_author: Karntikoon, Kritkorn and Shen, Yiheng and Gollapudi, Sreenivas and
  Kollias, Kostas and Schild, Aaron and K Sinop, Ali
author:
- given: Kritkorn
  family: Karntikoon
- given: Yiheng
  family: Shen
- given: Sreenivas
  family: Gollapudi
- given: Kostas
  family: Kollias
- given: Aaron
  family: Schild
- given: Ali
  family: K Sinop
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
pdf: https://proceedings.mlr.press/v238/karntikoon24a/karntikoon24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
