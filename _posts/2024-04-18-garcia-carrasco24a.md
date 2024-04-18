---
title: " How does GPT-2 Predict Acronyms? Extracting and Understanding a Circuit via
  Mechanistic Interpretability "
software: " https://github.com/jgcarrasco/acronyms_paper "
abstract: " Transformer-based language models are treated as black-boxes because of
  their large number of parameters and complex internal interactions, which is a serious
  safety concern. Mechanistic Interpretability (MI) intends to reverse-engineer neural
  network behaviors in terms of human-understandable components. In this work, we
  focus on understanding how GPT-2 Small performs the task of predicting three-letter
  acronyms. Previous works in the MI field have focused so far on tasks that predict
  a single token. To the best of our knowledge, this is the first work that tries
  to mechanistically understand a behavior involving the prediction of multiple consecutive
  tokens. We discover that the prediction is performed by a circuit composed of 8
  attention heads (${\\sim}5%$ of the total heads) which we classified in three groups
  according to their role. We also demonstrate that these heads concentrate the acronym
  prediction functionality. In addition, we mechanistically interpret the most relevant
  heads of the circuit and find out that they use positional information which is
  propagated via the causal mask mechanism. We expect this work to lay the foundation
  for understanding more complex behaviors involving multiple-token predictions. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: garcia-carrasco24a
month: 0
tex_title: " How does {GPT-2} Predict Acronyms? Extracting and Understanding a Circuit
  via Mechanistic Interpretability "
firstpage: 3322
lastpage: 3330
page: 3322-3330
order: 3322
cycles: false
bibtex_author: Garc\'{i}a-Carrasco, Jorge and Mat\'{e}, Alejandro and Carlos Trujillo,
  Juan
author:
- given: Jorge
  family: García-Carrasco
- given: Alejandro
  family: Maté
- given: Juan
  family: Carlos Trujillo
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
pdf: https://proceedings.mlr.press/v238/garcia-carrasco24a/garcia-carrasco24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
