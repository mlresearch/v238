---
title: 'Training a Tucker Model With Shared Factors: a Riemannian Optimization Approach'
software: https://github.com/johanDDC/tucker_riemopt
abstract: Factorization of a matrix into a product of two rectangular factors, is
  a classic tool in various machine learning applications. Tensor factorizations generalize
  this concept to more than two dimensions. In applications, where some of the tensor
  dimensions have the same size or encode the same objects (e.g., knowledge graphs
  with entity-relation-entity 3D tensors), it can also be beneficial for the respective
  factors to be shared. In this paper, we consider a well-known Tucker tensor factorization
  and study its properties under the shared factor constraint. We call it a shared-factor
  Tucker factorization (SF-Tucker). Since sharing factors breaks polylinearity of
  classical tensor factorizations, common optimization schemes such as alternating
  least squares become inapplicable. Nevertheless, as we show in this paper, a set
  of fixed-rank SF-Tucker tensors preserves a Riemannian manifold structure. Therefore,
  we develop efficient algorithms for the main ingredients of Riemannian optimization
  on the SF-Tucker manifold and implement a Riemannian optimization method with momentum.
  We showcase the benefits of our approach on several machine learning tasks including
  knowledge graph completion and compression of neural networks.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: peshekhonov24a
month: 0
tex_title: 'Training a {T}ucker Model With Shared Factors: a {R}iemannian Optimization
  Approach'
firstpage: 3304
lastpage: 3312
page: 3304-3312
order: 3304
cycles: false
bibtex_author: Peshekhonov, Ivan and Arzhantsev, Aleksey and Rakhuba, Maxim
author:
- given: Ivan
  family: Peshekhonov
- given: Aleksey
  family: Arzhantsev
- given: Maxim
  family: Rakhuba
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
pdf: https://proceedings.mlr.press/v238/peshekhonov24a/peshekhonov24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
