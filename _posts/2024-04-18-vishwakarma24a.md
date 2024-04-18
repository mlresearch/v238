---
title: " Taming False Positives in Out-of-Distribution Detection with Human Feedback "
software: " https://github.com/2454511550Lin/TameFalsePositives-OOD "
abstract: " Robustness to out-of-distribution (OOD) samples is crucial for the safe
  deployment of machine learning models in the open world. Recent works have focused
  on designing scoring functions to quantify OOD uncertainty. Setting appropriate
  thresholds for these scoring functions for OOD detection is challenging as OOD samples
  are often unavailable up front. Typically, thresholds are set to achieve a desired
  true positive rate (TPR), e.g., $95%$ TPR. However, this can lead to very high false
  positive rates (FPR), ranging from 60 to 96%, as observed in the Open-OOD benchmark.
  In safety critical real-life applications, e.g., medical diagnosis, controlling
  the FPR is essential when dealing with various OOD samples dynamically. To address
  these challenges, we propose a mathematically grounded OOD detection framework that
  leverages expert feedback to \\emph{safely} update the threshold on the fly. We
  provide theoretical results showing that it is guaranteed to meet the FPR constraint
  at all times while minimizing the use of human feedback. Another key feature of
  our framework is that it can work with any scoring function for OOD uncertainty
  quantification. Empirical evaluation of our system on synthetic and benchmark OOD
  datasets shows that our method can maintain FPR at most $5%$ while maximizing TPR. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vishwakarma24a
month: 0
tex_title: " Taming False Positives in Out-of-Distribution Detection with Human Feedback "
firstpage: 1486
lastpage: 1494
page: 1486-1494
order: 1486
cycles: false
bibtex_author: Vishwakarma, Harit and Lin, Heguang and Korlakai Vinayak, Ramya
author:
- given: Harit
  family: Vishwakarma
- given: Heguang
  family: Lin
- given: Ramya
  family: Korlakai Vinayak
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
pdf: https://proceedings.mlr.press/v238/vishwakarma24a/vishwakarma24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
