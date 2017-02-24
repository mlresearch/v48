---
supplementary: Supplementary:hernandez-lobatoa16-supp.pdf
title: Predictive Entropy Search for Multi-objective Bayesian Optimization
abstract: We present \small PESMO, a Bayesian method for identifying the Pareto set
  of multi-objective optimization problems, when the functions are expensive to evaluate.
  \small PESMO chooses the evaluation points to maximally reduce the entropy of the
  posterior distribution over the Pareto set. The \small PESMO acquisition function
  is decomposed as a sum of objective-specific acquisition functions, which makes
  it possible to use the algorithm in \emphdecoupled scenarios in which the objectives
  can be evaluated separately and perhaps with different costs. This decoupling capability
  is useful to identify difficult objectives that require more evaluations. \small
  PESMO also offers gains in efficiency, as its cost scales linearly with the number
  of objectives, in comparison to the exponential cost of other methods. We compare
  \small PESMO with other methods on synthetic and real-world problems. The results
  show that \small PESMO produces better recommendations with a smaller number of
  evaluations, and that a decoupled evaluation can lead to improvements in performance,
  particularly when the number of objectives is large.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: hernandez-lobatoa16
month: 0
firstpage: 1492
lastpage: 1501
page: 1492-1501
sections: 
author:
- given: Daniel
  family: Hernandez-Lobato
- given: Jose
  family: Hernandez-Lobato
- given: Amar
  family: Shah
- given: Ryan
  family: Adams
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
pdf: http://proceedings.mlr.press/v48/hernandez-lobatoa16.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
