---
title: Sample complexity of population recovery
abstract: 'The problem of population recovery refers to estimating a distribution
  based on incomplete or corrupted samples.  Consider a random poll of sample size
  $n$ conducted on a population of individuals, where each pollee is asked to answer
  $d$ binary questions.  We consider one of the two polling impediments: \beginitemize
  \item in lossy population recovery, a pollee may skip each question with probability
  $ε$; \item in noisy population recovery, a pollee may lie on each question with
  probability $ε$. \enditemize Given $n$ lossy or noisy samples, the goal is to estimate
  the probabilities of all $2^d$ binary vectors simultaneously within accuracy $δ$
  with high probability. This paper settles the sample complexity of population recovery.  For
  lossy model, the optimal sample complexity is $\tildeΘ(δ^ -2\max{\fracε1-ε,1})$,
  improving the state of the art by Moitra and Saks in several ways: a lower bound
  is established, the upper bound is improved and the result is dimension-free. Surprisingly,
  the sample complexity undergoes a phase transition from parametric to nonparametric
  rate when $ε$ exceeds $1/2$. For noisy population recovery, the sharp sample complexity
  turns out to be dimension-dependent and scales as $\exp(Θ(d^1/3 \log^2/3(1/δ)))$
  except for the trivial cases of $ε=0,1/2$ or $1$. For both models, our estimators
  simply compute the empirical mean of a certain function, which is found by pre-solving
  a linear program (LP). Curiously, the dual LP can be understood as Le Cam’s method
  for lower-bounding the minimax risk, thus establishing the statistical optimality
  of the proposed estimators. The value of the LP is determined by complex-analytic
  methods. '
layout: inproceedings
series: Proceedings of Machine Learning Research
id: polyanskiy17a
month: 0
tex_title: Sample complexity of population recovery
firstpage: 1589
lastpage: 1618
page: 1589-1618
order: 1589
cycles: false
author:
- given: Yury
  family: Polyanskiy
- given: Ananda Theertha
  family: Suresh
- given: Yihong
  family: Wu
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
pdf: http://proceedings.mlr.press/v65/polyanskiy17a/polyanskiy17a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
