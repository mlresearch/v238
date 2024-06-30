---
title: Weight-Sharing Regularization
software: https://github.com/motahareh-sohrabi/weight-sharing-regularization
abstract: Weight-sharing is ubiquitous in deep learning. Motivated by this, we propose
  a “weight-sharing regularization” penalty on the weights $w \in \mathbb{R}^d$ of
  a neural network, defined as $\mathcal{R}(w) = \frac{1}{d - 1}\sum_{i > j}^d |w_i
  - w_j|$. We study the proximal mapping of $\mathcal{R}$ and provide an intuitive
  interpretation of it in terms of a physical system of interacting particles. We
  also parallelize existing algorithms for $\mathrm{prox}_{\mathcal{R}}$ (to run on
  GPU) and find that one of them is fast in practice but slow ($O(d)$) for worst-case
  inputs. Using the physical interpretation, we design a novel parallel algorithm
  which runs in $O(\log^3 d)$ when sufficient processors are available, thus guaranteeing
  fast training. Our experiments reveal that weight-sharing regularization enables
  fully connected networks to learn convolution-like filters even when pixels have
  been shuffled while convolutional neural networks fail in this setting. Our code
  is available on \href{https://github.com/motahareh-sohrabi/weight-sharing-regularization}{github}.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: shakerinava24a
month: 0
tex_title: Weight-Sharing Regularization
firstpage: 4204
lastpage: 4212
page: 4204-4212
order: 4204
cycles: false
bibtex_author: Shakerinava, Mehran and MS Sohrabi, Motahareh and Ravanbakhsh, Siamak
  and Lacoste-Julien, Simon
author:
- given: Mehran
  family: Shakerinava
- given: Motahareh
  family: MS Sohrabi
- given: Siamak
  family: Ravanbakhsh
- given: Simon
  family: Lacoste-Julien
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
pdf: https://proceedings.mlr.press/v238/shakerinava24a/shakerinava24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
