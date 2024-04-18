---
title: " Sharpened Lazy Incremental Quasi-Newton Method "
software: " https://github.com/aakashlahoti/sliqn "
abstract: " The problem of minimizing the sum of $n$ functions in $d$ dimensions is
  ubiquitous in machine learning and statistics. In many applications where the number
  of observations $n$ is large, it is necessary to use incremental or stochastic methods,
  as their per-iteration cost is independent of $n$. Of these, Quasi-Newton (QN) methods
  strike a balance between the per-iteration cost and the convergence rate. Specifically,
  they exhibit a superlinear rate with $O(d^2)$ cost in contrast to the linear rate
  of first-order methods with $O(d)$ cost and the quadratic rate of second-order methods
  with $O(d^3)$ cost. However, existing incremental methods have notable shortcomings:
  Incremental Quasi-Newton (IQN) only exhibits asymptotic superlinear convergence.
  In contrast, Incremental Greedy BFGS (IGS) offers explicit superlinear convergence
  but suffers from poor empirical performance and has a per-iteration cost of $O(d^3)$.
  To address these issues, we introduce the Sharpened Lazy Incremental Quasi-Newton
  Method (SLIQN) that achieves the best of both worlds: an explicit superlinear convergence
  rate, and superior empirical performance at a per-iteration $O(d^2)$ cost. SLIQN
  features two key changes: first, it incorporates a hybrid strategy of using both
  classic and greedy BFGS updates, allowing it to empirically outperform both IQN
  and IGS. Second, it employs a clever constant multiplicative factor along with a
  lazy propagation strategy, which enables it to have a cost of $O(d^2)$. Additionally,
  our experiments demonstrate the superiority of SLIQN over other incremental and
  stochastic Quasi-Newton variants and establish its competitiveness with second-order
  incremental methods. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sunil-lahoti24a
month: 0
tex_title: " Sharpened Lazy Incremental Quasi-{N}ewton Method "
firstpage: 4735
lastpage: 4743
page: 4735-4743
order: 4735
cycles: false
bibtex_author: Sunil Lahoti, Aakash and Senapati, Spandan and Rajawat, Ketan and Koppel,
  Alec
author:
- given: Aakash
  family: Sunil Lahoti
- given: Spandan
  family: Senapati
- given: Ketan
  family: Rajawat
- given: Alec
  family: Koppel
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
pdf: https://proceedings.mlr.press/v238/sunil-lahoti24a/sunil-lahoti24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
