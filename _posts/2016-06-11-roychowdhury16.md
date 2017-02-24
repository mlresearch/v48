---
supplementary: Supplementary:roychowdhury16-supp.pdf
title: Robust Monte Carlo Sampling using Riemannian Nos\'{e}-Poincar\'{e} Hamiltonian
  Dynamics
abstract: We present a Monte Carlo sampler using a modified Nosé-Poincaré Hamiltonian
  along with Riemannian preconditioning. Hamiltonian Monte Carlo samplers allow better
  exploration of the state space as opposed to random walk-based methods, but, from
  a molecular dynamics perspective, may not necessarily provide samples from the canonical
  ensemble. Nosé-Hoover samplers rectify that shortcoming, but the resultant dynamics
  are not Hamiltonian. Furthermore, usage of these algorithms on large real-life datasets
  necessitates the use of stochastic gradients, which acts as another potentially
  destabilizing source of noise. In this work, we propose dynamics based on a modified
  Nosé-Poincaré Hamiltonian augmented with Riemannian manifold corrections. The resultant
  symplectic sampling algorithm samples from the canonical ensemble while using structural
  cues from the Riemannian preconditioning matrices to efficiently traverse the parameter
  space. We also propose a stochastic variant using additional terms in the Hamiltonian
  to correct for the noise from the stochastic gradients. We show strong performance
  of our algorithms on synthetic datasets and high-dimensional Poisson factor analysis-based
  topic modeling scenarios.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: roychowdhury16
month: 0
firstpage: 2673
lastpage: 2681
page: 2673-2681
sections: 
author:
- given: Anirban
  family: Roychowdhury
- given: Brian
  family: Kulis
- given: Srinivasan
  family: Parthasarathy
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
pdf: http://proceedings.mlr.press/v48/roychowdhury16/roychowdhury16.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
