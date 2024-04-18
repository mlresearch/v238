---
title: " Autoregressive Bandits "
software: " https://github.com/gianmarcogenalti/autoregressive-bandits "
abstract: " Autoregressive processes naturally arise in a large variety of real-world
  scenarios, including stock markets, sales forecasting, weather prediction, advertising,
  and pricing. When facing a sequential decision-making problem in such a context,
  the temporal dependence between consecutive observations should be properly accounted
  for guaranteeing convergence to the optimal policy. In this work, we propose a novel
  online learning setting, namely, Autoregressive Bandits (ARBs), in which the observed
  reward is governed by an autoregressive process of order $k$, whose parameters depend
  on the chosen action. We show that, under mild assumptions on the reward process,
  the optimal policy can be conveniently computed. Then, we devise a new optimistic
  regret minimization algorithm, namely, AutoRegressive Upper Confidence Bound (AR-UCB),
  that suffers sublinear regret of order $\\tilde{O} ( \\frac{(k+1)^{3/2}\\sqrt{nT}}{(1-\\Gamma)^2}
  )$, where $T$ is the optimization horizon, $n$ is the number of actions, and $\\Gamma
  < 1$ is a stability index of the process. Finally, we empirically validate our algorithm,
  illustrating its advantages w.r.t. bandit baselines and its robustness to misspecification
  of key parameters. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bacchiocchi24a
month: 0
tex_title: " Autoregressive Bandits "
firstpage: 937
lastpage: 945
page: 937-945
order: 937
cycles: false
bibtex_author: Bacchiocchi, Francesco and Genalti, Gianmarco and Maran, Davide and
  Mussi, Marco and Restelli, Marcello and Gatti, Nicola and Maria Metelli, Alberto
author:
- given: Francesco
  family: Bacchiocchi
- given: Gianmarco
  family: Genalti
- given: Davide
  family: Maran
- given: Marco
  family: Mussi
- given: Marcello
  family: Restelli
- given: Nicola
  family: Gatti
- given: Alberto
  family: Maria Metelli
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
pdf: https://proceedings.mlr.press/v238/bacchiocchi24a/bacchiocchi24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
