---
title: 'Fair Machine Unlearning: Data Removal while Mitigating Disparities'
software: https://github.com/AI4LIFE-GROUP/fair-unlearning
abstract: The Right to be Forgotten is a core principle outlined by regulatory frameworks
  such as the EU’s General Data Protection Regulation (GDPR). This principle allows
  individuals to request that their personal data be deleted from deployed machine
  learning models. While "forgetting" can be naively achieved by retraining on the
  remaining dataset, it is computationally expensive to do to so with each new request.
  As such, several machine unlearning methods have been proposed as efficient alternatives
  to retraining. These methods aim to approximate the predictive performance of retraining,
  but fail to consider how unlearning impacts other properties critical to real-world
  applications such as fairness. In this work, we demonstrate that most efficient
  unlearning methods cannot accommodate popular fairness interventions, and we propose
  the first fair machine unlearning method that can efficiently unlearn data instances
  from a fair objective. We derive theoretical results which demonstrate that our
  method can provably unlearn data and provably maintain fairness performance. Extensive
  experimentation with real-world datasets highlight the efficacy of our method at
  unlearning data instances while preserving fairness. Code is provided at https://github.com/AI4LIFE-GROUP/fair-unlearning.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: oesterling24a
month: 0
tex_title: 'Fair Machine Unlearning: Data Removal while Mitigating Disparities'
firstpage: 3736
lastpage: 3744
page: 3736-3744
order: 3736
cycles: false
bibtex_author: Oesterling, Alex and Ma, Jiaqi and Calmon, Flavio and Lakkaraju, Himabindu
author:
- given: Alex
  family: Oesterling
- given: Jiaqi
  family: Ma
- given: Flavio
  family: Calmon
- given: Himabindu
  family: Lakkaraju
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
pdf: https://proceedings.mlr.press/v238/oesterling24a/oesterling24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
