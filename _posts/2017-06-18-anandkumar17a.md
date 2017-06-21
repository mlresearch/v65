---
title: Homotopy Analysis for Tensor PCA
abstract: Developing efficient and guaranteed nonconvex algorithms has been an important
  challenge in modern machine learning. Algorithms with good empirical performance
  such as stochastic gradient descent often lack theoretical guarantees. In this paper,
  we analyze the class of homotopy or continuation methods for global optimization
  of nonconvex functions. These  methods start from an objective function that is
  efficient to optimize (e.g. convex), and progressively modify it to obtain the required
  objective, and the solutions are passed along the homotopy path. For the challenging
  problem of tensor PCA, we prove global convergence of the homotopy method  in the
  “high noise” regime.   The signal-to-noise requirement for our algorithm is tight
  in the sense that it matches the recovery guarantee for the \em best degree-$4$
  sum-of-squares algorithm. In addition, we prove a phase transition along the homotopy
  path for  tensor PCA. This allows us to simplify the homotopy method to a local
  search algorithm, viz., tensor power iterations, with a specific initialization
  and a noise injection procedure, while retaining the theoretical guarantees.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: anandkumar17a
month: 0
tex_title: Homotopy Analysis for Tensor PCA
firstpage: 79
lastpage: 104
page: 79-104
order: 79
cycles: false
author:
- given: Anima
  family: Anandkumar
- given: Yuan
  family: Deng
- given: Rong
  family: Ge
- given: Hossein
  family: Mobahi
date: 2017-06-18
address: 
publisher: PMLR
container-title: Proceedings of the 2017 Conference on Learning Theory
volume: '65'
genre: inproceedings
issued:
  date-parts:
  - 2017
  - 6
  - 18
pdf: http://proceedings.mlr.press/v65/anandkumar17a/anandkumar17a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
