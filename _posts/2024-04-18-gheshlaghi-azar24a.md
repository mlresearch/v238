---
title: A General Theoretical Paradigm to Understand Learning from Human Preferences
abstract: 'The prevalent deployment of learning from human preferences through reinforcement
  learning (RLHF) relies on two important approximations: the first assumes that pairwise
  preferences can be substituted with pointwise rewards. The second assumes that a
  reward model trained on these pointwise rewards can generalize from collected data
  to out-of-distribution data sampled by the policy. Recently, Direct Preference Optimisation
  DPO has been proposed as an approach that bypasses the second approximation and
  learn directly a policy from collected data without the reward modelling stage.
  However, this method still heavily relies on the first approximation. In this paper
  we try to gain a deeper theoretical understanding of these practical algorithms.
  In particular we derive a new general objective called ${\Psi}$PO for learning from
  human preferences that is expressed in terms of pairwise preferences and therefore
  bypasses both approximations. This new general objective allows us to perform an
  in-depth analysis of the behavior of RLHF and DPO (as special cases of ${\Psi}$PO)
  and to identify their potential pitfalls. We then consider another special case
  for ${\Psi}$PO by setting $\Psi$ simply to Identity, for which we can derive an
  efficient optimisation procedure, prove performance guarantees and demonstrate its
  empirical superiority to DPO on some illustrative examples.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gheshlaghi-azar24a
month: 0
tex_title: A General Theoretical Paradigm to Understand Learning from Human Preferences
firstpage: 4447
lastpage: 4455
page: 4447-4455
order: 4447
cycles: false
bibtex_author: Gheshlaghi Azar, Mohammad and Daniel Guo, Zhaohan and Piot, Bilal and
  Munos, Remi and Rowland, Mark and Valko, Michal and Calandriello, Daniele
author:
- given: Mohammad
  family: Gheshlaghi Azar
- given: Zhaohan
  family: Daniel Guo
- given: Bilal
  family: Piot
- given: Remi
  family: Munos
- given: Mark
  family: Rowland
- given: Michal
  family: Valko
- given: Daniele
  family: Calandriello
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
pdf: https://proceedings.mlr.press/v238/gheshlaghi-azar24a/gheshlaghi-azar24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
