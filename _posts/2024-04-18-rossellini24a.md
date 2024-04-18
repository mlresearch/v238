---
title: " Integrating Uncertainty Awareness into Conformalized Quantile Regression "
software: " https://github.com/rrross/UACQR "
abstract: " Conformalized Quantile Regression (CQR) is a recently proposed method
  for constructing prediction intervals for a response $Y$ given covariates $X$, without
  making distributional assumptions. However, existing constructions of CQR can be
  ineffective for problems where the quantile regressors perform better in certain
  parts of the feature space than others. The reason is that the prediction intervals
  of CQR do not distinguish between two forms of uncertainty: first, the variability
  of the conditional distribution of $Y$ given $X$ (i.e., aleatoric uncertainty),
  and second, our uncertainty in estimating this conditional distribution (i.e., epistemic
  uncertainty). This can lead to intervals that are overly narrow in regions where
  epistemic uncertainty is high. To address this, we propose a new variant of the
  CQR methodology, Uncertainty-Aware CQR (UACQR), that explicitly separates these
  two sources of uncertainty to adjust quantile regressors differentially across the
  feature space. Compared to CQR, our methods enjoy the same distribution-free theoretical
  coverage guarantees, while demonstrating in our experiments stronger conditional
  coverage properties in simulated settings and real-world data sets alike. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: rossellini24a
month: 0
tex_title: " Integrating Uncertainty Awareness into Conformalized Quantile Regression "
firstpage: 1540
lastpage: 1548
page: 1540-1548
order: 1540
cycles: false
bibtex_author: Rossellini, Raphael and Foygel Barber, Rina and Willett, Rebecca
author:
- given: Raphael
  family: Rossellini
- given: Rina
  family: Foygel Barber
- given: Rebecca
  family: Willett
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
pdf: https://proceedings.mlr.press/v238/rossellini24a/rossellini24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
