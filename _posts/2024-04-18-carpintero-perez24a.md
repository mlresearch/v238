---
title: Gaussian process regression with Sliced Wasserstein Weisfeiler-Lehman graph
  kernels
software: https://gitlab.com/drti/swwl/
abstract: Supervised learning has recently garnered significant attention in the field
  of computational physics due to its ability to effectively extract complex patterns
  for tasks like solving partial differential equations, or predicting material properties.
  Traditionally, such datasets consist of inputs given as meshes with a large number
  of nodes representing the problem geometry (seen as graphs), and corresponding outputs
  obtained with a numerical solver. This means the supervised learning model must
  be able to handle large and sparse graphs with continuous node attributes. In this
  work, we focus on Gaussian process regression, for which we introduce the Sliced
  Wasserstein Weisfeiler-Lehman (SWWL) graph kernel. In contrast to existing graph
  kernels, the proposed SWWL kernel enjoys positive definiteness and a drastic complexity
  reduction, which makes it possible to process datasets that were previously impossible
  to handle. The new kernel is first validated on graph classification for molecular
  datasets, where the input graphs have a few tens of nodes. The efficiency of the
  SWWL kernel is then illustrated on graph regression in computational fluid dynamics
  and solid mechanics, where the input graphs are made up of tens of thousands of
  nodes.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: carpintero-perez24a
month: 0
tex_title: "{G}aussian process regression with Sliced {W}asserstein {W}eisfeiler-{L}ehman
  graph kernels"
firstpage: 1297
lastpage: 1305
page: 1297-1305
order: 1297
cycles: false
bibtex_author: Carpintero Perez, Rapha\"{e}l and Da Veiga, S\'{e}bastien and Garnier,
  Josselin and Staber, Brian
author:
- given: Raphaël
  family: Carpintero Perez
- given: Sébastien
  family: Da Veiga
- given: Josselin
  family: Garnier
- given: Brian
  family: Staber
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
pdf: https://proceedings.mlr.press/v238/carpintero-perez24a/carpintero-perez24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
