---
title: " Dissimilarity Bandits "
software: " https://github.com/paolob2/sed "
abstract: " We study a novel sequential decision-making setting, namely the dissimilarity
  bandits. At each round, the learner pulls an arm that provides a stochastic d-dimensional
  observation vector. The learner aims to identify the pair of arms with the maximum
  dissimilarity, where such an index is computed over pairs of expected observation
  vectors. We propose Successive Elimination for Dissimilarity (SED), a fixed-confidence
  best-pair identification algorithm based on sequential elimination. SED discards
  individual arms when there is statistical evidence that they cannot belong to a
  pair of most dissimilar arms and, thus, effectively exploits the structure of the
  setting by reusing the estimates of the expected observation vectors. We provide
  results on the sample complexity of SED, depending on {HP}, a novel index characterizing
  the complexity of identifying the pair of the most dissimilar arms. Then, we provide
  a sample complexity lower bound, highlighting the challenges of the identification
  problem for dissimilarity bandits, which is almost matched by our SED. Finally,
  we compare our approach over synthetically generated data and a realistic environmental
  monitoring domain against classical and combinatorial best-arm identification algorithms
  for the cases $d=1$ and $d>1$. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: battellani24a
month: 0
tex_title: " Dissimilarity Bandits "
firstpage: 3637
lastpage: 3645
page: 3637-3645
order: 3637
cycles: false
bibtex_author: Battellani, Paolo and Maria Metelli, Alberto and Trov\`{o}, Francesco
author:
- given: Paolo
  family: Battellani
- given: Alberto
  family: Maria Metelli
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
pdf: https://proceedings.mlr.press/v238/battellani24a/battellani24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
