---
title: Ten Steps of EM Suffice for Mixtures of Two Gaussians
abstract: The Expectation-Maximization (EM) algorithm is a widely used method for
  maximum likelihood estimation in models with latent variables. For estimating mixtures
  of Gaussians, its iteration can be viewed as a soft version of the k-means clustering
  algorithm. Despite its wide use and applications, there are essentially no known
  convergence guarantees for this method. We provide global convergence guarantees
  for  mixtures of two Gaussians with known covariance matrices. We show that the
  population version of EM, where the algorithm is given access to infinitely many
  samples from the mixture, converges geometrically to the correct mean vectors, and
  provide simple, closed-form expressions for the convergence rate. As a simple illustration,
  we show that, in one dimension, ten steps of the EM algorithm initialized at infinity
  result in less than $1%$ error estimation of the means. In the finite sample regime,
  we show that, under a random initialization, $\tildeO(d/ε^2)$ samples suffice to
  compute the unknown vectors to within $ε$ in Mahalanobis distance, where $d$ is
  the dimension. In particular, the error rate of the EM based estimator is $\tildeO\left(\sqrtd
  \over n\right)$ where $n$ is the number of samples, which is optimal up to logarithmic
  factors.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: daskalakis17b
month: 0
tex_title: Ten Steps of EM Suffice for Mixtures of Two Gaussians
firstpage: 704
lastpage: 710
page: 704-710
order: 704
cycles: false
author:
- given: Constantinos
  family: Daskalakis
- given: Christos
  family: Tzamos
- given: Manolis
  family: Zampetakis
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
pdf: http://proceedings.mlr.press/v65/daskalakis17b/daskalakis17b.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
