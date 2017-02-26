---
supplementary: http://proceedings.mlr.press/v48/prabhakaran16-supp.pdf
title: Dirichlet Process Mixture Model for Correcting Technical Variation in Single-Cell
  Gene Expression Data
abstract: We introduce an iterative normalization and clustering method for single-cell
  gene expression data. The emerging technology of single-cell RNA-seq gives access
  to gene expression measurements for thousands of cells, allowing discovery and characterization
  of cell types. However, the data is confounded by technical variation emanating
  from experimental errors and cell type-specific biases. Current approaches perform
  a global normalization prior to analyzing biological signals, which does not resolve
  missing data or variation dependent on latent cell types. Our model is formulated
  as a hierarchical Bayesian mixture model with cell-specific scalings that aid the
  iterative normalization and clustering of cells, teasing apart technical variation
  from biological signals. We demonstrate that this approach is superior to global
  normalization followed by clustering. We show identifiability and weak convergence
  guarantees of our method and present a scalable Gibbs inference algorithm. This
  method improves cluster inference in both synthetic and real single-cell data compared
  with previous methods, and allows easy interpretation and recovery of the underlying
  structure and cell types.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: prabhakaran16
month: 0
tex_title: Dirichlet Process Mixture Model for Correcting Technical Variation in Single-Cell
  Gene Expression Data
firstpage: 1070
lastpage: 1079
page: 1070-1079
order: 1070
cycles: false
author:
- given: Sandhya
  family: Prabhakaran
- given: Elham
  family: Azizi
- given: Ambrose
  family: Carr
- given: Dana
  family: Pe’er
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
pdf: http://proceedings.mlr.press/v48/prabhakaran16.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
