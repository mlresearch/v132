---
title: Uncertainty quantification using martingales for misspecified Gaussian processes
abstract: 'We address uncertainty quantification for Gaussian processes (GPs) under
  misspecified priors, with an eye towards Bayesian Optimization (BO). GPs are widely
  used in BO because they easily enable exploration based on posterior uncertainty
  bands. However, this convenience comes at the cost of robustness: a typical function
  encountered in practice is unlikely to have been drawn from the data scientist’s
  prior, in which case uncertainty estimates can be misleading, and the resulting
  exploration can be suboptimal. We present a frequentist approach to GP/BO uncertainty
  quantification. We utilize the GP framework as a working model, but do not assume
  correctness of the prior. We instead construct a \emph{confidence sequence} (CS)
  for the unknown function using martingale techniques. There is a necessary cost
  to achieving robustness: if the prior was correct, posterior GP bands are narrower
  than our CS. Nevertheless, when the prior is wrong, our CS is statistically valid
  and empirically outperforms standard GP methods, in terms of both coverage and utility
  for BO. Additionally, we demonstrate that powered likelihoods provide robustness
  against model misspecification.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: neiswanger21a
month: 0
tex_title: Uncertainty quantification using martingales for misspecified Gaussian
  processes
firstpage: 963
lastpage: 982
page: 963-982
order: 963
cycles: false
bibtex_author: Neiswanger, Willie and Ramdas, Aaditya
author:
- given: Willie
  family: Neiswanger
- given: Aaditya
  family: Ramdas
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
pdf: http://proceedings.mlr.press/v132/neiswanger21a/neiswanger21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
