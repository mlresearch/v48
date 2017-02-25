---
supplementary: Supplementary:bhattacharya16-supp.pdf
title: Non-negative Matrix Factorization under Heavy Noise
abstract: 'The Noisy Non-negative Matrix factorization (NMF) is: given a data matrix
  A (d x n), find non-negative matrices B;C (d x k, k x n respy.) so that A = BC +N,
  where N is a noise matrix. Existing polynomial time algorithms with proven error
  guarantees require EACH column N_⋅j to have l1 norm much smaller than ||(BC)_⋅j
  ||_1, which could be very restrictive. In important applications of NMF such as
  Topic Modeling as well as theoretical noise models (e.g. Gaussian with high sigma),
  almost EVERY column of N_.j violates this condition. We introduce the heavy noise
  model which only requires the average noise over large subsets of columns to be
  small. We initiate a study of Noisy NMF under the heavy noise model. We show that
  our noise model subsumes noise models of theoretical and practical interest (for
  e.g. Gaussian noise of maximum possible sigma). We then devise an algorithm TSVDNMF
  which under certain assumptions on B,C, solves the problem under heavy noise. Our
  error guarantees match those of previous algorithms. Our running time of O(k.(d+n)^2)
  is substantially better than the O(d.n^3) for the previous best. Our assumption
  on B is weaker than the “Separability” assumption made by all previous results.
  We provide empirical justification for our assumptions on C. We also provide the
  first proof of identifiability (uniqueness of B) for noisy NMF which is not based
  on separability and does not use hard to check geometric conditions. Our algorithm
  outperforms earlier polynomial time algorithms both in time and error, particularly
  in the presence of high noise.'
layout: inproceedings
series: Proceedings of Machine Learning Research
id: bhattacharya16
month: 0
tex_title: Non-negative Matrix Factorization under Heavy Noise
firstpage: 1426
lastpage: 1434
page: 1426-1434
sections: 
author:
- given: Chiranjib
  family: Bhattacharya
- given: Navin
  family: Goyal
- given: Ravindran
  family: Kannan
- given: Jagdeep
  family: Pani
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
pdf: http://proceedings.mlr.press/v48/bhattacharya16.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
