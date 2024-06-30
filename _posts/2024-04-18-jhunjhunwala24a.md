---
title: 'FedFisher: Leveraging Fisher Information for One-Shot Federated Learning'
software: https://github.com/Divyansh03/FedFisher
abstract: Standard federated learning (FL) algorithms typically require multiple rounds
  of communication between the server and the clients, which has several drawbacks,
  including requiring constant network connectivity, repeated investment of computational
  resources, and susceptibility to privacy attacks. One-Shot FL is a new paradigm
  that aims to address this challenge by enabling the server to train a global model
  in a single round of communication. In this work, we present FedFisher, a novel
  algorithm for one-shot FL that makes use of Fisher information matrices computed
  on local client models, motivated by a Bayesian perspective of FL. First, we theoretically
  analyze FedFisher for two-layer over-parameterized ReLU neural networks and show
  that the error of our one-shot FedFisher global model becomes vanishingly small
  as the width of the neural networks and amount of local training at clients increases.
  Next, we propose practical variants of FedFisher using the diagonal Fisher and K-FAC
  approximation for the full Fisher and highlight their communication and compute
  efficiency for FL. Finally, we conduct extensive experiments on various datasets,
  which show that these variants of FedFisher consistently improve over competing
  baselines.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: jhunjhunwala24a
month: 0
tex_title: "{FedFisher}: Leveraging {F}isher Information for One-Shot Federated Learning"
firstpage: 1612
lastpage: 1620
page: 1612-1620
order: 1612
cycles: false
bibtex_author: Jhunjhunwala, Divyansh and Wang, Shiqiang and Joshi, Gauri
author:
- given: Divyansh
  family: Jhunjhunwala
- given: Shiqiang
  family: Wang
- given: Gauri
  family: Joshi
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
pdf: https://proceedings.mlr.press/v238/jhunjhunwala24a/jhunjhunwala24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
