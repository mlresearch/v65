---
title: Square Hellinger Subadditivity for Bayesian Networks and its Applications to
  Identity Testing
abstract: We show that the square Hellinger distance between two Bayesian networks
  on the same directed graph, $G$, is subadditive with respect to the neighborhoods
  of $G$. Namely, if $P$ and $Q$ are the probability distributions defined by two
  Bayesian networks on the same DAG, our inequality states that the square Hellinger
  distance, $H^2(P,Q)$, between $P$ and $Q$ is upper bounded by the sum, $\sum_v H^2(P_{v}
  ∪\Pi_v, Q_{v} ∪\Pi_v)$, of the square Hellinger distances between the marginals
  of $P$ and $Q$ on every node $v$ and its parents $\Pi_v$ in the DAG. Importantly,
  our bound does not involve the conditionals but the marginals of $P$ and $Q$. We
  derive a similar inequality for more general Markov Random Fields. As an application
  of our inequality, we show that distinguishing whether two (unknown) Bayesian networks
  $P$ and $Q$ on the same (but potentially unknown) DAG satisfy $P=Q$ vs $d_\rm TV(P,Q)>ε$
  can be performed from $\tilde{O}(|Σ|^3/4(d+1) ⋅n/ε^2)$ samples, where $d$ is the maximum
  in-degree of the DAG and $Σ$ the domain of each variable of the Bayesian networks.
  If $P$ and $Q$ are defined on potentially different and potentially unknown trees,
  the sample complexity becomes $\tilde{O}(|Σ|^4.5 n/ε^2)$. In both cases the dependence
  of the sample complexity on $n, ε$ is optimal up to logarithmic factors. Lastly,
  if $P$ and $Q$ are product distributions over ${0,1}^n$ and $Q$ is known, the sample
  complexity becomes $O(\sqrt{n}/ε^2)$, which is optimal up to constant factors.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: daskalakis17a
month: 0
tex_title: Square Hellinger Subadditivity for Bayesian Networks and its Applications
  to Identity Testing
firstpage: 697
lastpage: 703
page: 697-703
order: 697
cycles: false
author:
- given: Constantinos
  family: Daskalakis
- given: Qinxuan
  family: Pan
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
pdf: http://proceedings.mlr.press/v65/daskalakis17a/daskalakis17a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
