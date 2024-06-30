---
title: Differentially Private Reward Estimation with Preference Feedback
software: https://github.com/sayakrc/Differentialy_Private_Estimation
abstract: Learning from preference-based feedback has recently gained considerable
  traction as a promising approach to align generative models with human interests.
  Instead of relying on numerical rewards, the generative models are trained using
  reinforcement learning with human feedback (RLHF). These approaches first solicit
  feedback from human labelers typically in the form of pairwise comparisons between
  two possible actions, then estimate a reward model using these comparisons, and
  finally employ a policy based on the estimated reward model. An adversarial attack
  in any step of the above pipeline might reveal private and sensitive information
  of human labelers. In this work, we adopt the notion of \emph{label differential
  privacy} (DP) and focus on the problem of reward estimation from preference-based
  feedback while protecting privacy of each individual labelers. Specifically, we
  consider the parametric Bradley-Terry-Luce (BTL) model for such pairwise comparison
  feedback involving a latent reward parameter $\theta^* \in \mathbb{R}^d$. Within
  a standard minimax estimation framework, we provide tight upper and lower bounds
  on the error in estimating $\theta^*$ under both \emph{local} and \emph{central}
  models of DP. We show, for a given privacy budget $\epsilon$ and number of samples
  $n$, that the additional cost to ensure label-DP under local model is $\Theta \big(\frac{1}{
  e^\epsilon-1}\sqrt{\frac{d}{n}}\big)$, while it is $\Theta\big(\frac{\sqrt{d}}{\epsilon
  n} \big)$ under the weaker central model. We perform simulations on synthetic data
  that corroborate these theoretical results.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ray-chowdhury24a
month: 0
tex_title: Differentially Private Reward Estimation with Preference Feedback
firstpage: 4843
lastpage: 4851
page: 4843-4851
order: 4843
cycles: false
bibtex_author: Ray Chowdhury, Sayak and Zhou, Xingyu and Natarajan, Nagarajan
author:
- given: Sayak
  family: Ray Chowdhury
- given: Xingyu
  family: Zhou
- given: Nagarajan
  family: Natarajan
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
pdf: https://proceedings.mlr.press/v238/ray-chowdhury24a/ray-chowdhury24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
