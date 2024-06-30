---
title: Discriminator Guidance for Autoregressive Diffusion Models
software: https://github.com/filipekstrm/graph_ardm
abstract: We introduce discriminator guidance in the setting of Autoregressive Diffusion
  Models. The use of a discriminator to guide a diffusion process has previously been
  used for continuous diffusion models, and in this work we derive ways of using a
  discriminator together with a pretrained generative model in the discrete case.
  First, we show that using an optimal discriminator will correct the pretrained model
  and enable exact sampling from the underlying data distribution. Second, to account
  for the realistic scenario of using a sub-optimal discriminator, we derive a sequential
  Monte Carlo algorithm which iteratively takes the predictions from the discriminator
  into account during the generation process. We test these approaches on the task
  of generating molecular graphs and show how the discriminator improves the generative
  performance over using only the pretrained model.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ekstrom-kelvinius24a
month: 0
tex_title: Discriminator Guidance for Autoregressive Diffusion Models
firstpage: 3403
lastpage: 3411
page: 3403-3411
order: 3403
cycles: false
bibtex_author: Ekstr\"{o}m Kelvinius, Filip and Lindsten, Fredrik
author:
- given: Filip
  family: Ekström Kelvinius
- given: Fredrik
  family: Lindsten
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
pdf: https://proceedings.mlr.press/v238/ekstrom-kelvinius24a/ekstrom-kelvinius24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
