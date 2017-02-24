---
supplementary: Supplementary:shalev-shwartzb16-supp.pdf
title: 'Minimizing the Maximal Loss: How and Why'
abstract: A commonly used learning rule is to approximately minimize the \emphaverage
  loss over the training set. Other learning algorithms, such as AdaBoost and hard-SVM,
  aim at minimizing the \emphmaximal loss over the training set. The average loss
  is more popular, particularly in deep learning, due to three main reasons. First,
  it can be conveniently minimized using online algorithms, that process few examples
  at each iteration. Second, it is often argued that there is no sense to minimize
  the loss on the training set too much, as it will not be reflected in the generalization
  loss. Last, the maximal loss is not robust to outliers. In this paper we describe
  and analyze an algorithm that can convert any online algorithm to a minimizer of
  the maximal loss. We show, theoretically and empirically, that in some situations
  better accuracy on the training set is crucial to obtain good performance on unseen
  examples. Last, we propose robust versions of the approach that can handle outliers.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: shalev-shwartzb16
month: 0
firstpage: 793
lastpage: 801
page: 793-801
sections: 
author:
- given: Shai
  family: Shalev-Shwartz
- given: Yonatan
  family: Wexler
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
pdf: http://proceedings.mlr.press/v48/shalev-shwartzb16/shalev-shwartzb16.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
