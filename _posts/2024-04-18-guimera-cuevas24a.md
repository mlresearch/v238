---
title: Robust Non-linear Normalization of Heterogeneous Feature Distributions with
  Adaptive Tanh-Estimators
software: https://github.com/FelipGC/Heterogeneous-Feature-Normalization
abstract: Feature normalization is a crucial step in machine learning that scales
  numerical values to improve model effectiveness. Noisy or impure datasets can pose
  a challenge for traditional normalization methods as they may contain outliers that
  violate statistical assumptions, leading to reduced model performance and increased
  unpredictability. Non-linear Tanh-Estimators (TE) have been found to provide robust
  feature normalization, but their fixed scaling factor may not be appropriate for
  all distributions of feature values. This work presents a refinement to the TE that
  employs the Wasserstein distance to adaptively estimate the optimal scaling factor
  for each feature individually against a specified target distribution. The results
  demonstrate that this adaptive approach can outperform the current TE method in
  the literature in terms of convergence speed by enabling better initial training
  starts, thus reducing or eliminating the need to re-adjust model weights during
  early training phases due to inadequately scaled features. Empirical evaluation
  was done on synthetic data, standard toy computer vision datasets, and a real-world
  numeric tabular dataset.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: guimera-cuevas24a
month: 0
tex_title: Robust Non-linear Normalization of Heterogeneous Feature Distributions
  with Adaptive Tanh-Estimators
firstpage: 406
lastpage: 414
page: 406-414
order: 406
cycles: false
bibtex_author: Guimer\`{a} Cuevas, Felip and Schmid, Helmut
author:
- given: Felip
  family: Guimerà Cuevas
- given: Helmut
  family: Schmid
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
pdf: https://proceedings.mlr.press/v238/guimera-cuevas24a/guimera-cuevas24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
