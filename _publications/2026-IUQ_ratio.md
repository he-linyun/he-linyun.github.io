---
title: "Efficient Input Uncertainty Quantification for Ratio Estimator"
authors: '<b>Linyun He</b>, Mingbin Ben Feng, Eunhye Song'
collection: publications
permalink: /publication/2026-IUQ_ratio
date: 2026-03-25
venue: 'INFORMS Journal on Computing'
venueType: journal
paperurl: 'https://pubsonline.informs.org/doi/10.1287/ijoc.2024.0914'
status: published
---

## Abstract
We study the construction of a confidence interval (CI) for a simulation output performance measure that accounts for input uncertainty when the input models are estimated from finite data. In particular, we focus on performance measures that can be expressed as a ratio of two dependent simulation outputs’ means. We adopt the parametric bootstrap method to mimic input data sampling and construct the percentile bootstrap CI after estimating the ratio at each bootstrap sample. The standard estimator, which takes the ratio of two sample means, tends to exhibit large finite-sample bias and variance, leading to overcoverage of the percentile bootstrap CI. To address this, we propose two new ratio estimators that replace the sample means with pooled mean estimators via the k-nearest neighbor (kNN) regression: the kNN estimator and the kLR estimator. The kNN estimator performs well in low dimensions, but its estimation error converges more slowly as the dimension increases. The kLR estimator combines the likelihood ratio (LR) method with the kNN regression, leveraging the strengths of both while mitigating their weaknesses; the LR method removes dependence of the error convergence rate on the dimension, whereas the kNN method controls the variance of the kLR estimator to be asymptotically bounded. From the asymptotic analyses and finite-sample heuristics, we propose an experiment design for the ratio estimators and demonstrate their superior empirical performances over the standard ratio estimator using three examples, including one in the enterprise risk management application.

## Citation
```bibtex
@article{he2026efficient,
  title={Efficient input uncertainty quantification for ratio estimator},
  author={He, Linyun and Feng, Mingbin Ben and Song, Eunhye},
  journal={INFORMS Journal on Computing},
  year={2026},
  publisher={INFORMS}
}
```