---
title: "Nonparametric Learning of Two-Layer ReLU Residual Units"
authors: 'Zhunxuan Wang, <b>Linyun He</b>, Chunchuan Lyu, Shay B Cohen'
collection: publications
permalink: /publication/2022-NP_Learning_2L_ReLU
date: 2022-11-23
venue: 'Transactions on Machine Learning Research'
venueType: journal
volume: 2022
paperurl: https://openreview.net/pdf?id=YiOI0vqJ0n
status: published
citation: 'Zhunxuan Wang, <b>Linyun He</b>, Chunchuan Lyu, Shay B Cohen. (2022). &quot;Learning Two-Layer Residual Networks with Nonparametric Function Estimation by Convex Programming&quot;, Transactions on Machine Learning Research'
---

## Abstract
We describe an algorithm that learns two-layer residual units using rectified linear unit (ReLU) activation: suppose the input $\mathbf{x}$ is from a distribution with support space $\mathbb{R}^d$ and the groundtruth generative model is a residual unit of this type, given by $\mathbf{y}=\mathbf{B}^∗[(\mathbf{A}^∗{\mathbf{x}})^+ + \mathbf{x}]$, where ground-truth network parameters $\mathbf{A}^* \in \mathbb{R}^{d\times d}$ represent a full-rank matrix with nonnegative entries and $\mathbf{B}^* \in\mathbb{R}^{m\times d}$ is full-rank with  $m \geq d$ and for $\mathbf{c} \in \mathbb{R}$, $[\mathbf{c}^+]_i = \max\{0,c_i\}$. We design layer-wise objectives as functionals whose analytic minimizers express the exact ground-truth network in terms of its parameters and nonlinearities. Following this objective landscape, learning residual units from finite samples can be formulated using convex optimization of a nonparametric function: for each layer, we first formulate the corresponding empirical risk minimization (ERM) as a positive semi-definite quadratic program (QP), then we show the
solution space of the QP can be equivalently determined by a set of linear inequalities, which can then be efficiently solved by linear programming (LP). We further prove the strong statistical consistency of our algorithm, and demonstrate its robustness and sample efficiency through experimental results on synthetic data and a set of benchmark regression datasets.
