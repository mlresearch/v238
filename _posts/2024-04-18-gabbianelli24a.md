---
title: Offline Primal-Dual Reinforcement Learning for Linear MDPs
abstract: Offline Reinforcement Learning (RL) aims to learn a near-optimal policy
  from a fixed dataset of transitions collected by another policy. This problem has
  attracted a lot of attention recently, but most existing methods with strong theoretical
  guarantees are restricted to finite-horizon or tabular settings. In contrast, few
  algorithms for infinite-horizon settings with function approximation and minimal
  assumptions on the dataset are both sample and computationally efficient. Another
  gap in the current literature is the lack of theoretical analysis for the average-reward
  setting, which is more challenging than the discounted setting. In this paper, we
  address both of these issues by proposing a primal-dual optimization method based
  on the linear programming formulation of RL. Our key contribution is a new reparametrization
  that allows us to derive low-variance gradient estimators that can be used in a
  stochastic optimization scheme using only samples from the behavior policy. Our
  method finds an $\varepsilon$-optimal policy with $O(\varepsilon^{-4})$ samples,
  while being computationally efficient for infinite-horizon discounted and average-reward
  MDPs with realizable linear function approximation and partial coverage. Moreover,
  to the best of our knowledge, this is the first theoretical result for average-reward
  offline RL.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gabbianelli24a
month: 0
tex_title: Offline Primal-Dual Reinforcement Learning for Linear {MDPs}
firstpage: 3169
lastpage: 3177
page: 3169-3177
order: 3169
cycles: false
bibtex_author: Gabbianelli, Germano and Neu, Gergely and Papini, Matteo and M Okolo,
  Nneka
author:
- given: Germano
  family: Gabbianelli
- given: Gergely
  family: Neu
- given: Matteo
  family: Papini
- given: Nneka
  family: M Okolo
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
pdf: https://proceedings.mlr.press/v238/gabbianelli24a/gabbianelli24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
