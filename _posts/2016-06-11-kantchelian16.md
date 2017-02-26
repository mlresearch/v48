---
supplementary: http://proceedings.mlr.press/v48/kantchelian16-supp.pdf
title: Evasion and Hardening of Tree Ensemble Classifiers
abstract: Classifier evasion consists in finding for a given instance x the “nearest”
  instance x’ such that the classifier predictions of x and x’ are different. We present
  two novel algorithms for systematically computing evasions for tree ensembles such
  as boosted trees and random forests. Our first algorithm uses a Mixed Integer Linear
  Program solver and finds the optimal evading instance under an expressive set of
  constraints. Our second algorithm trades off optimality for speed by using symbolic
  prediction, a novel algorithm for fast finite differences on tree ensembles. On
  a digit recognition task, we demonstrate that both gradient boosted trees and random
  forests are extremely susceptible to evasions. Finally, we harden a boosted tree
  model without loss of predictive accuracy by augmenting the training set of each
  boosting round with evading instances, a technique we call adversarial boosting.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: kantchelian16
month: 0
tex_title: Evasion and Hardening of Tree Ensemble Classifiers
firstpage: 2387
lastpage: 2396
page: 2387-2396
order: 2387
cycles: false
author:
- given: Alex
  family: Kantchelian
- given: J. D.
  family: Tygar
- given: Anthony
  family: Joseph
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
pdf: http://proceedings.mlr.press/v48/kantchelian16.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
