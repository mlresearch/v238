---
title: " Graph Machine Learning through the Lens of Bilevel Optimization "
software: " https://github.com/amberyzheng/BloomGML "
abstract: " Bilevel optimization refers to scenarios whereby the optimal solution
  of a lower-level energy function serves as input features to an upper-level objective
  of interest. These optimal features typically depend on tunable parameters of the
  lower-level energy in such a way that the entire bilevel pipeline can be trained
  end-to-end. Although not generally presented as such, this paper demonstrates how
  a variety of graph learning techniques can be recast as special cases of bilevel
  optimization or simplifications thereof. In brief, building on prior work we first
  derive a more flexible class of energy functions that, when paired with various
  descent steps (e.g., gradient descent, proximal methods, momentum, etc.), form graph
  neural network (GNN) message-passing layers; critically, we also carefully unpack
  where any residual approximation error lies with respect to the underlying constituent
  message-passing functions. We then probe several simplifications of this framework
  to derive close connections with non-GNN-based graph learning approaches, including
  knowledge graph embeddings, various forms of label propagation, and efficient graph-regularized
  MLP models. And finally, we present supporting empirical results that demonstrate
  the versatility of the proposed bilevel lens, which we refer to as BloomGML, referencing
  that BiLevel Optimization Offers More Graph Machine Learning. Our code is available
  at \\url{https://github.com/amberyzheng/BloomGML}. Let graph ML bloom. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: yijia-zheng24a
month: 0
tex_title: " Graph Machine Learning through the Lens of Bilevel Optimization "
firstpage: 982
lastpage: 990
page: 982-990
order: 982
cycles: false
bibtex_author: Yijia Zheng, Amber and He, Tong and Qiu, Yixuan and Wang, Minjie and
  Wipf, David
author:
- given: Amber
  family: Yijia Zheng
- given: Tong
  family: He
- given: Yixuan
  family: Qiu
- given: Minjie
  family: Wang
- given: David
  family: Wipf
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
pdf: https://proceedings.mlr.press/v238/yijia-zheng24a/yijia-zheng24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
