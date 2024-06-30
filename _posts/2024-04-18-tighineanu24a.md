---
title: Scalable Meta-Learning with Gaussian Processes
software: https://github.com/boschresearch/Scalable-Meta-Learning-with-Gaussian-Processes
abstract: Meta-learning is a powerful approach that exploits historical data to quickly
  solve new tasks from the same distribution. In the low-data regime, methods based
  on the closed-form posterior of Gaussian processes (GP) together with Bayesian optimization
  have achieved high performance. However, these methods are either computationally
  expensive or introduce assumptions that hinder a principled propagation of uncertainty
  between task models. This may disrupt the balance between exploration and exploitation
  during optimization. In this paper, we develop ScaML-GP, a modular GP model for
  meta-learning that is scalable in the number of tasks. Our core contribution is
  carefully designed multi-task kernel that enables hierarchical training and task
  scalability. Conditioning ScaML-GP on the meta-data exposes its modular nature yielding
  a test-task prior that combines the posteriors of meta-task GPs. In synthetic and
  real-world meta-learning experiments, we demonstrate that ScaML-GP can learn efficiently
  both with few and many meta-tasks.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: tighineanu24a
month: 0
tex_title: Scalable Meta-Learning with {G}aussian Processes
firstpage: 1981
lastpage: 1989
page: 1981-1989
order: 1981
cycles: false
bibtex_author: Tighineanu, Petru and Grossberger, Lukas and Baireuther, Paul and Skubch,
  Kathrin and Falkner, Stefan and Vinogradska, Julia and Berkenkamp, Felix
author:
- given: Petru
  family: Tighineanu
- given: Lukas
  family: Grossberger
- given: Paul
  family: Baireuther
- given: Kathrin
  family: Skubch
- given: Stefan
  family: Falkner
- given: Julia
  family: Vinogradska
- given: Felix
  family: Berkenkamp
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
pdf: https://proceedings.mlr.press/v238/tighineanu24a/tighineanu24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
