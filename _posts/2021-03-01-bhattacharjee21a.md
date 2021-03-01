---
title: No-substitution k-means Clustering with Adversarial Order
abstract: ' We investigate $k$-means clustering in the online no-substitution setting
  when the input arrives in \emph{arbitrary} order. In this setting, points arrive
  one after another, and the algorithm is required to instantly decide whether to
  take the current point as a center before observing the next point. Decisions are
  irrevocable. The goal is to minimize both the number of centers and the $k$-means
  cost. Previous works in this setting assume that the input’s order is random, or
  that the input’s aspect ratio is bounded. It is known that if the order is arbitrary
  and there is no assumption on the input, then any algorithm must take all points
  as centers. Moreover, assuming a bounded aspect ratio is too restrictive — it does
  not include natural input generated from mixture models. We introduce a new complexity
  measure that quantifies the difficulty of clustering a dataset arriving in arbitrary
  order. We design a new random algorithm and prove that if applied on data with complexity
  $d$, the algorithm takes $O(d\log(n) k\log(k))$ centers and is an $O(k^3)$-approximation.
  We also prove that if the data is sampled from a “natural" distribution, such as
  a mixture of $k$ Gaussians, then the new complexity measure is equal to $O(k^2\log(n))$.
  This implies that for data generated from those distributions, our new algorithm
  takes only $poly(k\log(n))$ centers and is a $poly(k)$-approximation. In terms of
  negative results, we prove that the number of centers needed to achieve an $\alpha$-approximation
  is at least $\Omega\left(\frac{d}{k\log(n\alpha)}\right)$.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bhattacharjee21a
month: 0
tex_title: No-substitution k-means Clustering with Adversarial Order
firstpage: 345
lastpage: 366
page: 345-366
order: 345
cycles: false
bibtex_author: Bhattacharjee, Robi and Moshkovitz, Michal
author:
- given: Robi
  family: Bhattacharjee
- given: Michal
  family: Moshkovitz
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
pdf: http://proceedings.mlr.press/v132/bhattacharjee21a/bhattacharjee21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
