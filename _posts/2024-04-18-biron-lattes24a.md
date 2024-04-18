---
title: " autoMALA: Locally adaptive Metropolis-adjusted Langevin algorithm "
software: " https://github.com/Julia-Tempering/autoMALA-mev "
abstract: " Selecting the step size for the Metropolis-adjusted Langevin algorithm
  (MALA) is necessary in order to obtain satisfactory performance. However, finding
  an adequate step size for an arbitrary target distribution can be a difficult task
  and even the best step size can perform poorly in specific regions of the space
  when the target distribution is sufficiently complex. To resolve this issue we introduce
  autoMALA, a new Markov chain Monte Carlo algorithm based on MALA that automatically
  sets its step size at each iteration based on the local geometry of the target distribution.
  We prove that autoMALA has the correct invariant distribution, despite continual
  automatic adjustments of the step size. Our experiments demonstrate that autoMALA
  is competitive with related state-of-the-art MCMC methods, in terms of the number
  of log density evaluations per effective sample, and it outperforms state-of-the-art
  samplers on targets with varying geometries. Furthermore, we find that autoMALA
  tends to find step sizes comparable to optimally-tuned MALA when a fixed step size
  suffices for the whole domain. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: biron-lattes24a
month: 0
tex_title: " {autoMALA}: Locally adaptive {M}etropolis-adjusted {L}angevin algorithm "
firstpage: 4600
lastpage: 4608
page: 4600-4608
order: 4600
cycles: false
bibtex_author: Biron-Lattes, Miguel and Surjanovic, Nikola and Syed, Saifuddin and
  Campbell, Trevor and Bouchard-Cote, Alexandre
author:
- given: Miguel
  family: Biron-Lattes
- given: Nikola
  family: Surjanovic
- given: Saifuddin
  family: Syed
- given: Trevor
  family: Campbell
- given: Alexandre
  family: Bouchard-Cote
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
pdf: https://proceedings.mlr.press/v238/biron-lattes24a/biron-lattes24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
