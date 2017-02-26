---
supplementary: http://proceedings.mlr.press/v48/hernandez-lobatob16-supp.pdf
title: Black-Box Alpha Divergence Minimization
abstract: Black-box alpha (BB-α) is a new approximate inference method based on the
  minimization of α-divergences. BB-αscales to large datasets because it can be implemented
  using stochastic gradient descent. BB-αcan be applied to complex probabilistic models
  with little effort since it only requires as input the likelihood function and its
  gradients. These gradients can be easily obtained using automatic differentiation.
  By changing the divergence parameter α, the method is able to interpolate between
  variational Bayes (VB) (α→0) and an algorithm similar to expectation propagation
  (EP) (α= 1). Experiments on probit regression and neural network regression and
  classification problems show that BB-αwith non-standard settings of α, such as α=
  0.5, usually produces better predictions than with α→0 (VB) or α= 1 (EP).
layout: inproceedings
series: Proceedings of Machine Learning Research
id: hernandez-lobatob16
month: 0
tex_title: Black-Box Alpha Divergence Minimization
firstpage: 1511
lastpage: 1520
page: 1511-1520
order: 1511
cycles: false
author:
- given: Jose
  family: Hernandez-Lobato
- given: Yingzhen
  family: Li
- given: Mark
  family: Rowland
- given: Thang
  family: Bui
- given: Daniel
  family: Hernandez-Lobato
- given: Richard
  family: Turner
date: 2016-06-11
address: New York, New York, USA
publisher: PMLR
container-title: Proceedings of The 33rd International Conference on Machine Learning
volume: '48'
genre: inproceedings
issued:
  date-parts:
  - 2016
  - 6
  - 11
pdf: http://proceedings.mlr.press/v48/hernandez-lobatob16.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
