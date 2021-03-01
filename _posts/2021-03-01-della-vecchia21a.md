---
title: An Efficient Algorithm for Cooperative Semi-Bandits
abstract: We consider the problem of asynchronous online combinatorial optimization
  on a network of communicating agents. At each time step, some of the agents are
  stochastically activated, requested to make a prediction, and the system pays the
  corresponding loss. Then, neighbors of active agents receive semi-bandit feedback
  and exchange some succinct local information. The goal is to minimize the network
  regret, defined as the difference between the cumulative loss of the predictions
  of active agents and that of the best action in hindsight, selected from a combinatorial
  decision set. The main challenge in such a context is to control the computational
  complexity of the resulting algorithm while retaining minimax optimal regret guarantees.
  We introduce Coop-FTPL, a cooperative version of the well-known Follow The Perturbed
  Leader algorithm, that implements a new loss estimation procedure generalizing the
  Geometric Resampling of Neu and Bartók [2013] to our setting. Assuming that the
  elements of the decision set are $k$-dimensional binary vectors with at most $m$
  non-zero entries and $\alpha_1$ is the independence number of the network, we show
  that the expected regret of our algorithm after $T$ time steps is of order $Q\sqrt{mkT\log(k)
  (k\alpha_1/Q+m)}$, where $Q$ is the total activation probability mass. Furthermore,
  we prove that this is only $\sqrt{k\log k}$-away from the best achievable rate and
  that Coop-FTPL has a state-of-the-art $T^{3/2}$ worst-case computational complexity.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: della-vecchia21a
month: 0
tex_title: An Efficient Algorithm for Cooperative Semi-Bandits
firstpage: 529
lastpage: 552
page: 529-552
order: 529
cycles: false
bibtex_author: Della Vecchia, Riccardo and Cesari, Tommaso
author:
- given: Riccardo
  family: Della Vecchia
- given: Tommaso
  family: Cesari
date: 2021-03-01
address: 
container-title: Proceedings of the 32nd International Conference on Algorithmic Learning
  Theory
volume: '132'
genre: inproceedings
issued:
  date-parts:
  - 2021
  - 3
  - 1
pdf: http://proceedings.mlr.press/v132/della-vecchia21a/della-vecchia21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
