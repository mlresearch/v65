---
title: 'The Simulator: Understanding Adaptive Sampling in the Moderate-Confidence
  Regime'
abstract: " We propose a novel technique for analyzing adaptive sampling called the
  Simulator. Our approach differs from the existing methods by considering not how
  much information could be gathered by any fixed sampling strategy, but how difficult
  it is to distinguish a good sampling strategy from a bad one given the limited amount
  of data collected up to any given time. This change of perspective allows us to
  match the strength of both Fano and change-of-measure techniques, without succumbing
  to the limitations of either method. For concreteness, we apply our techniques to
  a structured multi-arm bandit problem in the fixed-confidence pure exploration setting,
  where we show that the constraints on the means imply a substantial gap between
  the moderate-confidence sample complexity, and the asymptotic sample complexity
  as the confidence delta tends to zero, as found in the literature. We also prove
  the first instance-based lower bounds for the top-k problem which incorporate the
  appropriate log-factors. Moreover, our lower bounds zero-in on the number of times
  each individual arm needs to be pulled, uncovering new phenomena which are drowned
  out in the aggregate sample complexity. Our new analysis inspires a simple and near-optimal
  algorithm for the best-arm and top-k identification, the first practical algorithm
  of its kind for the latter problem which removes extraneous log factors, and outperforms
  the state-of-the-art in experiments. "
layout: inproceedings
series: Proceedings of Machine Learning Research
id: simchowitz17a
month: 0
tex_title: 'The Simulator: Understanding Adaptive Sampling in the Moderate-Confidence
  Regime'
firstpage: 1794
lastpage: 1834
page: 1794-1834
order: 1794
cycles: false
author:
- given: Max
  family: Simchowitz
- given: Kevin
  family: Jamieson
- given: Benjamin
  family: Recht
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
pdf: http://proceedings.mlr.press/v65/simchowitz17a/simchowitz17a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
